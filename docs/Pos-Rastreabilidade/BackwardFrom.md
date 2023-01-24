# Backward-from

## <a>Histórico de Versão</a>
|    Data    | Data Prevista de Revisão | Versão |      Descrição       |                   Autor                    |                  Revisor                   |
| :--------: | :----------------------: | :----: | :------------------: | :----------------------------------------: | :----------------------------------------: |
| 23/01/2023 |        23/01/2023        |  1.0   | Criação do documento | [Pedro Lucas](https://github.com/PedroLSF) e [Eduardo](https://github.com/edudsan) | [João Lucas](https://github.com/HacKairos) |


## <a>Introdução</a>
A pós-rastreabilidade visa ligar os elementos/artefatos desenvolvidos durante o ciclo de vida do projeto. Portanto, o documento terá como objetivo registrar a pós-rastreabilidade dos artefatos e requisitos do projeto, utilizando a metodologia "Backward-From".

## <a>Metodologia</a>
Para realizar a pós-rastreabilidade do projeto, utilizando a meotodologia backward-from, será utilizado um tipo de tabelas com as seguintes colunas:

* ID
* Descrição
* Técnica Utilizada

O Documento irá tratar de forma similar os Requisitos Funcionais e Não Funcionais, colocando eles na mesma tabela.

<center>

Abaixo segue os modelos de tabelas que serão usados para os RF's e RNF's respectivamente:<br>

|  ID   |    Descrição     |    Técnica Utilizada     |
| :---: | :--------------: | :----------------------: |
|   1   | "Descrição aqui" | "Técnica Utilizada aqui" |


_Tabela 1 - Exemplo_

</center>

## <a>Legenda</a>

- BS: Brainstorming
- ENT : Entrevista
- IS: Introspecção

## <a>Requisitos Funcionais e Não Funcionais</a>

|  ID   |                                    Descrição                                     |                                                                                                                          Técnica Utilizada                                                                                                                          |
| :---: | :------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|  RF1  |                 O Usuário deve conseguir cadastrar e autenticar                  |                                              [BS01](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Brainstorming/), [ENT1](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Entrevista/)                                              |
|  RF2  |                  O Usuário deve ser capaz de realizar um login                   |  [BS02](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Brainstorming/), [IS01](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Introspeccao/) e [ENT5](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Entrevista/)   |
|  RF3  |        O Usuário deve conseguir ativar lembretes para o pagamento do DAS         |                                                                                        [BS03](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Brainstorming/)                                                                                        |
|  RF4  |      O Usuário deve receber avisos para as operações realizadas com sucesso      |                                              [BS06](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Brainstorming/), [ENT4](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Entrevista/)                                              |
|  RF5  |                O Usuário deve ter acesso ao suporte do aplicativo                |                                             [BS07](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Brainstorming/), [IS05](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Introspeccao/)                                             |
|  RF6  |        O Usuário deve conseguir ativar lembretes para o pagamento do DAS         |                                                                                        [BS03](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Brainstorming/)                                                                                        |
|  RNF7  | O Usuário deve conseguir ir até o final da operação antes de realizar outra ação |                                              [ENT2](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Entrevista/), [BS04](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Brainstorming/)                                              |
|  RNF8  |              O Usuário deve conseguir utilizar o sistema sem erros               |                                              [ENT3](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Entrevista/), [BS05](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Brainstorming/)                                              |
|  RNF9  |        O Usuário deve conseguir utilizar o sistema em diversos aparelhos         | [BS08](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Brainstorming/), [IS06](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Introspeccao/) e [BS10](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Brainstorming/) |
| RNF10  |                     O Sistema deve validar o CNPJ utilizado                      |                                             [BS09](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Brainstorming/), [IS07](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Introspeccao/)                                             |
| RNF11  |                O Sistema deve abranger todos os tipos de usuários                |                                             [BS11](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Brainstorming/), [IS08](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Introspeccao/)                                             |
| RNF12  |                O Sistema deve abranger todos os tipos de usuários                | [BS11](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Brainstorming/), [IS08](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Introspeccao/) e [BS12](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Brainstorming/) |
| RF13  |                      O Usuário deve conseguir emitir o DAS                       |                                                                                        [IS02](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Introspeccao/)                                                                                         |
| RF14  |      O Usuário deve conseguir obter informações sobre o status do seu CNPJ       |                                                                                        [IS03](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Introspeccao/)                                                                                         |
| RF15  |                  O Usuário deve conseguir solicitar Restituição                  |                                                                                        [IS04](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Introspeccao/)                                                                                         |

# Elos funcionais

### RF1

**Categoria:** Desenvolvimento

**Elementos Rastreáveis:**
Brainstorm: [BS01](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Brainstorming/)
Entrevista: [ENT1](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Entrevista/) 

**Elos:**
Agregação: [ENT1](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Entrevista/)    Agrega: [BS01](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Brainstorming/)


### RF2

**Categoria:** Desenvolvimento

**Elementos Rastreáveis:**
Brainstorm: [BS02](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Brainstorming/) 
Entrevista: [ENT5](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Entrevista/) 
Introspecção: [IS01](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Introspeccao/)

**Elos:**
Agregação: [ENT5](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Entrevista/)   Agrega: [IS01](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Introspeccao/) e  [BS02](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Brainstorming/)


### RF3

**Categoria:** Desenvolvimento
  
**Elementos Rastreáveis:**
Brainstorm: [BS03](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Brainstorming/)
  
**Elos:**
* Não possui artefatos para moldar o elo


### RF4

**Categoria:** Desenvolvimento

**Elementos Rastreáveis:**
Brainstorm: [BS06](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Brainstorming/)
Entrevista: [ENT4](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Entrevista/)

**Elos:**
Agregação: [ENT4](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Entrevista/)
   Agrega: [BS06](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Brainstorming/)


### RF5

**Categoria:** Desenvolvimento

**Elementos Rastreáveis:**
Brainstorm: [BS07](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Brainstorming/)
Introspecção: [IS05](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Introspeccao/)

**Elos:**
Agregação: , [IS05](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Introspeccao/)  Agrega: [BS07](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Brainstorming/)


### RF6

**Categoria:** Desenvolvimento

**Elementos Rastreáveis:**
Brainstorm: [BS03](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Brainstorming/)

**Elos:**
* Não possui artefatos para moldar o elo


### RNF7

**Categoria:** Desenvolvimento

**Elementos Rastreáveis:**
Brainstorm: [BS04](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Brainstorming/)
Entrevista: [ENT2](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Entrevista/)

**Elos:**
Agregação: [ENT2](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Entrevista/)  Agrega: [BS04](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Brainstorming/)


### RNF8

**Categoria:** Desenvolvimento

**Elementos Rastreáveis:**
Brainstorm: [BS05](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Brainstorming/)
Entrevista: [ENT3](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Entrevista/)

**Elos:**
Agregação: [BS05](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Brainstorming/)  Agrega: [ENT3](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Entrevista/)


### RNF9

**Categoria:** Desenvolvimento

**Elementos Rastreáveis:**
Brainstorm: [BS08](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Brainstorming/) [BS10](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Brainstorming/)
Introspecção: [IS06](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Introspeccao/) 

**Elos:**
Agregação: [IS06](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Introspeccao/)  Agrega: [BS08](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Brainstorming/) e [BS10](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Brainstorming/)
Representação: [BS08](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Brainstorming/) e [BS10](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Brainstorming/)   Representa: [IS06](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Introspeccao/)


### RNF10

**Categoria:** Desenvolvimento

**Elementos Rastreáveis:**
Brainstorm: [BS09](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Brainstorming/)
Introspecção: [IS07](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Introspeccao/) 

**Elos:**
Agregação: [BS09](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Brainstorming/)  Agrega: [IS07](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Introspeccao/)  


### RNF11

**Categoria:** Desenvolvimento

**Elementos Rastreáveis:**
Brainstorm: [BS11](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Brainstorming/)
Introspecção: [IS08](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Introspeccao/) 

**Elos:**
Agregação: [BS11](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Brainstorming/)  Agrega: [IS08](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Introspeccao/) 


### RNF12

**Categoria:** Desenvolvimento

**Elementos Rastreáveis:**
Brainstorm: [BS11](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Brainstorming/) e [BS12](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Brainstorming/)
Introspecção: [IS08](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Introspeccao/) 

**Elos:**
Agregação: [BS11](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Brainstorming/) e [BS12](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Brainstorming/)  Agrega: [IS08](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Introspeccao/) 
Representação: [IS08](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Introspeccao/)      Representa: [BS11](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Brainstorming/) e [BS12](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Brainstorming/)


### RF13

**Categoria:** Desenvolvimento

**Elementos Rastreáveis:**
Introspecção: [IS02](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Introspeccao/)

**Elos:**
* Não possui artefatos para moldar o elo


### RF14

**Categoria:** Desenvolvimento

**Elementos Rastreáveis:**
Introspecção: [IS03](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Introspeccao/)       

**Elos:**
* Não possui artefatos para moldar o elo


### RF15

**Categoria:** Desenvolvimento

**Elementos Rastreáveis:**
Introspecção: [IS04](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Introspeccao/)

**Elos:**
* Não possui artefatos para moldar o elo


## <a>Referencias</a>

[1] SERRANO, Maurício; SERRANO, MilenRequisitos - Aula 21º/202Material apresentado para a disciplina de Requisitos de Software no curso de Engenharia de Software da UnB, FGA.

[2] Projeto Do Github - Noruh - da displina Requisitos de Software, da Universidade de Brasilia(UnB) do semestre 2022.1, disponivel [aqui](https://requisitos-de-software.github.io/2022.1-Noruh/)

[3] Barbosa, J.; Silva, da; Silveira, S.; Gasparini, I.; Darin, T.; Barbosa, (2021) Interação Humano-Computador e Experiência do usuári
AutopublicaçãISBN: 978-65-00-19677-1.

