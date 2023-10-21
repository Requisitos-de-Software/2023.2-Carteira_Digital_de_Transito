# Casos de Uso

## Introdução

Um caso de uso é uma forma de representar as interações entre um sistema ou aplicativo e os usuários ou entidades externas que se beneficiam dele. Um diagrama de caso de uso é uma ferramenta visual que usa símbolos e conectores UML para mostrar os casos de uso, os atores e o limite do sistema. Um diagrama de caso de uso ajuda a definir e organizar os requisitos funcionais do sistema, especificar o contexto e as metas do sistema e modelar o fluxo básico de eventos no caso de uso. Um diagrama de caso de uso UML é ideal para representar as metas de interações entre sistemas e usuários.

## Metodologia

O artefato que foi criado é um diagrama de casos de uso UML, que representa as interações entre o sistema e os usuários ou entidades externas. A abordagem utilizada para a criação do diagrama foi a tradicional, que segue os padrões e símbolos da UML. A ferramenta escolhida para a diagramação foi o LucidChart, um software online que permite criar diversos tipos de diagramas. Para entender melhor as necessidades e desejos dos usuários finais do sistema, foi utilizada a persona Jair Motonaro, que representa um tipo de usuário com características específicas. Com a persona Jair Motonaro, foi possível modelar cenários realistas de uso do sistema, levando em conta as diferentes necessidades e objetivos do usuário.

## Glossário

Um diagrama de casos de uso é uma forma poderosa de capturar requisitos, definindo as interações entre um sistema e seus usuários, conhecidos como "atores". Neste glossário, você encontrará explicações detalhadas de cada um dos elementos que compõem um diagrama de casos de uso. Vamos explorar os conceitos-chave que possibilitam a representação visual de sistemas de forma eficaz e compreensível.

<center>

<font size="3"><p style="text-align: center"><b>Tabela 1</b>: Elementos do diagrama de casos de uso</p></font>

|    Símbolo    |     Nome     |    Descrição    |
| ------------- | ------------ | --------------- |
| ![Elipse](../assets/elipseCasosDeUso.png)| Caso de uso  | Representa uma funcionalidade ou objetivo do sistema. A elipse contém o nome do caso de uso dentro ou abaixo dela.|
| ![StickMan](../assets/stickmanCasosDeUso.png)     | Ator         | Um ator é um elemento que participa das interações com o seu sistema ou aplicativo. Um ator pode ser uma pessoa, uma organização ou um sistema externo que tem algum interesse ou benefício no seu sistema.  |
| ![Retângulo](../assets/retanguloCasosDeUso.png)    | Sistema      | Representa o limite do sistema, ou seja, o escopo e o contexto do sistema que está sendo modelado. O retângulo pode conter os casos de uso que são internos ao sistema e separá-los dos atores que são externos ao sistema. |
| ![Flechas](../assets/setas_casosDeUso.png)| Relações     | As flechas representam os relacionamentos entre os casos de uso e os atores ou entre os próprios casos de uso. Existem diferentes tipos de flechas que indicam diferentes tipos de relacionamentos, como associação, inclusão e extensão. A associação é uma linha sólida entre um ator e um caso de uso que indica uma interação entre eles. A inclusão é uma linha tracejada entre dois casos de uso que indica que um caso de uso é incluído em outro caso de uso. A extensão é uma linha tracejada com uma seta entre dois casos de uso que indica que um caso de uso é estendido por outro caso de uso. |

