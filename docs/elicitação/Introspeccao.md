# Introspecção

## Introdução
Quando falamos em técnicas de elicitação, de acordo com Goguen (1994), a técnica de introspecção é uma das mais utilizadas, já que depende apenas do avaliador. A introspecção é uma técnica na qual a atividade é baseada em "imaginar" como o sistema deve ser e se comportar para solucionar um determinado problema do usuário.

Como foi dito, esta técnica é realizada pelo próprio avaliador, levando em consideração um ponto de vista particular. Isso nos traz benefícios e vantagens ao utilizar esta técnica, que são:

**Vantagens**: Dá a oportunidade para o avaliador conseguir ter uma concepção de como o sistema funciona e se comporta rapidamente, especialmente quando está utilizando uma certa "encenação" de um usuário imaginário.

**Desvantagens**: O avaliador pode estar fortemente vinculado ao uso do sistema, o que pode dificultar a visão na perspectiva de algum outro tipo de usuário.

## Metodologia
Para a preparação da técnica, foi necessário elaborar mentalmente um cenário de como o sistema deve ser para um usuário que busca resolver um determinado problema.

O cenário imaginário elaborado foi: "Um jovem que tirou recentemente sua carteira de habilitação e herdou de presente o carro do pai. Ele pretende usar o aplicativo da carteira digital de trânsito para poder armazenar sua CNH e o documento do seu carro para está sempre com ele em seu dispositivo móvel, além dele consultar se o veiculo está com alguma pendência antes de começar a dirijo-lo".

## Requisitos Elicitados
Após o exercício mental de utilizar o aplicativo da Carteira Digital de Trânsito para solucionar o problema de um usuário imaginário, conseguimos eliciar os requisitos apresentados na Tabela 1. Identificamos cada requisito por uma sigla formada por "ITP" + um número. Para representar o tipo do requisito, serão usadas as siglas "RF" ou "RNF", que representam o tipo do requisito funcional ou não funcional. Também indicaremos se já há uma implementação do requisito no aplicativo.

<center>

<p align="center"><b>Tabela 01</b> - Requisitos elicitados </p>

| **Identificador** | **Requisitos** | **Tipo** | **Implementado** |
|--------------|-------------|-----|-----------------|
|ITP01 |Login pelo gov  		|RF |   Implementado    |
|ITP02 |Obter versão digital da habilitação 						|RF |   Implementado  |
|ITP03 |Obter versão digital dos veiculos que você é principal condultor 		|RF  |  Implementado    |
|ITP04 |Obter versão digital do CRLV												            |RF   |     Implementado     |
|ITP05 |Consultar multas associadas a sua habilitação					                        |RF  |    Implementado     |
|ITP06 |Consultar multas do seu veículo								                        |RF   |   Implementado    |
|ITP07 |Consultar multas dos veículos que você é principal condutor	                        |RF   |    Implementado  |
|ITP08 |O Aplicativo possui diferentes meios de pagamento de multa		                        |RF    |    Implementado  |
|ITP09 |Renvidicar a multa																		|RF  |   Implementado      |
|ITP10 |O aplicativo permite solicitar renvidicação da multa para outro condutor				|RF   |    Implementado  |
|ITP11 |Indicar principal condutor do veículo 													|RF   |    Implementado    |
|ITP12 |Permite o acompanhamento do status da multa (a cobrar e pago)						    |RF  |    Implementado      |
|ITP13 |Permite ao usuário fazer transferência de veículo							            |RF   |  Não implementado  |
|ITP14 |Aplicativo mostra restrições e indicadores (restrição no veiculo, multa, judicial) 	|RF  |  Implementado     |
|ITP15 |O aplicativo permite visualizar a politica de privicidade								|RF   |   Implementado  |
|ITP16 |O aplicativo deve divulgar campanhas e projetos do DETRAN								|RF   |   Implementado   |
|ITP17 |Validar cadastro de CNH																|RNF   |   Implementado    |
|ITP18 |Aplicativo funciona em multisistemas (android e IOS) 									|RNF  |    Implementado   |
|ITP19 |Aplicativo possui interface simple 													|RNF   | Implementado     |
|ITP20 |Aplicativo deve evitar erros e telas brancas durante o uso 							|RNF  |  Não implementado    |
|ITP21 |Possui modo escuro/claro																|RNF  |  Não implementado   |

Fonte: [Breno Queiroz](https://github.com/brenob6), [Limirio Guimarães](https://github.com/LimirioGuimaraes) e [Mayara Alves](https://github.com/Mayara-tech) 

</center>

## Bibliografia
> Elicitação de Requisitos, PUC-Rio. Disponível em: [https://www.maxwell.vrac.puc-rio.br/15760/15760_3.PDF](https://www.maxwell.vrac.puc-rio.br/15760/15760_3.PDF).<br>
> Luiz Eduardo Galvão Martins. Uma Metodologia de Elicitação de Requisitos de Software Baseada na Teoria da Atividade. Unicamp, 2001. <br>
> Marcelo Medeiros Eler. Aula 5 - Requisitos de Software - Conceitos e Técnicas de Elicitação. Universidade de São Paulo, 2006. Disponível em: [https://edisciplinas.usp.br/pluginfile.php/7993139](https://edisciplinas.usp.br/pluginfile.php/7993139/mod_resource/content/1/05%20-%20Requisitos%20de%20Software%20-%20Conceitos%20e%20T%C3%A9cnicas%20de%20Elicita%C3%A7%C3%A3o.PDF).<br>

## 📑 Histórico de Versões
| **Versão**   |   **Data**   | **Descrição** | **Autores** | **Revisor** |
|--------|---------|-----------|--------|---------|
|`1.0`| 21/10/2023 | Criação da página de introspecção | [Breno Queiroz](https://github.com/brenob6), [Limirio Guimarães](https://github.com/LimirioGuimaraes) e [Mayara Alves](https://github.com/Mayara-tech)| [Vinicius Mendes](https://github.com/yabamiah) |
|`1.1`| 06/12/2023 | Ajustes na padronização do projeto | [Limirio Guimarães](https://github.com/LimirioGuimaraes)  |[Mayara Alves](https://github.com/Mayara-tech) |
