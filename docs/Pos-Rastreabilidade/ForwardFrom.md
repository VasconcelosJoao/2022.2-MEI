# Forward-from

## <a>Histórico de Versão</a>
|    Data    | Data Prevista de Revisão | Versão |        Descrição         |                     Autor                      |                  Revisor                   |
| :--------: | :----------------------: | :----: | :----------------------: | :--------------------------------------------: | :----------------------------------------: |
| 23/01/2023 |        23/01/2023        |  1.0   |   Criação do documento   | [Thiago Oliveira](https://github.com/Thiab394) | [João Lucas](https://github.com/HacKairos) |
| 23/01/2023 |        23/01/2023        |  1.1   | Finalização do documento |   [João Lucas](https://github.com/HacKairos)   | [-](https://github.com/) |


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

## <a>Legenda</a>

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

<center>

### <a>BS01</a>

|          BS01           |      O aplicativo deve instruir o [usuário](../../Modelagem/Lexicos/#l17-usuario) para a criação do [CNPJ](../../Modelagem/Lexicos/#l03-cnpj)      |
| :---------------------: | :------------------------------------------------------------------------------------------------------------------------------------------------: |
|          Épico          |                         [Cadastro e Autenticação](../../Modelagem/Agil/BacklogDoProduto/#epico-1-cadastro-e-autenticacao)                          |
|          Tema           |                   [Feature 1 - Cadastro e Autenticação](../../Modelagem/Agil/BacklogDoProduto/#epico-1-cadastro-e-autenticacao)                    |
|           US            |                                                   [US01](../../Modelagem/UserCases/#11-cadastro)                                                   |
| Status da implementação |                                                              Parcialmente Incompleto                                                               |
|        Artefatos        | [L17](../../Modelagem/Lexicos/#l17-usuario)<br> [L03](../../Modelagem/Lexicos/#l03-cnpj)<br> [UC02](../../Modelagem/CasosdeUso/#uc02-cadastro)<br> |
|     Funcionalidade      |                                 <img src="../../assets/forwardfrom/Loginlogin.png" width="100" height="100"></img>                                 |

### <a>BS02</a>

|          BS02           |               Implementação de um sistema de [login](../../Modelagem/Lexicos/#l01-acessar)               |
| :---------------------: | :------------------------------------------------------------------------------------------------------: |
|          Épico          |    [Cadastro e Autenticação](../../Modelagem/Agil/BacklogDoProduto/#epico-1-cadastro-e-autenticacao)     |
|          Tema           |       [Feature 2 - Login](../../Modelagem/Agil/BacklogDoProduto/#epico-1-cadastro-e-autenticacao)        |
|           US            |                               [US03](../../Modelagem/UserCases/#21-login)                                |
| Status da implementação |                                                 Completo                                                 |
|        Artefatos        | [L01](../../Modelagem/Lexicos/#l01-acessar)<br> [UC01](../../Modelagem/CasosdeUso/#uc01-fazer-login)<br> |
|     Funcionalidade      |              <img src="../../assets/forwardfrom/Login.gif" width="100" height="100"></img>               |

### <a>BS03</a>

|          BS03           |     O aplicativo deve [emitir](../../Modelagem/Lexicos/#l09-emitir) um lembrete para o pagamento do [DAS](../../Modelagem/Lexicos/#l07-das)      |
| :---------------------: | :----------------------------------------------------------------------------------------------------------------------------------------------: |
|          Épico          |                                  [Configurações](../../Modelagem/Agil/BacklogDoProduto/#epico-2-configuracoes)                                   |
|          Tema           |                             [Feature 4 - Notificações](../../Modelagem/Agil/BacklogDoProduto/#epico-2-configuracoes)                             |
|           US            |                                                  [US05](../../Modelagem/UserCases/#31-lembrete)                                                  |
| Status da implementação |                                                                    Incompleto                                                                    |
|        Artefatos        | [L09](../../Modelagem/Lexicos/#l09-emitir)<br> [L07](../../Modelagem/Lexicos/#l07-das)<br> [UC04](../../Modelagem/CasosdeUso/#uc04-lembrete)<br> |
|     Funcionalidade      |                               <img src="../../assets/forwardfrom/MenuInicial.png" width="100" height="100"></img>                                |

### <a>BS06</a>

|          BS06           | O aplicativo deve [mostrar](../../Modelagem/Lexicos/#l10-exibir) de forma clara se uma ação foi realizada com sucesso ou não |
| :---------------------: | :--------------------------------------------------------------------------------------------------------------------------: |
|          Épico          |                        [Configurações](../../Modelagem/Agil/BacklogDoProduto/#epico-2-configuracoes)                         |
|          Tema           |                   [Feature 4 - Notificações](../../Modelagem/Agil/BacklogDoProduto/#epico-2-configuracoes)                   |
|           US            |                                         [US06](../../Modelagem/UserCases/#32-aviso)                                          |
| Status da implementação |                                                          Imcompleto                                                          |
|        Artefatos        |                                          [L10](../../Modelagem/Lexicos/#l10-exibir)                                          |
|     Funcionalidade      |                         <img src="../../assets/forwardfrom/DAS.png" width="100" height="100"></img>                          |

### <a>BS07</a>

|          BS07           |                                  O aplicativo deve fornecer suporte para os [usuários](../../Modelagem/Lexicos/#l17-usuario)                                  |
| :---------------------: | :-----------------------------------------------------------------------------------------------------------------------------------------------------------: |
|          Épico          |                                               [Suporte](../../Modelagem/Agil/BacklogDoProduto/#epico-3-suporte)                                               |
|          Tema           |                                         [Feature 6 - Suporte](../../Modelagem/Agil/BacklogDoProduto/#epico-3-suporte)                                         |
|           US            |                                                          [US11](../../Modelagem/UserCases/#41-chat)                                                           |
| Status da implementação |                                                                          Imcompleto                                                                           |
|        Artefatos        | [C02](../../Modelagem/Cenarios/#cenarios_1)<br> [L17](../../Modelagem/Lexicos/#l17-usuario)<br> [UC03](../../Modelagem/CasosdeUso/#uc03-acesso-a-suporte)<br> |
|     Funcionalidade      |                                      <img src="../../assets/forwardfrom/MenuInicial.png" width="100" height="100"></img>                                      |

### <a>ENT05</a>

|          ENT05          |         O aplicativo deve realizar o [login](../../Modelagem/Lexicos/#l01-acessar) em mais de uma [conta](../../Modelagem/Lexicos/#l05-conta)          |
| :---------------------: | :----------------------------------------------------------------------------------------------------------------------------------------------------: |
|          Épico          |                           [Cadastro e Autenticação](../../Modelagem/Agil/BacklogDoProduto/#epico-1-cadastro-e-autenticacao)                            |
|          Tema           |                              [Feature 2 - Login](../../Modelagem/Agil/BacklogDoProduto/#epico-1-cadastro-e-autenticacao)                               |
|           US            |                                                      [US03](../../Modelagem/UserCases/#21-login)                                                       |
| Status da implementação |                                                                       Incompleto                                                                       |
|        Artefatos        | [L01](../../Modelagem/Lexicos/#l01-acessar)<br> [L05](../../Modelagem/Lexicos/#l05-conta)<br> [UC01](../../Modelagem/CasosdeUso/#uc01-fazer-login)<br> |
|     Funcionalidade      |                                   <img src="../../assets/forwardfrom/Loginlogin.png" width="100" height="100"></img>                                   |

### <a>IS01</a>

|          IS01           |           Deve ser possível realizar [login](../../Modelagem/Lexicos/#l01-acessar) a partir de um [CNPJ](../../Modelagem/Lexicos/#l03-cnpj)           |
| :---------------------: | :---------------------------------------------------------------------------------------------------------------------------------------------------: |
|          Épico          |                           [Cadastro e Autenticação](../../Modelagem/Agil/BacklogDoProduto/#epico-1-cadastro-e-autenticacao)                           |
|          Tema           |                              [Feature 2 - Login](../../Modelagem/Agil/BacklogDoProduto/#epico-1-cadastro-e-autenticacao)                              |
|           US            |                                                      [US03](../../Modelagem/UserCases/#21-login)                                                      |
| Status da implementação |                                                                       Completo                                                                        |
|        Artefatos        | [L01](../../Modelagem/Lexicos/#l01-acessar)<br> [L03](../../Modelagem/Lexicos/#l03-cnpj)<br> [UC01](../../Modelagem/CasosdeUso/#uc01-fazer-login)<br> |
|     Funcionalidade      |                                <img src="../../assets/forwardfrom/CodigodeAcesso.png" width="100" height="100"></img>                                 |

### <a>IS02</a>

|          IS02           |               Deve ser possível [emitir](../../Modelagem/Lexicos/#l09-emitir) o [DAS](../../Modelagem/Lexicos/#l07-das)                |
| :---------------------: | :------------------------------------------------------------------------------------------------------------------------------------: |
|          Épico          |                                [Financeiro](../../Modelagem/Agil/BacklogDoProduto/#epico-4-financeiro)                                 |
|          Tema           |                            [Feature 6 - Boletos](../../Modelagem/Agil/BacklogDoProduto/#epico-4-financeiro)                            |
|           US            |                                          [US14](../../Modelagem/UserCases/#51-emitir-boletos)                                          |
| Status da implementação |                                                                Completo                                                                |
|        Artefatos        | [C01](../../Modelagem/Cenarios/#cenarios_1)<br> [L09](../../Modelagem/Lexicos/#l09-emitir)<br> [L07](../../Modelagem/Lexicos/#l07-das) |
|     Funcionalidade      |                              <img src="../../assets/forwardfrom/DAS.png" width="100" height="100"></img>                               |

### <a>IS03</a>

|          IS03           |          Deve ser possível [Consultar](../../Modelagem/Lexicos/#l04-consultar) [informações](../../Modelagem/Lexicos/#l11-informacao) do [CNPJ](../../Modelagem/Lexicos/#l03-cnpj)          |
| :---------------------: | :-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|          Épico          |                                                        [Configurações](../../Modelagem/Agil/BacklogDoProduto/#epico-2-configuracoes)                                                        |
|          Tema           |                                                     [Feature 5 - Perfil](../../Modelagem/Agil/BacklogDoProduto/#epico-2-configuracoes)                                                      |
|           US            |                                                                   [US16](../../Modelagem/UserCases/#53-informacoes-cnpj)                                                                    |
| Status da implementação |                                                                                          Completo                                                                                           |
|        Artefatos        | [C06](../../Modelagem/Cenarios/#cenarios_1)<br> [L04](../../Modelagem/Lexicos/#l04-consultar)<br>[L11](../../Modelagem/Lexicos/#l11-informacao)<br>[L03](../../Modelagem/Lexicos/#l03-cnpj) |
|     Funcionalidade      |                                                        <img src="../../assets/forwardfrom/cnpj.png" width="100" height="100"></img>                                                         |

### <a>IS04</a>

|          IS04           |           Deve ser possível pedir [restituição](../../Modelagem/Lexicos/#l15-restituir)           |
| :---------------------: | :-----------------------------------------------------------------------------------------------: |
|          Épico          |              [Financeiro](../../Modelagem/Agil/BacklogDoProduto/#epico-4-financeiro)              |
|          Tema           |       [Feature 7 - Restituição](../../Modelagem/Agil/BacklogDoProduto/#epico-4-financeiro)        |
|           US            |                    [US15](../../Modelagem/UserCases/#52-solicitar-restituicao)                    |
| Status da implementação |                                             Completo                                              |
|        Artefatos        | [C10](../../Modelagem/Cenarios/#cenarios_1)<br> [L15](../../Modelagem/Lexicos/#l15-restituir)<br> |
|     Funcionalidade      |          <img src="../../assets/forwardfrom/Pedido.png" width="100" height="100"></img>           |

### <a>IS05</a>

|          IS05           |                             Deve ser possível [consultar](../../Modelagem/Lexicos/#l04-consultar) perguntas e respostas frequentes                              |
| :---------------------: | :-------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|          Épico          |                                                [Suporte](../../Modelagem/Agil/BacklogDoProduto/#epico-3-suporte)                                                |
|          Tema           |                                          [Feature 6 - Suporte](../../Modelagem/Agil/BacklogDoProduto/#epico-3-suporte)                                          |
|           US            |                                                            [US13](../../Modelagem/UserCases/#43-faq)                                                            |
| Status da implementação |                                                                           Incompleto                                                                            |
|        Artefatos        | [C02](../../Modelagem/Cenarios/#cenarios_1)<br> [L04](../../Modelagem/Lexicos/#l04-consultar)<br> [UC03](../../Modelagem/CasosdeUso/#uc03-acesso-a-suporte)<br> |
|     Funcionalidade      |                                       <img src="../../assets/forwardfrom/MenuInicial.png" width="100" height="100"></img>                                       |

</center>

## <a>Requisitos Não-Funcionais</a>

<center>

### <a>BS04</a>

|          BS04           |      O aplicativo deve obter dados dentro do próprio aplicativo      |
| :---------------------: | :------------------------------------------------------------------: |
|           NFR           |    [SIG de Desempenho](../../Modelagem/NFRFramework/#desempenho)     |
|           ES            | [Performance](../../Modelagem/EspecificacaoSuplementar/#performance) |
| Status da implementação |                               Completo                               |

### <a>BS05</a>

|          BS05           | O aplicativo deve solicitar autorização para pegar dados de outros sites do governo |
| :---------------------: | :---------------------------------------------------------------------------------: |
|           NFR           |            [SIG de Desempenho](../../Modelagem/NFRFramework/#desempenho)            |
|           ES            |     [Confiabilidade](../../Modelagem/EspecificacaoSuplementar/#confiabilidade)      |
| Status da implementação |                                     Incompleto                                      |

### <a>BS08</a>

|          BS08           | O aplicativo deve ser possível de ser utilizado na maioria dos modelos de dispositivos |
| :---------------------: | :------------------------------------------------------------------------------------: |
|           NFR           |        [SIG de Suportabilidade](../../Modelagem/NFRFramework/#suportabilidade)         |
|           ES            |      [Suportabilidade](../../Modelagem/EspecificacaoSuplementar/#suportabilidade)      |
| Status da implementação |                                        Completo                                        |

### <a>BS09</a>

|          BS09           | O aplicativo deve validar a [pessoa](../../Modelagem/Lexicos/#l17-usuario) que está utilizando o [CNPJ](../../Modelagem/Lexicos/#l03-cnpj) |
| :---------------------: | :----------------------------------------------------------------------------------------------------------------------------------------: |
|           NFR           |                                   [SIG de Confiabilidade](../../Modelagem/NFRFramework/#confiabilidade)                                    |
|           ES            |                                                                   [-]()                                                                    |
| Status da implementação |                                                                  Completo                                                                  |

### <a>BS010</a>

|          BS010          | O aplicativo deve ser possível de ser utilizado na maioria dos modelos de SO |
| :---------------------: | :--------------------------------------------------------------------------: |
|           NFR           |   [SIG de Suportabilidade](../../Modelagem/NFRFramework/#suportabilidade)    |
|           ES            | [Suportabilidade](../../Modelagem/EspecificacaoSuplementar/#suportabilidade) |
| Status da implementação |                                   Completo                                   |

### <a>BS011</a>

|          BS011          | O aplicativo deve ser acessível para [usuário](../../Modelagem/Lexicos/#l17-usuario) com algum tipo de deficiência |
| :---------------------: | :----------------------------------------------------------------------------------------------------------------: |
|           NFR           |                          [SIG de Usabilidade](../../Modelagem/NFRFramework/#usabilidade)                           |
|           ES            |                        [Usabilidade](../../Modelagem/EspecificacaoSuplementar/#usabilidade)                        |
| Status da implementação |                                                      Completo                                                      |

### <a>BS012</a>

|          BS012          |    O aplicativo deve conter texto que seja de fácil entendimento     |
| :---------------------: | :------------------------------------------------------------------: |
|           NFR           |   [SIG de Usabilidade](../../Modelagem/NFRFramework/#usabilidade)    |
|           ES            | [Usabilidade](../../Modelagem/EspecificacaoSuplementar/#usabilidade) |
| Status da implementação |                               Completo                               |

### <a>ENT01</a>

|          ENT01          | O aplicativo deve solicitar o [CNPJ](../../Modelagem/Lexicos/#l03-cnpj) apenas uma vez |
| :---------------------: | :------------------------------------------------------------------------------------: |
|           NFR           |         [SIG de Confiabilidade](../../Modelagem/NFRFramework/#confiabilidade)          |
|           ES            |                                         [-]()                                          |
| Status da implementação |                                        Completo                                        |

### <a>ENT02</a>

|          ENT02          | O aplicativo deve ir até o final da operação antes de realizar qualquer outra etapa |
| :---------------------: | :---------------------------------------------------------------------------------: |
|           NFR           |            [SIG de Desempenho](../../Modelagem/NFRFramework/#desempenho)            |
|           ES            |                                        [-]()                                        |
| Status da implementação |                                      Completo                                       |

### <a>ENT03</a>

|          ENT03          | O aplicativo deve evitar os erros e telas brancas através do uso |
| :---------------------: | :--------------------------------------------------------------: |
|           NFR           | [SIG de Usabilidade](../../Modelagem/NFRFramework/#usabilidade)  |
|           ES            |                              [-]()                               |
| Status da implementação |                             Completo                             |

### <a>ENT04</a>

|          ENT04          | O aplicativo deve salvar as [informações](../../Modelagem/Lexicos/#l11-informacao) |
| :---------------------: | :--------------------------------------------------------------------------------: |
|           NFR           |           [SIG de Desempenho](../../Modelagem/NFRFramework/#desempenho)            |
|           ES            |        [Performance](../../Modelagem/EspecificacaoSuplementar/#performance)        |
| Status da implementação |                                      Completo                                      |

### <a>IS06</a>

|          IS06           |       O aplicativo deve ser suportado pelos principais sistemas mobile       |
| :---------------------: | :--------------------------------------------------------------------------: |
|           NFR           |   [SIG de Suportabilidade](../../Modelagem/NFRFramework/#suportabilidade)    |
|           ES            | [Suportabilidade](../../Modelagem/EspecificacaoSuplementar/#suportabilidade) |
| Status da implementação |                                   Completo                                   |

### <a>IS07</a>

|          IS07           | Deve se exigir um [CNPJ](../../Modelagem/Lexicos/#l03-cnpj) para acesso do aplicativo |
| :---------------------: | :-----------------------------------------------------------------------------------: |
|           NFR           |         [SIG de Confiabilidade](../../Modelagem/NFRFramework/#confiabilidade)         |
|           ES            |         [Usabilidade](../../Modelagem/EspecificacaoSuplementar/#usabilidade)          |
| Status da implementação |                                       Completo                                        |

### <a>IS08</a>

|          IS08           | O aplicativo deve ser de fácil entendimento e uso por seus [usuários](../../Modelagem/Lexicos/#l17-usuario) |
| :---------------------: | :---------------------------------------------------------------------------------------------------------: |
|           NFR           |                       [SIG de Usabilidade](../../Modelagem/NFRFramework/#usabilidade)                       |
|           ES            |                    [Usabilidade](../../Modelagem/EspecificacaoSuplementar/#usabilidade)                     |
| Status da implementação |                                                  Completo                                                   |

</center>

## <a>Referencias</a>

[1] SERRANO, Maurício; SERRANO, MilenRequisitos - Aula 21º/202Material apresentado para a disciplina de Requisitos de Software no curso de Engenharia de Software da UnB, FGA.

[2] Projeto Do Github - Noruh - da displina Requisitos de Software, da Universidade de Brasilia(UnB) do semestre 2022.1, disponivel [aqui](https://requisitos-de-software.github.io/2022.1-Noruh/)

[3] Barbosa, J.; Silva, da; Silveira, S.; Gasparini, I.; Darin, T.; Barbosa, (2021) Interação Humano-Computador e Experiência do usuári
AutopublicaçãISBN: 978-65-00-19677-1.


