# Pós Rastreabilidade

## Introdução

Este documento inaugura uma etapa crucial em nosso projeto, focada na pós-rastreabilidade, com o propósito fundamental de estabelecer uma conexão sólida entre requisitos, arquitetura e implementação. Nossa abordagem visa destacar 
de forma explícita as relações de dependência entre os requisitos e seus artefatos correlacionados, abrangendo as esferas de requisitos, arquitetura e implementação. A pós-rastreabilidade aqui delineada se materializa por meio de
ligações e elos que emergem da intrincada interrelação entre os artefatos especificados. Este processo busca não apenas documentar, mas também compreender as conexões fundamentais que permeiam o ciclo de vida do projeto,
oferecendo uma visão abrangente e detalhada das dependências existentes. Assim, ao explorar as intricadas relações entre requisitos, arquitetura e implementação, este documento se propõe a ser uma ferramenta vital na compreensão
do panorama do projeto.

## Metodologia

O meta-modelo que orienta a realização da rastreabilidade neste projeto foi inicialmente proposto por Toranzo^1^, classificando as informações rastreadas em quatro categorias distintas:

1. **Ambiental:** Engloba aspectos como leis, objetivos, estratégias e padrões.
2. **Organizacional:** Inclui objetivos, regras e processos.
3. **Gerencial:** Envolvendo objetivos, tarefas e restrições.
4. **Desenvolvimento:** Relacionado a requisitos, diagramas e programas.

É relevante ressaltar que, no contexto específico deste projeto, todas as informações rastreadas estão categorizadas como "Desenvolvimento". Além disso, realizou-se uma adaptação do meta-modelo de Toranzo para a execução da 
pós-rastreabilidade. Essa adaptação visa explicitar a conexão entre os artefatos de desenho e implementação com os requisitos elicitados, e vice-versa. Nesse modelo adaptado, os elos são definidos por seis categorias principais: 
satisfação, recurso, responsabilidade, representação, alocado e agregação. É importante observar que, no escopo deste artefato, o elo de responsabilidade não será abordado. Tal decisão fundamenta-se na presença de informações 
nos artefatos que impossibilitam a execução eficaz dessa forma específica de rastreabilidade.<br/>
Assim, a metodologia aplicada neste artefato de pós-rastreabilidade busca não apenas seguir o meta-modelo de Toranzo, mas também adaptá-lo de maneira pragmática para as necessidades específicas do projeto. Esta abordagem visa 
aprimorar a compreensão das inter-relações entre os artefatos, proporcionando uma visão mais precisa e aplicável ao contexto do desenvolvimento em questão. A tabela 1 mostra o modelo que será utilizado para documentar a 
pós-rastreabilidade dos requisitos do projeto.

<center>

Tabela 1 - Template Pós-Rastreabilidade

|                 Artefato Analisado                   | Classificação do Artefato Analisado |
| :--------------------------------------------------: | :---------------------------------: |
|                     Tipos de Elo                     |       Artefatos Relacionados        |
|                      Satisfação                      |                  -                  |
|                       Recurso                        |                  -                  |
|                    Representação                     |                  -                  |
|                       Alocado                        |                  -                  |
|                      Agregação                       |                  -                  |

Fonte: Meta-modelo de Toranzo (TORANZO, 2002)^1^.

</center>

Com base nos slides da aula 26 da professora Milene Serrano e Maurício Serrano^2^, os principais **elos de rastreabilidade** são:

1. **Satisfação**: Indica que a classe de origem depende da satisfação proporcionada pela classe de destino.
2. **Recurso**: Reflete a dependência de recursos da classe de origem em relação à classe de destino.
3. **Responsabilidade**: Registra a participação, responsabilidade e ação de pessoas sobre os artefatos.
4. **Representação**: Captura a forma como os requisitos são representados ou modelados em outras linguagens.
5. **Alocado**: Relaciona a classe de origem a uma classe de destino que representa um subsistema.
6. **Agregação**: Indica a "composição" de elementos.

## Rastreabilidade

Neste tópico, serão apresentadas as tabelas referentes aos elos dos artefatos analisados, que se referem aos requisitos implementados e não implementados pela Carteira Digital de Trânsito. Sendo assim, as Tabelas de 2 a 42 apresentam a rastreabilidade dos requisitos funcionais e não funcionais.
<center>
 
#### **Tabela 5 - RF 04**


