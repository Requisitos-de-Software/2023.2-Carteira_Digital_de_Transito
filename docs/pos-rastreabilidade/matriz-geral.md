# Matriz de Rastreabilidade

## Introdução 
A Matriz Geral, um documento essencial no contexto do projeto, desempenha um papel crucial ao apresentar de maneira organizada os requisitos elicitados, tanto em suas fases prévias quanto posteriores, por meio de uma estrutura tabular. Esta matriz estabelece uma conexão abrangente entre os requisitos e os documentos correspondentes. A utilização da técnica de referências e documentos cruzados oferece uma vantagem significativa, permitindo a identificação e destaque das dependências entre os requisitos. 

# Objetivo 
A implementação de uma Matriz Geral no contexto do nosso projeto possui como objetivo central promover uma gestão mais eficiente e compreensiva dos requisitos elicitados, desde suas fases iniciais até as etapas posteriores. Essa ferramenta, estruturada de maneira tabular, desempenha um papel crucial ao estabelecer uma conexão detalhada entre os requisitos e os documentos correspondentes. Portanto, a implementação da Matriz Geral no nosso projeto visa otimizar a organização, análise e compreensão dos requisitos, promovendo uma abordagem mais estruturada e detalhada que, por sua vez, contribuirá para o sucesso e eficácia do projeto como um todo.

## Metodologia
A metodologia a ser utilizada vai consistir em uma matriz que contém 6 colunas, no qual estão especificadas abaixo, que buscam garantir a clareza e a eficácia na gestão dos requisitos ao longo do ciclo de vida do projeto. Os requisitos apresentados são os elicitados no artefato de [requisitos elicitados](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicitação/requisitos_elicitados/).

As colunas serão apresentadas da seguinte forma:

* **ID** : Identificação do requisito analisado.
* **Descrição** : Explicação do requisito.
* **Pré-Rastreabilidade** : Origem do requisito elicitado.
* **Implementado**: Indica se o requisito está implementado ou não implementado no aplicativo.
* **Artefatos Relacionados**: representa os artefatos que estão relacionados ao requisito.
* **Elo** : rastrear a relação entre requisitos e os artefatos.

## Mapeamento

<center> 

Serão apresentados na Tabela 1, o mapeamento dos documentos e sua referência dos artefatos apresentados em seguida.

Tabela 1: Legenda do mapeamento de requisitos 
| Legenda                                                                                                                 | Descrição                             |
| ----------------------------------------------------------------------------------------------------------------------- |-------------------------------------- |
| RF                                                                                                                      | Requisito Funcional                   |
| RNF                                                                                                                     | Requisito Não-Funcional               | 
| [GL](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/glossario/)      | Requisito elicitado pelo Glossário    |
| [SB](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/storyboard/)     | Requisito elicitado pela StoryBoard   |
| [ENT](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/entrevista/)    | Requisito elicitado pela Entrevista   |
| [ITP](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/Introspeccao/)  | Requisito elicitado pela Introspecção |
| [HU](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/agil/historiasUsuario/)     | História usuário                      |
| [CU](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/casosDeUso/)                | Casos de Uso                          |
| [C](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/cenarios/)                   | Cenários                              |
| [ES](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/especificacao-suplementar/) | Especificação Suplementar             |
| [NFR](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/agil/framework/)           | NFR Framework                         |
| [L](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/léxicos/)                    | Léxicos                               |

