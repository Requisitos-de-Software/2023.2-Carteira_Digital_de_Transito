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

Tabela 1: Legenda do mapeamento de requisitos<br/>


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
| RF01  |Login pelo gov|[ITP](../elicitação/Introspeccao.md)| Sim|[C](../modelagem/cenarios.md)|      |
| RF02  | Obter versão digital da habilitação | [ITP](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/Introspeccao/), [ENT](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/entrevista/), [SB](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/storyboard/)                    |   Sim            | [HU](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/agil/historiasUsuario/), [C](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/cenarios/), [CU](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/casosDeUso/),  [L](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/léxicos/)          |      |
| RF03  |  Obter versão digital dos veiculos que você é principal condultor |  [ITP](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/Introspeccao/)                    | Sim              |[HU](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/agil/historiasUsuario/), [C](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/cenarios/), [CU](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/casosDeUso/), [L](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/léxicos/)           |      |
| RF04  | Obter versão digital do CRLV| [ITP](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/Introspeccao/), [GL](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/glossario/), [SB](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/storyboard/), [ENT](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/entrevista/) | Sim | [HU](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/agil/historiasUsuario/),  [C](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/cenarios/), [CU](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/casosDeUso/),  [L](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/léxicos/)   |   [RF4](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/pos-rastreabilidade/pos-rastreabilidade/)   |
| RF05  |  Consultar multas associadas a sua habilitação           |      [ITP](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/Introspeccao/)               |     Sim          |   [HU](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/agil/historiasUsuario/), [CU](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/casosDeUso/), [L](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/léxicos/)       |      |
| RF06  |  Consultar as multas do seu veículo           |   [ITP](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/Introspeccao/), [SB](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/storyboard/)                  |   Sim            | [HU](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/agil/historiasUsuario/), [CU](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/casosDeUso/),   [L](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/léxicos/)           |      |
| RF07  |             |                     |               |           |      |
| RF08  |O Aplicativo possui diferentes meios de pagamento de multa|[ITP](../elicitação/Introspeccao.md), [SB](../elicitação/storyboard.md)|Sim|[CU](../modelagem/casosDeUso.md)|  |           |                     |               |           |      |
| RF09  | Reivindicar a multa | [ITP](https://requisitos-de-software.github.io/2023.2Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/Introspeccao/)  |  Sim   |  [CU](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/casosDeUso/)     |      |
| RF10  |Contato com suporte|[ITP](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/Introspeccao/), [ENT](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/entrevista/)| Sim |[C](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/cenarios/), [CU](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/casosDeUso/)|      |
| RF11  | Indicar principal condutor do veículo      |  [ITP](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/Introspeccao/)        |  Sim             |  [HU](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/agil/historiasUsuario/), [C](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/cenarios/), [CU](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/casosDeUso/),   [L](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/léxicos/)        |      |
| RF12  | Permite o acompanhamento do status da multa (a cobrar e pago)            |  [ITP](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/Introspeccao/), [SB](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/storyboard/)                |   Sim      |  [HU](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/agil/historiasUsuario/), [CU](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/casosDeUso/), [L](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/léxicos/)         |      |
| RF13  | Permite visualizar histórico de multas do contudor   | [ITP](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/Introspeccao/)   |   Sim   |     [C](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/cenarios/),  [L](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/léxicos/) |      |
| RF14  |    Permite ao usuário fazer transferência de veículo         |     [ITP](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/Introspeccao/), [ENT](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/entrevista/)                |  Sim             |   [C](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/cenarios/), [L](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/léxicos/)       |      |
| RF15  | Aplicativo deve possuir um FAQ  | [ITP](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/Introspeccao/), [ENT](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/entrevista/) |  Sim           | [CU](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/casosDeUso/ ), [C](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/cenarios/)         |      |
| RF16  |Aplicativo mostra restrições e indicadores (restrição no veiculo, multa, judicial)| [ITP](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/Introspeccao/)  |     Sim          | [CU](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/casosDeUso/), [C](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/cenarios/),  [L](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/léxicos/),  [HU](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/agil/historiasUsuario/)           |      |
| RF17  |O aplicativo deve divulgar campanhas e projetos do DETRAN (ITP) | [ITP](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/Introspeccao/)    | Sim|           |      |
| RF18  |  Deve ser possível consultar as siglas apresentadas | [GL](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/glossario/)    |   Não            |           |      |
| RF19  |  Deve ser possível baixar os CRLV dos veículos  |    [GL](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/glossario/)       |    Sim      |           |      |
| RF20  | Deve ser possível participar no Cadastro Positivo             |  [GL](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/glossario/)      |   Sim             |  [HU](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/agil/historiasUsuario/),  [L](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/léxicos/), [NFR](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/agil/framework/), [ES](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/especificacao-suplementar/)         |      |
| RF21  |    Dever ser possível consultar a classificação da infração         |   [GL](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/glossario/), [ENT](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/entrevista/)                |       Não       |          |      |
| RF22  |     Deve ser possível compartilhar os documentos de um veículo com seus coatores        |   [ENT](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/entrevista/), [SB](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/storyboard/)                  |   Sim            |       [L](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/léxicos/)       |      |
| RF23  |O usuário deve conseguir solicitar a outro usuário o compartilhamento dos documentos do veículo.|[SB](../elicitação/storyboard.md)|Sim|[L](../modelagem/léxicos.md)| |
| RF24  | O aplicativo deve permitir a pesquisa de informações sobre veículos por meio do número da placa | [ENT](../elicitação/requisitos_elicitados.md/#metodologia) | Não | [C](../modelagem/cenarios.md/#c08---pesquisar-informações-sobre-veículos-por-meio-do-número-da-placa)|  |
| RF25  | Deve ser possível cadastrar e gerenciar múltiplos veículos na carteira digital  |  [ENT](../elicitação/requisitos_elicitados.md/#metodologia), [GL](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/glossario/)                   |   Sim            | [CU](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/casosDeUso/), [HU](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/agil/historiasUsuario/), [L](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/léxicos/)          |      |
| RF26  | O aplicativo deve disponibilizar informações em tempo real sobre condições de tráfego, acidentes e congestionamentos | [ENT](../elicitação/requisitos_elicitados.md/#metodologia) | Não | [CU](../modelagem/casosDeUso.md/#especialização-dos-casos-de-uso), [ES](../modelagem/especificacao-suplementar.md/#requisito-de-confiabilidade-1), [NFR](../modelagem/agil/framework.md/#nfr-confiabilidade)|  |
| RF27  |Deve ser possível configurar alertas de vencimento da CNH e do licenciamento do veículo.|[ENT](../elicitação/entrevista.md)|Não| - ||
| RF28  | O aplicativo deve oferecer uma opção de backup seguro de todos os documentos e dados do usuário | [ENT](../elicitação/requisitos_elicitados.md/#metodologia) | Não | [CU](../modelagem/casosDeUso.md/#especialização-dos-casos-de-uso), [ES](../modelagem/especificacao-suplementar.md/#requisito-de-desempenho-3) |  |
| RF29  | Deve ser possível realizar o agendamento de serviços de manutenção e inspeção veicular            |      [ENT](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/entrevista/)               |          Não     |   [C](../modelagem/cenarios.md/#c09---realizar-o-agendamento-de-serviços-de-manutenção-e-inspeção-veicular)           |    |
| RF30  | O aplicativo deve notificar o usuário sobre recalls e informações importantes do fabricante do veículo | [ENT](../elicitação/requisitos_elicitados.md/#metodologia) | Não | [HU](../modelagem/agil/historiasUsuario.md/#us11---aderir-ao-sistema-de-notificação-eletrônica), [C](../modelagem/cenarios.md/#c09---realizar-o-agendamento-de-serviços-de-manutenção-e-inspeção-veicular), [L](../modelagem/léxicos.md/#l10---visualizar-recall)|  |
| RF31  | Deve ser possível obter informações sobre as normas de trânsito, regulamentações e penalidades em vigor | [ENT](../elicitação/requisitos_elicitados.md/#metodologia) | Não | [ES](../modelagem/especificacao-suplementar.md/#requisito-de-desempenho-1) |  |
| RNF01 | O aplicativo permite visualizar a politica de privicidade            | [ITP](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/Introspeccao/)                    |  Sim               | [ES](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/especificacao-suplementar/), [NFR](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/agil/framework/)          |     |
| RNF02 |Validar cadastro de CNH|[ITP](../elicitação/Introspeccao.md)|Sim|[L](../modelagem/léxicos.md)|      |
| RNF03 |Aplicativo funciona em multisistemas (android e IOS)|[ITP](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/Introspeccao/)| Sim | [ES](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/especificacao-suplementar/), [NFR](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/agil/framework/) |      |
| RNF04 | Aplicativo possui interface simples	              | [ITP](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/Introspeccao/)                    |   Sim            |  [ES](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/especificacao-suplementar/), [NFR](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/agil/framework/)         |      |
| RNF05 |Aplicativo deve evitar erros e telas brancas durante o uso|[ITP](../elicitação/Introspeccao.md)|Não| - |      |
| RNF06 | Possui modo escuro/claro     |    [ITP](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/Introspeccao/)        |  Sim   |           |      |
| RNF07 |Facilitar o usuário a chegar a funcionalidade de aderir ao SNE | [GL](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/glossario/) | Sim | [CU](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/casosDeUso/),  [L](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/léxicos/), |      |
| RNF08 |Deve ser possível acessar a CNH(digital) mesmo sem acesso a internet.| [SB](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/storyboard/)| Sim | [HU](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/agil/historiasUsuario/),  [C](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/cenarios/),  [CU](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/casosDeUso/) |      |
| RNF09 |  Deve existir um prazo de validade do compartilhamento da CNH |  [SB](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/storyboard/)         |     Não          |           |      |
| RNF10 |O aplicativo deve alertar o usuário caso seja multado |  [SB](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/storyboard/), [ENT](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/entrevista/)| Não | - |      |



Fonte: [Limirio Guimarães](https://github.com/LimirioGuimaraes)

</center>

## Bibliografia
> KLAUS POHL, CHRIS RUPP. Requirements Engineering Fundamentals.

## 📑 Histórico de Versões
|Versão|Data|Descrição|Autor|Revisor|
|:----:|----|---------|-----|:-------:|
|`1.0`|16/11/2023|Criação do documento|[Luis Miranda](https://github.com/LuisMiranda10) |[Limirio Guimarães](https://github.com/LimirioGuimaraes)| 
|`1.1`|17/11/2023|Adicionado introdução e objetivo|[Limirio Guimarães](https://github.com/LimirioGuimaraes) |[Breno Queiroz](https://github.com/brenob6) | 
|`1.2`|18/11/2023|Adicionada os requisitos RF4, RF10, RNF3, RNF7, RNF8 e RNF10 a matriz|[Limirio Guimarães](https://github.com/LimirioGuimaraes) |[Breno Queiroz](https://github.com/brenob6) | 
|`1.3`|18/11/2023|Adicionada os requisitos RF6, RF11, RNF1, RF20, RF12, RNF4 a matriz|[Luis Miranda](https://github.com/LuisMiranda10)|[Breno Queiroz](https://github.com/brenob6) | 
|`1.4`|20/11/2023|Adicionada os requisitos RF24, RF26, RF28, RF30, RF31 a matriz|[Milena Baruc](https://github.com/MilenaBaruc) |[Breno Queiroz](https://github.com/brenob6) |
|`1.5`|20/11/2023|Adicionada os requisitos RF1, RF27, RF8, RNF2, RF23, RNF5 a matriz| [Breno Queiroz](https://github.com/brenob6) | [Vinícius Mendes](https://github.com/yabamiah)|
|`1.6`|20/11/2023|Adicionada os requisitos RF13, RF9, RF19, RF17, RF18, RNF9 a matriz|[Vinícius Mendes](https://github.com/yabamiah) |[Breno Queiroz](https://github.com/brenob6)
|`1.7`|20/11/2023|Adicionada os requisitos RF05, RF14, RF21, RF22, RF29,  a matriz|[Mayara Alves](https://github.com/Mayara-tech) |[Breno Queiroz](https://github.com/brenob6)|

