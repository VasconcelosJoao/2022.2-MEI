# Matriz Geral
## <a>Histórico de Versão</a>
|    Data    | Data Prevista de Revisão | Versão | Descrição | Autor  | Revisor |
| :--------: | :----------------------: | :----: | :-------: | :----: | :-----: |
| 22/01/2023 | 23/01/2023 | 1.0 | Criação do documento | [Ana Luiza](https://github.com/AnHoff) | [Arthur Taylor](https://github.com/Eruel6) |

## <a>Introdução</a>
A matriz geral elaborada e apresentada neste documento tem o objetivo de melhorar a visualização da pós-rastreabilidade dos requisitos identificados durante o projeto. A matriz reúne informações presentes nos documentos [Backward-From](./BackwardFrom.md) e [Forward-From](./ForwardFrom.md). [1]

## <a>Metodologia</a>
A matriz possui 8 colunas com o propósito de promover os dados de forma mais clara e completa possível. São elas:

* **ID**: identificação de cada item da matriz;
* **Descrição**: título ou resumo dos itens da matriz;
* **Elicitação**: identifica quais técnicas foram utilizadas para elicitar os requisitos;
* **Artefatos**: identifica quais artefatos foram elaborados a partir dos requisitos;
* **Implementação**:
    * 🟢: o requisito está completamente implementado;
    * 🟡: o requisito está parcialmente implementado;
    * 🔴: o requisito não foi implementado;
* **Forward-From**: link para seu rastro em forward-from.

## <a>Matriz Geral</a>
A tabela 1 abaixo apresenta a matriz elaborada:

<center>
  
|  ID   | Descrição | Elicitação | Artefatos | Implementação  | Forward-from |
| :---: | :-------: | :--------: | :-------: | :------------: | :----------: |
| RF01  | O aplicativo deve instruir o [usuário](../../Modelagem/Lexicos/#l17-usuario) para a criação do [CNPJ](../../Modelagem/Lexicos/#l03-cnpj) | Brainstorm | [US01](../../Modelagem/UserCases/#11-cadastro)<br>[L17](../../Modelagem/Lexicos/#l17-usuario)<br>[L03](../../Modelagem/Lexicos/#l03-cnpj)<br>[UC02](../../Modelagem/CasosdeUso/#uc02-cadastro) | 🔴  | [BS01](../ForwardFrom/#bs01)|
| RF02  | Implementação de um sistema de [login](../../Modelagem/Lexicos/#l01-acessar) | Brainstorm | [US03](../../Modelagem/UserCases/#21-login)<br>[L01](../../Modelagem/Lexicos/#l01-acessar)<br> [UC01](../../Modelagem/CasosdeUso/#uc01-fazer-login) | 🟢  | [BS02](../ForwardFrom/#bs02)|
| RF03  | O aplicativo deve [emitir](../../Modelagem/Lexicos/#l09-emitir) um lembrete para o pagamento do [DAS](../../Modelagem/Lexicos/#l07-das) | Brainstorm | [US05](../../Modelagem/UserCases/#31-lembrete)<br>[L09](../../Modelagem/Lexicos/#l09-emitir)<br> [L07](../../Modelagem/Lexicos/#l07-das)<br> [UC04](../../Modelagem/CasosdeUso/#uc04-lembrete) | 🔴  | [BS03](../ForwardFrom/#bs03)|
| RF04  | O aplicativo deve [mostrar](../../Modelagem/Lexicos/#l10-exibir) de forma clara se uma ação foi realizada com sucesso ou não | Brainstorm | [US06](../../Modelagem/UserCases/#32-aviso)<br>[L09](../../Modelagem/Lexicos/#l09-emitir)<br> [L10](../../Modelagem/Lexicos/#l10-exibir) | 🟡  | [BS06](../ForwardFrom/#bs06)|
| RF05  | O aplicativo deve fornecer suporte para os [usuários](../../Modelagem/Lexicos/#l17-usuario) | Brainstorm | [US11](../../Modelagem/UserCases/#41-chat)<br>[C02](../../Modelagem/Cenarios/#cenarios_1)<br> [L17](../../Modelagem/Lexicos/#l17-usuario)<br> [UC03](../../Modelagem/CasosdeUso/#uc03-acesso-a-suporte) | 🟢  | [BS07](../ForwardFrom/#bs07)|
| RF06  | O aplicativo deve realizar o [login](../../Modelagem/Lexicos/#l01-acessar) em mais de uma [conta](../../Modelagem/Lexicos/#l05-conta) | Entrevista | [US03](../../Modelagem/UserCases/#21-login)<br>[L01](../../Modelagem/Lexicos/#l01-acessar)<br> [L05](../../Modelagem/Lexicos/#l05-conta)<br> [UC01](../../Modelagem/CasosdeUso/#uc01-fazer-login) | 🔴  | [ENT05](../ForwardFrom/#ent05)|
| RF07  | Deve ser possível realizar [login](../../Modelagem/Lexicos/#l01-acessar) a partir de um [CNPJ](../../Modelagem/Lexicos/#l03-cnpj) | Introspecção | [US03](../../Modelagem/UserCases/#21-login)<br>[L01](../../Modelagem/Lexicos/#l01-acessar)<br> [L03](../../Modelagem/Lexicos/#l03-cnpj)<br> [UC01](../../Modelagem/CasosdeUso/#uc01-fazer-login) | 🟢  | [IS01](../ForwardFrom/#is01)|
| RF08  | Deve ser possível [emitir](../../Modelagem/Lexicos/#l09-emitir) o [DAS](../../Modelagem/Lexicos/#l07-das) | Introspecção | [US14](../../Modelagem/UserCases/#51-emitir-boletos)<br>[C01](../../Modelagem/Cenarios/#cenarios_1)<br> [L09](../../Modelagem/Lexicos/#l09-emitir)<br> [L07](../../Modelagem/Lexicos/#l07-das) | 🟢  | [IS02](../ForwardFrom/#is02)|
| RF09  | Deve ser possível [Consultar](../../Modelagem/Lexicos/#l04-consultar) [informações](../../Modelagem/Lexicos/#l11-informacao) do [CNPJ](../../Modelagem/Lexicos/#l03-cnpj) | Introspecção | [US16](../../Modelagem/UserCases/#53-informacoes-cnpj)<br>[C06](../../Modelagem/Cenarios/#cenarios_1)<br> [L04](../../Modelagem/Lexicos/#l04-consultar)<br>[L11](../../Modelagem/Lexicos/#l11-informacao)<br>[L03](../../Modelagem/Lexicos/#l03-cnpj) | 🟢  | [IS03](../ForwardFrom/#is03)|
| RF10  | Deve ser possível pedir [restituição](../../Modelagem/Lexicos/#l15-restituir) | Introspecção | [US15](../../Modelagem/UserCases/#52-solicitar-restituicao)<br>[C10](../../Modelagem/Cenarios/#cenarios_1)<br> [L15](../../Modelagem/Lexicos/#l15-restituir) | 🟢  | [IS04](../ForwardFrom/#is04)|
| RF11  | Deve ser possível [consultar](../../Modelagem/Lexicos/#l04-consultar) perguntas e respostas frequentes | Introspecção | [US13](../../Modelagem/UserCases/#43-faq)<br>[C02](../../Modelagem/Cenarios/#cenarios_1)<br> [L04](../../Modelagem/Lexicos/#l04-consultar)<br> [UC03](../../Modelagem/CasosdeUso/#uc03-acesso-a-suporte) | 🟡  | [IS05](../ForwardFrom/#is05)|
| RNF01  | O aplicativo deve obter dados dentro do próprio aplicativo | Brainstorm | [SIG de Desempenho](../../Modelagem/NFRFramework/#desempenho)<br>[Performance](../../Modelagem/EspecificacaoSuplementar/#performance) | 🟢  | [BS04](../ForwardFrom/#bs04)|
| RNF02  | O aplicativo deve solicitar autorização para pegar dados de outros sites do governo | Brainstorm | [SIG de Desempenho](../../Modelagem/NFRFramework/#desempenho)<br>[Confiabilidade](../../Modelagem/EspecificacaoSuplementar/#confiabilidade) | 🔴  | [BS05](../ForwardFrom/#bs05)|
| RNF03  | O aplicativo deve ser possível de ser utilizado na maioria dos modelos de dispositivos | Brainstorm | [SIG de Suportabilidade](../../Modelagem/NFRFramework/#suportabilidade)<br>[Suportabilidade](../../Modelagem/EspecificacaoSuplementar/#suportabilidade) | 🟢  | [BS08](../ForwardFrom/#bs08)|
| RNF04  | O aplicativo deve validar a [pessoa](../../Modelagem/Lexicos/#l17-usuario) que está utilizando o [CNPJ](../../Modelagem/Lexicos/#l03-cnpj) | Brainstorm | [SIG de Confiabilidade](../../Modelagem/NFRFramework/#confiabilidade) | 🟢  | [BS09](../ForwardFrom/#bs09)|
| RNF05  | O aplicativo deve ser possível de ser utilizado na maioria dos modelos de SO | Brainstorm | [SIG de Suportabilidade](../../Modelagem/NFRFramework/#suportabilidade)<br>[Suportabilidade](../../Modelagem/EspecificacaoSuplementar/#suportabilidade) | 🟢  | [BS10](../ForwardFrom/#bs010)|
| RNF06  | O aplicativo deve ser acessível para [usuário](../../Modelagem/Lexicos/#l17-usuario) com algum tipo de deficiência | Brainstorm | [SIG de Usabilidade](../../Modelagem/NFRFramework/#usabilidade)<br> [Usabilidade](../../Modelagem/EspecificacaoSuplementar/#usabilidade) | 🟢  | [BS11](../ForwardFrom/#bs011)|
| RNF07  | O aplicativo deve conter texto que seja de fácil entendimento | Brainstorm | [SIG de Usabilidade](../../Modelagem/NFRFramework/#usabilidade)<br> [Usabilidade](../../Modelagem/EspecificacaoSuplementar/#usabilidade) | 🟢  | [BS12](../ForwardFrom/#bs012)|
| RNF08  | O aplicativo deve solicitar o [CNPJ](../../Modelagem/Lexicos/#l03-cnpj) apenas uma vez | Entrevista | [SIG de Confiabilidade](../../Modelagem/NFRFramework/#confiabilidade) | 🟢  | [ENT01](../ForwardFrom/#ent01)|
| RNF09  | O aplicativo deve ir até o final da operação antes de realizar qualquer outra etapa | Entrevista | [SIG de Desempenho](../../Modelagem/NFRFramework/#desempenho) | 🟢  | [ENT02](../ForwardFrom/#ent02)|
| RNF10  | O aplicativo deve evitar os erros e telas brancas através do uso | Entrevista | [SIG de Usabilidade](../../Modelagem/NFRFramework/#usabilidade) | 🟢  | [ENT03](../ForwardFrom/#ent03)|
| RNF11  | O aplicativo deve salvar as [informações](../../Modelagem/Lexicos/#l11-informacao) | Entrevista | [SIG de Desempenho](../../Modelagem/NFRFramework/#desempenho)<br>[Performance](../../Modelagem/EspecificacaoSuplementar/#performance) | 🟢  | [ENT04](../ForwardFrom/#ent04)|
| RNF12  |  O aplicativo deve ser suportado pelos principais sistemas mobile | Instrospecção | [SIG de Suportabilidade](../../Modelagem/NFRFramework/#suportabilidade)<br>[Suportabilidade](../../Modelagem/EspecificacaoSuplementar/#suportabilidade)| 🟢  | [IS06](../ForwardFrom/#is06)|
| RNF13  | Deve se exigir um [CNPJ](../../Modelagem/Lexicos/#l03-cnpj) para acesso do aplicativo | Instrospecção | [SIG de Confiabilidade](../../Modelagem/NFRFramework/#confiabilidade)<br> [Usabilidade](../../Modelagem/EspecificacaoSuplementar/#usabilidade)| 🟢  | [IS07](../ForwardFrom/#is07)|
| RNF14  | O aplicativo deve ser de fácil entendimento e uso por seus [usuários](../../Modelagem/Lexicos/#l17-usuario) | Instrospecção | [SIG de Usabilidade](../../Modelagem/NFRFramework/#usabilidade)<br>[Usabilidade](../../Modelagem/EspecificacaoSuplementar/#usabilidade) | 🟢  | [IS08](../ForwardFrom/#is08)|

*Tabela 1 - Matriz Geral*

</center>

## <a>Bibliografia</a>
[1] Projeto Do Github - Noruh - da displina Requisitos de Software, da Universidade de Brasilia(UnB) do semestre 2022.1, disponivel [aqui](https://requisitos-de-software.github.io/2022.1-Noruh/)

[3] Barbosa, J.; Silva, da; Silveira, S.; Gasparini, I.; Darin, T.; Barbosa, (2021) Interação Humano-Computador e Experiência do usuári
AutopublicaçãISBN: 978-65-00-19677-1.
