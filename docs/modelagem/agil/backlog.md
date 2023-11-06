# Backlog do Produto

## Introdução

O Backlog do Produto desempenha um papel fundamental na gestão de projetos ágeis, funcionando como um repositório dinâmico que armazena todas as tarefas pendentes relacionadas ao projeto. O Product Owner (PO) é o responsável por sugerir, priorizar e gerenciar os itens contidos no backlog. Esse documento é o resultado de uma estreita colaboração com o Product Owner do projeto, que foi entrevistado via Discord em 06 de novembro de 2023. Através dessa interação, o PO e a equipe de desenvolvimento podem manter uma visão clara e atualizada das demandas do projeto, facilitando a tomada de decisões e a adaptação às mudanças à medida que o projeto avança. Essa abordagem ágil proporciona flexibilidade e agilidade, permitindo que o projeto evolua de acordo com as necessidades e prioridades em constante evolução.

### Participantes da Entrevista

| Participante     | Função        |
| ---------------- | ------------- |
| Rômulo           | Product Owner |
| Altino Arthur    | Entrevistador |

### Registro da Entrevista

- **Vídeo da Entrevista**: [Assista aqui](https://www.youtube.com/embed/)

## Metodologia

A entrevista com o Product Owner (PO) teve como objetivo central a identificação das funcionalidades desejadas para o produto. Durante esse processo, os desenvolvedores e entrevistadores trabalharam em conjunto para documentar histórias de usuários que descrevem as necessidades e os cenários de uso do sistema. Além disso, foram estabelecidos critérios de aceitação para cada história de usuário, detalhando as condições que precisam ser atendidas para considerar uma funcionalidade como concluída com sucesso.

Para priorizar as histórias de usuário, a equipe utilizou o método Three Level Scale, que é uma abordagem eficaz para classificar as funcionalidades com base em sua importância e complexidade. Isso permitiu definir uma ordem de prioridade clara, garantindo que as funcionalidades mais críticas ou valiosas para o cliente fossem desenvolvidas primeiro.

Após a priorização das histórias de usuário, a equipe avançou para a organização do Backlog do Produto. Nesse estágio, as histórias de usuário foram agrupadas em temas, épicos e features, proporcionando uma visão hierárquica e organizada das funcionalidades a serem desenvolvidas. Essa estrutura facilita a gestão e o planejamento do projeto, além de permitir uma visão mais ampla das metas e entregas ao longo do tempo.

Essa abordagem metódica e colaborativa na construção e organização do Backlog do Produto é fundamental para o sucesso de um projeto ágil, garantindo que as necessidades do cliente sejam atendidas de maneira eficiente e priorizada de acordo com seu valor.

### Product Backlog

A seguir, apresentamos o backlog do produto elaborado em colaboração com o PO, detalhando cada história de usuário e sua priorização.

<center>
<p align="center"> Tabela 1: Funcionalidades</p>

| ID    | Requisito                                                   | Rastreabilidade |
| ----- | ----------------------------------------------------------- | --------------- |
| RF01  | Fazer Login com GOV                                         |                 |
| RF02  | FAzer Logoff com GOV                                        |                 |
| RF03  | Acessar Carteira de Habilitação                             |                 |
| RF04  | Adicionar Documento CLRV-e                                  |                 |
| RF05  | Acessar Documento CLRV-e                                    |                 |
| RF06  | Visualizar Exames Toxicológicos                             |                 |
| RF07  | Acessar Infração                                            |                 |
| RF08  | Pagar Infração                                              |                 |
| RF09  | Consultar Campanhas e Projetos                              |                 |
| RF10  | Visualizar Cadastro Positivo                                |                 |
| RF11  | Aderir ao Sistema de Notificação Eletrônica                 |                 |
| RF12  | Central de Mensagens                                        |                 |
| RF13  | Tirar Foto para o Perfil                                    |                 |
| RF14  | Remover Foto de Perfil                                      |                 |
| RF15  | Escolher Foto da Galeria                                    |                 |
| RF16  | Visualizar Cursos Especializados                            |                 |
| RF17  | Permitir Biometria Para Desbloquear a Carteira              |                 |


<p align="center"> Fonte: Altino Arthur</p>
</center>

<center>
<p align="center"> Tabela 2: Interface de Usuário</p>

| ID    | Requisito                                                   | Rastreabilidade |
| ---   | ----------------------------------------------------------- | --------------- |
| UI01  | Interface de usuário intuitiva e fácil de usar              |                 |
| UI02  | Interface de usuário personalizável                         |                 |
| UI03  | Responsividade da interface de usuário em diferentes tamanhos de tela |       |


<p align="center"> Fonte: Altino Arthur</p>
</center>

<center>
<p align="center"> Tabela 3: Armazenamento</p>

| ID  | Requisito                                                               | Rastreabilidade                           |
| --- | ----------------------------------------------------------------------- | ----------------------------------------- |
| RNF01 | O aplicativo deve ocupar um espaço de armazenamento razoável.         |                                           |


<p align="center"> Fonte: Altino Arthur</p>
</center>

<center>
<p align="center"> Tabela 4: Desempenho</p>

| ID  | Requisito                                                               | Rastreabilidade                           |
| --- | ----------------------------------------------------------------------- | ----------------------------------------- |
| RNF02 | O Aplicativo deve ser rápido ao carregar                              |                                           |


<p align="center"> Fonte: Altino Arthur</p>
</center>

<center>
<p align="center"> Tabela 5: Segurança</p>

| ID  | Requisito                                                               | Rastreabilidade                           |
| --- | ----------------------------------------------------------------------- | ----------------------------------------- |
| RNF03 | O aplicativo deve garantir a segurança dos dados do usuário.          |                                           |


<p align="center"> Fonte: Altino Arthur</p>
</center>

Para diminuir o nível de abstração expresso nos temas, foram registrados os épicos, que são histórias de usuário que ainda podem ser mais especificadas. Para facilitar a leitura do backlog, os épicos estão especificados a seguir.

### Histórias de Usuário

Elas especificam ainda mais as _features_ e serão detalhadas melhor na seção de [Histórias de Usuário](../historia-de-usuario). Se apresentam como descrições concisas e de alto nível de uma funcionalidade desejada em termos do cliente. Usualmente seguem a forma "Eu, como \_\_\_, desejo \_\_\_ para ___."


### Épicos e User Stories

#### Épico 1: Gerenciamento de Conta do Usuário

<center>
<p align="center"> Tabela 6: Gerenciamento de Conta do Usuário</p>

| ID   | Requisito                        | User Story                                                                                                            | Prioridade |
| ---  | ------------------------------- | ---------------------------------------------------------------------------------------------------------------------  | ---------- |
| US01 | Fazer Login com GOV             | Como um usuário, desejo poder fazer login na aplicação usando o GOV para acessar meus recursos.                        | Alta       |
| US02 | Fazer Logoff com GOV            | Como um usuário, desejo poder fazer logoff da aplicação usando o GOV para garantir minha segurança.                    | Alta       |
| US03 | Acessar Carteira de Habilitação | Como um usuário, desejo poder acessar minha carteira de habilitação eletrônica para visualizar suas informações.       | Alta       |
| US12 | Central de Mensagens            | Como um usuário, desejo ter acesso a uma central de mensagens onde posso receber comunicações e notificações importantes. | Média   |
| US13 | Tirar Foto para o Perfil        | Como um usuário, desejo poder tirar uma foto para usar como minha imagem de perfil na aplicação.                         | Média    |
| US14 | Remover Foto de Perfil          | Como um usuário, desejo poder remover minha foto de perfil, se desejar.                                                  | Média    |
| US15 | Escolher Foto da Galeria        | Como um usuário, desejo poder escolher uma foto da minha galeria de imagens para usar como minha foto de perfil.         | Média    |


<p align="center"> Fonte: Altino Arthur</p>
</center>

#### Épico 2: Documentos e Certificados

| ID   | Requisito                   | User Story                                                                                                            | Prioridade |
| ---  | --------------------------  | --------------------------------------------------------------------------------------------------------------------- | ---------- |
| US04 | Adicionar Documento CLRV-e  | Como um usuário, desejo poder adicionar o documento CLRV-e (Certificado de Registro e Licenciamento de Veículo eletrônico) à minha conta. | Média    |
| US05 | Acessar Documento CLRV-e    | Como um usuário, desejo poder acessar o documento CLRV-e associado à minha conta.                                     |Média       |


<p align="center"> Fonte: Altino Arthur</p>
</center>

#### Épico 3: Exames e Infrações

| ID   | Requisito                      | User Story                                                                                                            | Prioridade |
| ---  | -----------------------------  | --------------------------------------------------------------------------------------------------------------------- | ---------- |
| US06 | Visualizar Exames Toxicológicos | Como um usuário, desejo poder visualizar os resultados dos meus exames toxicológicos.                                | Média      |
| US07 | Acessar Infração                | Como um usuário, desejo poder acessar informações sobre infrações relacionadas à minha carteira de motorista.        | Média      |
| US08 | Pagar Infração                  | Como um usuário, desejo poder pagar infrações diretamente através da aplicação.                                      | Média      |


<p align="center"> Fonte: Altino Arthur</p>
</center>


#### Épico 4: Campanhas e Projetos
 
| ID   | Requisito                      | User Story                                                                                                            | Prioridade |
| ---  | -----------------------------  | --------------------------------------------------------------------------------------------------------------------- | ---------- |
| US09 | Consultar Campanhas e Projetos | Como um usuário, desejo poder consultar informações sobre campanhas e projetos relacionados à segurança no trânsito.  | Baixa      |


<p align="center"> Fonte: Altino Arthur</p>
</center>

#### Épico 5: Cadastro Positivo e Notificações

| ID   | Requisito                        | User Story                                                                                                            | Prioridade |
| ---  | -------------------------------  | --------------------------------------------------------------------------------------------------------------------- | ---------- |
| US10 | Visualizar Cadastro Positivo     | Como um usuário, desejo poder visualizar meu cadastro positivo de trânsito para entender meu histórico.               | Média      |
| US11 | Aderir ao Sistema de Notificação Eletrônica | Como um usuário, desejo poder aderir ao sistema de notificação eletrônica para receber atualizações e alertas importantes. | Média    |


<p align="center"> Fonte: Altino Arthur</p>
</center>

#### Épico 6: Cursos Especializados

| ID   | Requisito                              | User Story                                                                                                            | Prioridade |
| ---  | -------------------------------------  | --------------------------------------------------------------------------------------------------------------------- | ---------- |
| US16 | Visualizar Cursos Especializados       | Como um usuário, desejo poder visualizar informações sobre cursos especializados relacionados à segurança no trânsito. | Baixa     |


<p align="center"> Fonte: Altino Arthur</p>
</center>

#### Épico 7: Segurança e Autenticação

| ID   | Requisito                                        | User Story                                                                                                            | Prioridade |
| ---  | -----------------------------------------------  | --------------------------------------------------------------------------------------------------------------------- | ---------- |
| US17 | Permitir Biometria Para Desbloquear a Carteira   | Como um usuário, desejo poder usar minha biometria para desbloquear minha carteira de habilitação eletrônica para maior segurança. | Alta    |


<p align="center"> Fonte: Altino Arthur</p>
</center>


## Bibliografia

> SOUZA, Nicolas; MACEDO, Lucas. Backlog do Produto. Repositório do Grupo Lichess da disciplina de Requisitos de Software da Universidade de Brasília, 2022. Disponível em: <<https://requisitos-de-software.github.io/2022.2-Lichess/modelagem/agil/backlog/>>. Acesso em: 18 maio 2023.

> POPOV, Arthur Taylor de Jesus; SANTOS, Eduardo Schuindt. Backlog do Produto. Repositório do Grupo MEI da disciplina de Requisitos de Software da Universidade de Brasília, 2022. Disponível em: <<https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Agil/BacklogDoProduto/>>. Acesso em: 18 maio 2023.

> PRESSMAN, Roger S.; MAXIM, Bruce R.. Engenharia de software: uma abordagem profissional. 8 Porto Alegre: AMGH, 2016, 940 p.

> Bourque, P., Fairley, R. E. Guide to the Software Engineering Body of Knowledge, Version 3.0. SWEBOK. IEEE Computer Society, 2014. Disponível em: http://www.computer.org/web/swebok/v3. p. 38.




## Histórico de Versões

| Versão | Data       | Descrição                              | Autor(es)                        | Revisor(es)                       |
| ------ | ---------- | -------------------------------------- | -------------------------------- | --------------------------------- |
| 1.0    | 05/11/2023 | Criação da página inicial.             | [Altino Arthur](https://github.com/arthurrochamoreira) | [Nome do Revisor](https://github.com/) |