| RF04 Obter versão digital do CRLV 			| Requisito Funcional 		      |
|----------------------------------------------------------- | ----------------------- |
| Satisfação 						| [História de Usuário US4](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/agil/historiasUsuario/), [História de Usuário US5](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/agil/historiasUsuario/)|
| Recurso						|[Cenário C06](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/cenarios/), [Léxico L11](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/léxicos/), |
| Representação 					| [Diagrama de casos de uso](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/casosDeUso/) |
| Alocado 						| [Cenário C09](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/cenarios/), [Léxico L12](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/léxicos/) |
| Agregação | [Caso de Uso UC01](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/casosDeUso/), [Caso de Uso UC02](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/casosDeUso/),  [História de Usuário US4](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/agil/historiasUsuario/), [História de Usuário US5](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/agil/historiasUsuario/), [Cenário C2](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/cenarios/), [Cenário C10](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/cenarios/), [Léxico L11](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/léxicos/) |

Fonte: [Limirio Guimarães](https://github.com/LimirioGuimaraes).

#### **Tabela 7 - RF 06**


| RF06 Consultar as multas do seu veículo 			| Requisito Funcional 		      |
|----------------------------------------------------------- | ----------------------- |
| Satisfação 						| [História de Usuário US07](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/agil/historiasUsuario/)|
| Recurso						|[Casos de Uso UC03](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/casosDeUso/) |
| Representação 					| [Diagrama de casos de uso](https://requisi.2-Catos-de-software.github.io/2023rteira_Digital_de_Transito/modelagem/casosDeUso/) |
| Alocado 						| [Caso de Uso UC04](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/casosDeUso/), [Caso de Uso UC05](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/casosDeUso/) |
| Agregação | [Caso de Uso UC01](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/casosDeUso/), [Caso de Uso UC03](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/casosDeUso/), [Caso de Uso UC04](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/casosDeUso/), [História de Usuário US07](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/agil/historiasUsuario/), [Léxicos L08](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/l%C3%A9xicos/) |

Fonte: [Luis Miranda](https://github.com/LuisMiranda10).

#### **Tabela 11 - RF 10**

| RF10 Contato com suporte 				| Requisito Funcional |
|----------------------------------------------------------- | ----------------------- |
| Satisfação 						| [NFR03](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/agil/framework/) |
| Recurso 						| [Caso de Uso UC06](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/casosDeUso/) |
| Representação 					| [Diagrama de casos de uso](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/casosDeUso/) |
| Alocado 						| [NFR Suportabilidade](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/agil/framework/)|
| Agregação 						| [História de Usuário US12](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/agil/historiasUsuario/), [Cenário C4](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/cenarios/) |

Fonte: [Limirio Guimarães](https://github.com/LimirioGuimaraes).

#### **Tabela 12 - RF 11**


| RF11 Indicar principal condutor do veículo 		| Requisito Funcional 		      |
|----------------------------------------------------------- | ----------------------- |
| Satisfação 						|  [História de Usuário US03](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/agil/historiasUsuario/) |
| Recurso						|  [Léxicos L08](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/l%C3%A9xicos/) , [Caso de Uso UC04](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/casosDeUso/) |
| Representação 					| [Diagrama de casos de uso](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/casosDeUso/) |
| Alocado 						| [](), []() |
| Agregação | [](), [](),  [](), [](), [](), [](), []() |

Fonte: [Luis Miranda](https://github.com/LuisMiranda10).

#### **Tabela 13 - RF 12**


| RF04 Obter versão digital do CRLV 			| Requisito Funcional 		      |
|----------------------------------------------------------- | ----------------------- |
| Satisfação 						| , []()|
| Recurso						|[](), [](), |
| Representação 					| []() |
| Alocado 						| [](), []() |
| Agregação | [](), [](),  [](), [](), [](), [](), []() |

Fonte: [Luis Miranda](https://github.com/LuisMiranda10).

#### **Tabela 21 - RF 20**


| RF04 Obter versão digital do CRLV 			| Requisito Funcional 		      |
|----------------------------------------------------------- | ----------------------- |
| Satisfação 						| [](), []()|
| Recurso						|[](), [](), |
| Representação 					| []() |
| Alocado 						| [](), []() |
| Agregação | [](), [](),  [](), [](), [](), [](), []() |

Fonte: [Luis Miranda](https://github.com/LuisMiranda10).

#### **Tabela 33 - RNF 01**


| RF04 Obter versão digital do CRLV 			| Requisito Não Funcional 		      |
|----------------------------------------------------------- | ----------------------- |
| Satisfação 						| [](), []()|
| Recurso						|[](), [](), |
| Representação 					| []() |
| Alocado 						| [](), []() |
| Agregação | [](), [](),  [](), [](), [](), [](), []() |

Fonte: [Luis Miranda](https://github.com/LuisMiranda10).

#### **Tabela 35 - RNF 03**

| RNF03 Aplicativo funciona em multisistemas (android e IOS) | Requisito Não Funcional |
|----------------------------------------------------------- | ----------------------- |
| Satisfação 						     | [Especificação Suplementar RS1](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/especificacao-suplementar/), [NFR6](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/agil/framework/) |
| Recurso 						     | - |
| Representação						     | [NFR06](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/agil/framework/) |
| Alocado 						     | [Especificação suplementar suportabilidade](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/especificacao-suplementar/) |
| Agregação 						     | [NFR Suportabilidade](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/agil/framework/) |

Fonte: [Limirio Guimarães](https://github.com/LimirioGuimaraes).

#### **Tabela 36 - RNF 04**


| RF04 Obter versão digital do CRLV 			| Requisito Não Funcional 		      |
|----------------------------------------------------------- | ----------------------- |
| Satisfação 						| [](), []()|
| Recurso						|[](), [](), |
| Representação 					| []() |
| Alocado 						| [](), []() |
| Agregação | [](), [](),  [](), [](), [](), [](), []() |

Fonte: [Luis Miranda](https://github.com/LuisMiranda10).

#### **Tabela 39 - RNF 07**

| RNF07 Facilitar o usuário a chegar a funcionalidade de aderir ao SNE | Requisito Não Funcional |
|----------------------------------------------------------- | ----------------------- |
| Satisfação 							       | [História de Usuário US11](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/agil/historiasUsuario/)|
| Recurso          | [Caso de Uso UC05](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/casosDeUso/) |
| Representação							       | [Diagrama de casos de uso](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/casosDeUso/) |
| Alocado 							       | [Caso de Uso UC05](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/casosDeUso/) |
| Agregação							       | [Léxico L8](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/léxicos/) |

Fonte: [Limirio Guimarães](https://github.com/LimirioGuimaraes).

#### **Tabela 40 - RNF 08**

| RNF08 Deve ser possível acessar a CNH(digital) mesmo sem acesso a internet | Requisito Não Funcional |
|----------------------------------------------------------- | ----------------------- |
| Satisfação 								     | [História de Usuário US03](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/agil/historiasUsuario/) |
| Recurso         | [Cenário C10](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/cenarios/) |
| Representação 							     | [Diagrama de casos de uso](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/casosDeUso/) |
| Alocado 								     | [NFR Confiabilidade](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/agil/framework/) |
| Agregação 								     | [História de Usuário US03](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/agil/historiasUsuario/), [Caso de Uso UC01](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/casosDeUso/)|

Fonte: [Limirio Guimarães](https://github.com/LimirioGuimaraes).

#### **Tabela 42 - RNF 10**

| RNF10 O aplicativo deve alertar o usuário caso seja multado | Requisito Não Funcional |
|----------------------------------------------------------- | ----------------------- |
| Satisfação 						      | [História de Usuário US12](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/agil/historiasUsuario/) |
| Recurso                | - |
| Representação 					      | Protótipo de alta fidelidade: <br/>![prototipoNotificação](../assets/imagem_2023-11-20_100146911.png) |
| Alocado 						      |  [NFR Confiabilidade](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/agil/framework/) |
| Agregação 						      | - |

Fonte: [Limirio Guimarães](https://github.com/LimirioGuimaraes).


</center>

# Referência Bibliográficas
> 1.</a> TORANZO, M.; CASTRO, J; MELLO, E. Uma proposta para melhorar o rastreamento de requisitos. PUC-Rio: Workshop em Engenharia de Requisitos, Rio de Janeiro, 2002. Disponível em: http://wer.inf.puc-rio.br/WERpapers/artigos/artigos_WER02/toranzo.pdf. Acesso em: 17/11/2023.<br/>
> 2. Slides da Aula 26 da Professora Milene Serrano. Disponível em: https://aprender3.unb.br/pluginfile.php/2692879/mod_resource/content/1/Requisitos%20-%20Aula%20026.pdf. Acesso em: 18/11/2023.

# Bibliografia
> KLAUS POHL, CHRIS RUPP. Requirements Engineering Fundamentals.<br/>
> REQUISITOS DE SOFTWARE. Bilheteria Digital. Distrito Federal, 2023. Disponível em: <https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/>. Acesso em: 17/11/2023.

## Histórico de Versões
|Versão|Data|Descrição|Autor|Revisor|
|:----:|----|---------|-----|:-------:|
|`1.0`|16/11/2023|Criação do documento|[Limirio Guimarães](https://github.com/LimirioGuimaraes) | | 
|`1.1`|18/11/2023|Adicionada tabela dos requisitos RF4, RF10, RNF3, RNF7, RNF8 e RNF10 |[Limirio Guimarães](https://github.com/LimirioGuimaraes) | | 
 
