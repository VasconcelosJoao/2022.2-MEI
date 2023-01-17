# Verificação

## <a>Histórico de Versão</a>
|    Data    | Data Prevista de Revisão | Versão |          Descrição          |                   Autor                    |                  Revisor                   |
| :--------: | :----------------------: | :----: | :-------------------------: | :----------------------------------------: | :----------------------------------------: |
| 07/01/2023 |        08/01/2023        |  1.0   |    Criação do documento     | [João Lucas](https://github.com/HacKairos) | [Pedro Lucas](https://github.com/PedroLSF) |
| 07/01/2023 |        16/01/2023        |  1.1   | Adição sobre o Planejamento | [Pedro Lucas](https://github.com/PedroLSF) | [João Lucas](https://github.com/HacKairos) |


## <a>Introdução</a>
Aqui vamos comentar um pouco da escolha do nosso método de Verificação e Validação, a fim de obter um melhor padronização e organização, foi dividido em pastas que representam as mesmas contidas no projeto. Vale ressaltar que será uma análise feita pelos próprios desenvolvedores, mas o que isso significa?

Em resumo, há algo de errado com o modelo em termos de notação, processos, procedimentos? Ele atende às expectativas? Portanto, interessa apenas aos desenvolvedores de software. Nenhuma intervenção do cliente é necessária. <br></br>

## <a>Metodologias</a>

Existem várias estratégias de verificação de software. Dado que algumas destas estratégias estão relacionadas com o levantamento de requisitos, há algumas que se destacam, dentre elas, podemos citar três em específico:

• <a>**As Inspeções**</a>.

• <a>**Uso de estratégias formais**</a>.

• <a>**Reutilização de domínios**</a>.


### <a>Inspeção</a>
A Inspeção pode ser aplicada ao definir requisitos de verificação em um documento de requisitos. Isso é aplicável se for escrito por um cliente e não tiver estrutura própria ou se for escrito por um engenheiro de software/requisitos (lista de requisitos neste caso).
Uma técnica de gerenciamento de reuniões destinada a detectar erros em documentos. Ele define claramente o papel que cada membro da equipe deve desempenhar e quais resultados devem ser alcançados.<br></br>
De acordo com relatórios da indústria, a produtividade do uso de inspeções em desenhos e revisões de código é excelente. Portanto, você pode encontrar bugs com eficiência antes de testar seu sistema.
O principal objetivo da verificação é garantir que o modelo de requisitos esteja em conformidade com a notação do modelo e com o que se espera desse modelo. Segundo Fagan, existe um método de inspeção que define o processo em seis etapas principais do conhecimento: <br></br>

<center>

• <a>**Planejamento**</a>
  
• <a>**Visão Geral**</a>
  
• <a>**Preparação**</a>
  
• <a>**Inspeção**</a>
  
• <a>**Correção**</a>
  
• <a>**Acompanhamento**</a>
  
<br>
</center>

### <a>Estratégias formais</a>
Aqui o engenheiro de software assume o papel de provador de teoremas. Portanto, é realizada uma verificação para a possibilidade de detectar uma discrepância.<br></br>
Na lógica e na matemática, a lógica proposicional é um sistema de formalismos no qual expressões representam proposições que podem ser formadas pela combinação de proposições atômicas usando conexões lógicas e um sistema de regras de derivação pelas quais uma determinada expressão pode ser declarada como um sistema formal de "teorema".<br></br>
Uma proposição é uma afirmação que tem um valor verdadeiro ou falso. A lógica proposicional estuda como inferir declarações verdadeiras ou falsas derivando de um conjunto particular de hipóteses (declarações verdadeiras) e considerando um contexto particular.<br>

### <a>Reutilização de domínios</a>
Técnicas usando estratégias de inteligência artificial e heurísticas. Destina-se a criticar requisitos e comparar com domínios previamente codificados.<br></br>
A formação desse domínio é, portanto, baseada em fatos de sistemas semelhantes que já foram determinados. Assistentes inteligentes fornecem feedback sobre requisitos preparados por engenheiros de software/requisitos. Dada a disponibilidade do domínio. É possível identificar fatos falsos ou ausentes.<br>

## <a>Método de Avaliação</a>

Para a verificação em questão, será utilizada a técnica de inspeção. Para a aplicação dessa técnica, haverá o uso de uma tabela com perguntas que visam avaliar se o artefato foi feito da maneira demandada pela disciplina. Assim, torna-se fácil visualizar se o mesmo foi elaborado corretamente.

Para a realização da inspeção, será utilizada uma checklist com o objetivo de avaliar se o artefato foi feito da maneira demandada pela disciplina. Com isso, torna-se fácil visualizar se o mesmo está correto. O checklist será preenchido de acordo com as seguintes classificações:

* 🟢: O tópico está completamente satisfeito;
* 🟡: O tópico está incompleto;
* 🔴: O tópico não foi realizado ou está errado;
* N/A: questão não se aplica.

Sabendo dessa análise, vamos utilizar uma tabela seguindo o exemplo abaixo:

<center>

|  ID   |  Questão   | Inspeção |
| :---: | :--------: | :------: |
|   1   | Pergunta 1 |    🔴     |
|   2   | Pergunta 2 |    🟡     |
|   3   | Pergunta 3 |    🟢     |
|   4   | Pergunta 4 |    🔴     |
|   5   | Pergunta 5 |    🟢     |
|   6   | Pergunta 6 |    🔴     |
|   7   | Pergunta 7 |    🟢     |
|   8   | Pergunta 8 |    🟢     |


*Tabela 1 - Preparação das questões para inspeção*

</center>

## <a>Conclusão</a>
O grupo 3 do projeto MEI ao analisar essas 3 técnicas de verificação, optou por utilizar a estratégia de <a>**Inspeção**</a>. 

## <a>Bibliografia</a>
SERRANO, Maurício; SERRANO, Milene; Requisitos - Aula 23.
