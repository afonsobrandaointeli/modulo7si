# Regras de Negócio e Tomada de Decisão

## Autoestudos
| Autoestudo | Link |
|------------|------|
| [📚](https://img.icons8.com/ios/50/000000/book.png) | **[Regras de Negócio](https://integrada.minhabiblioteca.com.br/reader/books/9788595021792/pageid/58)** |
| [🎥](https://img.icons8.com/ios/50/000000/video.png) | **[#07 - Análise de Requisitos (4) - Regras de Negócio](https://www.youtube.com/watch?v=Tr50dJEf0BA)** |
| [📄](https://img.icons8.com/ios/50/000000/document.png) | **[DECISION MODEL AND NOTATION™ (DMN™)](https://www.omg.org/dmn/)** |
| [📝](https://img.icons8.com/ios/50/000000/note.png) | **[O que é DMN – Decision model notation e qual a relação com o BPMN?](https://holmes.app/blog/o-que-e-dmn-decision-model-notation)** |

## Agenda

| Horário   | Atividade                       | Descrição                                              |
|-----------|---------------------------------|--------------------------------------------------------|
| 09:00 - 09:15 | Daily Stand-up                   | Reunião rápida de 15 minutos para alinhamento diário. |
| 09:15 - 09:35 | Kahoot Quiz                      | Sessão de 20 minutos com quiz interativo para revisão. |
| 09:35 - 10:30 | Aula Interativa                  | Aula de 55 minutos com atividades práticas e discussão. |


---

## Tabela de Regras de Negócio

| Nº| Descrição                                      | Critérios de Aplicação                               | Ações                                                      | Responsável        |
|-------------------|------------------------------------------------|-----------------------------------------------------|------------------------------------------------------------|--------------------|
| CO001               | Política de Desconto para Compras Acima de R$500 | Aplicável a compras superiores a R$500              | Conceder 10% de desconto sobre o valor total da compra.     | Equipe de Vendas   |
| AC002               | Critério de Aprovação de Crédito                | Crédito do cliente deve ser superior a R$1.000       | Aprovar crédito solicitado se o critério for atendido.     | Departamento de Crédito |
| MA003               | Política de Retorno de Produtos                 | Devolução dentro de 30 dias com embalagem original   | Aceitar devolução e emitir reembolso ou troca do produto.  | Atendimento ao Cliente |
| EX004               | Requisitos para Frete Grátis                    | Compra mínima de R$100                              | Oferecer frete grátis para compras que atendam o requisito.| Equipe de Logística |
| NF005               | Desconto Adicional para Clientes VIP            | Compras acima de R$200 e cliente VIP                | Aplicar 5% de desconto adicional na compra.               | Equipe de Vendas   |
| 006               | Política de Aprovação de Devoluções Excepcionais | Produtos defeituosos ou com erro de envio           | Aceitar devoluções excepcionais e processar o reembolso.   | Atendimento ao Cliente |

---

<div class="container d-flex justify-content-center">
    <img src="https://www.sydle.com/blog/assets/post/regras-de-negocio-5f6333be1e43744c69d995e0/importancia-regras-de-negocio.png" class="img-fluid rounded" alt="Descrição da Imagem">
</div>

<div class="container mt-4">
    <h1 class="text-primary">1. Regras de Negócio</h1>

    <p><strong>Definição:</strong> Regras de negócio são condições ou políticas que definem ou restringem vários aspectos de um negócio. Elas são essenciais para garantir que as operações sejam realizadas de acordo com diretrizes estabelecidas, ajudando a padronizar processos e garantir conformidade com normas e políticas internas. Regras de negócio podem ser usadas para definir procedimentos operacionais, restringir decisões ou garantir que as práticas sejam consistentes com os objetivos estratégicos da organização.</p>

    <h2 class="text-info">Importância das Regras de Negócio:</h2>
    <ul>
        <li><strong>Padronização:</strong> Garantem que todas as operações sejam realizadas de acordo com um conjunto uniforme de diretrizes.</li>
        <li><strong>Conformidade:</strong> Ajudam a garantir que as práticas estejam alinhadas com leis, regulamentações e políticas internas.</li>
        <li><strong>Eficiência:</strong> Automatizam processos e decisões, reduzindo a necessidade de intervenção manual e minimizando erros.</li>
        <li><strong>Transparência:</strong> Facilitam a compreensão e a comunicação dos processos e decisões de negócios entre as partes interessadas.</li>
    </ul>

    <h2 class="text-info">Tipos de Regras de Negócio:</h2>

    <ol>
        <li><strong>Regras de Decisão:</strong> Determinam a lógica por trás das decisões de negócios.
            <div class="alert alert-light">
                <strong>Exemplo:</strong> <em>Critério de Aprovação de Crédito:</em> "Um pedido de crédito será aprovado somente se o histórico de crédito do cliente for classificado como 'bom' e a renda mensal for superior a R$5.000."
            </div>
        </li>
        <li><strong>Regras de Processos:</strong> Definem como um processo deve ser executado.
            <div class="alert alert-light">
                <strong>Exemplo:</strong> <em>Política de Retorno:</em> "Produtos podem ser retornados dentro de 30 dias após a compra, desde que estejam em sua embalagem original e não tenham sido utilizados."
            </div>
        </li>
        <li><strong>Regras de Condições:</strong> Estabelecem condições que devem ser atendidas para a execução de uma ação.
            <div class="alert alert-light">
                <strong>Exemplo:</strong> <em>Requisitos de Compra:</em> "Um cliente deve fazer uma compra mínima de R$100 para se qualificar para o frete grátis."
            </div>
        </li>
        <li><strong>Regras de Exceção:</strong> Definem como lidar com situações fora do padrão.
            <div class="alert alert-light">
                <strong>Exemplo:</strong> <em>Desconto Excepcional:</em> "Clientes VIP podem receber um desconto adicional de 5% em compras acima de R$200, mesmo que a promoção padrão não esteja em vigor."
            </div>
        </li>
    </ol>

    <h2 class="text-info">Exemplos Detalhados:</h2>

    <div class="card mb-4">
        <div class="card-body">
            <h5 class="card-title">Política de Desconto</h5>
            <p><strong>Descrição:</strong> Oferecemos um desconto de 10% para clientes que gastam mais de R$500 em uma única compra.</p>
            <p><strong>Objetivo:</strong> Incentivar compras maiores e aumentar a receita média por cliente.</p>
            <p><strong>Exemplo:</strong> Um cliente que compra produtos no valor total de R$600 receberá um desconto de R$60, resultando em um total de R$540 a pagar.</p>
        </div>
    </div>

    <div class="card mb-4">
        <div class="card-body">
            <h5 class="card-title">Critério de Aprovação de Crédito</h5>
            <p><strong>Descrição:</strong> Os pedidos de crédito são analisados e aprovados somente se o crédito do cliente for superior a R$1.000.</p>
            <p><strong>Objetivo:</strong> Minimizar o risco financeiro ao garantir que apenas clientes com bom histórico de crédito possam obter crédito.</p>
            <p><strong>Exemplo:</strong> Um cliente que solicita um crédito de R$2.000 e possui um crédito atual de R$1.500 será aprovado, enquanto um cliente com crédito de R$900 não será aprovado.</p>
        </div>
    </div>

    <div class="card mb-4">
        <div class="card-body">
            <h5 class="card-title">Política de Devolução</h5>
            <p><strong>Descrição:</strong> Produtos devem ser devolvidos dentro de 30 dias da compra, com recibo e na embalagem original.</p>
            <p><strong>Objetivo:</strong> Garantir que as devoluções sejam feitas de maneira organizada e justa, enquanto se protege contra fraudes.</p>
            <p><strong>Exemplo:</strong> Um cliente que comprou um item em 10 de junho pode devolvê-lo até 10 de julho. Se o item estiver em boas condições e o recibo estiver presente, o cliente receberá um reembolso total.</p>
        </div>
    </div>

    <div class="card mb-4">
        <div class="card-body">
            <h5 class="card-title">Requisitos de Compra Mínima para Frete Grátis</h5>
            <p><strong>Descrição:</strong> Oferecemos frete grátis para compras acima de R$100.</p>
            <p><strong>Objetivo:</strong> Incentivar os clientes a gastar mais para obter frete grátis, aumentando o valor médio das transações.</p>
            <p><strong>Exemplo:</strong> Um cliente que compra R$120 em produtos receberá frete grátis, enquanto um cliente que compra R$90 pagará pelo frete.</p>
        </div>
    </div>

    <h2 class="text-info">Considerações para Implementação:</h2>
    <ul>
        <li><strong>Clareza e Especificidade:</strong> As regras devem ser claramente definidas e específicas para evitar ambiguidades e mal-entendidos.</li>
        <li><strong>Comunicação:</strong> As regras devem ser bem comunicadas a todos os envolvidos para garantir que sejam seguidas corretamente.</li>
        <li><strong>Monitoramento e Atualização:</strong> As regras de negócio devem ser periodicamente revisadas e atualizadas para se manterem relevantes e eficazes.</li>
    </ul>
</div>

<div class="container d-flex justify-content-center">
    <img src="https://www.ateomomento.com.br/wp-content/uploads/2016/05/software-requisito-funcional-regra-de-negocio-requisito-nao-funcional.png" class="img-fluid rounded" alt="Descrição da Imagem">
</div>

---

<div class="container mt-4">
    <h1 class="text-primary">2. As Regras de Negócio no SAP</h1>

    <p><strong>SAP e Regras de Negócio:</strong> No SAP, as regras de negócio são integradas em diferentes módulos e processos para automatizar e padronizar as operações empresariais. Isso permite que as organizações definam, implementem e ajustem regras de forma centralizada, assegurando que todos os processos estejam alinhados com as diretrizes e objetivos da empresa.</p>

    <h2 class="text-info">Componentes Relacionados:</h2>
    <ul>
        <li><strong>SAP Business Rules Framework (BRF):</strong> Uma ferramenta poderosa que permite a modelagem e execução de regras de negócio dentro do SAP. O BRF facilita a criação e manutenção de regras sem a necessidade de programar diretamente em ABAP, proporcionando uma interface amigável para o usuário.</li>
        <li><strong>SAP Business Process Management (BPM):</strong> Permite a definição e automação dos processos de negócios. O SAP BPM ajuda na modelagem de processos complexos e garante que as regras de negócio sejam aplicadas de forma consistente durante a execução dos processos.</li>
    </ul>

    <h2 class="text-info">Exemplo:</h2>
    <div class="alert alert-light">
        <strong>Configuração de Regras para Gestão de Inventário:</strong>
        <p>As regras podem incluir a definição de níveis mínimos e máximos de estoque e a reordenação automática de produtos. Por exemplo, se o nível de estoque de um item cair abaixo do nível mínimo definido, o sistema pode gerar automaticamente uma ordem de compra para reabastecer o inventário. Isso ajuda a garantir que a empresa mantenha níveis adequados de estoque e minimize a interrupção nas operações devido à falta de produtos.</p>
    </div>

</div>

---

<div class="container mt-4">
    <h1 class="text-primary">3. O que é DMN - Decision Making Model</h1>

    <p><strong>Definição:</strong> DMN (Decision Model and Notation) é uma notação padrão para modelar decisões de negócios e regras de decisão. Ele fornece uma forma gráfica e estruturada de definir e documentar decisões e processos de decisão, ajudando a garantir que as decisões sejam tomadas de forma consistente e transparente.</p>

    <h2 class="text-info">Componentes Principais:</h2>
    <ul>
        <li><strong>Decisions:</strong> Entidades que representam as decisões a serem tomadas. Elas definem quais decisões são necessárias e como devem ser executadas.</li>
        <li><strong>Business Knowledge Models:</strong> Regras e fórmulas que fornecem o conhecimento necessário para as decisões. Eles contêm o conhecimento especializado e as regras usadas para chegar a uma decisão.</li>
        <li><strong>Decision Tables:</strong> Tabelas que detalham como diferentes entradas resultam em diferentes saídas. Elas ajudam a visualizar a lógica de decisão de forma clara e estruturada, facilitando a análise e a implementação.</li>
    </ul>

    <h2 class="text-info">Vantagens:</h2>
    <ul>
        <li><strong>Clareza:</strong> Facilita a compreensão e documentação das regras de decisão, proporcionando uma visão clara de como as decisões são tomadas.</li>
        <li><strong>Flexibilidade:</strong> Permite a adaptação e evolução das regras de negócio. O DMN permite que as regras sejam modificadas e ajustadas com facilidade à medida que as necessidades do negócio mudam.</li>
    </ul>

</div>

---

<div class="container mt-4">
    <h1 class="text-primary">4. Como o DMN se Relaciona com o BPMN</h1>

    <p><strong>BPMN (Business Process Model and Notation)</strong> e <strong>DMN (Decision Model and Notation)</strong> são usados em conjunto para fornecer uma visão completa dos processos de negócios e das decisões envolvidas. Enquanto BPMN foca na modelagem dos processos de negócios e workflows, DMN é especializado na modelagem das decisões dentro desses processos.</p>

    <h2 class="text-info">Diferenças e Foco:</h2>
    <ul>
        <li><strong>BPMN:</strong> Foca na modelagem de processos de negócios e workflows. Ele permite que as organizações representem visualmente os passos e interações envolvidas em um processo, incluindo atividades, eventos e gateways.</li>
        <li><strong>DMN:</strong> Foca na modelagem das decisões dentro desses processos. Ele permite que as regras e lógica de decisão sejam definidas e documentadas de forma estruturada, garantindo que as decisões sejam tomadas com base em critérios claros e consistentes.</li>
    </ul>

    <h2 class="text-info">Integração:</h2>
    <ul>
        <li><strong>Decisões em BPMN:</strong> BPMN pode incorporar decisões modeladas em DMN para garantir que as decisões sejam tomadas com base nas regras definidas. A integração permite que os processos de negócios representados em BPMN usem as regras e tabelas de decisão definidas em DMN, garantindo uma execução consistente das decisões.</li>
        <li><strong>Exemplo de Integração:</strong> Um processo de aprovação de crédito modelado em BPMN pode usar tabelas de decisão DMN para determinar a elegibilidade do crédito. O BPMN define o fluxo do processo de aprovação, enquanto o DMN especifica as regras e critérios usados para avaliar se um crédito deve ser aprovado ou não.</li>
    </ul>

</div>

---
<h2>Fluxo de Gestão de Regras de Negócio</h2>
<div class="container d-flex justify-content-center">
    <img src="https://arquivo.devmedia.com.br/REVISTAS/es/imagens/66/8/2.png" class="img-fluid rounded" alt="Descrição da Imagem">
</div>
---

<div class="container mt-4">
    <h1 class="text-primary">Missão!</h1>

    <p>Entre neste site: <a href="https://camunda.com/dmn/" class="btn btn-link">Camunda</a> e clique no exemplo para entender melhor na prática.</p>

    <h2 class="text-info">Agora sim, vamos à missão: Criar um DMN de uma Situação de SAP</h2>

    <h3 class="text-success">Objetivo:</h3>
    <p>Criar um modelo DMN para uma situação específica no SAP para praticar a modelagem de decisões.</p>

    <h3 class="text-success">Passos da Atividade:</h3>

    <ol>
        <li>
            <strong>Descrição da Situação:</strong>
            <p>Imagine que você está trabalhando em um módulo de SAP para gestão de pedidos e precisa modelar a decisão de aprovação de pedidos com base no valor total do pedido e no histórico de crédito do cliente.</p>
        </li>
        <li>
            <strong>Identificação das Regras de Decisão:</strong>
            <p>Defina as regras para aprovação de pedidos. Por exemplo:</p>
            <ul>
                <li>Pedido aprovado se o valor total for menor que R$5.000 e o crédito do cliente for suficiente.</li>
                <li>Pedido aprovado com revisão adicional se o valor total for superior a R$5.000.</li>
            </ul>
        </li>
        <li>
            <strong>Modelagem DMN:</strong>
            <p>Crie uma tabela de decisão DMN com as condições e resultados baseados nas regras definidas.</p>
        </li>
        <li>
            <strong>Discussão e Revisão:</strong>
            <p>Apresente o modelo DMN para a turma e discuta as decisões e regras aplicadas.</p>
        </li>
    </ol>

</div>