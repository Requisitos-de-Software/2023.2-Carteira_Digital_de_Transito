# Backlog do Produto

## Introdução

O Backlog do Produto desempenha um papel fundamental na gestão de projetos ágeis, funcionando como um repositório dinâmico que armazena todas as tarefas pendentes relacionadas ao projeto. O Product Owner (PO) é o responsável por sugerir, priorizar e gerenciar os itens contidos no backlog. Esse documento é o resultado de uma estreita colaboração com o Product Owner do projeto. Através dessa interação, o PO e a equipe de desenvolvimento podem manter uma visão clara e atualizada das demandas do projeto, facilitando a tomada de decisões e a adaptação às mudanças à medida que o projeto avança. Essa abordagem ágil proporciona flexibilidade e agilidade, permitindo que o projeto evolua de acordo com as necessidades e prioridades em constante evolução.

## Metodologia

A entrevista com o Product Owner (PO), que aconteceu via Microsoft Teams em 05 de novembro de 2023, teve como objetivo central a identificação das funcionalidades desejadas para o produto. Durante esse processo, os desenvolvedores e entrevistadores trabalharam em conjunto para documentar histórias de usuários que descrevem as necessidades e os cenários de uso do sistema. Além disso, foram estabelecidos critérios de aceitação para cada história de usuário, detalhando as condições que precisam ser atendidas para considerar uma funcionalidade como concluída com sucesso.

Para priorizar as histórias de usuário, a equipe utilizou o método Three Level Scale, que é uma abordagem eficaz para classificar as funcionalidades com base em sua importância e complexidade. Isso permitiu definir uma ordem de prioridade clara, garantindo que as funcionalidades mais críticas ou valiosas para o cliente fossem desenvolvidas primeiro.

Após a priorização das histórias de usuário, a equipe avançou para a organização do Backlog do Produto. Nesse estágio, as histórias de usuário foram agrupadas em épicos, proporcionando uma visão hierárquica e organizada das funcionalidades a serem desenvolvidas. Essa estrutura facilita a gestão e o planejamento do projeto, além de permitir uma visão mais ampla das metas e entregas ao longo do tempo.

Essa abordagem metódica e colaborativa na construção e organização do Backlog do Produto é fundamental para o sucesso de um projeto ágil, garantindo que as necessidades do cliente sejam atendidas de maneira eficiente e priorizada de acordo com seu valor.

<br>

<center>
  
### Participantes da Entrevista

| Participante     | Função        |
| ---------------- | ------------- |
| Rômulo           | Product Owner |
| Altino Arthur    | Entrevistador |

### Registro da Entrevista

