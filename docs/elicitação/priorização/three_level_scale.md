# Three Level Scale

## Introdução

A técnica de priorização _Three Level Scale_<a id="FTF1" href="#FTF1Ref">^1^</a> envolve a categorização dos requisitos em três categorias de acordo com sua prioridade 
relativa: alta, média e baixa prioridade. Nesse projeto, essa técnica foi utilizada por um desenvolvedor e um usuário, com o primeiro servindo de mediador e guiando o 
segundo durante o processo. Foi utilizado como inspiração o projeto _1/2023 Bilheteria Digital_<a id="FTF2" href="#FTF2Ref">^2^</a>.

## Metodologia

A eficácia desse método está diretamente ligada à obtenção de um consenso entre as partes envolvidas sobre o significado de cada nível de prioridade na escala. 
Portanto, é fundamental considerar a urgência e a importância de cada requisito ao determinar sua prioridade. Como resultado, as três categorias foram definidas da seguinte maneira:

* Alta prioridade: requisitos importantes e urgentes, devem estar implementados na release mais próxima.
* Média prioridade: requisitos importantes, mas não urgentes, logo podem esperar uma release mais distante.
* Baixa prioridade: requisitos nem importantes, nem urgentes, sua implementação pode demorar muito tempo.

Não existe uma atribuição de valores numéricos aos requisitos; em vez disso, eles são agrupados em categorias de prioridade. 
Embora o método não lide diretamente com a descrição das relações de dependência entre os requisitos, é crucial ter em mente essas interconexões ao avaliar e estabelecer as prioridades. 
As dependências podem ter um efeito significativo na relevância e nas implicações dos requisitos. 
Portanto, é aconselhável considerar cuidadosamente as interdependências ao avaliar os requisitos e tomar decisões bem informadas sobre sua ordenação.

## Participantes
O usuário da aplicativo da Carteira Digital de Trânsito Igor Luna Almeida foi convidado para participar do presente método de priorização, informada dos fins de pesquisa deste e concordou com o uso das informações no projeto e com o termo de consertimento. Na data de 01/10/2023, das 10h às 10:18, foi realizada uma reunião presencial entre a usuária e o desenvolvedor Mayara Alves, 
na qual toda a dinâmica do Three Level Scale foi explicada e a usuário categorizou os requisitos de acordo com sua visão. As tabelas 1 e 2 apresentam os resultados dessa priorização.

## Requisitos priorizados

Legenda das tabelas: 

* RFx: Requisito Funcional nºx
* RNFx: Requisito Não-Funcional nºx

### Requisitos Elicitados 

<font size="3"><p style="text-align: center">Tabela 1: Requisitos Elicitados.</p></font>

<center>


|Requisito| Tipo | Priorização 
|----|-----|-----|
|Login pelo gov  		|RF | Alta 
|Obter versão digital da habilitação 						|RF | Alta
|Obter versão digital dos veiculos que você é principal condultor 		|RF | Alta
|Obter versão digital do CRLV												            |RF | Alta
|Consultar multas associadas a sua habilitação					                        |RF | Alta
|Consultar multas do seu veículo								                        |RF | Alta
|Consultar multas dos veículos que você é principal condutor	                        |RF | Alta
|O Aplicativo possui diferentes meios de pagamento de multa		                        |RF | Baixa
|Renvidicar a multa																		|RF | Baixa
|O aplicativo permite solicitar renvidicação da multa para outro condutor				|RF | Baixa
|Contato com suporte																	|RF | Média
|Indicar principal condutor do veículo 													|RF | Baixa
|Permite ao condutor verificar exames (toxicológico) 									|RF | Baixa
|Permite que o usuario acesse cursos especializados associados a sua habilitação 	    |RF | Baixa
|Permite o acompanhamento do status da multa (a cobrar e pago)						    |RF | Média
|Permite visualizar histórico de multas do condutor									    |RF | Média
|Permite ao condutor participar do cadastro positivo 							        |RF | Baixa
|Permite ao usuário fazer transferência de veículo							            |RF | Média
|Aplicativo deve possuir um FAQ 														|RF | Média
|Aplicativo mostra restrições e indicadores (restrição no veiculo, multa, judicial) 	|RF | Alta
|O aplicativo permite visualizar a politica de privicidade								|RF | Alta
|O aplicativo deve divulgar campanhas e projetos do DETRAN								|RF | Baixa
|Validar cadastro de CNH																|RNF | Alta
|Aplicativo funciona em multisistemas (android e IOS) 									|RNF | Alta
|Aplicativo possui interface simple 													|RNF | Alta
|Aplicativo deve evitar erros e telas brancas durante o uso 							|RNF | Alta
|Possui modo escuro/claro																|RNF | Baixa
</center>


<font size="3"><p style="text-align: center">Fonte: [Douglas Alves](https://github.com/dougAlvs).</p></font>

## Referências Bibliográficas

> <a id="FTF1Ref" href="#FTF1">1.</a> FIRST things first: Setting requirement priorities. In: WIEGERS, Karl E.; BEATTY, Joy. Software Requirements. 3. ed. [S. l.]: Microsoft Press, 2013. cap. 16, p. 313-329. ISBN 0735679665.
> 
> <a id="FTF2Ref" href="#FTF2">2.</a> HENRIQUE, Matheus. FERREIRA, Rafael. Perfil do Usuário. Repositório da disciplina de Requisitos de Software da Universidade de Brasília, 1/2023. Disponível em: [https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/perfil_de_usuario/](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/perfil_de_usuario/). Acesso em: 29 setembro de 2023.


## Histórico de Versões

| Versão  | Data | Descrição | Autor(es) | Revisor(es) |
| ---------- | -----  | ------ | ---------- | ---------- |
| 1.0 | 04/10/2023 | Criação da página | [Mayara Alves](https://github.com/Mayara-tech) | [Breno Queiroz](https://github.com/brenob6)) |

 
