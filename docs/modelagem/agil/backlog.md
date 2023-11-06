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

 

### 3.1. Funcionalidades

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

### 3.2. Interface de Usuário

| ID    | Requisito                                                    | Rastreabilidade |
| ---   | ----------------------------------------------------------- | --------------- |
| UI01  | Interface de usuário intuitiva e fácil de usar              |                 |
| UI02  | Interface de usuário personalizável                         |                 |
| UI03  | Responsividade da interface de usuário em diferentes tamanhos de tela |       |

### 3.3. Requisitos de Armazenamento

| ID  | Requisito                                                               | Rastreabilidade                           |
| --- | ----------------------------------------------------------------------- | ----------------------------------------- |
| RNF | O aplicativo deve ocupar um espaço de armazenamento razoável.           |                                           |

### 3.4. Desempenho

| ID  | Requisito                                                               | Rastreabilidade                           |
| --- | ----------------------------------------------------------------------- | ----------------------------------------- |
| RE10 | O Aplicativo deve ser rápido ao carregar                               |                                           |

### 3.5. Segurança e Privacidade

| ID  | Requisito                                                               | Rastreabilidade                           |
| --- | ----------------------------------------------------------------------- | ----------------------------------------- |
| RE30 | O aplicativo deve garantir a segurança dos dados do usuário.           |                                           |

### Épicos e User Stories

#### Épico: Gerenciamento de Conta do Usuário

| ID   | Requisito                        | User Story                                                                                                            | Prioridade |
| ---  | ------------------------------- | --------------------------------------------------------------------------------------------------------------------- | ---------- |
| US01 | Fazer Login com GOV             | Como um usuário, desejo poder fazer login na aplicação usando o GOV para acessar meus recursos.                     | Alta       |
| US02 | Fazer Logoff com GOV            | Como um usuário, desejo poder fazer logoff da aplicação usando o GOV para garantir minha segurança.                  | Alta       |
| US03 | Acessar Carteira de Habilitação  | Como um usuário, desejo poder acessar minha carteira de habilitação eletrônica para visualizar suas informações.    | Alta       |
| US12 | Central de Mensagens            | Como um usuário, desejo ter acesso a uma central de mensagens onde posso receber comunicações e notificações importantes. | Média    |
| US13 | Tirar Foto para o Perfil        | Como um usuário, desejo poder tirar uma foto para usar como minha imagem de perfil na aplicação.                  | Média    |
| US14 | Remover Foto de Perfil          | Como um usuário, desejo poder remover minha foto de perfil, se desejar.                                              | Média    |
| US15 | Escolher Foto da Galeria        | Como um usuário, desejo poder escolher uma foto da minha galeria de imagens para usar como minha foto de perfil.    | Média    |

#### Épico: Documentos e Certificados

| ID   | Requisito                   | User Story                                                                                                            | Prioridade |
| ---  | --------------------------  | --------------------------------------------------------------------------------------------------------------------- | ---------- |
| US04 | Adicionar Documento CLRV-e   | Como um usuário, desejo poder adicionar o documento CLRV-e (Certificado de Registro e Licenciamento de Veículo eletrônico) à minha conta. | Média    |
| US05 | Acessar Documento CLRV-e     | Como um usuário, desejo poder acessar o documento CLRV-e associado à minha conta.                                 | Média    |

#### Épico: Exames e Infrações

| ID   | Requisito                      | User Story                                                                                                            | Prioridade |
| ---  | -----------------------------  | --------------------------------------------------------------------------------------------------------------------- | ---------- |
| US06 | Visualizar Exames Toxicológicos | Como um usuário, desejo poder visualizar os resultados dos meus exames toxicológicos.                                | Média    |
| US07 | Acessar Infração                | Como um usuário, desejo poder acessar informações sobre infrações relacionadas à minha carteira de motorista.     | Média    |
| US08 | Pagar Infração                  | Como um usuário, desejo poder pagar infrações diretamente através da aplicação.                                    | Média    |

#### Épico: Campanhas e Projetos

| ID   | Requisito                      | User Story                                                                                                            | Prioridade |
| ---  | -----------------------------  | --------------------------------------------------------------------------------------------------------------------- | ---------- |
| US09 | Consultar Campanhas e Projetos  | Como um usuário, desejo poder consultar informações sobre campanhas e projetos relacionados à segurança no trânsito. | Baixa    |

#### Épico: Cadastro Positivo e Notificações

| ID   | Requisito                        | User Story                                                                                                            | Prioridade |
| ---  | -------------------------------   | --------------------------------------------------------------------------------------------------------------------- | ---------- |
| US10 | Visualizar Cadastro Positivo     | Como um usuário, desejo poder visualizar meu cadastro positivo de trânsito para entender meu histórico.             | Média    |
| US11 | Aderir ao Sistema de Notificação Eletrônica | Como um usuário, desejo poder aderir ao sistema de notificação eletrônica para receber atualizações e alertas importantes. | Média    |

#### Épico: Cursos Especializados

| ID   | Requisito                              | User Story                                                                                                            | Prioridade |
| ---  | -------------------------------------  | --------------------------------------------------------------------------------------------------------------------- | ---------- |
| US16 | Visualizar Cursos Especializados        | Como um usuário, desejo poder visualizar informações sobre cursos especializados relacionados à segurança no trânsito. | Baixa    |

#### Épico: Segurança e Autenticação

| ID   | Requisito                                        | User Story                                                                                                            | Prioridade |
| ---  | -----------------------------------------------   | --------------------------------------------------------------------------------------------------------------------- | ---------- |
| US17 | Permitir Biometria Para Desbloquear a Carteira  | Como um usuário, desejo poder usar minha biometria para desbloquear minha carteira de habilitação eletrônica para maior segurança. | Alta    |








## Histórico de Versões

| Versão | Data       | Descrição                              | Autor(es)                        | Revisor(es)                       |
| ------ | ---------- | -------------------------------------- | -------------------------------- | --------------------------------- |
| 1.0    | 05/11/2023 | Criação da página inicial.             | [Altino Arthur](https://github.com/arthurrochamoreira) | [Nome do Revisor](https://github.com/) |
