# Backward-from

## <a>Histórico de Versão</a>
|    Data    | Data Prevista de Revisão | Versão |      Descrição       |                   Autor                    |                  Revisor                   |
| :--------: | :----------------------: | :----: | :------------------: | :----------------------------------------: | :----------------------------------------: |
| 23/01/2023 |        23/01/2023        |  1.0   | Criação do documento | [Pedro Lucas](https://github.com/PedroLSF) | [João Lucas](https://github.com/HacKairos) |


## <a>Introdução</a>
A pós-ratreabilidade visa ligar os elementos/artefatos desenvolvidos durante o ciclo de vida do projetPortanto, o documento terá como objetivo registrar a pós-rastreabilidade dos artefatos e requisitos do projeto, utilizando a metodologia "Backward-From".

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
|  RF7  | O Usuário deve conseguir ir até o final da operação antes de realizar outra ação |                                              [ENT2](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Entrevista/), [BS04](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Brainstorming/)                                              |
|  RF8  |              O Usuário deve conseguir utilizar o sistema sem erros               |                                              [ENT3](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Entrevista/), [BS05](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Brainstorming/)                                              |
|  RF9  |        O Usuário deve conseguir utilizar o sistema em diversos aparelhos         | [BS08](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Brainstorming/), [IS06](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Introspeccao/) e [BS10](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Brainstorming/) |
| RF10  |                     O Sistema deve validar o CNPJ utilizado                      |                                             [BS09](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Brainstorming/), [IS07](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Introspeccao/)                                             |
| RF11  |                O Sistema deve abranger todos os tipos de usuários                |                                             [BS11](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Brainstorming/), [IS08](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Introspeccao/)                                             |
| RF12  |                O Sistema deve abranger todos os tipos de usuários                | [BS11](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Brainstorming/), [IS08](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Introspeccao/) e [BS12](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Brainstorming/) |
| RF14  |                      O Usuário deve conseguir emitir o DAS                       |                                                                                        [IS02](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Introspeccao/)                                                                                         |
| RF15  |      O Usuário deve conseguir obter informações sobre o status do seu CNPJ       |                                                                                        [IS03](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Introspeccao/)                                                                                         |
| RF16  |                  O Usuário deve conseguir solicitar Restituição                  |                                                                                        [IS04](https://requisitos-de-software.github.io/2022.2-MEI/Elicitacao/Introspeccao/)                                                                                         |


## <a>Referencias</a>

[1] SERRANO, Maurício; SERRANO, MilenRequisitos - Aula 21º/202Material apresentado para a disciplina de Requisitos de Software no curso de Engenharia de Software da UnB, FGA.

[2] Projeto Do Github - Noruh - da displina Requisitos de Software, da Universidade de Brasilia(UnB) do semestre 2022.1, disponivel [aqui](https://requisitos-de-software.github.io/2022.1-Noruh/)

[3] Barbosa, J.; Silva, da; Silveira, S.; Gasparini, I.; Darin, T.; Barbosa, (2021) Interação Humano-Computador e Experiência do usuári
AutopublicaçãISBN: 978-65-00-19677-1.

