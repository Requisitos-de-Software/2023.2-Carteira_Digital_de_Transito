# Requisitos Elicitados

## Introdução 

Nesta página está listado todos requisitos obtidos com a etapa de elicitação, fornecendo uma melhor compreensão. Com isso, temos a Rastreabilidade, que tem capacidade de identificar, documentar e acompanhar as relações e conexões entre os diversos elementos dos requisitos ao longo do ciclo de vida. Essa prática tem como objetivo garantir a consistência, a compreensão e a gerência eficaz dos requisitos, permitindo que as mudanças sejam rastreadas e controladas de forma sistemática 

## Metodologia 

A metodologia adotada envolveu a consolidação de todos os requisitos funcionais (RF) e requisitos não funcionais (RNF) obtidos por meio de diversas técnicas de elicitação em uma tabela estruturada (Tabela 2). Nesta tabela, cada requisito é identificado por um ID exclusivo descrito na tabela 1, categorizado como RF ou RNF para indicar seu tipo e acompanhado de um status de implementação. Além disso, a tabela também rastreia a origem de cada requisito, destacando se ele foi obtido por meio de técnicas como o Glossario, StoryBoard, Introspecção e Entrevista.

<p align="center"><b>Tabela 01</b> - Legenda de identificação de ID.</p>
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


<p align="center"><b>Tabela 02</b> - Requisitos elicitados no aplicativo Carteira Digital de Trânsito.</p>
<center>