Fonte: [Limirio Guimarães](https://github.com/LimirioGuimaraes)


</center>

## Matriz Geral
A tabela 2 a seguir mostra a matriz geral de rastreabilidade.

<center>

**Tabela 2** - Matriz Geral.

| ID    | Descrição   | Pré-Rastreabilidade | Implementado? | Artefatos | Elos |
| ----- | ----------- | ------------------- | ------------- | --------- | ---- |
| RF01  |             |                     |               |           |      |
| RF02  |             |                     |               |           |      |
| RF03  |             |                     |               |           |      |
| RF04  | Obter versão digital do CRLV| [ITP](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/Introspeccao/), [GL](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/glossario/), [SB](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/storyboard/), [ENT](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/entrevista/) | Sim | [HU](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/agil/historiasUsuario/),  [C](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/cenarios/), [CU](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/casosDeUso/),  [L](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/léxicos/)   |      |
| RF05  |             |                     |               |           |      |
| RF06  |  Consultar as multas do seu veículo           |   [ITP](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/Introspeccao/), [SB](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/storyboard/)                  |   Sim            | [HU](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/agil/historiasUsuario/), [CU](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/casosDeUso/),   [L](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/léxicos/)           |      |
| RF07  |             |                     |               |           |      |
| RF08  |             |                     |               |           |      |
| RF09  |             |                     |               |           |      |
| RF10  |Contato com suporte|[ITP](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/Introspeccao/), [ENT](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/entrevista/)| Sim |[C](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/cenarios/), [CU](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/casosDeUso/)|      |
| RF11  |             |                     |               |           |      |
| RF12  |             |                     |               |           |      |
| RF13  |             |                     |               |           |      |
| RF14  |             |                     |               |           |      |
| RF15  |             |                     |               |           |      |
| RF16  |             |                     |               |           |      |
| RF17  |             |                     |               |           |      |
| RF18  |             |                     |               |           |      |
| RF19  |             |                     |               |           |      |
| RF20  |             |                     |               |           |      |
| RF21  |             |                     |               |           |      |
| RF22  |             |                     |               |           |      |
| RF23  |             |                     |               |           |      |
| RF24  |             |                     |               |           |      |
| RF25  |             |                     |               |           |      |
| RF26  |             |                     |               |           |      |
| RF27  |             |                     |               |           |      |
| RF28  |             |                     |               |           |      |
| RF29  |             |                     |               |           |      |
| RF30  |             |                     |               |           |      |
| RF31  |             |                     |               |           |      |
| RNF01 |             |                     |               |           |      |
| RNF02 |             |                     |               |           |      |
| RNF03 |Aplicativo funciona em multisistemas (android e IOS)|[ITP](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/Introspeccao/)| Sim | [ES](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/especificacao-suplementar/), [NFR](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/agil/framework/) |      |
| RNF04 |             |                     |               |           |      |
| RNF05 |             |                     |               |           |      |
| RNF06 |             |                     |               |           |      |
| RNF07 |Facilitar o usuário a chegar a funcionalidade de aderir ao SNE | [GL](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/glossario/) | Sim | [CU](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/casosDeUso/),  [L](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/léxicos/), |      |
| RNF08 |Deve ser possível acessar a CNH(digital) mesmo sem acesso a internet.| [SB](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/storyboard/)| Sim | [HU](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/agil/historiasUsuario/),  [C](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/cenarios/),  [CU](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/casosDeUso/) |      |
| RNF09 |             |                     |               |           |      |
| RNF10 |O aplicativo deve alertar o usuário caso seja multado |  [SB](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/storyboard/), [ENT](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/entrevista/)| Não | - |      |


Fonte: [Limirio Guimarães](https://github.com/LimirioGuimaraes)

</center>

## Bibliografia
> KLAUS POHL, CHRIS RUPP. Requirements Engineering Fundamentals.

## Histórico de Versões
|Versão|Data|Descrição|Autor|Revisor|
|:----:|----|---------|-----|:-------:|
|`1.0`|16/11/2023|Criação do documento|[Luis Miranda](https://github.com/LuisMiranda10) |[Limirio Guimarães](https://github.com/LimirioGuimaraes)| 
|`1.1`|17/11/2023|Adicionado introdução e objetivo|[Limirio Guimarães](https://github.com/LimirioGuimaraes) | | 
|`1.2`|18/11/2023|Adicionada os requisitos RF4, RF10, RNF3, RNF7, RNF8 e RNF10 a matriz|[Limirio Guimarães](https://github.com/LimirioGuimaraes) | | 