<font size="2"><p style="text-align: center"><b>Fonte: [Limirio Guimarães](https://github.com/LimirioGuimaraes)</b></p></font>

<center/>

## Diagrama de Casos de Uso

A figura 1 demonstra o diagrama de casos de uso.

<font size="3"><p style="text-align: center">Figura 1: Casos de uso do app Carteira Digital de Trânsito</p></font>

<img src="../assets/diagramaDeCasosDeUso.png" class="usecaseElement">

<font size="2"><p style="text-align: center"><b>Fonte: [Limirio Guimarães](https://github.com/LimirioGuimaraes)</b></p></font>

## Especialização dos casos de uso

As tabelas de 2 a 8 mostram a especialização dos casos de uso identificados.

<p style="text-align: center">Tabela 2: Acessar CNH digital</p>

| **UC 1**              | **Acessar CNH digital**    |
|-----------------------|----------------------------|
| Descrição             | Este caso de uso descreve o processo pelo qual o usuário acessa a Carteira Nacional de Habilitação (CNH) digital armazenada no dispositivo.             |
| Ator                  | Usuário                    | 
| Frequência de uso     | Média                      | 
| Pré-condições         |- O aplicativo está instalado e em funcionamento no dispositivo do usuário.    |
| Ação                  |- O usuário abre o aplicativo da CNH Digital.<br/> - O usuário seleciona a opção "Acessar CNH Digital".                                            |
| Fluxo principal       |- O aplicativo exibe as informações da CNH digital na tela. <br/> - O usuário pode navegar pelas informações da CNH, como nome, foto, número da CNH, categoria, data de validade, entre outras.<br/> - O usuário pode escolher sair do aplicativo a qualquer momento.                     |
| Fluxo alternativo     | Não há                     |
| Fluxo de exceção      | Se ocorrer algum erro durante o acesso à CNH digital, o aplicativo deve lidar com a exceção adequadamente, exibindo uma mensagem de erro e oferecendo opções para tentar novamente ou sair do aplicativo.                                          |
| Pós-condições         | O usuário pode visualizar as informações da CNH digital. |
| Data de criação       | 21/10/2023                 |
| Rastreabilidade       | xxxxx                      |

<font size="3"><p style="text-align: center">Fonte: [Limirio Guimarães](https://github.com/LimirioGuimaraes).</p></font>

<p style="text-align: center">Tabela 3: Acessar CRLV digital</p>

| **UC 2**              | **Acessar CRLV digital**     |
|-----------------------|------------------------------|
| Descrição             | Este caso de uso descreve o processo em que o usuário acessa o Certificado de Registro e Licenciamento de Veículo (CRLV) digital armazenado no dispositivo.|
| Ator                  | Usuário                      | 
| Frequência de uso     | Média                        |
| Pré-condições         | - O aplicativo está instalado e em funcionamento no dispositivo do usuário. |
| Ação                  | - O usuário abre o aplicativo CRLV Digital.<br/> - O usuário seleciona a opção "Acessar CRLV Digital".|
| Fluxo principal       | 1. Se um CRLV digital for encontrado no banco de dados do dispositivo:<br/> - O aplicativo exibe as informações do CRLV digital na tela.<br/> - O usuário pode visualizar detalhes como placa do veículo, número do Renavam, informações do proprietário, data de licenciamento, entre outros.<br/>2. Se nenhum CRLV digital for encontrado no banco de dados do dispositivo:<br/> - O aplicativo exibe uma mensagem informando que não há CRLV cadastrado na conta do dispositivo. |
| Fluxo alternativo     | Não há.|
| Fluxo de exceção      | Em caso de erro durante o acesso ao CRLV digital, o aplicativo deve lidar com a exceção adequadamente, exibindo uma mensagem de erro e oferecendo opções para tentar novamente ou sair do aplicativo. |
| Pós-condições         | O usuário pode visualizar as informações do CRLV digital, se disponíveis no dispositivo.|
| Data de criação       | 21/10/2023                   |
| Rastreabilidade       | xxxxx |


<font size="3"><p style="text-align: center">Fonte: [Limirio Guimarães](https://github.com/LimirioGuimaraes).</p></font>

<p style="text-align: center">Tabela 4: Visualizar Infrações</p>

| **UC 3**              | **Visualizar Infrações**   |
|-----------------------|----------------------------|
| Descrição             | Este caso de uso permite ao usuário visualizar infrações de trânsito. Existem duas opções: visualizar infrações associadas à Carteira Nacional de Habilitação (CNH) do usuário e visualizar infrações associadas a um veículo específico. As informações detalhadas das infrações são exibidas ao usuário. |
| Ator                  | Usuário                      | 
| Frequência de uso     | Baixa |
| Pré-condições         | - O aplicativo está instalado e em funcionamento no dispositivo do usuário.<br/>- O dispositivo do usuário possui uma conexão ativa com a internet. |
| Ação                  | - O usuário abre o aplicativo.<br/>- O usuário seleciona a opção "Visualizar Infrações".<br/> - O aplicativo apresenta ao usuário as duas opções: visualizar infrações associadas à CNH ou visualizar infrações associadas a um veículo.<br/> - O usuário escolhe uma das opções.<br/> - O aplicativo busca e exibe as informações detalhadas das infrações de acordo com a opção escolhida. |
| Fluxo principal       | 1. Para visualizar infrações associadas à CNH:<br/> - O aplicativo busca e exibe as informações das infrações associadas à CNH.<br/> 2. Para visualizar infrações associadas a um veículo:<br/> - O usuário escolhe um dos veículos a qual tem acesso a informação.<br/> - O aplicativo busca e exibe as informações das infrações associadas ao veículo em questão. |
| Fluxo alternativo     | - Se não houver infrações associadas à CNH ou ao veículo, o aplicativo deve informar o usuário de que não foram encontradas infrações.<br/> - O usuário pode optar por visualizar mais detalhes de cada infração listada. |
| Fluxo de exceção      | - Se ocorrer algum erro durante a busca ou exibição das infrações, o aplicativo deve lidar com a exceção adequadamente, exibindo uma mensagem de erro e oferecendo opções para tentar novamente ou sair do aplicativo. |
| Pós-condições         | - O usuário pode visualizar as informações detalhadas das infrações associadas à CNH ou ao veículo escolhido. <br/> - O usuário pode optar por visualizar mais detalhes de cada infração. <br/>|
| Data de criação       | 21/10/2023                   |
| Rastreabilidade       | xxxxx |

<font size="3"><p style="text-align: center">Fonte: [Limirio Guimarães](https://github.com/LimirioGuimaraes).</p></font>

<p style="text-align: center">Tabela 5: Reivindicar Infrações</p>

| **UC 4**              | **Reivindicar Infrações**  |
|-----------------------|----------------------------|
| Descrição             | Este caso de uso permite ao usuário abrir uma reivindicação em relação a uma multa de trânsito que tenha recebido. O objetivo é contestar ou esclarecer uma infração específica. |
| Ator                  | Usuário                      | 
| Frequência de uso     | Baixa |
| Pré-condições         | - O aplicativo está instalado e em funcionamento no dispositivo do usuário.<br/>- O dispositivo do usuário possui uma conexão ativa com a internet. <br/> - O usuário recebeu uma notificação ou identificou uma infração específica que deseja contestar. |
| Ação                  | - O usuário abre o aplicativo.<br/> - O usuário ecolhe uma infração para visualiza detalhes.<br/> - Ao ver detalhes da infração o usuário clica na aba d reinvindivar infração. - O aplicativo permite ao usuário fornecer detalhes e justificativas para a reivindicação. |
| Fluxo principal       | - O aplicativo exibe os detalhes da infração selecionada. <br/> - O usuário pode fornecer informações de reivindicação, anexar evidências, fornecer justificativas e enviar a reivindicação. <br/> - Após o envio da reivindicação, o aplicativo registra a solicitação. |
| Fluxo alternativo     | - Se não houver infrações a serem reivindicadas, o aplicativo deve informar o usuário de que não foram encontradas infrações para reivindicar. <br/> - O usuário pode optar por visualizar o status de suas reivindicações anteriores. <br/> - O usuário pode anexar evidências, como fotos ou documentos, para apoiar sua reivindicação. |
| Fluxo de exceção      | Se ocorrer algum erro durante o envio da reivindicação, o aplicativo deve lidar com a exceção adequadamente, exibindo uma mensagem de erro e oferecendo opções para tentar novamente ou sair do aplicativo. |
| Pós-condições         | - O usuário registra uma reivindicação relacionada a uma infração de trânsito específica. <br/> - O aplicativo armazena a reivindicação e envia para revisão e processamento pelas autoridades de trânsito. |
| Data de criação       | 21/10/2023                   |
| Rastreabilidade       | xxxxx |


<font size="3"><p style="text-align: center">Fonte: [Limirio Guimarães](https://github.com/LimirioGuimaraes).</p></font>

<p style="text-align: center">Tabela 6: Pagar multas</p>

| **UC 5**              | **Pagar Multas**         |
|-----------------------|--------------------------|
| Descrição             | Este caso de uso permite ao usuário pagar multas de trânsito. O usuário tem a opção de aderir a iniciativas do governo para ganhar descontos nas multas ou escolher um método de pagamento padrão. |
| Ator                  | Usuário                  | 
| Frequência de uso     | Baixa|
| Pré-condições         | - O aplicativo está instalado e em funcionamento no dispositivo do usuário.<br/>- O dispositivo do usuário possui uma conexão ativa com a internet. <br/> - O usuário possui multas registradas no sistema. |
| Ação                  | - O usuário abre o aplicativo. <br/> - o usuario seleciona a opção de visualizar infrações.<br/> - O usuário escolhe uma infração para pagar a multa referente a ela. <br/> - O aplicativo apresenta ao usuário as seguintes opções:<br/>1. Aderir a iniciativas do governo para ganhar descontos nas multas.<br/> 2. Escolher um método de pagamento padrão. <br/> - O usuário escolhe uma das opções.<br/> - Dependendo da opção escolhida, o aplicativo guia o usuário pelo processo de pagamento. |
| Fluxo principal       | - Se o usuário escolhe aderir a iniciativas do governo:<br/> 1. O aplicativo lista as iniciativas disponíveis com detalhes sobre descontos e requisitos. <br/> 2. O usuário escolhe uma iniciativa e segue as instruções para aderir.<br/> - Se o usuário escolhe um método de pagamento padrão:<br/> 1. O aplicativo permite ao usuário selecionar um método de pagamento.<br/> 2. O aplicativo fornece as informações necessárias para efetuar o pagamento de acordo com a opção selecionada. |
| Fluxo alternativo     | - O usuário pode optar por revisar um resumo de suas multas pendentes antes de prosseguir com o pagamento. <br/> - O aplicativo pode oferecer opções de parcelamento para multas em casos específicos.|
| Fluxo de exceção      | Se ocorrer algum erro durante o processo de pagamento, o aplicativo deve lidar com a exceção adequadamente, exibindo uma mensagem de erro e oferecendo opções para tentar novamente ou sair do aplicativo. |
| Pós-condições         | - O usuário efetua o pagamento das multas de trânsito, sejam elas com descontos de iniciativas do governo ou através de um método de pagamento padrão. <br/> - O usuário pode visualizar seu histórico de pagamentos e multas pagas. |
| Data de criação       | 21/10/2023               |
| Rastreabilidade       | xxxxx|

<font size="3"><p style="text-align: center">Fonte: [Limirio Guimarães](https://github.com/LimirioGuimaraes).</p></font>

<p style="text-align: center">Tabela 7: Contato com o Suporte</p>

| **UC 6**              | **Contato com o Suporte**  |
|-----------------------|---------------------------|
| Descrição             | Este caso de uso permite ao usuário entrar em contato com o suporte do aplicativo para tirar dúvidas, obter assistência ou resolver problemas por meio de um assistente virtual. |
| Ator                  | Usuário                   | 
| Frequência de uso     | Baixa |
| Pré-condições         | - O aplicativo está instalado e em funcionamento no dispositivo do usuário.<br/> - O dispositivo do usuário possui uma conexão ativa com a internet. |
| Ação                  | - O usuário abre o aplicativo.<br/> - O usuário acessa a seção de "Suporte" ou "Ajuda".<br/> - O aplicativo disponibiliza uma opção para iniciar uma conversa com o assistente virtual de suporte.<br/> - O usuário inicia a conversa com o assistente virtual.<br/> - O usuário pode fazer perguntas, obter informações, relatar problemas e receber assistência do assistente virtual. |
| Fluxo principal       | - O assistente virtual interage com o usuário para resolver suas dúvidas ou problemas por meio de mensagens de texto ou chatbot.<br/> - O assistente virtual pode fornecer informações, direcionar o usuário para recursos relevantes ou encaminhá-lo para suporte humano, se necessário.<br/> - O usuário conclui a interação com o assistente virtual quando suas dúvidas são resolvidas ou seu problema é encaminhado para o suporte humano. |
| Fluxo alternativo     | Se a conversa com o assistente virtual não resolver o problema do usuário, ele pode optar por ser direcionado para suporte humano ou fornecer informações de contato para que o suporte entre em contato posteriormente. |
| Fluxo de exceção      | Se ocorrer algum erro durante a interação com o assistente virtual, o aplicativo deve lidar com a exceção adequadamente, exibindo uma mensagem de erro e oferecendo opções para tentar novamente ou relatar o problema de outra forma. |
| Pós-condições         | - O usuário obteve assistência, informações ou resolução para suas dúvidas ou problemas por meio do assistente virtual. <br/> - O aplicativo pode registrar a interação com o assistente virtual para fins de acompanhamento e melhoria.<br/> - O usuário pode encerrar a conversa a qualquer momento. |
| Data de criação       | 21/10/2023                |
| Rastreabilidade       | xxxxxxx |

<font size="3"><p style="text-align: center">Fonte: [Limirio Guimarães](https://github.com/LimirioGuimaraes).</p></font>

<p style="text-align: center">Tabela 8: Atualizar Informações Salvas</p>

| **UC 7**              | **Atualizar Informações Salvas**   |
|-----------------------|------------------------------------|
| Descrição             | Este caso de uso descreve o processo em que o sistema do Departamento de Trânsito (Detran) atualiza as informações salvas no aplicativo do usuário sempre que o aplicativo é utilizado com acesso à internet. |
| Ator                  | Sistema do Detran                    | 
| Frequência de uso     | Alta |
| Pré-condições         | - O aplicativo está instalado e em funcionamento no dispositivo do usuário.<br/> - O dispositivo do usuário possui uma conexão ativa com a internet.|
| Ação                  | - O sistema do Detran detecta que o aplicativo do usuário está ativo e conectado à internet. <br/> - O sistema do Detran verifica se há informações a serem atualizadas no aplicativo do usuário.<br/> - Se houver informações a serem atualizadas, o sistema do Detran envia as atualizações para o aplicativo do usuário. |
| Fluxo principal       | - O sistema do Detran sincroniza automaticamente as informações no aplicativo do usuário com as informações mais recentes disponíveis. <br/> - As informações podem incluir atualizações sobre a CNH, CRLV, multas, infrações, licenciamento, entre outras. <br/> - O sistema do Detran registra a data da última sincronização. |
| Fluxo alternativo     | Se o sistema do Detran não detectar nenhuma informação a ser atualizada, a data de última sincronização é atualizada, mas o aplicativo do usuário permanece com as informações existentes previamente.|
| Fluxo de exceção      | Em caso de erro durante o processo de atualização, o sistema do Detran deve lidar com a exceção adequadamente e pode tentar a sincronização novamente posteriormente. |
| Pós-condições         | - As informações no aplicativo do usuário estão atualizadas com as informações mais recentes do sistema do Detran. <br/> - O sistema do Detran registra a data da última sincronização bem-sucedida. <br/> - O usuário tem acesso às informações atualizadas em seu aplicativo. |
| Data de criação       | 21/10/2023                           |
| Rastreabilidade       | xxxxxx |

<font size="3"><p style="text-align: center">Fonte: [Limirio Guimarães](https://github.com/LimirioGuimaraes).</p></font>

## Bibliografia

> BARBOSA, S. D. J.; SILVA, B. S. Interação Humano-Computador. Rio de Janeiro: Elsevier, 2011.

> LUCIDCHART. Diagrama de caso de uso, 2021. Disponível em: <https://www.lucidchart.com/pages/pt/diagrama-de-caso-de-uso-uml>. Acesso em: 21/10/2023.

## Histórico de Versões

| Versão |    Data    |      Descrição      |       Autor     | Revisor(es)  |
| ------ | ---------- | ------------------- | --------------- | ------------ |
| 1.0    | 19/10/2023 | Criação do template | [Limirio Guimarães](https://github.com/LimirioGuimaraes) |  |
| 1.1    | 21/10/2023 | Adicionado introdução, metodologia e glossário | [Limirio Guimarães](https://github.com/LimirioGuimaraes) |  |
| 1.2    | 21/10/2023 | Adicionado diagrama de casos de uso | [Limirio Guimarães](https://github.com/LimirioGuimaraes) |  |
| 1.3    | 21/10/2023 | Adicionada as tabelas de especialização dos casos de uso| [Limirio Guimarães](https://github.com/LimirioGuimaraes) |  |