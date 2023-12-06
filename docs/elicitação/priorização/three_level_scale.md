# Three Level Scale

## Introdução

A técnica de priorização Three Level Scale envolve a categorização dos requisitos em três categorias de acordo com sua prioridade 
relativa: alta, média e baixa prioridade^1^. Nesse projeto, essa técnica foi utilizada por um desenvolvedor e um usuário, com o primeiro servindo de mediador e guiando o 
segundo durante o processo. Foi utilizado como inspiração o projeto 1/2023 Bilheteria Digital^2^</a>.

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
O usuário da aplicativo da Carteira Digital de Trânsito Igor Luna Almeida foi convidado para participar do presente método de priorização, informada dos fins de pesquisa deste e concordou com o uso das informações no projeto e com o [termo de consertimento](https://github.com/Requisitos-de-Software/2023.2-Carteira_Digital_de_Transito/blob/main/docs/elicita%C3%A7%C3%A3o/Termo%20de%20Consentimento.pdf). Na data de 01/10/2023, das 10h às 10:18, foi realizada uma reunião presencial entre a usuário e o desenvolvedor Mayara Alves, 
na qual toda a dinâmica do Three Level Scale foi explicada e a usuário categorizou os requisitos de acordo com sua visão, na tabela 1 podemos observar o cronograma executado da priorização.

### cronograma executado 
<center>

**Tabela 1** - Cronograma executado - Priorização

| Data | Descrição | entrevistadora |  Entrevistado | Horário | Entrevista
| --- | ---------------------| ---------------------- |---------------------| ---------------------- | ---------------------------- |
| 01/10/2023| Priorização  | [Mayara Alves](https://github.com/Mayara-tech) | Igor Luna Almeida | 10h00/10:18  | Presencial 

Fonte: [Mayara Alves](https://github.com/Mayara-tech) 
</center>

## Requisitos priorizados

Para a priorização foram escolhidos apenas alguns requisitos elicitados, que coincidiam com o entendimento do usuário e que facilitariam o entendimento do usuário na priorização também foi levado em consideração a dependência entre os requisitos. A tabela 2 apresentam os resultados dessa priorização.

Legenda das tabelas: 

* RFx: Requisito Funcional nºx
* RNFx: Requisito Não-Funcional nºx

### Requisitos Elicitados 

<font size="3"><p style="text-align: center">Tabela 2: Requisitos Elicitados.</p> </font>

<center>


|Requisito| Tipo | Priorização 
|----|-----|-----|
|Login pelo gov  		|RF1 | Alta 
|Obter versão digital da habilitação 						|RF2 | Alta
|Obter versão digital dos veiculos que você é principal condultor 		|RF3 | Alta
|Obter versão digital do CRLV												            |RF4 | Alta
|Consultar multas associadas a sua habilitação					                        |RF5 | Alta
|Consultar multas do seu veículo								                        |RF6 | Alta
|Consultar multas dos veículos que você é principal condutor	                        |RF7 | Alta
|O Aplicativo possui diferentes meios de pagamento de multa		                        |RF8 | Baixa
|Renvidicar a multa																		|RF9 | Baixa
|Contato com suporte																	|RF10 | Média
|Permite o acompanhamento do status da multa (a cobrar e pago)						    |RF12 | Média
|Permite visualizar histórico de multas do condutor									    |RF13 | Média
|Permite ao usuário fazer transferência de veículo							            |RF14 | Média
|Aplicativo deve possuir um FAQ 														|RF15 | Média
|Aplicativo mostra restrições e indicadores (restrição no veiculo, multa, judicial) 	|RF16 | Alta
|O aplicativo permite visualizar a politica de privicidade								|RNF1 | Alta
|O aplicativo deve divulgar campanhas e projetos do DETRAN								|RF17 | Baixa
|Validar cadastro de CNH																|RNF2 | Alta
|Aplicativo funciona em multisistemas (android e IOS) 									|RNF3 | Alta
|Aplicativo possui interface simple 													|RNF4 | Alta
|Aplicativo deve evitar erros e telas brancas durante o uso 							|RNF5 | Alta
|Possui modo escuro/claro																|RNF6 | Baixa
</center>


<font size="3"><p style="text-align: center">Fonte: [Mayara Alves](https://github.com/Mayara-tech).</p></font>

## Referências Bibliográficas

> <a id="FTF1Ref" href="#FTF1">1.</a> FIRST things first: Setting requirement priorities. In: WIEGERS, Karl E.; BEATTY, Joy. Software Requirements. 3. ed. [S. l.]: Microsoft Press, 2013. cap. 16, p. 313-329. ISBN 0735679665.
> 
> <a id="FTF2Ref" href="#FTF2">2.</a> HENRIQUE, Matheus. FERREIRA, Rafael. Perfil do Usuário. Repositório da disciplina de Requisitos de Software da Universidade de Brasília, 1/2023. Disponível em: [https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/perfil_de_usuario/](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/perfil_de_usuario/). Acesso em: 29 setembro de 2023.


## 📑 Histórico de Versões

| Versão  | Data | Descrição | Autor(es) | Revisor(es) |
| ---------- | -----  | ------ | ---------- | ---------- |
| `1.0` | 04/10/2023 | Criação da página | [Mayara Alves](https://github.com/Mayara-tech) | [Breno Queiroz](https://github.com/brenob6) |
| `1.1` | 25/10/2023 | Adicionando rastreabilidade | [Mayara Alves](https://github.com/Mayara-tech) | [Breno Queiroz](https://github.com/brenob6) |
| `1.2` | 25/10/2023 | Correção do artefato | [Mayara Alves](https://github.com/Mayara-tech) | [Milena Baruc](https://github.com/MilenaBaruc) |

 
