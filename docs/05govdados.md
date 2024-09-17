# Governança Corporativa e de Dados

<iframe src="https://docs.google.com/presentation/d/10x3izehpivOdj3dD_tR89eq6XaEUL4s4/embed?start=false&loop=false&delayms=3000" frameborder="0" width="768" height="461" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>
---
# Modelo Entidade Relacionamento

![imagem](https://leonardofonseca.com.br/wp-content/uploads/2021/04/image.png)

A **cardinalidade** em modelagem de banco de dados se refere à relação entre entidades, indicando o número de ocorrências que uma entidade pode ter associada a outra entidade em um relacionamento.

### Cardinalidade Mínima
A **cardinalidade mínima** define **o número mínimo de vezes que uma entidade pode se associar a outra** em um relacionamento. Isso representa a obrigatoriedade ou opcionalidade da relação. Existem dois valores possíveis para a cardinalidade mínima:
1. **0 (opcional)**: Indica que uma entidade pode não ter nenhuma associação com outra. Ou seja, a participação dela no relacionamento é opcional.
2. **1 (obrigatória)**: Indica que uma entidade **deve** ter pelo menos uma associação com outra. A participação é obrigatória.

**Exemplo**:
- Em um relacionamento entre `Alunos` e `Disciplinas`, a cardinalidade mínima 0 entre `Alunos` e `Disciplinas` pode indicar que um aluno pode não estar matriculado em nenhuma disciplina.

### Cardinalidade Máxima
A **cardinalidade máxima** define **o número máximo de vezes que uma entidade pode se associar a outra** em um relacionamento. Isso descreve o limite superior de quantas vezes uma entidade pode se conectar à outra.

As opções mais comuns de cardinalidade máxima são:
1. **1**: Indica que uma entidade pode se associar com **no máximo uma** outra entidade.
2. **N** (ou muitos): Indica que uma entidade pode se associar a **múltiplas** instâncias de outra entidade.

**Exemplo**:
- Em um relacionamento entre `Professores` e `Disciplinas`, uma cardinalidade máxima de 1 pode indicar que um professor só pode ministrar uma disciplina, enquanto uma cardinalidade de N indica que o professor pode ministrar várias disciplinas.

### Exemplo Completo
Se tivermos um relacionamento entre `Funcionário` e `Departamento`:

- **Cardinalidade mínima de 0 e máxima de 1** no lado do `Departamento` indica que um funcionário pode ou não estar associado a um departamento (participação opcional) e, se estiver, é com apenas um departamento.
- **Cardinalidade mínima de 1 e máxima de N** no lado do `Departamento` significa que cada departamento deve ter ao menos um funcionário e pode ter muitos.

Assim, as cardinalidades mínima e máxima ajudam a descrever a **natureza e as restrições** dos relacionamentos entre entidades em um modelo de banco de dados.

---
# Vamos para uma prática! [SQL Designer](https://sql.toad.cz/)

### Cenário: Sistema de Biblioteca com Categorias (N para N)

#### Tabelas e Relacionamentos

```sql
CREATE TABLE authors (
    id INT PRIMARY KEY AUTO_INCREMENT,
    name VARCHAR(255) NOT NULL,
    birthdate DATE
);

CREATE TABLE categories (
    id INT PRIMARY KEY AUTO_INCREMENT,
    name VARCHAR(100) NOT NULL
);

CREATE TABLE books (
    id INT PRIMARY KEY AUTO_INCREMENT,
    title VARCHAR(255) NOT NULL,
    author_id INT,
    published_year INT,
    FOREIGN KEY (author_id) REFERENCES authors(id)
);

CREATE TABLE book_categories (
    book_id INT,
    category_id INT,
    PRIMARY KEY (book_id, category_id),
    FOREIGN KEY (book_id) REFERENCES books(id),
    FOREIGN KEY (category_id) REFERENCES categories(id)
);

CREATE TABLE members (
    id INT PRIMARY KEY AUTO_INCREMENT,
    name VARCHAR(255) NOT NULL,
    email VARCHAR(255) NOT NULL,
    join_date DATE
);

CREATE TABLE loans (
    id INT PRIMARY KEY AUTO_INCREMENT,
    book_id INT,
    member_id INT,
    loan_date DATE,
    return_date DATE,
    FOREIGN KEY (book_id) REFERENCES books(id),
    FOREIGN KEY (member_id) REFERENCES members(id)
);
```
### Descrição das Tabelas

1. **Tabela `authors`**: Armazena os dados dos autores.
2. **Tabela `categories`**: Armazena os dados das categorias de livros (ex: Ficção, Ciência, História).
3. **Tabela `books`**: Contém os livros com seus respectivos títulos, autor e ano de publicação.
4. **Tabela `book_categories`**: Esta tabela intermediária faz a relação N para N entre **livros** e **categorias**, já que um livro pode ter várias categorias e uma categoria pode conter vários livros.
5. **Tabela `members`**: Contém os membros da biblioteca.
6. **Tabela `loans`**: Armazena o histórico de empréstimos, com as datas de empréstimo e devolução.

### Relacionamentos

- Um **autor** pode ter vários **livros** (um-para-muitos entre `authors` e `books`).
- Um **livro** pode pertencer a várias **categorias**, e uma **categoria** pode conter vários **livros**. Isso cria a relação N para N, que é gerenciada pela tabela intermediária `book_categories`.
- Um **membro** pode emprestar vários **livros** (um-para-muitos entre `members` e `loans`).
- Um **livro** pode ser emprestado várias vezes (um-para-muitos entre `books` e `loans`).

### Criando o Diagrama no wwwsqldesigner

1. Crie as tabelas: **authors**, **books**, **categories**, **book_categories**, **members**, e **loans**.
2. Conecte as tabelas usando as chaves estrangeiras.
3. Para a relação N para N, conecte a tabela `book_categories` com `books` e `categories`.


# Ponderada

Elabore um diagrama entidade-relacionamento que contemple as principais entidades relacionadas aos dados mestres que seu grupo identificou no projeto.

Utilize o sql Designer para fazer a ponderada, verifique os dados mestres e crie as entidades e relacionamentos.

## Entrega Individual na data 15 de setembro de 2024