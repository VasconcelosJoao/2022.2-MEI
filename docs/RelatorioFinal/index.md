# Post Mortem

## <a>Histórico de Versão</a>

| Data de Realização | Data Prevista de Revisão | Versão |          Descrição           |                   Autor                    |                    Revisor                    |
| :----------------: | :----------------------: | :----: | :--------------------------: | :----------------------------------------: | :-------------------------------------------: |
|     27/01/2023     |        28/01/2023        |  1.0   |     Criação do Documento     |   [Ana Luiza](https://github.com/AnHoff)   | [Thiago Olivera](https://github.com/Thiab394)   |
|     29/01/2023     |        30/01/2023        |  1.1   |     Finaliza Artefatos, Resultados e V&V     |   [Ana Luiza](https://github.com/AnHoff)   |  [Thiago Olivera](https://github.com/Thiab394)   |
|     31/01/2023     |        01/02/2023        |  1.2   |     Adição da Seção Planejamento     |   [Thiago Olivera](https://github.com/Thiab394)   |  [Ana Luiza](https://github.com/AnHoff)|
|     31/01/2023     |        01/02/2023        |  1.3   |     Adição da Seção Mei e Técnicas     |   [Pedro Lucas](https://github.com/PedroLSF)   |  [Eduardo](https://github.com/edudsan)|

## <a>Introdução</a>
O presente documento visa reunir os materiais requisitados pelo professor André Barros de Sales, da disciplina Requisitos de Software da Universidade de Brasília, para a realização da apresentação final. O conteúdo presente abaixo aborda os seguintes tópicos detalhadamente:

* O **aplicativo** selecionado;
* **Planejamento** de recursos e entregas;
* **Execução** do projeto;
* **Resultados** alcançados;
* Tabelas sintetizando as **técnicas** utilizadas, **artefatos** criados, métodos de **verificação e validação**, **ferramentas** e seu uso, vídeos das **apresentações**;
* Facilidades e dificuldades.

Vale destacar que o documento foi elaborado seguindo o template utilizado pelo projeto do YouTube [1], realizado no semestre 2022.1.

## <a>Objetivo</a>

A disciplina de requisitos de software possui objetivo de ensinar os alunos sobre requisitos, desde o seu processo de elicitação até técnicas de como priorizá-los. O projeto foi desenvolvido com a finalidade de aprender de forma prática sobre os tópicos da ementa da disciplina, com isso foi escolhido um aplicativo para podermos aplicar as técnicas de elicitaçãao e modelagem que nos foram apresentados no decorrer da dsiciplina.

## <a>MEI</a>
### <a>Sobre o MEI</a>
Microempreendedor Individual ou mais conhecido como MEI, é um aplicativo ligado ao Portal do Empreendedor, o aplicativo fornece vários auxílios para quem deseja formalizar algum trabalho a fim de obter, por exemplo, uma aposentadoria. O aplicativo lista algumas funções, são elas:
* Gerar guia de pagamento do DAS;
* Status do CNPJ;
* Solicitar Restituição;
* Entre outros.

Todos esses pontos estão presentes e foram trabalhos ao longo do nosso projeto.

### <a>Por quê o MEI?</a>
Antes de entender a razão da escolha do MEI vale citar que foram analisados 6 [aplicativos](https://requisitos-de-software.github.io/2022.2-MEI/Planejamento/AplicativosAnalisados/), foram feitos Rich Picture e uma reunião para análise dos problemas encontrados em casa aplicativo. Por fim, depois de muitas análises foi possível levantar dados maiores sobre o MEI e entender que seria o melhor aplicativo para nosso projeto, existe um documento explicando o [Motivo do Aplicativo MEI](https://requisitos-de-software.github.io/2022.2-MEI/Planejamento/MEI/).


## <a>Planejamento</a>
Esta seção tem como objetivo relatar o planejamento feito ao decorrer da disciplina, que consiste basicamente nos documentos realizadas como um meio de "preparação" para o bom desenvolvimento da mesma. 

Em tal etapa temos diversos documentos, tais como aplicativos analisados, aplicativo escolhido, Ferramentas, etc, que estão listados e podem ser visualizados na seção de [Artefatos - Etapa 1](#etapa 1: planejamento), porém aqui será mostrado apenas o cronograma planejado do projeto, que seria a essência do planejamento do mesmo, por possuir em detalhes a realização de cada artefate e de cada "Sub-artefato" ou até documentos e etapas auxiliares para que seja realizada uma boa execução.

O Cronograma Planejado pode ser visto [aqui](../Planejamento/Roadmap/#cronograma-planejado), porém também será listado logo abaixo, nas Tabelas de 1-6 Relacionadas ás etapas 1-6 respectivamente:

<center>

**Etapa 1**

| Tarefa | Responsáveis | Início | Fim | Revisão | Revisor |
| --- | --- | --- | --- | --- | --- |
| Listar apps avaliados | Ana e Pedro | 28/10/2022 | 01/11/2022 | 02/11/2022 | João
| Discorrer sobre o app selecionado | Ana e Pedro | 01/11/2022 | 19/11/2022| 20/11/2022 | Pedro
| Ferramentas do projeto | Arthur, Eduardo e Thiago | 12/11/2022 | 19/11/2022 | 20/11/2022 | Ana
| Adicionar Rich Pictures | Ana, Arthur, Pedro, João, Thiago, Eduardo | 12/11/2022 | 19/11/2022 | 20/11/2022 | Thiago
| Refazer Rich Picture do app selecionado | João | 19/11/2022 | 23/11/2022 | 24/11/2022 | Arthur
| Cronograma de atividades | Arthur e Thiago | 16/11/2022 | 23/11/2022 | 24/11/2022 | Eduardo
| Heatmap | Eduardo | 16/11/2022 | 23/11/2022 | 24/11/2022 | João
| Metodologias | Arthur e Thiago | 16/11/2022 | 23/11/2022 | 24/11/2022 | João
| Equipe | Thiago | 16/11/2022 | 23/11/2022 | 24/11/2022 | João
| Atas | Arthur | 16/11/2022 | 23/11/2022 | 24/11/2022 | Ana

*Tabela 1 - Tarefas para a Etapa 1*<br><br>

**Etapa 2**

| Tarefa | Responsáveis | Início | Fim | Revisão | Revisor |
| --- | --- | --- | --- | --- | --- |
| Traçar perfil de usuários | Eduardo, João e Pedro | 23/11/2022 | 29/11/2022 | 30/11/2022 | João, Ana
| Personas | Pedro | 23/11/2022 | 29/11/2022 | 30/11/2022 | João
| Perfil - Questionário | Eduardo | 23/11/2022 | 29/11/2022 | 30/11/2022 | Thiago
| Elicitação - Introspecção | Arthur | 23/11/2022 | 29/11/2022 | 30/11/2022 | Ana
| Elicitação - Entrevista | Arthur | 23/11/2022 | 29/11/2022 | 30/11/2022 | João
| Elicitação - Brainstorm | Pedro | 23/11/2022 | 29/11/2022 | 30/11/2022 | Ana
| Priorização - MoSCoW | Ana | 23/11/2022 | 29/11/2022 | 30/11/2022 | João
| Priorização - First Things First | Ana | 23/11/2022 | 29/11/2022 | 30/11/2022 | João
| Priorização - Three-Level Scale | Ana | 23/11/2022 | 29/11/2022 | 30/11/2022 | Arthur
| Cronograma para elicitação de requisitos | Thiago | 23/11/2022 | 29/11/2022 | 30/11/2022 | Arthur
| Cronograma para priorização de requisitos | Thiago | 23/11/2022 | 29/11/2022 | 30/11/2022 | João
| Gravação de priorização - Three-Level Scale| Ana | 23/11/2022 | 29/11/2022 | 30/11/2022 | Eduardo
| Gravação de priorização - Moscow| Pedro | 23/11/2022 | 29/11/2022 | 30/11/2022 | Arthur
| Gravação de elicitação - entrevista | Pedro | 23/11/2022 | 29/11/2022 | 30/11/2022 | Eduardo
| Gravação de elicitação - introspecção | Arthur | 23/11/2022 | 29/11/2022 | 30/11/2022 | João
| Gravação de elicitação e priorização - brainstorm | Pedro, Arthur, Thiago, Eduardo | 23/11/2022 | 29/11/2022 | 30/11/2022 | João

*Tabela 2 - Tarefas para a Etapa 2*<br><br>

**Etapa 3**

| Tarefa | Responsáveis | Início | Fim | Revisão | Revisor |
| --- | --- | --- | --- | --- | --- |
| Cenários - especificações | João, Eduardo | 30/11/2022 | 11/12/2022 | 12/12/2022 | Thiago
| Cenários - criação| João, Eduardo | 30/11/2022 | 11/12/2022 | 12/12/2022 | Thiago
| Léxicos - especificações | Ana | 30/11/2022 | 11/12/2022 | 12/12/2022 | Pedro
| Léxicos - definições | Ana | 30/11/2022 | 11/12/2022 | 12/12/2022 | Pedro
| Casos de Uso - especificação | Pedro, Thiago | 02/12/2022 | 11/12/2022 | 12/12/2022 | Ana
| Casos de Uso - atores | Pedro, Thiago | 02/12/2022 | 11/12/2022 | 12/12/2022 | Ana
| Casos de Uso - diagrama | Pedro, Thiago | 02/12/2022 | 11/12/2022 | 12/12/2022 | Ana
| Especificação suplementar | Eduarto, Arthur | 02/12/2022 | 11/12/2022 | 12/12/2022 | João
| Modelo FURPS+ | Eduardo | 02/12/2022 | 11/12/2022 | 12/12/2022 | Arthur

*Tabela 3 - Tarefas para a Etapa 3*<br><br>

**Etapa 4**

| Tarefa | Responsáveis | Início | Fim | Revisão | Revisor |
| --- | --- | --- | --- | --- | --- |
| Histórias de usuário | Eduardo | 13/12/2022 | 03/01/2023 | 04/01/2023 | João
| Histórias de usuário - contato com usuário/persona| Pedro | 13/12/2022 | 03/01/2023 | 04/01/2023 | Thiago
| Histórias de usuário - critérios de aceitação | Arthur | 13/12/2022 | 03/01/2023 | 04/01/2023 | Ana
| Backlogs - épicos | Thiago | 13/12/2022 | 03/01/2023 | 04/01/2023 | Arthur
| Backlogs - temas | Thiago | 13/12/2022 | 03/01/2023 | 04/01/2023 | Arthur
| NFR Framework | Ana | 13/12/2022 | 03/01/2023 | 04/01/2023 | Eduardo
| Softgoals | Arthur | 13/12/2022 | 03/01/2023 | 04/01/2023 | João
| Impactos | João | 13/12/2022 | 03/01/2023 | 04/01/2023 | Thiago

*Tabela 4 - Tarefas para a Etapa 4*<br><br>

**Etapa 5**

| Tarefa | Responsáveis | Início | Fim | Revisão | Revisor |
| --- | --- | --- | --- | --- | --- |
| Verificação de requisitos | Ana, Pedro, Thiago | 05/01/2023 | 10/01/2023 | 11/01/2023 | João
| Validação de requisitos| João, Arthur, Eduardo | 05/01/2023 | 10/01/2023 | 11/01/2023 | Thiago

*Tabela 5 - Tarefas para a Etapa 5*<br><br>

**Etapa 6**

| Tarefa | Responsáveis | Início | Fim | Revisão | Revisor |
| --- | --- | --- | --- | --- | --- |
| Pós-rastreabilidade | Pedro, Thiago | 11/01/2023 | 15/01/2023 | 16/01/2023 | João
| Backward From| Ana, Arthur | 11/01/2023 | 15/01/2023 | 16/01/2023 | Thiago
| Forward From| João, Eduardo | 11/01/2023 | 15/01/2023 | 16/01/2023 | Ana
| Planejamento de verificação de artefatos | Ana, Pedro | 15/01/2023 | 18/01/2023 | 19/01/2023 | Arthur
| Relatos da verificação de artefatos | João, Thiago | 15/01/2023 | 18/01/2023 | 19/01/2023 | Eduardo

*Tabela 6 - Tarefas para a Etapa 6*<br><br>

</center>


## <a>Execução</a>

Durante a execução do projeto a equipe tentou realizar o mais fielmente possivel o cronograma Planejado, porem infelizmente não foi possível seguir a risca tal cronograma como pode ser visto no [Cronograma Realizado](../Planejamento/Roadmap/#cronograma-realizado), portanto na tabela a seguir está apresentado as 7 fases do nosso projeto, cada uma delas com sua respectiva descrição. 


### <a>1ª Etapa</a>

A primeira etapa do projeto se caracteriza principalmente pela formação da equipe e escolha do aplicativo, durante a primeria etapa do projeto pode se dizer que ela ira definir o projeto inteiro por isso a sua importancia, alem disso pode se dar destaque a alguns artefatos muito importante para o andamento do projeto, tais como o [Roadmap](../Planejamento/Roadmap.md) , as [Ferramentas Utilizadas](../Planejamento/Ferramentas.md) e os [Rich Pictures](../Planejamento/AplicativosAnalisados/#mei).

### <a>2ª Etapa</a>

A segunda etapa do projeto é caracterizada pela elicitação, nessa etapa a equipe tinha como objetivo listar tecnicas de [priorização](../Elicitacao/tecnicas-priorizacao.md) e [elicitação](../Elicitacao/index.md) as quais seriam utilizadas no projeto, alem de definir açguns artefatos muito importantes para o andamento do projeto tais como o [Perfil de Usúario](../Elicitacao/perfil.md) e o elenco de [Personas](../Elicitacao/personas.md).

### <a>3ª Etapa</a>

Na terceira etapa do projeto o objetivo principal da equipe era aprender e aplicar tecnicas de Modelagem de Requisitos portanto nesse etapa do projeto os artefatos desenvolvidos foram [Cenários](../Modelagem/Cenarios.md) , [Léxico](../Modelagem/Lexicos.md), [Use Cases](../Modelagem/CasosdeUso.md) e [Especificação Suplementar](../Modelagem/EspecificacaoSuplementar.md).

### <a>4ª Etapa</a>

Devido a complexidade no modelagem de requisitos a quate etapa apresenta como principal caracteristica ser uma continuação da terceira etapa, portanto com intuito de complementar a Modelagem inicial de requisitos aplicando principalmente os estudos realizados sobre o modelo agil tais como o Scrum, foram confecionados os seguintes artefatos [Histórias de Usuário](../Modelagem/UserCases.md), [Backlogs](../Modelagem/Agil/BacklogDoProduto.md), [NFR Framework](../Modelagem/NFRFramework.md).

### <a>5ª Etapa</a>

Na quinta etapa somos apresentados aos estudos de verificação e validação, para a melhora da qualidade individual de cada artefato, com o principio fundamentalmente didatico fomos introduzidos a analise, por meio de uma analise externa, portanto nesta primeira etapa de analise outro grupo realizou a analise do projeto em quanto o nosso grupo realizou a analise do grupo [Linkedin](../Analise/Linkedin/Verificacao/index.md).



## <a>Ferramentas</a>

## <a>Técnicas</a>

### <a>Planejamento</a>
Dentro do planejamento o grupo seguiu alguns passos para iniciarmos os trabalhos com relação ao MEI, a primeira etapa foi analisar alguns aplicativos e utilizar a técnica do "Rich Picture" para entender o sistema como um todo, depois de analisar todos Rich Pictures, o MEI foi escolhido. Tabém foi decidido a forma de ser trabalho, foi utilizado o sistema de Sprints, com [reuniões](https://requisitos-de-software.github.io/2022.2-MEI/Reunioes/) de forma predominante no sábado.

Nesse primeiro momento foi feito alguns documentos que auxiliam o trabalho, como por exemplo, [Heatmap](https://requisitos-de-software.github.io/2022.2-MEI/Planejamento/Heatmap/), [Roadmap](https://requisitos-de-software.github.io/2022.2-MEI/Planejamento/Roadmap/) e [Políticas de Trabalho](https://requisitos-de-software.github.io/2022.2-MEI/Politicas/CodigoDeConduta/).

Os participantes do Planejamento foram: Ana, Pedro, João Lucas, Thiago, Eduardo e Arthur

### <a>Elicitação</a>
O Grupo buscou algumas técnicas para elicitar os requisitos, o primeiro a ser trabalhado foi o questionário, porém não tivemos os resultados esperados para, portanto, não conseguimos utilizar esses dados e atrasamos em primeiro momento. Logo depois, conseguimos utilizar de forma correta 3 técnicas, sendo elas:

* [Brainstorming](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Brainstorming/) - Os participantes dessa técnica foram: João Lucas, Eduardo, Thiago e Pedro
* [Entrevista](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Entrevista/) - Os participante dessa técnica foi: Pedro
* [Introspecção](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Introspeccao/) - Os participante dessa técnica foi: Arthur

Com essas três técnicas, o grupo MEI conseguiu listar requisitos funcionais e não funcionais para serem trabalhados ao longo do projeto. Vale ressaltar a importância do trabalho com as [personas](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/personas/).

Os perfis de Usuário e as Personas foram elaborados por: Ana, Eduardo e Pedro.

Um último passo da Elicitação, foi a Priorização. O Grupo utilizou algumas técnicas para [priorizar](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/tecnicas-priorizacao/), podemos citar as 3:

* Moscow
* First Things First (FTF)
* Three-Level Scale

A Priorização foi realizada pela Ana.

### <a> Modelagem </a>
Foram utilizados algumas técnicas para modelar os requisitos. Aqui vamos comentar sobre um pouco de cada um:

#### <a>Cenários</a>
Os [cenários](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Cenarios/) estão presentes para representar algumas possíveis histórias. O Documento foi feito pelo: João Lucas e Eduardo

#### <a>Léxicos</a>
Os [Léxicos](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Lexicos/) estão presentes quando o grupo precisou identificar palavras-chaves ou frases com relação as etapas presentes no aplicativo. Foi desenvolvida por: Ana.

#### <a>Casos de Uso</a>
Os [Casos de Uso](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/CasosdeUso/) são processos que descrevem um conjunto de ações entre o usuário e o sistema e isso gera um resultado observável. Foi levantado tabelas e diagramas para representar os casos de uso. Desenvolvido por: Thiago, Pedro e Eduardo.

#### <a>Especificação Suplementar</a>
O Grupo buscou a metodologia FURPS+ para identificar as [especificações suplementares](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/EspecificacaoSuplementar/) e assim identificar informações adicionais sobre os requisitos. Foi desenvolvido por: Arthur e Eduardo.

#### <a>NFR Framework</a>
Utilizamos esse [framework](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/NFRFramework/) para conduzir melhor o processo de Design, colocando os requisitos não funcionais em primeiro lugar

#### <a>Histórias de Usuáriso</a>
As [histórias de usuários](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/UserCases/) levantaram desejos do usuário dentro do aplicativo e também seus objetivos. Desenvolvido por Thiago e Pedro Lucas.

#### <a>Backlog</a>
Por fim, fizemos uma lista de afazeres, conhecido como [Backlog](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/UserCases/). Feito por: Arthur

### <a>Pós-Rastreabilidade</a>
Aqui ligamos os requisitos que são desenvolvidos ao longo do ciclo de vida do projeto com seus artefatos. O Grupo desenvolveu 3 artefatos:

* [Backward-from](https://requisitos-de-software.github.io/2022.2-MEI/Pos-Rastreabilidade/BackwardFrom/) - Feito por: Pedro Lucas e Eduardo
* [Forward-from](https://requisitos-de-software.github.io/2022.2-MEI/Pos-Rastreabilidade/ForwardFrom/) - Feito por: Thiago e João Lucas
* [Matriz Geral](https://requisitos-de-software.github.io/2022.2-MEI/Pos-Rastreabilidade/MatrizGeral/) - Feito por: Ana Luiza e Arthur.

## <a>Artefatos</a>
A seguir estão apresentadas as tabelas referentes a cada etapa do projeto. Vale destacar que a **Etapa 5: Verificação e Validação** está apresentada no tópico [V&V](#vv).

### <a>Etapa 1: Planejamento</a>
A tabela 7 abaixo apresenta os artefatos criados durante o projeto na **Etapa 1: Planejamento**, com o nome de seus respectivos criadores e revisores.

<center>

|Artefato|Criador|Revisor|Data de Finalização|
|--------|-------|-------|-------------------|
|[Página inicial do projeto](../index.md)|[João Lucas](https://github.com/HacKairos)|[Thiago Oliveira](https://github.com/Thiab394)|20/11/2022|
|[Aplicativos Analisados](../Planejamento/AplicativosAnalisados.md)|[Ana Luiza](https://github.com/AnHoff)<br>[Pedro Lucas](https://github.com/PedroLSF)<br>[Thiago Oliveira](https://github.com/Thiab394)|[Ana Luiza](https://github.com/AnHoff)<br>[Pedro Lucas](https://github.com/PedroLSF)<br>[João Lucas](https://github.com/HacKairos)|30/11/2022|
|[Aplicativo Escolhido](../Planejamento/MEI.md)|[Ana Luiza](https://github.com/AnHoff)<br>[Pedro Lucas](https://github.com/PedroLSF)<br>[Thiago Oliveira](https://github.com/Thiab394)|[Ana Luiza](https://github.com/AnHoff)<br>[Pedro Lucas](https://github.com/PedroLSF)<br>[João Lucas](https://github.com/HacKairos)<br>[Eduardo](https://github.com/edudsan)|20/01/2023|
|[Metodologia e Processos](../Planejamento/Metodologia.md)|[Arthur Taylor](https://github.com/Eruel6)<br>[Thiago Oliveira](https://github.com/Thiab394)|[Arthur Taylor](https://github.com/Eruel6)<br>[Thiago Oliveira](https://github.com/Thiab394)<br> [João Lucas](https://github.com/HacKairos)| 30/11/2022|
|[Ferramentas](../Planejamento/Ferramentas.md)|[Ana Luiza](https://github.com/AnHoff)<br> [João Lucas](https://github.com/HacKairos)<br>[Thiago Oliveira](https://github.com/Thiab394)|  [Ana Luiza](https://github.com/AnHoff)<br>[João Lucas](https://github.com/HacKairos)|21/11/2022|
|[Heatmap](../Planejamento/Heatmap.md)|[Eduardo](https://github.com/edudsan)<br>[Thiago Oliveira](https://github.com/Thiab394)|[João Lucas](https://github.com/HacKairos)|30/11/2022|
|[Roadmap](../Planejamento/Roadmap.md)|[Arthur Taylor](https://github.com/Eruel6)<br>[Thiago Oliveira](https://github.com/Thiab394)<br>[Ana Luiza](https://github.com/AnHoff)|[Arthur Taylor](https://github.com/Eruel6)<br>[Thiago Oliveira](https://github.com/Thiab394)|09/12/2022|
|Políticas - [Código de Conduta para Colaboradores](../Politicas/CodigoDeConduta.md)|[João Lucas](https://github.com/HacKairos)| [Ana Luiza](https://github.com/AnHoff)|11/11/2022|
|Políticas - [Política de Contribuição](../Politicas/PolitcaDeContribuicao.md)|[João Lucas](https://github.com/HacKairos)|[Ana Luiza](https://github.com/AnHoff)|11/11/2022|
|Políticas - [Política de Issue](../Politicas/PolitcaDeIssue.md)|[João Lucas](https://github.com/HacKairos)|[Ana Luiza](https://github.com/AnHoff)|11/11/2022|
|Políticas - [Política de Branch](../Politicas/PolitcaDeBranch.md)|[João Lucas](https://github.com/HacKairos)|[Pedro Lucas](https://github.com/PedroLSF)|11/11/2022|
|Políticas - [Política de Commit](../Politicas/PolitcaDeCommit.md)|[João Lucas](https://github.com/HacKairos)<br>[Ana Luiza](https://github.com/AnHoff)|[João Lucas](https://github.com/HacKairos)<br>[Ana Luiza](https://github.com/AnHoff)|11/11/2022|
|Políticas - [Política de Pull Request](../Politicas/PolitcaDePR.md)|[João Lucas](https://github.com/HacKairos)|[Ana Luiza](https://github.com/AnHoff)|11/11/2022|
|Políticas - [Política de Segurança](../Politicas/PolitcaDeSeguranca.md)|[João Lucas](https://github.com/HacKairos)|[Ana Luiza](https://github.com/AnHoff)|11/11/2022|
|[Cronograma de Elicitação/Priorização](../Elicitacao/Cronogramas.md)|[Thiago Oliveira](https://github.com/Thiab394)|[Arthur Taylor](https://github.com/Eruel6)<br>[João Lucas](https://github.com/HacKairos)|07/12/2022|
|[Termo de Consentimento](../Elicitacao/ModeloTermoConsentimento.md)|[Ana Luiza](https://github.com/AnHoff)<br>|[Thiago Oliveira](https://github.com/Thiab394)<br>[Ana Luiza](https://github.com/AnHoff)<br>[Eduardo](https://github.com/edudsan)|20/01/2023|

*Tabela 7 - Artefatos realizados durante a etapa 1*
<br><br>

</center>

### <a>Etapa 2: Elicitação</a>
A tabela 8 abaixo apresenta os artefatos criados durante o projeto durante a **Etapa 2: Elicitação - Técnicas e Priorização**, com o nome de seus respectivos criadores e revisores.

<center>

|Artefato|Criador|Revisor|Data de Finalização|
|--------|-------|-------|-------------------|
|[Elicitação](../Elicitacao/index.md)|[Arthur Taylor](https://github.com/Eruel6)<br>[Thiago Oliveira](https://github.com/Thiab394)|[Arthur Taylor](https://github.com/Eruel6)<br>[João Lucas](https://github.com/HacKairos)| 30/11/2022|
|[Brainstorming](../Elicitacao/Brainstorming.md)|[Ana Luiza](https://github.com/AnHoff)<br>[João Lucas](https://github.com/HacKairos)<br>[Pedro Lucas](https://github.com/PedroLSF)|  [Ana Luiza](https://github.com/AnHoff)<br>[Pedro Lucas](https://github.com/PedroLSF)<br>[Arthur Taylor](https://github.com/Eruel6)|20/01/2023|
|[Entrevista](../Elicitacao/Entrevista.md)|[Pedro Lucas](https://github.com/PedroLSF)<br>[Ana Luiza](https://github.com/AnHoff)|[João Lucas](https://github.com/HacKairos)<br>[Eduardo](https://github.com/edudsan)|20/01/2023|
|[Introspecção](../Elicitacao/Introspeccao.md)|[Arthur Taylor](https://github.com/Eruel6)<br>[Ana Luiza](https://github.com/AnHoff)|[Arthur Taylor](https://github.com/Eruel6)<br>[Ana Luiza](https://github.com/AnHoff)|20/01/2023|
|[Perfil do Usuário](../Elicitacao/perfil.md)|[Eduardo](https://github.com/edudsan)<br>[Ana Luiza](https://github.com/AnHoff)| [João Lucas](https://github.com/HacKairos)<br>[Thiago Oliveira](https://github.com/Thiab394)|26/01/2023|
|[Persona](../Elicitacao/personas.md)|[Ana Luiza](https://github.com/AnHoff)<br>[Pedro Lucas](https://github.com/PedroLSF)|[João Lucas](https://github.com/HacKairos)|30/11/2022|
|[Priorização](../Elicitacao/tecnicas-priorizacao.md)|[Ana Luiza](https://github.com/AnHoff)|[Arthur Taylor](https://github.com/Eruel6)<br>[Thiago Oliveira](https://github.com/Thiab394)|04/12/2022|

*Tabela 8 - Artefatos realizados durante a etapa 2*
<br><br>

</center>

### <a>Etapas 3 e 4: Modelagem</a>
A tabela 9 abaixo apresenta os artefatos criados durante o projeto durante a **Etapas 3 e 4: Modelagem de Requisitos**, com o nome de seus respectivos criadores e revisores.

<center>

|Artefato|Criador|Revisor|Data de Finalização|
|--------|-------|-------|-------------------|
|[Cenários](../Modelagem/Cenarios.md)|[João Lucas](https://github.com/HacKairos)<br>[Eduardo](https://github.com/edudsan)|[Ana Luiza](https://github.com/AnHoff)| 10/12/2022|
|[Léxicos](../Modelagem/Lexicos.md)|[Ana Luiza](https://github.com/AnHoff)|[João Lucas](https://github.com/HacKairos)<br>[Pedro Lucas](https://github.com/PedroLSF)|10/12/2022|
|[Casos de Uso](../Modelagem/CasosdeUso.md)|[Pedro Lucas](https://github.com/PedroLSF)<br>[Eduardo](https://github.com/edudsan)<br>[Thiago Oliveira](https://github.com/Thiab394)|[Thiago Oliveira](https://github.com/Thiab394)<br>[Ana Luiza](https://github.com/AnHoff)<br>[Pedro Lucas](https://github.com/PedroLSF)|23/01/2023|
|[Especificação Suplementar](../Modelagem/EspecificacaoSuplementar.md)|[Arthur Taylor](https://github.com/Eruel6)<br>[Eduardo](https://github.com/edudsan)|[Ana Luiza](https://github.com/AnHoff)<br>[João Lucas](https://github.com/HacKairos)|04/01/2023|
|[NFR Framework](../Modelagem/NFRFramework.md)|[Ana Luiza](https://github.com/AnHoff)<br>[João Lucas](https://github.com/HacKairos)| [João Lucas](https://github.com/HacKairos)<br>[Ana Luiza](https://github.com/AnHoff)|28/12/2022|
|[Histórias de Usuário](../Modelagem/UserCases.md)|[Pedro Lucas](https://github.com/PedroLSF)<br>[Thiago Oliveira](https://github.com/Thiab394)|[Ana Luiza](https://github.com/AnHoff)<br>[Thiago Oliveira](https://github.com/Thiab394)|25/01/2023|
|[Backlog](../Modelagem/Agil/BacklogDoProduto.md)|[Arthur Taylor](https://github.com/Eruel6)| [Eduardo](https://github.com/edudsan)|02/01/2023|

*Tabela 9 - Artefatos realizados durante as etapas 3 e 4*
<br><br>

</center>

### <a>Etapa 6: Pós-Rastreabilidade</a>
A tabela 10 abaixo apresenta os artefatos criados durante o projeto durante a **Etapa 6: Pós-Rastreabilidade**, com o nome de seus respectivos criadores e revisores.

<center>

|Artefato|Criador|Revisor|Data de Finalização|
|--------|-------|-------|-------------------|
|[Backward-from](../Pos-Rastreabilidade/BackwardFrom.md)|[Pedro Lucas](https://github.com/PedroLSF)<br>[Eduardo](https://github.com/edudsan)|[João Lucas](https://github.com/HacKairos)|23/01/2023|
|[Forward-from](../Pos-Rastreabilidade/ForwardFrom.md)|[Thiago Oliveira](https://github.com/Thiab394)<br>[João Lucas](https://github.com/HacKairos)|[Thiago Oliveira](https://github.com/Thiab394)<br>[João Lucas](https://github.com/HacKairos)<br>[Ana Luiza](https://github.com/AnHoff)|27/01/2023|
|[Matriz Geral](../Pos-Rastreabilidade/MatrizGeral.md)|[Ana Luiza](https://github.com/AnHoff)|[Arthur Taylor](https://github.com/Eruel6)|23/01/2023|

*Tabela 10 - Artefatos realizados durante a etapa 6*
<br><br>

</center>

### <a>Contagem Individual</a>
A tabela 11 abaixo apresenta a quantidade total de artefatos criados e revisados por cada integrante. Vale lembrar que as gravações com os usuários e os artefatos de [V&V](#vv) não são contabilizadas na listagem.

<center>

|Integrante|Criados|Revisados|
|----------|-------|---------|
|[Ana Luiza](https://github.com/AnHoff)|15|18|
|[Arthur Taylor](https://github.com/Eruel6)|6|8|
|[Eduardo](https://github.com/edudsan)|6|4|
|[João Lucas](https://github.com/HacKairos)|12|16|
|[Pedro Lucas](https://github.com/PedroLSF)|8|6|
|[Thiago Oliveira](https://github.com/Thiab394)|13|9|

*Tabela 11 - Artefatos por integrante*
<br><br>

</center>

### <a>Comentários</a>

* O número total de artefatos criados é inferior à soma dos artefatos criados por cada integrante. Isso se deve ao fato de que diversos integrantes participaram da criação de um mesmo artefato;
* Os integrantes [Pedro Lucas](https://github.com/PedroLSF), [Eduardo](https://github.com/edudsan) e [Arthur Taylor](https://github.com/Eruel6) foram responsáveis por realizar as gravações com os usuários;
* O integrante [Arthur Taylor](https://github.com/Eruel6) foi o responsável por criar as atas de reunião e apresentações;
* O questionário sobre o perfil do usuário foi criado e divulgado pelo integrante [Eduardo](https://github.com/edudsan).

## <a>Resultados</a>
Acreditamos que o objetivo primordial desse projeto, aplicar na prática o que foi aprendido em sala de aula, foi alcançado de diferentes formas. No início, os resultados não foram satisfatórios, deixando muito a desejar. As técnicas e conceitos foram aplicados de forma incorreta e, com isso, o trabalho iniciou "com o pé esquerdo". Apesar desse fato, o grupo conseguiu se reorganizar e melhorar muito a qualidade dos artefatos que estavam sendo elaborados a partir das [Etapas 3 e 4](#etapas-3-e-4-modelagem), sem deixar de lado as melhorias a serem realizadas nos artefatos iniciais. Com isso em mente, pode-se afirmar que a aplicação de técnicas e conceitos aprendidos em sala foi realizada com sucesso durante o projeto.

O outro objetivo do projeto, não menos importante que o primeiro apresentado, era analisar um aplicativo. O MEI foi escolhido após a elaboração e análise dos diferentes [Rich Pictures](../Planejamento/AplicativosAnalisados.md) elaborados pelos integrantes do grupo. Após a escolha do aplicativo, foi possível iniciar a aplicação dos conceitos e ténicas aprendidos, por meio da realização das fases de **Planejamento**, **Elicitação e Priorização**, **Modelagem** e **Pós-rastreabilidade**.

Todos os integrantes presentes nas tabelas de [Artefatos](#artefatos) participaram ativamente do projeto. Seja por meio da elaboração direta de artefatos ou da realização de pesquisas e entrevistas com os usuários, todos participaram dando o melhor de si. Todos concordam: houve grande desenvolvimento de softskills. As mais notáveis foram:

* Organização;
* Planejamento;
* Resiliência.

A seguir, confira um resumo dos resultados mais notáveis do projeto.

### <a>Perfil do Usuário</a>
O [Perfil do Usuário](../Elicitacao/perfil.md) identificado pelo grupo é semelhante ao perfil encontrado em estudos realizados por outros pesquisadores [2]. Esse fato dá suporte aos dados obtidos pelo grupo, que são compatíveis com os obtidos por meio de pesquisas oficiais de grandes empresas.

### <a>Requisitos</a>
Diversos requisitos elicitados não são atendidos pelo aplicativo atual. Com isso em mente, foi possível realizar uma priorização de requisitos e determinar quais eram os mais importantes de serem implementados ou melhorados. Também foi possível criar [SIGs](../Modelagem/NFRFramework.md) que mapeiam de forma clara o que é e o que não é atendido pelo sistema atualmente.

### <a>Protótipo de Alta Fidelidade</a>
O [Protótipo de Alta Fidelidade](../Analise/Validacao/protAlta.md) foi elaborado pelo integrante [João Lucas](https://github.com/HacKairos), em colaboração com [Arthur Taylor](https://github.com/Eruel6), e aprovado por todo o grupo (Ana, Pedro, Thiago e Eduardo). Sua criação visava melhorar pontos críticos, como a segurança do aplicativo, a partir do resultado da análise e modelagem de requisitos. Confira aqui o [Protótipo](https://www.figma.com/proto/YVsTmRLQiocQb1d258RRZE/MEI?node-id=1%3A11&starting-point-node-id=1%3A9).

## <a>V&V</a>
### <a>Verificação</a>
Para realizar a verificação dos artefatos do projeto, foram escolhidas pessoas não envolvidas na criação de cada artefato. Com isso, buscava-se encontrar erros não percebidos pelo criador e/ou revisor do mesmo até então.

A metodologia adotada foi a [Inspeção](../Analise/Verificacao/#inspecao) com o auxílio de [Checklists](../Analise/#metodo-de-avaliacao). Na tabela X abaixo, Autor representa o criador da checklist e Revisor o responsável por aplicar a inspeção.

<center>

|Artefato|Autor|Revisor|Data de Aplicação|
|--------|-------|-------|-------------------|
|[Rich Picture](../Analise/Verificacao/Planejamento/VerificacaoRichPicture.md)|[Arthur Taylor](https://github.com/Eruel6)|[Ana Luiza](https://github.com/AnHoff)|09/01/2023|
|[Aplicativo Escolhido](../Analise/Verificacao/Planejamento/verificacaoAplicativoEscolhido.md)|[Eduardo](https://github.com/edudsan)|[João Lucas](https://github.com/HacKairos)|15/01/2023|
|[Termo de Consentimento](../Analise/Verificacao/Planejamento/verificacaoTermoConsentimento.md)|[Ana Luiza](https://github.com/AnHoff)|[João Lucas](https://github.com/HacKairos)|15/01/2023|
|[Brainstorming](../Analise/Verificacao/Elicitacao/Verifica%C3%A7%C3%A3oBrainstorming.md)|[Pedro Lucas](https://github.com/PedroLSF)|[João Lucas](https://github.com/HacKairos)|16/01/2023|
|[Entrevista](../Analise/Verificacao/Elicitacao/VerificacaoEntrevista.md)|[Pedro Lucas](https://github.com/PedroLSF)|[João Lucas](https://github.com/HacKairos)|16/01/2023|
|[Introspecção](../Analise/Verificacao/Elicitacao/VerificacaoInstropeccao.md)|[Pedro Lucas](https://github.com/PedroLSF)|[João Lucas](https://github.com/HacKairos)|16/01/2023|
|[Perfil de Usuário](../Analise/Verificacao/Elicitacao/VerificacaoPerfilUsuario.md)|[Arthur Taylor](https://github.com/Eruel6)|[João Lucas](https://github.com/HacKairos)|16/01/2023|
|[Personas](../Analise/Verificacao/Elicitacao/VerificacaoPersonas.md)|[Arthur Taylor](https://github.com/Eruel6)|[João Lucas](https://github.com/HacKairos)|16/01/2023|
|[Priorização](../Analise/Verificacao/Elicitacao/VerificacaoPriorizacao.md)|[Arthur Taylor](https://github.com/Eruel6)<br>[Ana Luiza](https://github.com/AnHoff)|[João Lucas](https://github.com/HacKairos)<br>[Arthur Taylor](https://github.com/Eruel6)|18/01/2023|
|[Léxicos](../Analise/Verificacao/Modelagem/VerificacaoLexicos.md)|[Thiago Oliveira](https://github.com/Thiab394)|[João Lucas](https://github.com/HacKairos)|16/01/2023|
|[Cenários](../Analise/Verificacao/Modelagem/VerificacaoCenarios.md)|[Thiago Oliveira](https://github.com/Thiab394)|[João Lucas](https://github.com/HacKairos)|16/01/2023|
|[Casos de Uso](../Analise/Verificacao/Modelagem//verificacaoCasosdeUso.md)|[Ana Luiza](https://github.com/AnHoff)|[João Lucas](https://github.com/HacKairos)|15/01/2023|
|[Especificação Suplementar](../Analise/Verificacao/Modelagem/VerificacaoEspecifacao.md)|[João Lucas](https://github.com/HacKairos)|[Eduardo](https://github.com/edudsan)|16/01/2023|
|[NFR Framework](../Analise/Verificacao/Modelagem/verificacaoNFRFramework.md)|[Eduardo](https://github.com/edudsan)|[João Lucas](https://github.com/HacKairos)|15/01/2023|
|[Backlog](../Analise/Verificacao/Modelagem/verificacaoBacklog.md)|[Eduardo](https://github.com/edudsan)|[João Lucas](https://github.com/HacKairos)|15/01/2023|

*Tabela 12 - Artefatos de verificação*
<br><br>

</center>

### <a>Validação</a>
Para realizar a [Validação](../Analise/Validacao/), foram escolhidas as técnicas de validação informal e prototipagem. Essas técnicas permitem que um stakeholder comente sobre o trabalho realizado até então.

<center>

|Técnica|Criador|Revisor|Data de Finalização|
|--------|-------|-------|-------------------|
|[Validação Informal](../Analise/Validacao/Informal.md)|[Thiago Oliveira](https://github.com/Thiab394)<br>[Ana Luiza](https://github.com/AnHoff)|[João Lucas](https://github.com/HacKairos)<br>[Ana Luiza](https://github.com/AnHoff)|16/01/2023|
|[Prototipagem](../Analise/Validacao/protAlta.md)|[Ana Luiza](https://github.com/AnHoff)<br>[João Lucas](https://github.com/HacKairos)|[João Lucas](https://github.com/HacKairos)<br>[Pedro Lucas](https://github.com/PedroLSF)|15/01/2023|

*Tabela 13 - Artefatos de validação*
<br><br>

</center>

## <a>BIbliografia</a>
[1] 2022.1-YouTube. Disponível em: https://requisitos-de-software.github.io/2022.1-Youtube/apresentacao-final/. Acesso em: 27 de Janeiro de 2023.

[2] Análise do perfil do Microempreendedor Individual (MEI). Disponível em: https://www.jurozero.sc.gov.br/padrao-categoria-noticias/342-analise-do-perfil-do-microempreendedor-individual-mei.html. Acesso em 20 de Janeiro de 2023.
