# Gestão de Stakeholders

## Autoestudos

|Autoestudo|Link|
|----------|----|
|Gestão de projetos: gestão de stakeholders|[Link](https://escritoriodeprojetos.com.br/guia-pmbok-setima-edicao/)|
|Análise e classificação dos Stakeholders para Gestão de Projetos|[Link](https://pmkb.com.br/artigos/analise-e-classificacao-dos-stakeholders-para-gestao-de-projetos/)|
|Gestão de Stakeholders, Ética e Sustentabilidade Empresarial|[Link](https://pt.coursera.org/learn/gestao-de-stakeholders-etica-e-sustentabilidade-empresarial)|


<div style="text-align: center; margin-top: 20px;">
    <h1>Vamos jogar KAHOOT!</h1>
    <a href="https://kahoot.it" target="_blank">
        <button style="background-color: #4CAF50; /* Green */
                       color: white;
                       padding: 14px 20px;
                       margin: 8px 0;
                       border: none;
                       border-radius: 4px;
                       cursor: pointer;">
            Acesse Kahoot.it
        </button>
    </a>
</div>

---

<div style="display: flex; justify-content: center; align-items: center;">
    <iframe src="https://docs.google.com/presentation/d/1KTF5LgGmDr0l_kanu0ajkDiTqxgJhLN4/embed?start=false&loop=false&delayms=3000" 
            frameborder="0" 
            width="768" 
            height="461" 
            allowfullscreen="true" 
            mozallowfullscreen="true" 
            webkitallowfullscreen="true">
    </iframe>
</div>


---

## Introdução

No ambiente corporativo contemporâneo, a gestão eficaz dos stakeholders é essencial para o sucesso de qualquer projeto ou organização. Stakeholders, ou partes interessadas, podem influenciar significativamente os resultados e o progresso de iniciativas empresariais. Nesta aula, exploraremos em profundidade o conceito de gestão de stakeholders, sua importância, metodologias de identificação e engajamento, além de melhores práticas e estudos de caso.

---

<style>
    .important {
        color: #333;
        background-color: #f9f9f9;
        padding: 10px;
        border-left: 5px solid #0a4870;
        margin: 20px 0;
    }

    .table-custom {
        width: 100%;
        margin-top: 20px;
        border-collapse: collapse;
    }

    .table-custom, .table-custom th, .table-custom td {
        border: 1px solid #ddd;
        padding: 8px;
        text-align: left;
    }

    .table-custom th {
        background-color: #f2f2f2;
    }
</style>

## O que são Stakeholders?

<div class="important">
    <p><strong>Definição:</strong> Stakeholders são indivíduos, grupos ou organizações que podem afetar ou ser afetados pelas atividades, decisões ou resultados de um projeto ou negócio.</p>
    <h3>Tipos de Stakeholders:</h3>
    <ul>
        <li><strong>Internos:</strong>
            <ul>
                <li><strong>Funcionários:</strong> Equipe operacional, gerencial e executiva.</li>
                <li><strong>Acionistas:</strong> Proprietários e investidores da empresa.</li>
                <li><strong>Gerência:</strong> Diretores e líderes de departamento.</li>
            </ul>
        </li>
        <li><strong>Externos:</strong>
            <ul>
                <li><strong>Clientes:</strong> Consumidores finais ou clientes empresariais.</li>
                <li><strong>Fornecedores:</strong> Parceiros de suprimentos e serviços.</li>
                <li><strong>Comunidade Local:</strong> Residentes e entidades locais afetadas.</li>
                <li><strong>Governo e Reguladores:</strong> Órgãos legislativos e regulatórios.</li>
                <li><strong>Concorrentes:</strong> Empresas que competem no mesmo mercado.</li>
                <li><strong>ONGs e Grupos de Interesse:</strong> Organizações com agendas específicas.</li>
            </ul>
        </li>
    </ul>
</div>

## Identificação de Stakeholders

<div class="important">
    <p><strong>Passos para Identificação:</strong></p>
    <ol>
        <li><strong>Análise de Documentos:</strong> Revisar planos de projeto, contratos e documentos legais.</li>
        <li><strong>Brainstorming em Equipe:</strong> Envolver a equipe para identificar partes interessadas.</li>
        <li><strong>Mapeamento de Processos:</strong> Analisar processos organizacionais para identificar interações.</li>
        <li><strong>Consultas Externas:</strong> Conversar com parceiros e consultores para insights adicionais.</li>
    </ol>
</div>
<div class="table-custom">
    <h3>Matriz Poder/Interesse:</h3>
    <table>
        <tr>
            <th></th>
            <th>Alto Interesse</th>
            <th>Baixo Interesse</th>
        </tr>
        <tr>
            <th>Alto Poder</th>
            <td>Gerenciar de perto</td>
            <td>Manter satisfeito</td>
        </tr>
        <tr>
            <th>Baixo Poder</th>
            <td>Manter informado</td>
            <td>Monitorar com esforço mínimo</td>
        </tr>
    </table>
</div>

# Elementos que Devem Estar Presentes no Artefato de Plano de Cutover Final

### **Equipe Envolvida**
- **Gerente de Projeto**: Nome do Responsável
- **Líder Técnico**: Nome do Responsável
- **Equipe de Suporte**: Nome do Responsável
- **Equipe de Desenvolvimento**: Nome do Responsável
- **Gestores de Área**: Nome do Responsável

---

### **Cronograma de Atividades de Cutover**
| **Atividade**              | **Responsável**      | **Data de Início** | **Data de Término** | **Dependências**   |
|----------------------------|----------------------|--------------------|--------------------|--------------------|
| Backup dos Dados Atuais     | Nome do Responsável  | [Data]             | [Data]             | Nenhuma            |
| Configuração de Ambientes   | Nome do Responsável  | [Data]             | [Data]             | Backup Completo    |
| Validação dos Ambientes     | Nome do Responsável  | [Data]             | [Data]             | Configuração       |
| Teste de Integração         | Nome do Responsável  | [Data]             | [Data]             | Validação          |
| Entrar em Operação (Go-Live)| Nome do Responsável  | [Data]             | [Data]             | Testes Concluídos  |

---

### **Plano de Comunicação**
| **Stakeholder**            | **Forma de Comunicação**  | **Frequência**          | **Responsável**        |
|----------------------------|--------------------------|-------------------------|------------------------|
| Equipe Técnica              | Reuniões e E-mails        | Diariamente durante o Cutover | Gerente de Projeto     |
| Diretoria                   | Relatório Resumido        | No início e no final    | Gerente de Projeto      |
| Usuários Finais             | E-mail                    | Pós-Cutover             | Líder Técnico           |
| Parceiros Externos          | Reunião e Relatório       | Semanal                 | Gestor de Área          |

---

### **Plano de Contenção**
Se o Cutover falhar ou se problemas críticos forem identificados durante a transição, o seguinte plano de contenção será ativado para mitigar o impacto:

| **Cenário**                            | **Ação de Contenção**                                         | **Responsável**        | **Prazo**    |
|----------------------------------------|---------------------------------------------------------------|------------------------|--------------|
| Falha na Migração de Dados             | Restaurar o backup realizado antes do Cutover                 | Equipe de Suporte       | Imediato     |
| Incompatibilidade nos Sistemas         | Reverter para a versão anterior do sistema                    | Líder Técnico           | Até 2h       |
| Interrupção nos Serviços               | Ativar ambiente de contingência (servidores de backup)        | Equipe Técnica          | Imediato     |
| Falha de Integração com Sistemas Legados| Escalonar para equipe de integração e implementar correções   | Gestor de Integração    | Até 1h       |

---

### **Matriz de Risco**

| **Risco**                              | **Probabilidade** | **Impacto**   | **Severidade** | **Mitigação**                                                | **Responsável** |
|----------------------------------------|------------------|---------------|----------------|--------------------------------------------------------------|-----------------|
| Falha no Backup                        | Média            | Alto          | Crítico         | Verificar a integridade dos backups antes do Cutover          | Equipe Técnica  |
| Incompatibilidade entre Sistemas       | Baixa            | Médio         | Moderado        | Realizar testes extensivos de integração antes do Cutover     | Líder Técnico   |
| Erros de Configuração no Ambiente Novo | Alta             | Alto          | Crítico         | Realizar configuração paralela com validação antecipada       | Equipe Técnica  |
| Falha na Comunicação com Stakeholders  | Média            | Médio         | Alto            | Acompanhamento em tempo real com atualizações frequentes       | Gerente de Projeto |

---

### **Matriz RACI**

| **Atividade**                          | **Responsável (R)** | **Aprovador (A)** | **Consultado (C)** | **Informado (I)** |
|----------------------------------------|---------------------|-------------------|--------------------|-------------------|
| Preparação do Ambiente                 | Equipe Técnica      | Gerente de Projeto| Líder Técnico       | Diretoria         |
| Execução do Backup                     | Equipe de Suporte   | Líder Técnico     | Gerente de Projeto  | Gestores de Área  |
| Configuração do Novo Ambiente          | Líder Técnico       | Gerente de Projeto| Equipe Técnica      | Usuários Finais   |
| Validação e Testes                     | Equipe Técnica      | Gerente de Projeto| Equipe de Suporte   | Gestores de Área  |
| Execução do Cutover                    | Gerente de Projeto  | Diretoria         | Equipe Técnica      | Todos os Stakeholders |
| Comunicação Pós-Cutover                | Gerente de Projeto  | Diretoria         | -                  | Todos os Stakeholders |