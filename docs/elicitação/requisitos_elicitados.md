# Requisitos Elicitados

## Introdução 

Nesta página está listado todos requisitos obtidos com a etapa de elicitação, fornecendo uma melhor compreensão. Com isso, temos a Rastreabilidade, que tem capacidade de identificar, documentar e acompanhar as relações e conexões entre os diversos elementos dos requisitos ao longo do ciclo de vida. Essa prática tem como objetivo garantir a consistência, a compreensão e a gerência eficaz dos requisitos, permitindo que as mudanças sejam rastreadas e controladas de forma sistemática 

## Metodologia 

A metodologia adotada envolveu a consolidação de todos os requisitos funcionais (RF) e requisitos não funcionais (RNF) obtidos por meio de diversas técnicas de elicitação em duas tabelas estruturadas sendo elas respectivamente, tabela 3 e tabela 4. Nestas tabelas, cada requisito é identificado por um ID exclusivo descrito na tabela 2, categorizado como RF ou RNF para indicar seu tipo e acompanhado de um status de implementação. Além disso, a tabela também rastreia a origem de cada requisito, destacando se ele foi obtido por meio de técnicas como o Glossario, StoryBoard, Introspecção e Entrevista. Na Tabela 1, encontramos o cronograma de execução da elicitação de requisitos, que apresenta as datas de realização do levantamento de requisitos.

<p align="center"><b>Tabela 01</b> - Cronograma de elicitação de requisitos .</p>
<center>

| Método | Data da elicitação        |
|------ |-------------------------------------|
| Glossário  | 22/10/2023               |
| StoryBoard  |  20/10/2023             |
| Entrevista  | 20/10/2023 |
| Introspecção  | 21/10/2023 |

