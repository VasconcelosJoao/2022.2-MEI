# Forward-from

## <a>Histórico de Versão</a>
|    Data    | Data Prevista de Revisão | Versão | Descrição | Autor  | Revisor |
| :--------: | :--------: | :----: | :-------: | :----: | :-----: |
| 23/01/2023 | 23/01/2023 | 1.0 | Criação do documento | [Thiago Oliveira](https://github.com/Thiab394) |[-](https://github.com/)  |


## 1. Introdução
Este documento tem como objetivo registrar a pós-rastreabilidade dos artefatos e requisitos do projeto, utilizando a metodologia "Forward-from", na qual
liga os requisitos gerados por meio da elicitação de requisitos, aos seus artefatos feitos durante o andamento do projeto e da disciplina, e também o seu estado
de implementação.

## 2. Metodologia
Para realizar a pós-rastreabilidade do projeto, utilizando a meotodologia forwar-from, será utilizado de dois tipos diferentes de tabelas, uma delas para requisitos
funcionais, e outra para requisitos não funcionais, e portanto separando tais requisitos em partes diferentes do documento.

Visto que os requisitos elicitados não foram todos chamados de RF(Requisito funcional) e RNF(Requisito não funcional), os requisitos serão chamados pelas siglas
da técnica de elicitação que foi usada, assim como foi colocado nos documentos de elicitação, tais siglas podendo serem vistas na seção abaixo. Porém não deixando
de serem separados em RF's e RNF's

Abaixo segue os modelos de tabelas que serão usados para os RF's e RNF's respectivamente:<br>
|           ID            |"Identificador do requisito"|
| :---------------------: | :-----------: |
|          Épico          |"Épico onde se encontra o requisito no backlog"|
|          Tema           |"Tema onde se encontra o requisito no backlog"|
|           US            |"História de usuário correspondente ao requisito"|
| Status da implementação |"Status da implementação do requisito"|
|        Artefatos        |"Artefatos derivados do requisito"|
|     Funcionalidade      |"Vídeo/print da tela onde esta implementada a funcionalidade"|

|          ID             |"Identificador do requisito"|
| :---------------------: | :------------------------: |
|           NFR           |"NFR derivado do requisito"|
|           ES            |"Especificação Suplementar derivada do requisito"|
| Status da implementação |"Status da implementação do requisito"|

## 3. Legenda:

- BS: Brainstorming
- ENT : Entrevista
- IS: Introspecção
- C: cenário
- UC: Caso de uso
- US: História de usuário
- ES: Especificação Suplementar
- NFR: NFR Framework

## 4. Requisitos Funcionais
### BS01

|           BS01            |O aplicativo deve instruir o [usuário](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Lexicos/#l17-usuario) para a criação do [CNPJ](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Lexicos/#l03-cnpj)|
| :---------------------: | :-----------: |
|          Épico          |[Cadastro e Autenticação](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Agil/BacklogDoProduto/#epico-1-cadastro-e-autenticacao)|
|          Tema           |[Feature 1 - Cadastro e Autenticação](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Agil/BacklogDoProduto/#epico-1-cadastro-e-autenticacao)|
|           US            |[US01](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/UserCases/#11-cadastro)|
| Status da implementação |"Status da implementação do requisito"|
|        Artefatos        |"Artefatos derivados do requisito"|
|     Funcionalidade      |"Vídeo/print da tela onde esta implementada a funcionalidade"|

### BS02

|           BS02            |Implementação de um sistema de [login](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Lexicos/#l01-acessar)|
| :---------------------: | :-----------: |
|          Épico          |[Cadastro e Autenticação](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Agil/BacklogDoProduto/#epico-1-cadastro-e-autenticacao)|
|          Tema           |[Feature 2 - Login](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Agil/BacklogDoProduto/#epico-1-cadastro-e-autenticacao)|
|           US            |[US03](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/UserCases/#21-login)|
| Status da implementação |"Status da implementação do requisito"|
|        Artefatos        |"Artefatos derivados do requisito"|
|     Funcionalidade      |"Vídeo/print da tela onde esta implementada a funcionalidade"|

### BS03

|           BS03            |O aplicativo deve [emitir](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Lexicos/#l09-emitir) um lembrete para o pagamento do [DAS](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Lexicos/#l07-das)|
| :---------------------: | :-----------: |
|          Épico          |[Configurações](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Agil/BacklogDoProduto/#epico-2-configuracoes)|
|          Tema           |[Feature 4 - Notificações](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Agil/BacklogDoProduto/#epico-2-configuracoes)|
|           US            |[US05](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/UserCases/#31-lembrete)|
| Status da implementação |"Status da implementação do requisito"|
|        Artefatos        |"Artefatos derivados do requisito"|
|     Funcionalidade      |"Vídeo/print da tela onde esta implementada a funcionalidade"|

### BS06

|           BS06            |O aplicativo deve [mostrar](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Lexicos/#l10-exibir) de forma clara se uma ação foi realizada com sucesso ou não|
| :---------------------: | :-----------: |
|          Épico          |[Configurações](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Agil/BacklogDoProduto/#epico-2-configuracoes)|
|          Tema           |[Feature 4 - Notificações](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Agil/BacklogDoProduto/#epico-2-configuracoes)|
|           US            |[US06](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/UserCases/#32-aviso)|
| Status da implementação |"Status da implementação do requisito"|
|        Artefatos        |"Artefatos derivados do requisito"|
|     Funcionalidade      |"Vídeo/print da tela onde esta implementada a funcionalidade"|

### BS07

|           BS07            |O aplicativo deve fornecer suporte para os [usuários](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Lexicos/#l17-usuario)|
| :---------------------: | :-----------: |
|          Épico          |[Suporte](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Agil/BacklogDoProduto/#epico-3-suporte)|
|          Tema           |[Feature 6 - Suporte](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Agil/BacklogDoProduto/#epico-3-suporte)|
|           US            |[US11](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/UserCases/#41-chat)|
| Status da implementação |"Status da implementação do requisito"|
|        Artefatos        |"Artefatos derivados do requisito"|
|     Funcionalidade      |"Vídeo/print da tela onde esta implementada a funcionalidade"|

### ENT05

|           ENT05            |O aplicativo deve realizar o [login](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Lexicos/#l01-acessar) em mais de uma [conta](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Lexicos/#l05-conta)|
| :---------------------: | :-----------: |
|          Épico          |[Cadastro e Autenticação](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Agil/BacklogDoProduto/#epico-1-cadastro-e-autenticacao)|
|          Tema           |[Feature 2 - Login](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Agil/BacklogDoProduto/#epico-1-cadastro-e-autenticacao)|
|           US            |[US03](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/UserCases/#21-login)|
| Status da implementação |"Status da implementação do requisito"|
|        Artefatos        |"Artefatos derivados do requisito"|
|     Funcionalidade      |"Vídeo/print da tela onde esta implementada a funcionalidade"|

### IS01

|           IS01            |Deve ser possível realizar [login](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Lexicos/#l01-acessar) a partir de um [CNPJ](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Lexicos/#l03-cnpj)|
| :---------------------: | :-----------: |
|          Épico          |[Cadastro e Autenticação](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Agil/BacklogDoProduto/#epico-1-cadastro-e-autenticacao)|
|          Tema           |[Feature 2 - Login](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Agil/BacklogDoProduto/#epico-1-cadastro-e-autenticacao)|
|           US            |[US03](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/UserCases/#21-login)|
| Status da implementação |"Status da implementação do requisito"|
|        Artefatos        |"Artefatos derivados do requisito"|
|     Funcionalidade      |"Vídeo/print da tela onde esta implementada a funcionalidade"|

### IS02

|           IS02            |Deve ser possível [emitir](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Lexicos/#l09-emitir) o [DAS](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Lexicos/#l07-das)|
| :---------------------: | :-----------: |
|          Épico          |[Financeiro](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Agil/BacklogDoProduto/#epico-4-financeiro)|
|          Tema           |[Feature 6 - Boletos](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Agil/BacklogDoProduto/#epico-4-financeiro)|
|           US            |[US14](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/UserCases/#51-emitir-boletos)|
| Status da implementação |"Status da implementação do requisito"|
|        Artefatos        |"Artefatos derivados do requisito"|
|     Funcionalidade      |"Vídeo/print da tela onde esta implementada a funcionalidade"|

### IS03

|           IS03            |Deve ser possível [Consultar](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Lexicos/#l04-consultar) [informações](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Lexicos/#l11-informacao) do [CNPJ](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Lexicos/#l03-cnpj)|
| :---------------------: | :-----------: |
|          Épico          |[Configurações](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Agil/BacklogDoProduto/#epico-2-configuracoes)|
|          Tema           |[Feature 5 - Perfil](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Agil/BacklogDoProduto/#epico-2-configuracoes)|
|           US            |[US16](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/UserCases/#53-informacoes-cnpj)|
| Status da implementação |"Status da implementação do requisito"|
|        Artefatos        |"Artefatos derivados do requisito"|
|     Funcionalidade      |"Vídeo/print da tela onde esta implementada a funcionalidade"|

### IS04

|           IS04            |Deve ser possível pedir [restituição](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Lexicos/#l15-restituir)|
| :---------------------: | :-----------: |
|          Épico          |[Financeiro](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Agil/BacklogDoProduto/#epico-4-financeiro)|
|          Tema           |[Feature 7 - Restituição](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Agil/BacklogDoProduto/#epico-4-financeiro)|
|           US            |[US15](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/UserCases/#52-solicitar-restituicao)|
| Status da implementação |"Status da implementação do requisito"|
|        Artefatos        |"Artefatos derivados do requisito"|
|     Funcionalidade      |"Vídeo/print da tela onde esta implementada a funcionalidade"|

### IS05

|           IS05            |Deve ser possível [consultar](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Lexicos/#l04-consultar) perguntas e respostas frequentes|
| :---------------------: | :-----------: |
|          Épico          |[Suporte](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Agil/BacklogDoProduto/#epico-3-suporte)|
|          Tema           |[Feature 6 - Suporte](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Agil/BacklogDoProduto/#epico-3-suporte)|
|           US            |[US13](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/UserCases/#43-faq)|
| Status da implementação |"Status da implementação do requisito"|
|        Artefatos        |"Artefatos derivados do requisito"|
|     Funcionalidade      |"Vídeo/print da tela onde esta implementada a funcionalidade"|

## 5. Requisitos Não-Funcionais
### BS04

|          BS04             |"Identificador do requisito"|
| :---------------------: | :------------------------: |
|           NFR           |"NFR derivado do requisito"|
|           ES            |"Especificação Suplementar derivada do requisito"|
| Status da implementação |"Status da implementação do requisito"|

### BS05

|          BS05             |"Identificador do requisito"|
| :---------------------: | :------------------------: |
|           NFR           |"NFR derivado do requisito"|
|           ES            |"Especificação Suplementar derivada do requisito"|
| Status da implementação |"Status da implementação do requisito"|

### BS08

|          BS08             |"Identificador do requisito"|
| :---------------------: | :------------------------: |
|           NFR           |"NFR derivado do requisito"|
|           ES            |"Especificação Suplementar derivada do requisito"|
| Status da implementação |"Status da implementação do requisito"|

### BS09

|          BS09             |"Identificador do requisito"|
| :---------------------: | :------------------------: |
|           NFR           |"NFR derivado do requisito"|
|           ES            |"Especificação Suplementar derivada do requisito"|
| Status da implementação |"Status da implementação do requisito"|

### BS010

|          BS010             |"Identificador do requisito"|
| :---------------------: | :------------------------: |
|           NFR           |"NFR derivado do requisito"|
|           ES            |"Especificação Suplementar derivada do requisito"|
| Status da implementação |"Status da implementação do requisito"|

### BS011

|          BS011             |"Identificador do requisito"|
| :---------------------: | :------------------------: |
|           NFR           |"NFR derivado do requisito"|
|           ES            |"Especificação Suplementar derivada do requisito"|
| Status da implementação |"Status da implementação do requisito"|

### BS012

|          BS012             |"Identificador do requisito"|
| :---------------------: | :------------------------: |
|           NFR           |"NFR derivado do requisito"|
|           ES            |"Especificação Suplementar derivada do requisito"|
| Status da implementação |"Status da implementação do requisito"|

### ENT01

|          ENT01             |"Identificador do requisito"|
| :---------------------: | :------------------------: |
|           NFR           |"NFR derivado do requisito"|
|           ES            |"Especificação Suplementar derivada do requisito"|
| Status da implementação |"Status da implementação do requisito"|

### ENT02

|          ENT02             |"Identificador do requisito"|
| :---------------------: | :------------------------: |
|           NFR           |"NFR derivado do requisito"|
|           ES            |"Especificação Suplementar derivada do requisito"|
| Status da implementação |"Status da implementação do requisito"|

### ENT03

|          ENT03             |"Identificador do requisito"|
| :---------------------: | :------------------------: |
|           NFR           |"NFR derivado do requisito"|
|           ES            |"Especificação Suplementar derivada do requisito"|
| Status da implementação |"Status da implementação do requisito"|

### ENT04

|          ENT04             |"Identificador do requisito"|
| :---------------------: | :------------------------: |
|           NFR           |"NFR derivado do requisito"|
|           ES            |"Especificação Suplementar derivada do requisito"|
| Status da implementação |"Status da implementação do requisito"|

### IS06

|          IS06             |"Identificador do requisito"|
| :---------------------: | :------------------------: |
|           NFR           |"NFR derivado do requisito"|
|           ES            |"Especificação Suplementar derivada do requisito"|
| Status da implementação |"Status da implementação do requisito"|

### IS07

|          IS07             |"Identificador do requisito"|
| :---------------------: | :------------------------: |
|           NFR           |"NFR derivado do requisito"|
|           ES            |"Especificação Suplementar derivada do requisito"|
| Status da implementação |"Status da implementação do requisito"|

### IS08

|          IS08             |"Identificador do requisito"|
| :---------------------: | :------------------------: |
|           NFR           |"NFR derivado do requisito"|
|           ES            |"Especificação Suplementar derivada do requisito"|
| Status da implementação |"Status da implementação do requisito"|

## Referencias

[1] SERRANO, Maurício; SERRANO, Milene. Requisitos - Aula 26. 1º/2022. Material apresentado para a disciplina de Requisitos de Software no curso de Engenharia de Software da UnB, FGA.

[2] Projeto Do Github - Noruh - da displina Requisitos de Software, da Universidade de Brasilia(UnB) do semestre 2022.1, disponivel [aqui](https://requisitos-de-software.github.io/2022.1-Noruh/)

[3] Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021) Interação Humano-Computador e Experiência do usuário. 
Autopublicação. ISBN: 978-65-00-19677-1.