|Rastreabilidade |Requisito| Tipo | Implementação|
| ---- |-----| ------ | ------ |
| [ITP](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/Introspeccao/) |Login pelo gov  		|RF |   Implementado    |
| [ITP](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/Introspeccao/), [ENT](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/entrevista/), [SB](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/storyboard/) |Obter versão digital da habilitação 						|RF | Implementado  |
| [ITP](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/Introspeccao/) | Obter versão digital dos veiculos que você é principal condultor 		|RF  |  Implementado  |
| [ITP](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/Introspeccao/), [GL](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/glossario/), [SB](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/storyboard/), [ENT](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/entrevista/)| Obter versão digital do CRLV												            |RF   |    Implementado    |
| [ITP](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/Introspeccao/)  |Consultar multas associadas a sua habilitação					                        |RF  |  Implementado     |
| [ITP](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/Introspeccao/), [SB](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/storyboard/)   |Consultar multas do seu veículo								                        |RF   | Implementado    |
| [ITP](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/Introspeccao/) |Consultar multas dos veículos que você é principal condutor	                        |RF   | Implementado   |
| [ITP](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/Introspeccao/), [SB](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/storyboard/) |O Aplicativo possui diferentes meios de pagamento de multa		                        |RF    |   Implementado |
| [ITP](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/Introspeccao/) |Renvidicar a multa																		|RF  |    Implementado   |
| [ITP](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/Introspeccao/), [ENT](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/entrevista/) |Contato com suporte																	|RF   | Não implemetado   |
| [ITP](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/Introspeccao/) |Indicar principal condutor do veículo 													|RF   |    Implementado  |
| [ITP](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/Introspeccao/), [SB](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/storyboard/) |Permite o acompanhamento do status da multa (a cobrar e pago)						    |RF  |   Implementado     |
| [ITP](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/Introspeccao/) |Permite visualizar histórico de multas do condutor									    |RF  |    Implementado    |
| [ITP](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/Introspeccao/), [ENT](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/entrevista/) |Permite ao usuário fazer transferência de veículo							            |RF   |  Não implementado  |
| [ITP](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/Introspeccao/), [ENT](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/entrevista/) |Aplicativo deve possuir um FAQ 														|RF   |   Implementado  |
| [ITP](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/Introspeccao/) |Aplicativo mostra restrições e indicadores (restrição no veiculo, multa, judicial) 	|RF  |  Implementado     |
| [ITP](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/Introspeccao/) |O aplicativo permite visualizar a politica de privicidade								|RNF   |  Implementado   |
| [ITP](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/Introspeccao/) |O aplicativo deve divulgar campanhas e projetos do DETRAN								|RF   |  Implementado   |
| [ITP](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/Introspeccao/) |Validar cadastro de CNH																|RNF   | Implementado     |
| [ITP](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/Introspeccao/) |Aplicativo funciona em multisistemas (android e IOS) 									|RNF  |  Implementado    |
| [ITP](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/Introspeccao/) |Aplicativo possui interface simple 													|RNF   | Implementado    |
| [ITP](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/Introspeccao/) |Aplicativo deve evitar erros e telas brancas durante o uso 							|RNF  |  Não implementado    |
| [ITP](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/Introspeccao/) |Possui modo escuro/claro																|RNF  |  Não implementado   |
| [GL](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/glossario/) | Deve ser possível consultar as siglas apresentadas| RF | Não implementado |f
| [GL](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/glossario/) | Deve ser possível baixar os CRLV dos veículos| RF | Implementado |
| [GL](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/glossario/) | Facilitar o usuário a chegar a funcionalidade de aderir ao SNE       | RNF | Não implementado |
| [GL](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/glossario/) |Deve ser possível participar no Cadastro Positivo | RF | Implementado |
| [GL](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/glossario/), [ENT](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/entrevista/) | Dever ser possível consultar a classificação da infração | RF | Não implementado |
| [SB](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/storyboard/), [ENT](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/entrevista/) |Deve ser possível compartilhar os documentos de um veículo com seus coatores.| RF | Implementado
| [SB](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/storyboard/) |O usuário deve conseguir solicitar a outro usuário o compartilhamento dos documentos do veículo.| RF | Implementado
| [SB](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/storyboard/) |Deve ser possível acessar a CNH(digital) mesmo sem acesso a internet.| RNF | Não implementado
| [SB](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/storyboard/) |Deve existir um prazo de validade do compartilhamento da CNH.| RNF | Não implementado
| [SB](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/storyboard/), [ENT](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/entrevista/) |O aplicativo deve alertar o usuário caso seja multado .|RNF | Não implementado
| [ENT](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/entrevista/)  | O aplicativo deve permitir a pesquisa de informações sobre veículos por meio do número da placa. | RF | Não implementado |
| [ENT](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/entrevista/), [GLO](https://github.com/Requisitos-de-Software/2023.2-Carteira_Digital_de_Transito/blob/main/docs/elicita%C3%A7%C3%A3o/glossario.md) | Deve ser possível cadastrar e gerenciar múltiplos veículos na carteira digital. | RF | Implementado |
| [ENT](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/entrevista/) | O aplicativo deve disponibilizar informações em tempo real sobre condições de tráfego, acidentes e congestionamentos. | RF | Não implementado |
| [ENT](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/entrevista/), [SB](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/storyboard/) | Deve ser possível configurar alertas de vencimento da CNH e do licenciamento do veículo. | RF | Não implementado |
| [ENT](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/entrevista/)  | O aplicativo deve oferecer uma opção de backup seguro de todos os documentos e dados do usuário. | RF | Não implementado |
| [ENT](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/entrevista/) | Deve ser possível realizar o agendamento de serviços de manutenção e inspeção veicular. | RF | Não implementado |
| [ENT](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/entrevista/) | O aplicativo deve notificar o usuário sobre recalls e informações importantes do fabricante do veículo. | RF | Não implementado |
| [ENT](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/entrevista/) | Deve ser possível obter informações sobre as normas de trânsito, regulamentações e penalidades em vigor. | RF | Não implementado |

Fonte: [Luis Miranda](https://github.com/LuisMiranda10) e [Mayara Alves](https://github.com/Mayara-tech)
  
</center>


## 📑 Histórico de versões:

| Versão |    Data    |    Descrição         | Autor(es)  |    Revisor(es) |                  
|:-----: | :--------: | :-------------:      | :--------: | :-------------:| 
| `1.0`    | 30/09/2023  | Criação do documento | Breno e Limírio| [Mayara Alves](https://github.com/Mayara-tech)|
| `1.1`    | 21/10/2023  | Modificação da introdução e adição da rastreabilidade da tabela |[Luis Miranda](https://github.com/LuisMiranda10) e [Mayara Alves](https://github.com/Mayara-tech)| [Vinícius Mendes](https://github.com/yabamiah)|

