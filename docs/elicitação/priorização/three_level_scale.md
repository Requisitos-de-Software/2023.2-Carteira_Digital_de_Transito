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


| Tipo |             Descrição            |   ID    | Prioridade |
|------|----------------------------------|--------|-------|
| RF01 	| O usuário deve poder realizar cadastro 	| BS01/IS05	| Alta  |
| RF02	| O usuário deve poder realizar login 	| BS02/IS05 	| Alta  |
| RF03	| O usuário deve poder comprar ingressos dentro do app 	|  BS03/IS04/OBS10	|  Alta |
| RF04	| O usuário deve poder buscar eventos 	| BS04/IS09/OBS02/Q01	|  Alta |
| RF05	| O usuário deve ser capaz de filtrar eventos 	|  BS05	| Alta  |
| RF06	| O usuário deve acessar as notificações sobre os eventos 	| BS06 	| Alta  |
| RF07	| O usuário deve salvar os dados do cartão no app 	| BS07 	| Media  |
| RF08	| O usuário deve poder filtrar as cidades que desejar 	| BS08/IS01/OBS01	|  Alta |
| RF09	| O usuário deve fornecer sua localização	| BS09 	| Alta  |
| RF10	|  O usuário deve poder acessar o calendário de eventos	| BS10	| Alta  |
| RF11	| O usuário deve poder acessar os eventos a gostos de acordo com o perfil do usuário 	|  BS11	| Alta  |
| RF12	| O usuário deve poder responder a pesquisa de perfil sobre seus gostos	|  BS12	| Media  |
| RF13	| O usuário deve ser capaz de acessar as informações do evento	|  BS13	| Alta  |
| RF14	| O usuário deve ser capaz de acessar as atrações do evento 	| BS14 	| Alta  |
| RF15	| O usuário deve poder realizar pagamento com de várias formas 	| BS15/IS07/Q08 	| Alta  |
| RF16	| O usuário deve ter acesso a pré-venda 	| BS16 	| Alta  |
| RF17	| O usuário deve receber a cópia do ingresso por e-mail 	| BS17 	| Alta  |
| RF18	| O usuário deve ser capaz de conectar uma carteira digital 	| BS18	| Media  |
| RF19	| O usuário deve ser capaz de mudar o idioma do app 	|  BS19	| Alta  |
| RF20	| O usuário deve ser capaz de aumentar a fonte 	| BS21 	| Baixa  |
| RF21	| O usuário deve ser capaz de dar zoom 	| BS22 	| Alta  |
| RF22	| O usuário deve ser capaz de acessar a assistente virtual 	| BS23 	| Media  |
| RF23	| O usuário deve ser capaz de compartilhar o evento 	| BS24/OBS03 	| Baixa  |
| RF24 | O aplicativo filtra os eventos por data e por horário.  | IS02/Q03 | Media |
| RF25 | O aplicativo filtra os eventos por idade mínima de entrada.  | IS03/Q02 | Media |
| RF26 | O aplicativo permite excluir cadastro.  | IS06 | Media |
| RF27 | O aplicativo permite cancelar compras.  | IS08/OBS12/Q09 | Alta |
| RF28 | O aplicativo permite escolher a quantidade de ingressos que o usuário deseja comprar. | OBS04 | Alta |
| RF29 | O aplicativo permite selecionar as poltronas para pessoas idosas, crianças, obesas ou com deficiência, caso as tenha. | OBS05 |  Alta  |
| RF30 | O aplicativo permite selecionar as poltronas especiais. | OBS06 | Alta |
| RF31 | Na seleção de ingresso, o aplicativo permite adicionar um cupom de desconto. | OBS07 |Alta |
| RF32 | Caso o local disponibilize, o aplicativo disponibiliza uma visão prévia da poltrona. | OBS08 | Alta |
| RF33 | O aplicativo permite a doação por parte do usuário para fundações. | OBS09 | Media  |
| RF34 | O aplicativo possui uma função para entrar em contato com o suporte. | OBS11 | Alta |
| RF35 | O aplicativo permite ao usuário alterar seus dados. | OBS13 |Alta |
| RF36 | O aplicativo possui uma função que auxilia na recuperação da conta do usuário. | OBS14 |  Alta  |
| RF37 | O aplicativo filtra eventos por categorias.  |Q04 | Alta  |
| RF38 | O aplicativo da sugestões de eventos com base no histórico de buscas do usuário.  |Q05 | Media  |
| RF39 | O aplicativo tem palavras-chave ou tags associadas a eventos para facilitar a busca.  |Q06 | Alta  |
| RF40 | O aplicativo notifica usuário sobre eventos, quando permitido | Q07 | Media|   

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

 