Fonte: [Mayara Alves](https://github.com/Mayara-tech)
</center>

<p align="center"><b>Tabela 02</b> - Legenda de identificação de ID.</p>
<center>

| Tipo | Descrição                           |
|------|-------------------------------------|
| RF   | Requisito Funcional                 |
| RNF  | Requisito Não-Funcional             |
| GL   | Requisito elicitado pelo Glossário  |
| SB   | Requisito elicitado pela StoryBoard |
| ENT  | Requisito elicitado pela Entrevista |
| ITP  | Requisito elicitado pela Introspecção |


Fonte: [Luis Miranda](https://github.com/LuisMiranda10) e [Mayara Alves](https://github.com/Mayara-tech)
</center>


<p align="center"><b>Tabela 03</b> - Requisitos funcionais  elicitados no aplicativo Carteira Digital de Trânsito.</p>
<center>

|Rastreabilidade |Requisito| Tipo | Implementação|
| ---- |-----| ------ | ------ |
| [ITP](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/Introspeccao/) |Login pelo gov  		|RF1 |   Implementado    |
| [ITP](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/Introspeccao/), [ENT](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/entrevista/), [SB](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/storyboard/) |Obter versão digital da habilitação 						|RF2 | Implementado  |
| [ITP](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/Introspeccao/) | Obter versão digital dos veiculos que você é principal condultor 		|RF3  |  Implementado  |
| [ITP](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/Introspeccao/), [GL](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/glossario/), [SB](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/storyboard/), [ENT](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/entrevista/)| Obter versão digital do CRLV												            |RF4   |    Implementado    |
| [ITP](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/Introspeccao/)  |Consultar multas associadas a sua habilitação					                        |RF5  |  Implementado     |
| [ITP](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/Introspeccao/), [SB](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/storyboard/)   |Consultar multas do seu veículo								                        |RF6   | Implementado    |
| [ITP](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/Introspeccao/) |Consultar multas dos veículos que você é principal condutor	                        |RF7   | Implementado   |
| [ITP](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/Introspeccao/), [SB](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/storyboard/) |O Aplicativo possui diferentes meios de pagamento de multa		                        |RF8    |   Implementado |
| [ITP](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/Introspeccao/) |Renvidicar a multa																		|RF9  |    Implementado   |
| [ITP](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/Introspeccao/), [ENT](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/entrevista/) |Contato com suporte																	|RF10  | Implemetado   |
| [ITP](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/Introspeccao/) |Indicar principal condutor do veículo 													|RF11   |    Implementado  |
| [ITP](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/Introspeccao/), [SB](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/storyboard/) |Permite o acompanhamento do status da multa (a cobrar e pago)						    |RF12  |   Implementado     |
| [ITP](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/Introspeccao/) |Permite visualizar histórico de multas do condutor									    |RF13  |    Implementado    |
| [ITP](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/Introspeccao/), [ENT](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/entrevista/) |Permite ao usuário fazer transferência de veículo							            |RF14   |  Não implementado  |
| [ITP](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/Introspeccao/), [ENT](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/entrevista/) |Aplicativo deve possuir um FAQ 														|RF15   |   Implementado  |
| [ITP](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/Introspeccao/) |Aplicativo mostra restrições e indicadores (restrição no veiculo, multa, judicial) 	|RF16  |  Implementado     |
| [ITP](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/Introspeccao/) |O aplicativo deve divulgar campanhas e projetos do DETRAN								|RF17   |  Implementado   |
| [GL](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/glossario/) | Deve ser possível consultar as siglas apresentadas| RF18 | Não implementado |f
| [GL](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/glossario/) | Deve ser possível baixar os CRLV dos veículos| RF19 | Implementado |
| [GL](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/glossario/) |Deve ser possível participar no Cadastro Positivo | RF20 | Implementado |
| [GL](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/glossario/), [ENT](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/entrevista/) | Dever ser possível consultar a classificação da infração | RF21 | Não implementado |
| [SB](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/storyboard/), [ENT](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/entrevista/) |Deve ser possível compartilhar os documentos de um veículo com seus coatores.| RF22 | Implementado
| [SB](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/storyboard/) |O usuário deve conseguir solicitar a outro usuário o compartilhamento dos documentos do veículo.| RF23 | Implementado
| [ENT](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/entrevista/)  | O aplicativo deve permitir a pesquisa de informações sobre veículos por meio do número da placa. | RF24 | Não implementado |
| [ENT](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/entrevista/), [GLO](https://github.com/Requisitos-de-Software/2023.2-Carteira_Digital_de_Transito/blob/main/docs/elicita%C3%A7%C3%A3o/glossario.md) | Deve ser possível cadastrar e gerenciar múltiplos veículos na carteira digital. | RF25 | Implementado |
| [ENT](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/entrevista/) | O aplicativo deve disponibilizar informações em tempo real sobre condições de tráfego, acidentes e congestionamentos. | RF26 | Não implementado |
| [ENT](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/entrevista/), [SB](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/storyboard/) | Deve ser possível configurar alertas de vencimento da CNH e do licenciamento do veículo. | RF27 | Não implementado |
| [ENT](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/entrevista/)  | O aplicativo deve oferecer uma opção de backup seguro de todos os documentos e dados do usuário. | RF28 | Não implementado |
| [ENT](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/entrevista/) | Deve ser possível realizar o agendamento de serviços de manutenção e inspeção veicular. | RF29 | Não implementado |
| [ENT](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/entrevista/) | O aplicativo deve notificar o usuário sobre recalls e informações importantes do fabricante do veículo. | RF30 | Não implementado |
| [ENT](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/entrevista/) | Deve ser possível obter informações sobre as normas de trânsito, regulamentações e penalidades em vigor. | RF31 | Não implementado |

Fonte: [Limírio Guimarães](https://github.com/LimirioGuimaraes), [Luis Miranda](https://github.com/LuisMiranda10) e [Mayara Alves](https://github.com/Mayara-tech)
  
</center>

<p align="center"><b>Tabela 04</b> - Requisitos não funcionais elicitados no aplicativo Carteira Digital de Trânsito.</p>
<center>


|Rastreabilidade |Requisito| Tipo | Implementação|
|------------|-----------|-----------|--------|
| [ITP](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/Introspeccao/) | O aplicativo permite visualizar a política de privacidade | RNF1 | Implementado |
| [ITP](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/Introspeccao/) | Validar cadastro de CNH | RNF2 | Implementado |
| [ITP](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/Introspeccao/) | Aplicativo funciona em multisistemas (Android e IOS) | RNF3 | Implementado |
| [ITP](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/Introspeccao/) | Aplicativo possui interface simples | RNF4 | Implementado |
| [ITP](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/Introspeccao/) | Aplicativo deve evitar erros e telas brancas durante o uso | RNF5 | Não implementado |
| [ITP](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/Introspeccao/) | Possui modo escuro/claro | RNF6 | Não implementado |
| [GL](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/glossario/) | Facilitar o usuário a chegar à funcionalidade de aderir ao SNE | RNF7 | Implementado |
| [SB](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/storyboard/) | Deve ser possível acessar a CNH (digital) mesmo sem acesso à internet | RNF8 | Implementado |
| [SB](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/storyboard/) | Deve existir um prazo de validade do compartilhamento da CNH | RNF9 | Não implementado |
| [SB](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/storyboard/), [ENT](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/entrevista/) | O aplicativo deve alertar o usuário caso seja multado | RNF10 | Não implementado |



Fonte: [Limírio Guimarães](https://github.com/LimirioGuimaraes), [Luis Miranda](https://github.com/LuisMiranda10) e [Mayara Alves](https://github.com/Mayara-tech)
  
</center>


## 📑 Histórico de versões:

| Versão |    Data    |    Descrição         | Autor(es)  |    Revisor(es) |                  
|:-----: | :--------: | :-------------:      | :--------: | :-------------:| 
| `1.0`    | 30/09/2023  | Criação do documento | Breno e [Limírio Guimarães](https://github.com/LimirioGuimaraes)| [Mayara Alves](https://github.com/Mayara-tech)|
| `1.1`    | 21/10/2023  | Modificação da introdução e adição da rastreabilidade da tabela |[Luis Miranda](https://github.com/LuisMiranda10) e [Mayara Alves](https://github.com/Mayara-tech)| [Vinícius Mendes](https://github.com/yabamiah)|
| `1.2`    | 25/10/2023  | Adicionando cronograma de elicitação |[Mayara Alves](https://github.com/Mayara-tech)| [Vinícius Mendes](https://github.com/yabamiah)|
| `2.0`    | 06/12/2023  | Correções aplicadas ao artefato após a verificação | [Limírio Guimarães](https://github.com/LimirioGuimaraes)| [Mayara Alves](https://github.com/Mayara-tech)|