**Vídeo da Entrevista**: [Assista aqui](https://www.youtube.com/embed/)

<center>

<br>

### Product Backlog

A seguir, apresentamos tabelas de 1 a 3 do o backlog do produto elaborado em colaboração com o PO, detalhando cada história de usuário e sua priorização.

<center>
 
Tabela 1: Funcionalidades

| Identificador | Requisitos                                                       | Rastreabilidade                         |
| ------------- | -------------------------------------------------------------    | ----------------------------------------|
| ITP01         | Fazer Login pelo GOV                                             | [ITP](../../elicitação/Introspeccao.md) |
| ITP02         | Obter versão digital da habilitação                              | [ITP](../../elicitação/Introspeccao.md) |
| ITP03         | Obter versão digital dos veículos que você é principal condutor  | [ITP](../../elicitação/Introspeccao.md) |
| ITP04         | Obter versão digital do CRLV-e                                   | [ITP](../../elicitação/Introspeccao.md) |
| ITP05         | Consultar multas associadas à sua habilitação                    | [ITP](../../elicitação/Introspeccao.md) |
| ITP06         | Consultar multas do seu veículo                                  | [ITP](../../elicitação/Introspeccao.md) |
| ITP07         | Consultar multas dos veículos que você é principal condutor      | [ITP](../../elicitação/Introspeccao.md) |
| ITP09         | Renvidicar a multa                                               | [ITP](../../elicitação/Introspeccao.md) |
| ITP11         | Indicar principal condutor do veículo                            | [ITP](../../elicitação/Introspeccao.md) |
| ITP12         | Acompanhar status da multa (a cobrar e pago)                     | [ITP](../../elicitação/Introspeccao.md) |
| ITP13         | Realizar transferência de veículo                                | [ITP](../../elicitação/Introspeccao.md) |
| ITP14         | Consultar restrições e indicadores (restrição no veículo, multa, judicial) | [ITP](../../elicitação/Introspeccao.md) |
| ITP16         | Consultar campanhas e projetos do DETRAN                         | [ITP](../../elicitação/Introspeccao.md) |
| ITP17         | Validar cadastro de CNH                                          | [ITP](../../elicitação/Introspeccao.md) |
| ITP20         | Aplicativo deve evitar erros e telas brancas durante o uso       | [ITP](../../elicitação/Introspeccao.md) |
| ITP21         | Transferir veículo                                               | [ITP](../../elicitação/Introspeccao.md) |
| ITP22         | Compartilhar documentos do veículo                               | [ITP](../../elicitação/Introspeccao.md) |
| ITP23         | Notificação de multas e informações importantes do fabricante do veículo | [ENT](../../elicitação/entrevista.md) |
| ENT01         | Pesquisa de informações sobre veículos por meio do número da placa | [ENT](../../elicitação/entrevista.md) |
| ENT02         | Configuração de alertas de vencimento da CNH e do licenciamento do veículo | [ENT](../../elicitação/entrevista.md) |
| ENT03         | Notificação ao usuário sobre recalls e informações importantes do fabricante do veículo | [ENT](../../elicitação/entrevista.md) |

Fonte: [Altino Arthur](https://github.com/arthurrochamoreira)

</center>

<br>

<center>

Tabela 2: Interface de Usuário

| Identificador | Requisitos                                                                                       | Rastreabilidade |
| ---           | -------------------------------------------------------------------------------------------------| --------------- |
| ITP19         | Aplicativo deve possuir interface simples                                                        | [ITP](../../elicitação/Introspeccao.md) |
| ITP21         | Modo escuro/claro                                                                                | [ITP](../../elicitação/Introspeccao.md) |
| UI03          | Responsividade da interface de usuário em diferentes tamanhos de tela                            | [ITP](../../elicitação/Introspeccao.md) | 
| RNF           | Evitar erros e telas brancas durante o uso                                                       | [ITP](../../elicitação/Introspeccao.md) | 

Fonte: [Altino Arthur](https://github.com/arthurrochamoreira)

</center>

<br>

<center>

Tabela 3: Não Funcionais

| Identificador | Requisitos                                                             | Rastreabilidade                           |
| ---           | ---------------------------------------------------------------------- | ----------------------------------------- |
| RNF01         | O aplicativo deve ocupar um espaço de armazenamento razoável.          | [ITP](../../elicitação/Introspeccao.md)   |
| ITP           | Backup seguro de documentos e dados do usuário                         | [ITP](../../elicitação/Introspeccao.md)   |
| RNF02         | O Aplicativo deve ser rápido ao carregar                               | [ITP](../../elicitação/Introspeccao.md)   |
| RNF03         | O aplicativo deve garantir a segurança dos dados do usuário.           | [ITP](../../elicitação/Introspeccao.md)   | 

Fonte: [Altino Arthur](https://github.com/arthurrochamoreira)

<br>

</center>

Para diminuir o nível de abstração expresso nos temas, foram registrados os épicos, que são histórias de usuário que ainda podem ser mais especificadas. Para facilitar a leitura do backlog, os épicos estão especificados a seguir.

### Histórias de Usuário

As tabelas de 4 a 10 especificam ainda mais as _features_ e serão detalhadas melhor na seção de [Histórias de Usuário](../agil/historiasUsuario.md). Se apresentam como descrições concisas e de alto nível de uma funcionalidade desejada em termos do cliente. Usualmente seguem a forma "Eu, como \_\_\_, desejo \_\_\_ para ___."

## Épicos e User Stories

### Épico 1: Gerenciamento de Conta do Usuário

<center>

Tabela 4: Gerenciamento de Conta do Usuário

| Identificador  | Requisitos                        | User Story                                                                                                            | Prioridade |
| ---            | ------------------------------- | ---------------------------------------------------------------------------------------------------------------------   | ---------- |
| US01           | Fazer Login com GOV             | Como um usuário, desejo poder fazer login na aplicação usando o GOV para acessar meus recursos.                         | Alta       |
| US02           | Fazer Logoff com GOV            | Como um usuário, desejo poder fazer logoff da aplicação usando o GOV para garantir minha segurança.                     | Alta       |
| US03           | Acessar Carteira de Habilitação  | Como um usuário, desejo poder acessar minha carteira de habilitação eletrônica para visualizar suas informações.       | Alta       |
| US12           | Central de Mensagens            | Como um usuário, desejo ter acesso a uma central de mensagens onde posso receber comunicações e notificações importantes.  | Média   |
| US13           | Tirar Foto para o Perfil        | Como um usuário, desejo poder tirar uma foto para usar como minha imagem de perfil na aplicação.                          | Média    |
| US14           | Remover Foto de Perfil          | Como um usuário, desejo poder remover minha foto de perfil, se desejar.                                                   | Média    |
| US15           | Escolher Foto da Galeria        | Como um usuário, desejo poder escolher uma foto da minha galeria de imagens para usar como minha foto de perfil.          | Média    |
| US18           | Visualizar Informações da Conta  | Como um usuário, desejo poder visualizar informações sobre a minha conta, como nome, e-mail e informações pessoais.      | Média    |
| US19           | Editar Informações da Conta     | Como um usuário, desejo poder editar as informações da minha conta para mantê-las atualizadas.                            | Média    |

</center>

### Épico 2: Documentos e Certificados

<center>

Tabela 5: Documentos e Certificados

| Identificador | Requisitos                   | User Story                                                                                                            | Prioridade |
| ---           | --------------------------  | ---------------------------------------------------------------------------------------------------------------------  | ---------- |
| US04          | Adicionar Documento CLRV-e   | Como um usuário, desejo poder adicionar o documento CLRV-e (Certificado de Registro e Licenciamento de Veículo eletrônico) à minha conta. | Média|
| US05          | Acessar Documento CLRV-e     | Como um usuário, desejo poder acessar o documento CLRV-e associado à minha conta.                                     | Média       |
| US20          | Visualizar Certificados       | Como um usuário, desejo poder visualizar e gerenciar todos os certificados e documentos associados à minha conta.    | Média       |

</center>

### Épico 3: Exames e Infrações

<center>

Tabela 6: Exames e Infrações

| Identificador | Requisitos                      | User Story                                                                                                            | Prioridade |
| ---           | -----------------------------  | ---------------------------------------------------------------------------------------------------------------------  | ---------- |
| US06          | Visualizar Exames Toxicológicos | Como um usuário, desejo poder visualizar os resultados dos meus exames toxicológicos.                                 | Média      |
| US07          | Acessar Infração                | Como um usuário, desejo poder acessar informações sobre infrações relacionadas à minha carteira de motorista.         | Média      |
| US08          | Pagar Infração                  | Como um usuário, desejo poder pagar infrações diretamente através da aplicação.                                       | Média      |
| US21          | Receber Notificações de Infrações | Como um usuário, desejo receber notificações sobre infrações relacionadas à minha carteira de motorista.            | Média      |

</center>

### Épico 4: Campanhas e Projetos

<center>

Tabela 7: Campanhas e Projetos
 
| Identificador  | Requisitos                         | User Story                                                                                                        | Prioridade |
| ---            | -----------------------------      | ------------------------------------------------------------------------------------------------------------------ | ---------- |
| US09           | Consultar Campanhas e Projetos     | Como um usuário, desejo poder consultar informações sobre campanhas e projetos relacionados à segurança no trânsito. | Baixa      |
| US22           | Participar de Campanhas e Projetos | Como um usuário, desejo poder participar ativamente de campanhas e projetos relacionados à segurança no trânsito. | Média      |

</center>

### Épico 5: Cadastro Positivo e Notificações

<center>

Tabela 8: Cadastro Positivo e Notificações

| Identificador  | Requisitos                       | User Story                                                                                                            | Prioridade |
| ---            | -------------------------------   | ---------------------------------------------------------------------------------------------------------------------| ---------- |
| US10           | Visualizar Cadastro Positivo     | Como um usuário, desejo poder visualizar meu cadastro positivo de trânsito para entender meu histórico.                 | Média    |
| US11 | Aderir ao Sistema de Notificação Eletrônica | Como um usuário, desejo poder aderir ao sistema de notificação eletrônica para receber atualizações e alertas importantes. | Média    |
| US23 | Gerenciar Preferências de Notificação | Como um usuário, desejo poder gerenciar minhas preferências de notificação, escolhendo quais tipos de alertas desejo receber. | Média    |

</center>

### Épico 6: Cursos Especializados

<center>

Tabela 9: Cursos Especializados

| Identificador   | Requisitos                              | User Story                                                                                                            | Prioridade |
| ---  | -------------------------------------  | --------------------------------------------------------------------------------------------------------------------- | ---------- |
| US16 | Visualizar Cursos Especializados        | Como um usuário, desejo poder visualizar informações sobre cursos especializados relacionados à segurança no trânsito. | Baixa    |
| US24 | Inscrever-se em Cursos Especializados  | Como um usuário, desejo poder inscrever-me em cursos especializados relacionados à segurança no trânsito.               | Média    |

</center>

### Épico 7: Segurança e Autenticação

<center>

Tabela 10: Segurança e Autenticação

| Identificador   | Requisitos                            | User Story                                                                                                      |Prioridade |
| ---  | -----------------------------------------------   | ---------------------------------------------------------------------------------------------------------------------  | ---------- |
| US17 | Permitir Biometria Para Desbloquear a Carteira  | Como um usuário, desejo poder usar minha biometria para desbloquear minha carteira de habilitação eletrônica para maior segurança. | Alta    |
| US25 | Recuperar Senha Perdida                         | Como um usuário, desejo poder recuperar minha senha perdida por meio de um processo seguro de redefinição de senha. | Média    |

</center>

<br>

## Bibliografia

> SOUZA, Nicolas; MACEDO, Lucas. Backlog do Produto. Repositório do Grupo Lichess da disciplina de Requisitos de Software da Universidade de Brasília, 2022. Disponível em: <<https://requisitos-de-software.github.io/2022.2-Lichess/modelagem/agil/backlog/>>. Acesso em: 18 maio 2023.

> POPOV, Arthur Taylor de Jesus; SANTOS, Eduardo Schuindt. Backlog do Produto. Repositório do Grupo MEI da disciplina de Requisitos de Software da Universidade de Brasília, 2022. Disponível em: <<https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Agil/BacklogDoProduto/>>. Acesso em: 18 maio 2023.

> PRESSMAN, Roger S.; MAXIM, Bruce R.. Engenharia de software: uma abordagem profissional. 8 Porto Alegre: AMGH, 2016, 940 p.

> Bourque, P., Fairley, R. E. Guide to the Software Engineering Body of Knowledge, Version 3.0. SWEBOK. IEEE Computer Society, 2014. Disponível em: http://www.computer.org/web/swebok/v3. p. 38.

<br>

## Histórico de Versões

| Versão | Data       | Descrição                              | Autor(es)                        | Revisor(es)                       |
| ------ | ---------- | -------------------------------------- | -------------------------------- | --------------------------------- |
| 1.0    | 05/11/2023 | Criação da página inicial.             | [Altino Arthur](https://github.com/arthurrochamoreira) | [Milena Baruc](https://github.com/MilenaBaruc) |
