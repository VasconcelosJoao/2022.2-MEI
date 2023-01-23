# Forward-from

## <a>Histórico de Versão</a>
|    Data    | Data Prevista de Revisão | Versão |      Descrição       |                     Autor                      |                  Revisor                   |
| :--------: | :----------------------: | :----: | :------------------: | :--------------------------------------------: | :----------------------------------------: |
| 23/01/2023 |        23/01/2023        |  1.0   | Criação do documento | [Thiago Oliveira](https://github.com/Thiab394) | [João Lucas](https://github.com/HacKairos) |


## <a>Introdução</a>
Este documento tem como objetivo registrar a pós-rastreabilidade dos artefatos e requisitos do projeto, utilizando a metodologia "Forward-from", na qual
liga os requisitos gerados por meio da elicitação de requisitos, aos seus artefatos feitos durante o andamento do projeto e da disciplina, e também o seu estado
de implementação.

## <a>Metodologia</a>
Para realizar a pós-rastreabilidade do projeto, utilizando a meotodologia forwar-from, será utilizado de dois tipos diferentes de tabelas, uma delas para requisitos
funcionais, e outra para requisitos não funcionais, e portanto separando tais requisitos em partes diferentes do documento.

Visto que os requisitos elicitados não foram todos chamados de RF(Requisito funcional) e RNF(Requisito não funcional), os requisitos serão chamados pelas siglas
da técnica de elicitação que foi usada, assim como foi colocado nos documentos de elicitação, tais siglas podendo serem vistas na seção abaixPorém não deixando
de serem separados em RF's e RNF's

Abaixo segue os modelos de tabelas que serão usados para os RF's e RNF's respectivamente:<br>
<center>

|           ID            |                 "Identificador do requisito"                  |
| :---------------------: | :-----------------------------------------------------------: |
|          Épico          |        "Épico onde se encontra o requisito no backlog"        |
|          Tema           |        "Tema onde se encontra o requisito no backlog"         |
|           US            |       "História de usuário correspondente ao requisito"       |
| Status da implementação |            "Status da implementação do requisito"             |
|        Artefatos        |              "Artefatos derivados do requisito"               |
|     Funcionalidade      | "Vídeo/print da tela onde esta implementada a funcionalidade" |

|           ID            |           "Identificador do requisito"            |
| :---------------------: | :-----------------------------------------------: |
|           NFR           |            "NFR derivado do requisito"            |
|           ES            | "Especificação Suplementar derivada do requisito" |
| Status da implementação |      "Status da implementação do requisito"       |

</center>

## <a>Legenda:</a>

- BS: Brainstorming
- ENT: Entrevista
- IS: Introspecção
- C: Cenário
- L: Léxico
- UC: Caso de uso
- US: História de usuário
- ES: Especificação Suplementar
- NFR: NFR Framework

## <a>Requisitos Funcionais</a>
### <a>BS01</a>

|          BS01           |                             O aplicativo deve instruir o [usuário](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Lexicos/#l17-usuario) para a criação do [CNPJ](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Lexicos/#l03-cnpj)                             |
| :---------------------: | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|          Épico          |                                                                       [Cadastro e Autenticação](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Agil/BacklogDoProduto/#epico-1-cadastro-e-autenticacao)                                                                        |
|          Tema           |                                                                 [Feature 1 - Cadastro e Autenticação](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Agil/BacklogDoProduto/#epico-1-cadastro-e-autenticacao)                                                                  |
|           US            |                                                                                                 [US01](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/UserCases/#11-cadastro)                                                                                                 |
| Status da implementação |                                                                                                                            "Status da implementação do requisito"                                                                                                                            |
|        Artefatos        | [L17](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Lexicos/#l17-usuario)<br> [L03](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Lexicos/#l03-cnpj)<br> [UC02](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/CasosdeUso/#uc02-cadastro)<br> |
|     Funcionalidade      |                                                                                                                "Vídeo/print da tela onde esta implementada a funcionalidade"                                                                                                                 |

### <a>BS02</a>

|          BS02           |                                      Implementação de um sistema de [login](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Lexicos/#l01-acessar)                                      |
| :---------------------: | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|          Épico          |                           [Cadastro e Autenticação](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Agil/BacklogDoProduto/#epico-1-cadastro-e-autenticacao)                            |
|          Tema           |                              [Feature 2 - Login](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Agil/BacklogDoProduto/#epico-1-cadastro-e-autenticacao)                               |
|           US            |                                                      [US03](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/UserCases/#21-login)                                                       |
| Status da implementação |                                                                                "Status da implementação do requisito"                                                                                |
|        Artefatos        | [L01](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Lexicos/#l01-acessar)<br> [UC01](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/CasosdeUso/#uc01-fazer-login)<br> |
|     Funcionalidade      |                                                                    "Vídeo/print da tela onde esta implementada a funcionalidade"                                                                     |

### <a>BS03</a>

|          BS03           |                            O aplicativo deve [emitir](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Lexicos/#l09-emitir) um lembrete para o pagamento do [DAS](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Lexicos/#l07-das)                             |
| :---------------------: | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|          Épico          |                                                                                [Configurações](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Agil/BacklogDoProduto/#epico-2-configuracoes)                                                                                 |
|          Tema           |                                                                           [Feature 4 - Notificações](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Agil/BacklogDoProduto/#epico-2-configuracoes)                                                                           |
|           US            |                                                                                                [US05](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/UserCases/#31-lembrete)                                                                                                |
| Status da implementação |                                                                                                                           "Status da implementação do requisito"                                                                                                                           |
|        Artefatos        | [L09](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Lexicos/#l09-emitir)<br> [L07](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Lexicos/#l07-das)<br> [UC04](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/CasosdeUso/#uc04-lembrete)<br> |
|     Funcionalidade      |                                                                                                               "Vídeo/print da tela onde esta implementada a funcionalidade"                                                                                                                |

### <a>BS06</a>

|          BS06           | O aplicativo deve [mostrar](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Lexicos/#l10-exibir) de forma clara se uma ação foi realizada com sucesso ou não |
| :---------------------: | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|          Épico          |                        [Configurações](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Agil/BacklogDoProduto/#epico-2-configuracoes)                         |
|          Tema           |                   [Feature 4 - Notificações](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Agil/BacklogDoProduto/#epico-2-configuracoes)                   |
|           US            |                                         [US06](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/UserCases/#32-aviso)                                          |
| Status da implementação |                                                                   "Status da implementação do requisito"                                                                   |
|        Artefatos        |                                          [L10](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Lexicos/#l10-exibir)                                          |
|     Funcionalidade      |                                                       "Vídeo/print da tela onde esta implementada a funcionalidade"                                                        |

### <a>BS07</a>

|          BS07           |                                                                                O aplicativo deve fornecer suporte para os [usuários](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Lexicos/#l17-usuario)                                                                                |
| :---------------------: | :-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|          Épico          |                                                                                             [Suporte](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Agil/BacklogDoProduto/#epico-3-suporte)                                                                                             |
|          Tema           |                                                                                       [Feature 6 - Suporte](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Agil/BacklogDoProduto/#epico-3-suporte)                                                                                       |
|           US            |                                                                                                        [US11](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/UserCases/#41-chat)                                                                                                         |
| Status da implementação |                                                                                                                                 "Status da implementação do requisito"                                                                                                                                  |
|        Artefatos        | [C02](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Cenarios/#cenarios_1)<br> [L17](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Lexicos/#l17-usuario)<br> [UC03](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/CasosdeUso/#uc03-acesso-a-suporte)<br> |
|     Funcionalidade      |                                                                                                                      "Vídeo/print da tela onde esta implementada a funcionalidade"                                                                                                                      |

### <a>ENT05</a>

|          ENT05          |                                O aplicativo deve realizar o [login](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Lexicos/#l01-acessar) em mais de uma [conta](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Lexicos/#l05-conta)                                 |
| :---------------------: | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|          Épico          |                                                                         [Cadastro e Autenticação](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Agil/BacklogDoProduto/#epico-1-cadastro-e-autenticacao)                                                                          |
|          Tema           |                                                                            [Feature 2 - Login](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Agil/BacklogDoProduto/#epico-1-cadastro-e-autenticacao)                                                                             |
|           US            |                                                                                                    [US03](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/UserCases/#21-login)                                                                                                     |
| Status da implementação |                                                                                                                              "Status da implementação do requisito"                                                                                                                              |
|        Artefatos        | [L01](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Lexicos/#l01-acessar)<br> [L05](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Lexicos/#l05-conta)<br> [UC01](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/CasosdeUso/#uc01-fazer-login)<br> |
|     Funcionalidade      |                                                                                                                  "Vídeo/print da tela onde esta implementada a funcionalidade"                                                                                                                   |

### <a>IS01</a>

|          IS01           |                                  Deve ser possível realizar [login](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Lexicos/#l01-acessar) a partir de um [CNPJ](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Lexicos/#l03-cnpj)                                  |
| :---------------------: | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|          Épico          |                                                                         [Cadastro e Autenticação](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Agil/BacklogDoProduto/#epico-1-cadastro-e-autenticacao)                                                                         |
|          Tema           |                                                                            [Feature 2 - Login](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Agil/BacklogDoProduto/#epico-1-cadastro-e-autenticacao)                                                                            |
|           US            |                                                                                                    [US03](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/UserCases/#21-login)                                                                                                    |
| Status da implementação |                                                                                                                             "Status da implementação do requisito"                                                                                                                              |
|        Artefatos        | [L01](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Lexicos/#l01-acessar)<br> [L03](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Lexicos/#l03-cnpj)<br> [UC01](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/CasosdeUso/#uc01-fazer-login)<br> |
|     Funcionalidade      |                                                                                                                  "Vídeo/print da tela onde esta implementada a funcionalidade"                                                                                                                  |

### <a>IS02</a>

|          IS02           |                                      Deve ser possível [emitir](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Lexicos/#l09-emitir) o [DAS](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Lexicos/#l07-das)                                       |
| :---------------------: | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|          Épico          |                                                                              [Financeiro](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Agil/BacklogDoProduto/#epico-4-financeiro)                                                                               |
|          Tema           |                                                                          [Feature 6 - Boletos](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Agil/BacklogDoProduto/#epico-4-financeiro)                                                                          |
|           US            |                                                                                        [US14](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/UserCases/#51-emitir-boletos)                                                                                        |
| Status da implementação |                                                                                                                      "Status da implementação do requisito"                                                                                                                      |
|        Artefatos        | [C01](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Cenarios/#cenarios_1)<br> [L09](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Lexicos/#l09-emitir)<br> [L07](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Lexicos/#l07-das) |
|     Funcionalidade      |                                                                                                          "Vídeo/print da tela onde esta implementada a funcionalidade"                                                                                                           |

### <a>IS03</a>

|          IS03           |                                 Deve ser possível [Consultar](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Lexicos/#l04-consultar) [informações](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Lexicos/#l11-informacao) do [CNPJ](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Lexicos/#l03-cnpj)                                 |
| :---------------------: | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|          Épico          |                                                                                                                             [Configurações](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Agil/BacklogDoProduto/#epico-2-configuracoes)                                                                                                                             |
|          Tema           |                                                                                                                          [Feature 5 - Perfil](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Agil/BacklogDoProduto/#epico-2-configuracoes)                                                                                                                           |
|           US            |                                                                                                                                        [US16](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/UserCases/#53-informacoes-cnpj)                                                                                                                                         |
| Status da implementação |                                                                                                                                                                       "Status da implementação do requisito"                                                                                                                                                                        |
|        Artefatos        | [C06](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Cenarios/#cenarios_1)<br> [L04](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Lexicos/#l04-consultar)<br>[L11](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Lexicos/#l11-informacao)<br>[L03](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Lexicos/#l03-cnpj) |
|     Funcionalidade      |                                                                                                                                                            "Vídeo/print da tela onde esta implementada a funcionalidade"                                                                                                                                                            |

### <a>IS04</a>

|          IS04           |                                  Deve ser possível pedir [restituição](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Lexicos/#l15-restituir)                                  |
| :---------------------: | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|          Épico          |                                     [Financeiro](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Agil/BacklogDoProduto/#epico-4-financeiro)                                     |
|          Tema           |                              [Feature 7 - Restituição](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Agil/BacklogDoProduto/#epico-4-financeiro)                               |
|           US            |                                           [US15](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/UserCases/#52-solicitar-restituicao)                                           |
| Status da implementação |                                                                            "Status da implementação do requisito"                                                                             |
|        Artefatos        | [C10](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Cenarios/#cenarios_1)<br> [L15](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Lexicos/#l15-restituir)<br> |
|     Funcionalidade      |                                                                 "Vídeo/print da tela onde esta implementada a funcionalidade"                                                                 |

### <a>IS05</a>

|          IS05           |                                                                           Deve ser possível [consultar](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Lexicos/#l04-consultar) perguntas e respostas frequentes                                                                            |
| :---------------------: | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|          Épico          |                                                                                              [Suporte](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Agil/BacklogDoProduto/#epico-3-suporte)                                                                                              |
|          Tema           |                                                                                        [Feature 6 - Suporte](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Agil/BacklogDoProduto/#epico-3-suporte)                                                                                        |
|           US            |                                                                                                          [US13](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/UserCases/#43-faq)                                                                                                          |
| Status da implementação |                                                                                                                                  "Status da implementação do requisito"                                                                                                                                   |
|        Artefatos        | [C02](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Cenarios/#cenarios_1)<br> [L04](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Lexicos/#l04-consultar)<br> [UC03](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/CasosdeUso/#uc03-acesso-a-suporte)<br> |
|     Funcionalidade      |                                                                                                                       "Vídeo/print da tela onde esta implementada a funcionalidade"                                                                                                                       |

## <a>Requisitos Não-Funcionais</a>
### <a>BS04</a>

|          BS04           |           "Identificador do requisito"            |
| :---------------------: | :-----------------------------------------------: |
|           NFR           |            "NFR derivado do requisito"            |
|           ES            | "Especificação Suplementar derivada do requisito" |
| Status da implementação |      "Status da implementação do requisito"       |

### <a>BS05</a>

|          BS05           |           "Identificador do requisito"            |
| :---------------------: | :-----------------------------------------------: |
|           NFR           |            "NFR derivado do requisito"            |
|           ES            | "Especificação Suplementar derivada do requisito" |
| Status da implementação |      "Status da implementação do requisito"       |

### <a>BS08</a>

|          BS08           |           "Identificador do requisito"            |
| :---------------------: | :-----------------------------------------------: |
|           NFR           |            "NFR derivado do requisito"            |
|           ES            | "Especificação Suplementar derivada do requisito" |
| Status da implementação |      "Status da implementação do requisito"       |

### <a>BS09</a>

|          BS09           |           "Identificador do requisito"            |
| :---------------------: | :-----------------------------------------------: |
|           NFR           |            "NFR derivado do requisito"            |
|           ES            | "Especificação Suplementar derivada do requisito" |
| Status da implementação |      "Status da implementação do requisito"       |

### <a>BS010</a>

|          BS010          |           "Identificador do requisito"            |
| :---------------------: | :-----------------------------------------------: |
|           NFR           |            "NFR derivado do requisito"            |
|           ES            | "Especificação Suplementar derivada do requisito" |
| Status da implementação |      "Status da implementação do requisito"       |

### <a>BS011</a>

|          BS011          |           "Identificador do requisito"            |
| :---------------------: | :-----------------------------------------------: |
|           NFR           |            "NFR derivado do requisito"            |
|           ES            | "Especificação Suplementar derivada do requisito" |
| Status da implementação |      "Status da implementação do requisito"       |

### <a>BS012</a>

|          BS012          |           "Identificador do requisito"            |
| :---------------------: | :-----------------------------------------------: |
|           NFR           |            "NFR derivado do requisito"            |
|           ES            | "Especificação Suplementar derivada do requisito" |
| Status da implementação |      "Status da implementação do requisito"       |

### <a>ENT01</a>

|          ENT01          |           "Identificador do requisito"            |
| :---------------------: | :-----------------------------------------------: |
|           NFR           |            "NFR derivado do requisito"            |
|           ES            | "Especificação Suplementar derivada do requisito" |
| Status da implementação |      "Status da implementação do requisito"       |

### <a>ENT02</a>

|          ENT02          |           "Identificador do requisito"            |
| :---------------------: | :-----------------------------------------------: |
|           NFR           |            "NFR derivado do requisito"            |
|           ES            | "Especificação Suplementar derivada do requisito" |
| Status da implementação |      "Status da implementação do requisito"       |

### <a>ENT03</a>

|          ENT03          |           "Identificador do requisito"            |
| :---------------------: | :-----------------------------------------------: |
|           NFR           |            "NFR derivado do requisito"            |
|           ES            | "Especificação Suplementar derivada do requisito" |
| Status da implementação |      "Status da implementação do requisito"       |

### <a>ENT04</a>

|          ENT04          |           "Identificador do requisito"            |
| :---------------------: | :-----------------------------------------------: |
|           NFR           |            "NFR derivado do requisito"            |
|           ES            | "Especificação Suplementar derivada do requisito" |
| Status da implementação |      "Status da implementação do requisito"       |

### <a>IS06</a>

|          IS06           |           "Identificador do requisito"            |
| :---------------------: | :-----------------------------------------------: |
|           NFR           |            "NFR derivado do requisito"            |
|           ES            | "Especificação Suplementar derivada do requisito" |
| Status da implementação |      "Status da implementação do requisito"       |

### <a>IS07</a>

|          IS07           |           "Identificador do requisito"            |
| :---------------------: | :-----------------------------------------------: |
|           NFR           |            "NFR derivado do requisito"            |
|           ES            | "Especificação Suplementar derivada do requisito" |
| Status da implementação |      "Status da implementação do requisito"       |

### <a>IS08</a>

|          IS08           |           "Identificador do requisito"            |
| :---------------------: | :-----------------------------------------------: |
|           NFR           |            "NFR derivado do requisito"            |
|           ES            | "Especificação Suplementar derivada do requisito" |
| Status da implementação |      "Status da implementação do requisito"       |

## <a>Referencias</a>

[1] SERRANO, Maurício; SERRANO, MilenRequisitos - Aula 21º/202Material apresentado para a disciplina de Requisitos de Software no curso de Engenharia de Software da UnB, FGA.

[2] Projeto Do Github - Noruh - da displina Requisitos de Software, da Universidade de Brasilia(UnB) do semestre 2022.1, disponivel [aqui](https://requisitos-de-software.github.io/2022.1-Noruh/)

[3] Barbosa, J.; Silva, da; Silveira, S.; Gasparini, I.; Darin, T.; Barbosa, (2021) Interação Humano-Computador e Experiência do usuári
AutopublicaçãISBN: 978-65-00-19677-1.


