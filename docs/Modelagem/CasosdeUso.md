# Casos de Uso

## <a>Histórico de Versão</a>
|Data|Data Prevista de Revisão|Versão|Descrição|Autor|Revisor|
| :----------: |:-----------:| :------: | :-----------: | :---------: |:---------: |
|09/12/2022|10/12/2022|1.0|Criação do documento| [Pedro Lucas](https://github.com/PedroLSF) e [Eduardo](https://github.com/edudsan)|[Thiago Oliveira](https://github.com/Thiab394) |
|10/12/2022|11/12/2022|1.1|Adição Dos Diagramas de Caso de Uso| [Thiago Oliveira](https://github.com/Thiab394)| [Pedro Lucas](https://github.com/PedroLSF)|
|22/01/2022|23/01/2022|1.2|Correção do Documento de acordo com a verificação| [Thiago Oliveira](https://github.com/Thiab394)|[Ana Luiza](https://github.com/AnHoff)|

## <a>Introdução</a>
Um caso de uso define uma sequência de ações executadas pelo sistema que geram um resultado de valor observável para um ator em particular. Cada caso de uso deve gerar um significado de valor para o ator que utiliza o sistema.

## <a>Metodologia</a>
Após a elicitação de requisitos funcionais, o grupo escolheu os principais requisitos para o desenvolvimento de tabelas e diagramas de casos de uso.

Como podemos ver na "Figura 1", o diagrama geral de casos de uso do MEI, sem muitos detalhes e em seguida os diagramas especificos de cada caso de uso, representando
todos seus fluxos, sendo eles respectivamente as "Figuras" de 2 até 6, e as tabelas dos UC's, representadas respectivamente pelas "Tabelas" de 1 a 5.

Modelo de tabela de Caso de Uso:

|**UC0X**|*Titulo do UC*|
| :----------: |:-----------|
|Versão|*Versão do UC*|
|Autores|*Autores do UC*|
|Descrição|*Descrição do UC*|
|Atores|*Atores do UC*|
|Pré Condições|*Pré Condições do UC*|
|Fluxo Principal|*Fluxo Principal do UC em topicos*|
|Fluxo Alternativo|*Fluxo Altenativo do UC em topicos*|
|Fluxo de Exceção|*Fluxo de exceção do UC em topicos* |
|Pós Condições|*Pos condições do UC*|
|Rastreabilidade|*Rastreabilidade do UC*|

Explicação dos elementos:<br>
**Atores:** Representa os atores, podendo ser pessoas, instituições ou até sistemas do site ou app, que interagem com o caso de uso diretamente<br>
**Pré Condições:** Indica as condições para que pelo menos um dos fluxos seja atendido completamente <br>
**Fluxo Principal:** Representa o fluxo que ocorrerá com mais frequência quando o usuário utilizar tal recurso representado no caso de uso<br>
**Fluxo Alternativo:** Representa o fluxo mais relevante que ocorrerá com menos frequencia que o fluxo principal<br>
**Fluxo de Exceção:** Representa a exceção do recurso representado no caso de uso, normalmente sendo a recusação da funcionalidade ou saída da mesma<br>
**Pós Condições:** Indica as condições que obrigatoriamente ocorrerão após a realização de cada fluxo<br>
**Rastreabilidade:** Indica a rastreabilidade utilizada pra criação do caso de uso<br>


## <a>Casos de Uso</a>
Legenda:
* UC -> Caso de Uso
### <a>**Casos de Uso Geral**</a>

<center>
<img src='./../../assets/images/Casos de Uso/Diagrama de caso de uso - UC Geral.png'pngwidth="1000"> Figura 1 - Diagrama Do UC Geral</img>
</center>

### <a>**UC01 - Fazer Login**</a>
<center>
<img src='./../../assets/images/Casos de Uso/Diagrama de caso de uso - UC 01.png'pngwidth="1000">Figura 2 - Diagrama Do UC 01</img>


|**UC01**|**Fazer Login**|
| :----------: |:-----------|
|Versão|Atual: 1.0 (10/12)|
|Autores|Pedro Lucas e Thiago|
|Descrição|Fazer Login no MEI|
|Atores|> Usuário <br> > MEI|
|Pré Condições|> Estar deslogado|
|Fluxo Principal|> Usuário acessa o MEI <br> > Usuário digita o CNPJ <br> > Usuário digita sua senha <br> > Usuário clica em "Acessar" <br> > Usuário ficará logado até sair|
|Fluxo Alternativo|Por ser um processo burocrático, não tem fluxo alternativo|
|Fluxo de Exceção|**Fluxo de Exceção 1 - CNPJ inválido** <br> > Aplicativo avisa que não foi possível realizar o login <br> **Fluxo de Exceção 2 - Esquecer a Senha** <br> > Usuário clica em "Esqueceu a Senha?" <br> Usuário recebe um e-mail e sms para recuperar |
|Pós Condições|Usuário fica logado e pode realizar todas as ações|
|Rastreabilidade|BS02|

*Tabela 1 - Detalhe da figura 1 (Fonte: autoria própria - Pedro)*

</center>

### <a>**UC02 - Cadastro**</a>
<center>
<img src='./../../assets/images/Casos de Uso/Diagrama de caso de uso - UC 02.png'pngwidth="1000">Figura 3 - Diagrama Do UC 02</img>


|**UC02**|**Realizar Cadastro**|
| :----------: |:-----------|
|Versão|Atual: 1.0 (10/12)|
|Autores|Pedro Lucas e Thiago|
|Descrição|Enviar as documentações necessárias para virar MEI|
|Atores|> Usuário <br> > MEI <br> > Serviço de Autenticação do MEI|
|Pré Condições|> Não ser MEI|
|Fluxo Principal|> Usuário acessa o MEI <br> > Usuário clica em "Criar CNPJ" <br> > Usuário envia todas as documentações <br>|
|Fluxo Alternativo|Por ser um processo burocrático, não tem fluxo alternativo|
|Fluxo de Exceção|**Fluxo de Exceção 1 - Usuário já é MEI** <br> > Aplicativo indica que a pessoa em questão já é MEI|
|Pós Condições|Usuário volta para a página de Login|
|Rastreabilidade|BS01|

*Tabela 2 - Detalhe da figura 2 (Fonte: autoria própria - Pedro)*

</center>

### <a>**UC03 - Acesso a Suporte**</a>
<center>
<img src='./../../assets/images/Casos de Uso/Diagrama de caso de uso - UC 03.png'pngwidth="1000">Figura 4 - Diagrama Do UC 03</img>

|**UC03**|**Acesso a Suporte**|
| :----------: |:-----------|
|Versão|Atual: 1.0 (10/12)|
|Autores|Pedro Lucas e Thiago|
|Descrição|Fazer uma pergunta no chat|
|Atores|> Usuário <br> > MEI|
|Pré Condições|> Estar Logado|
|Fluxo Principal|> Usuário acessa o MEI <br> > Usuário digita o CNPJ <br> > Usuário digita sua senha <br> > Usuário clica em "Acessar" <br> > Usuário clica no balão de texto no canto inferior esquerdo <br> > Usuário pergunta no chat para receber logo em seguida uma resposta do Suporte|
|Fluxo Alternativo|Por ser um processo burocrático, não tem fluxo alternativo|
|Fluxo de Exceção|**Fluxo de Exceção 1 - Vaga consta no FAQ** <br> > Aplicativo indica um guia presente no FAQ|
|Pós Condições|Usuário volta para a página inicial|
|Rastreabilidade|BS07|

*Tabela 3 - Detalhe da figura 3 (Fonte: autoria própria - Pedro)*

</center>

### <a>**UC04 - Lembrete**</a>
<center>
<img src='./../../assets/images/Casos de Uso/Diagrama de caso de uso - UC 04.png'pngwidth="1000">Figura 5 - Diagrama Do UC 04</img>


|**UC04**|**Receber Lembrete de Pagamento**|
| :----------: |:-----------|
|Versão|Atual: 1.0 (10/12)|
|Autores|Pedro Lucas e Thiago|
|Descrição|Receber uma notificação para lembrar do pagamento do DAS|
|Atores|> Usuário <br> > MEI|
|Pré Condições|> Estar Logado|
|Fluxo Principal|> Usuário acessa o MEI <br> > Usuário digita o CNPJ <br> > Usuário digita sua senha <br> > Usuário clica em "Acessar" <br> > Ligar "Lembrete"|
|Fluxo Alternativo|> Usuário acessa o MEI <br> > Usuário digita o CNPJ <br> > Usuário digita sua senha <br> > Usuário recebe o lembrete como primeira mensagem antes de utilizar o MEI|
|Fluxo de Exceção|**Fluxo de Exceção 1 - Lembrete Desligado** <br> > Usuário deixa desligado os lembretes <br> **Fluxo de Exceção 2 - Silencioso** <br> > Usuário deixa  o celular no silencioso|
|Pós Condições|Usuário segue para a página principal|
|Rastreabilidade|BS03|

*Tabela 4 - Detalhe da figura 4 (Fonte: autoria própria - Pedro)*

</center>

### <a>**UC05 - Plataforma Unica**</a>
<center>
<img src='./../../assets/images/Casos de Uso/Diagrama de caso de uso - UC 05.png'pngwidth="1000">Figura 6 - Diagrama Do UC 05</img>


|**UC05**|**Utilizar apenas o MEI**|
| :----------: |:-----------|
|Versão|Atual: 1.0 (10/12)|
|Autores|Pedro Lucas e Thiago|
|Descrição|Autorizar acesso a dados externos|
|Atores|> Usuário <br> > MEI <br> > Serviço de Autorização do MEI|
|Pré Condições|> Estar Logado|
|Fluxo Principal|> Usuário acessa o MEI <br> > Usuário digita o CNPJ <br> > Usuário digita sua senha <br> > Usuário clica em "Acessar" <br> > Usuário autoriza a utilização de outros sites do governo|
|Fluxo Alternativo|Por ser um processo burocrático, não tem fluxo alternativo|
|Fluxo de Exceção|**Fluxo de Exceção 1 - Recusar** <br> > Usuário recusa a utilização|
|Pós Condições|Usuário pode realizar outras operações sem necessitar de sites externos do Governo|
|Rastreabilidade|BS04 e BS05|

*Tabela 5 - Detalhe da figura 5 (Fonte: autoria própria - Pedro*

</center>

## <a>Referências Bibliográficas</a>
[1] Duolingo Github Requisitos de Software, disponivel em: https://github.com/Requisitos-de-Software/2019.2-Duolingo Acesso em: 10 de dezembro de 2022

[2] Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021) Interação Humano-Computador e Experiência do usuário. Autopublicação. ISBN: 978-65-00-19677-1. Acesso em: 09 de janeiro de 2023
