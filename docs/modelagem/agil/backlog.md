
# Backlog do Produto
  
## Introdução

A entrevista com o Product Owner conduzida via Microsoft Teams em 05 de novembro de 2023 teve como foco a definição das funcionalidades que o produto deve oferecer. Para isso, foram criadas 'histórias de usuários', um artefato utilizado para capturar e entender as necessidades dos usuários finais, bem como os contextos nos quais a aplicação seria utilizada.
  
Após a entrevista, a equipe procedeu com a priorização das histórias de usuário, adotando o método Three Level Scale para avaliar e ordenar as funcionalidades por sua relevância e complexidade.

Depois de escolher as tarefas mais urgentes, elas foram agrupadas no Backlog do Produto. As tarefas foram separadas em grandes grupos chamados épicos e em menores chamados funcionalidades. Esta estruturação do Backlog do Produto é fundamental. Ela serve para estabelecer claramente quais são as prioridades, o que por sua vez facilita para a equipe de projeto manter a concentração nas atividades essenciais. Seguindo esta abordagem, o projeto pode progredir de forma ordenada, assegurando que cada fase seja concluída de acordo com o planejado, até que o projeto atinja sua finalização.


## Metodologia

<p align="justify">

A metodologia utilizada na entrevista com o Product Owner (PO) para a elicitação de requisitos e priorização das histórias de usuário envolveu os seguintes passos:

</p>

1. **Entrevista com o PO:** Durante a entrevista com o PO, as funcionalidades desejadas foram discutidas e detalhadas. O PO compartilhou suas ideias e visão para o produto.

2. **Anotações e Questionamentos:** Enquanto o PO comentava suas funcionalidades desejadas, os desenvolvedores/entrevistadores realizavam anotações detalhadas e faziam questionamentos para obter uma compreensão completa dos requisitos.

3. **Elicitação de Histórias de Usuário:** Com base nas informações fornecidas pelo PO, as histórias de usuário foram elicitadas. Cada história descrevia uma funcionalidade ou necessidade específica do usuário.

4. **Priorização das Histórias de Usuário:** As histórias de usuário foram priorizadas pelo PO em três níveis de prioridade: Alta, Média ou Baixa. Esse processo utilizou o método "Three Level Scale" de priorização de requisitos.

5. **Categorização em Temas, Épicos e Features:** Para uma melhor organização e categorização das histórias de usuário, temas, épicos e features foram definidos. Isso ajudou a agrupar funcionalidades relacionadas.
   
<p align="justify">
  
Nesse processo, as histórias de usuário foram detalhadas e priorizadas.

</p>

<br>

<center>
  
#### Participantes da Entrevista

| Participante     | Função        |
| ---------------- | ------------- |
| Rômulo Hannig    | Product Owner |
| Altino Arthur    | Entrevistador |

#### Registro da Entrevista

**Vídeo da Entrevista**: [Assista aqui](https://www.youtube.com/embed/)

</center>

<br>

## Product Backlog

A seguir, apresentamos a tabela 1 do backlog do produto elaborado em colaboração com o PO, detalhando cada funcionalidade que ira gerar as histórias de usuário e sua priorização.

<br>

<center>
 
Tabela 1: Funcionalidades

| Identificador | Descrição                                                     | Rastreabilidade                         |
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
| ITP21         | Transferir veículo                                               | [ITP](../../elicitação/Introspeccao.md) |
| ITP22         | Compartilhar documentos do veículo                               | [ITP](../../elicitação/Introspeccao.md) |
| ITP23         | Notificação de multas e informações importantes do fabricante do veículo | [ENT](../../elicitação/entrevista.md) |
| ENT01         | Pesquisa de informações sobre veículos por meio do número da placa | [ENT](../../elicitação/entrevista.md) |
| ENT02         | Configuração de alertas de vencimento da CNH e do licenciamento do veículo | [ENT](../../elicitação/entrevista.md) |
| ENT03         | Notificação ao usuário sobre recalls e informações importantes do fabricante do veículo | [ENT](../../elicitação/entrevista.md) |

Fonte: [Altino Arthur](https://github.com/arthurrochamoreira)

</center>

<br>
  
## Épicos

No desenvolvimento de software, 'épicos' são termos usados para descrever objetivos amplos ou funcionalidades de grande escala que precisam ser alcançados. Estes são compostos por múltiplas histórias de usuário, que são mais detalhadas e específicas, descrevendo as funcionalidades individuais necessárias para atingir a meta maior que o épico representa.

Comparando com a estrutura de um livro, os épicos seriam semelhantes a capítulos, fornecendo um resumo do conteúdo que será abordado, enquanto as histórias de usuário seriam semelhantes às páginas individuais, com detalhes específicos de cada parte do 'capítulo'. Essas histórias são interconectadas e cada uma contribui para a finalização do épico.

Além disso, temos as 'features', que são declarações de alto nível que descrevem uma funcionalidade do ponto de vista do cliente. Elas são formuladas de maneira a capturar o valor que o cliente busca, como por exemplo, a capacidade de acessar relatórios financeiros rapidamente ou a facilidade de integrar a plataforma com outros sistemas. As 'features' orientam a equipe sobre as necessidades do cliente e como elas se alinham com os objetivos maiores delineados pelos épicos.

As tabelas de 2 a 8 apresentam os épicos do projeto, que são grandes objetivos ou iniciativas dentro do desenvolvimento do produto. Cada épico é apresentado de forma a capturar uma necessidade ampla do usuário e pode ser detalhado em funcionalidades específicas que serão detalhadas melhor na seção de [Histórias de Usuário](../agil/historiasUsuario.md). Comumente, um épico é expresso por uma sentença ampla: "Como [perfil do usuário], preciso [de uma grande funcionalidade ou resultado] para [atingir um objetivo de negócio ou solucionar um problema significativo]". Esta abordagem mantém o foco nas metas de alto nível e nos benefícios estratégicos, orientando a priorização e o desenvolvimento de forma que alinhe com os principais objetivos do negócio.

<br>
  
### Épico 1: Gerenciamento de Conta do Usuário

Descrição: Este épico concentra-se no gerenciamento das contas de usuário na aplicação. Ele abrange funcionalidades relacionadas à autenticação, personalização do perfil do usuário e acesso a informações pessoais. Os objetivos incluem permitir que os usuários façam login usando a autenticação do GOV, acessem sua carteira de habilitação eletrônica, gerenciem mensagens, configurem fotos de perfil e visualizem informações da conta.

- Requisitos relacionados: US01, US02, US03, US12, US13, US14, US15, US18, US19.

<center>

<br>

Tabela 2: Gerenciamento de Conta do Usuário

| Identificador  | Requisitos                      | User Story                                                                                                              | Prioridade |
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

Fonte: [Altino Arthur](https://github.com/arthurrochamoreira)

<br>

</center>

<br>

### Épico 2: Documentos e Certificados

Descrição: Este épico trata da gestão de documentos e certificados dos usuários. Inclui a capacidade de adicionar, acessar e gerenciar documentos como o Certificado de Registro e Licenciamento de Veículo eletrônico (CLRV-e).

- Requisitos relacionados: US04, US05, US20

<center>

<br>

Tabela 3: Documentos e Certificados

| Identificador | Requisitos                   | User Story                                                                                                            | Prioridade |
| ---           | --------------------------  | ---------------------------------------------------------------------------------------------------------------------  | ---------- |
| US04          | Adicionar Documento CLRV-e   | Como um usuário, desejo poder adicionar o documento CLRV-e (Certificado de Registro e Licenciamento de Veículo eletrônico) à minha conta. | Média|
| US05          | Acessar Documento CLRV-e     | Como um usuário, desejo poder acessar o documento CLRV-e associado à minha conta.                                     | Média       |
| US20          | Visualizar Certificados       | Como um usuário, desejo poder visualizar e gerenciar todos os certificados e documentos associados à minha conta.    | Média       |

Fonte: [Altino Arthur](https://github.com/arthurrochamoreira)

<br>

</center>

<br>

### Épico 3: Exames e Infrações

Descrição: Este épico envolve a visualização de resultados de exames toxicológicos, acesso a informações sobre infrações de trânsito e pagamento de infrações diretamente pela aplicação, bem como receber notificações sobre infrações relacionadas à carteira de motorista.

- Requisitos relacionados: US06, US07, US08, US21

<center>

<br>

Tabela 4: Exames e Infrações

| Identificador | Requisitos                      | User Story                                                                                                            | Prioridade |
| ---           | -----------------------------  | ---------------------------------------------------------------------------------------------------------------------  | ---------- |
| US06          | Visualizar Exames Toxicológicos | Como um usuário, desejo poder visualizar os resultados dos meus exames toxicológicos.                                 | Média      |
| US07          | Acessar Infração                | Como um usuário, desejo poder acessar informações sobre infrações relacionadas à minha carteira de motorista.         | Média      |
| US08          | Pagar Infração                  | Como um usuário, desejo poder pagar infrações diretamente através da aplicação.                                       | Média      |
| US21          | Receber Notificações de Infrações | Como um usuário, desejo receber notificações sobre infrações relacionadas à minha carteira de motorista.            | Média      |

Fonte: [Altino Arthur](https://github.com/arthurrochamoreira)

<br>

</center>

<br>

### Épico 4: Campanhas e Projetos

Descrição: Neste épico, os usuários podem consultar informações sobre campanhas e projetos relacionados à segurança no trânsito, e têm a capacidade de participar ativamente dessas iniciativas.

- Requisitos relacionados: US09, US22

<center>

<br>

Tabela 5: Campanhas e Projetos
 
| Identificador  | Requisitos                         | User Story                                                                                                        | Prioridade |
| ---            | -----------------------------      | ------------------------------------------------------------------------------------------------------------------ | ---------- |
| US09           | Consultar Campanhas e Projetos     | Como um usuário, desejo poder consultar informações sobre campanhas e projetos relacionados à segurança no trânsito. | Baixa      |
| US22           | Participar de Campanhas e Projetos | Como um usuário, desejo poder participar ativamente de campanhas e projetos relacionados à segurança no trânsito. | Média      |

Fonte: [Altino Arthur](https://github.com/arthurrochamoreira)

<br>

</center>

<br>

### Épico 5: Cadastro Positivo e Notificações

Descrição: Este épico inclui a visualização do cadastro positivo de trânsito, a adesão ao sistema de notificação eletrônica para receber atualizações e alertas importantes, e a possibilidade de gerenciar as preferências de notificação.

- Requisitos relacionados: US10, US11, US23
  
<br>

<center>

Tabela 6: Cadastro Positivo e Notificações

| Identificador  | Requisitos                       | User Story                                                                                                            | Prioridade |
| ---            | -------------------------------   | ---------------------------------------------------------------------------------------------------------------------| ---------- |
| US10           | Visualizar Cadastro Positivo     | Como um usuário, desejo poder visualizar meu cadastro positivo de trânsito para entender meu histórico.                 | Média    |
| US11 | Aderir ao Sistema de Notificação Eletrônica | Como um usuário, desejo poder aderir ao sistema de notificação eletrônica para receber atualizações e alertas importantes. | Média    |
| US23 | Gerenciar Preferências de Notificação | Como um usuário, desejo poder gerenciar minhas preferências de notificação, escolhendo quais tipos de alertas desejo receber. | Média    |

Fonte: [Altino Arthur](https://github.com/arthurrochamoreira)

<br>

</center>

<br>

### Épico 6: Cursos Especializados

Descrição: Neste épico, os usuários podem visualizar informações sobre cursos especializados relacionados à segurança no trânsito e inscrever-se nesses cursos.

- Requisitos relacionados: US16, US24

<center>

<br>

Tabela 7: Cursos Especializados

| Identificador   | Requisitos                              | User Story                                                                                                            | Prioridade |
| ---  | -------------------------------------  | --------------------------------------------------------------------------------------------------------------------- | ---------- |
| US16 | Visualizar Cursos Especializados        | Como um usuário, desejo poder visualizar informações sobre cursos especializados relacionados à segurança no trânsito. | Baixa    |
| US24 | Inscrever-se em Cursos Especializados  | Como um usuário, desejo poder inscrever-me em cursos especializados relacionados à segurança no trânsito.               | Média    |

Fonte: [Altino Arthur](https://github.com/arthurrochamoreira)

<br>

</center>

### Épico 7: Segurança e Autenticação

Descrição: Este épico aborda a segurança e autenticação dos usuários, permitindo o uso de biometria para desbloquear a carteira de habilitação eletrônica e a recuperação segura de senhas perdidas.

- Requisitos relacionados: US17, US25

<center>

<br>

Tabela 8: Segurança e Autenticação

| Identificador   | Requisitos                            | User Story                                                                                                      |Prioridade |
| ---  | -----------------------------------------------   | ---------------------------------------------------------------------------------------------------------------------  | ---------- |
| US17 | Permitir Biometria Para Desbloquear a Carteira  | Como um usuário, desejo poder usar minha biometria para desbloquear minha carteira de habilitação eletrônica para maior segurança. | Alta    |
| US25 | Recuperar Senha Perdida                         | Como um usuário, desejo poder recuperar minha senha perdida por meio de um processo seguro de redefinição de senha. | Média    |

Fonte: [Altino Arthur](https://github.com/arthurrochamoreira)

</center>

<br>
  
## Features

<p align="justify">
Após o estabelecimento dos épicos, que constituem os objetivos gerais e abrangentes do projeto passamos a detalhar as features. Estas são as funcionalidades específicas que compõem o produto. Cada feature é um elemento que, ao ser implementado, atende a uma necessidade particular do usuário final e avança o projeto em direção ao cumprimento dos épicos, elas são elaboradas de modo a serem claras para todos os participantes do projeto, desde os desenvolvedores até os clientes finais. Ao contrário dos épicos, que são amplos e muitas vezes abstratos, as features são tangíveis e mensuráveis, oferecendo uma direção clara para a equipe sobre o que precisa ser construído.
</p>

<p align="justify">
As features, detalhadas nas tabelas de 9 a 15, são aspectos específicos do produto que serão mais profundamente explorados nas [Histórias de Usuário](../agil/historiasUsuario.md). Cada feature é tipicamente expressa por uma sentença padrão que identifica quem é o usuário, o que ele necessita e por que a necessidade existe, seguindo o modelo: "Eu, como [tipo de usuário], desejo [alguma ação ou funcionalidade] para [obter algum benefício ou resultado]". Este formato ajuda a equipe a se concentrar nas necessidades do usuário e no valor que a funcionalidade proporcionará, facilitando assim a priorização das tarefas e um desenvolvimento que esteja alinhado com as expectativas do cliente.
</p>

<br>

#### Feature 1: Autenticação e Conta do Usuário

Tabela 9: Autenticação e Conta do Usuário

| Como um/a...             | Eu quero...                                                 | Para que eu possa...                                             |
| ------------------------ | ----------------------------------------------------------- | --------------------------------------------------------------- |
| usuário                  | autenticar-me usando o sistema de autenticação do GOV       | garantir um acesso seguro e confiável à aplicação               |
| motorista                | acessar a versão digital da minha carteira de habilitação   | facilitar sua utilização no dia a dia                           |
| usuário                  | ter uma central de mensagens                                | receber comunicações e notificações importantes de forma centralizada |
| usuário                  | tirar uma foto para usar como imagem de perfil              | personalizar minha conta para melhor identificação              |
| usuário                  | remover a foto de perfil da minha conta                     | manter minha privacidade se eu assim escolher                   |
| usuário                  | escolher uma foto da galeria para meu perfil                | ter uma imagem de perfil que melhor me represente               |
| usuário                  | visualizar informações da minha conta                       | ter controle e conhecimento sobre os dados associados à minha identidade digital |

<center>

Fonte: [Altino Arthur](https://github.com/arthurrochamoreira)

</center>

<br>

#### Feature 2: Documentos e Certificados

Tabela 10: Documentos e Certificados

| Como um/a...             | Eu quero...                                         | Para que eu possa...                                     |
| ------------------------ | --------------------------------------------------- | ------------------------------------------------------- |
| usuário                  | adicionar o documento CLRV-e à minha conta          | ter acesso fácil e rápido ao meu documento eletrônico   |
| usuário                  | acessar meu documento CLRV-e                        | consultar informações do veículo sempre que necessário  |
| usuário                  | visualizar e gerenciar meus certificados            | manter o controle sobre os documentos importantes       |

<center>

Fonte: [Altino Arthur](https://github.com/arthurrochamoreira)

</center>

<br>

#### Feature 3: Exames e Infrações

Tabela 11: Exames e Infrações

| Como um/a...             | Eu quero...                                                 | Para que eu possa...                                             |
| ------------------------ | ----------------------------------------------------------- | --------------------------------------------------------------- |
| usuário                  | visualizar os resultados de exames toxicológicos             | acompanhar meu estado de saúde relacionado à condução            |
| usuário                  | acessar informações sobre infrações relacionadas à minha carteira de motorista | estar ciente das infrações e tomar as medidas necessárias      |
| usuário                  | pagar infrações diretamente pela aplicação                    | efetuar pagamentos de forma rápida e conveniente                  |
| usuário                  | receber notificações sobre infrações relacionadas à minha carteira de motorista | estar informado sobre eventuais infrações de trânsito           |

<center>

Fonte: [Altino Arthur](https://github.com/arthurrochamoreira)

</center>

<br>

#### Feature 4: Campanhas e Projetos

Tabela 12: Campanhas e Projetos

| Como um/a...             | Eu quero...                                         | Para que eu possa...                                     |
| ------------------------ | --------------------------------------------------- | ------------------------------------------------------- |
| usuário                  | consultar informações sobre campanhas e projetos relacionados à segurança no trânsito | estar informado sobre iniciativas de segurança no trânsito |
| usuário                  | participar ativamente de campanhas e projetos relacionados à segurança no trânsito | contribuir para a segurança viária e participar de ações de conscientização |

<center>

Fonte: [Altino Arthur](https://github.com/arthurrochamoreira)

</center>

<br>

#### Feature 5: Cadastro Positivo e Notificações

Tabela 13: Cadastro Positivo e Notificações

| Como um/a...             | Eu quero...                                         | Para que eu possa...                                     |
| ------------------------ | --------------------------------------------------- | ------------------------------------------------------- |
| usuário                  | visualizar meu cadastro positivo de trânsito       | entender meu histórico de conduta no trânsito          |
| usuário                  | aderir ao sistema de notificação eletrônica        | receber atualizações e alertas importantes de forma eletrônica |
| usuário                  | gerenciar minhas preferências de notificação        | escolher quais tipos de alertas desejo receber          |

<center>

Fonte: [Altino Arthur](https://github.com/arthurrochamoreira)

</center>

<br>

#### Feature 6: Cursos Especializados

Tabela 14: Cursos Especializados

| Como um/a...             | Eu quero...                                                 | Para que eu possa...                                             |
| ------------------------ | ----------------------------------------------------------- | --------------------------------------------------------------- |
| usuário                  | visualizar informações sobre cursos especializados relacionados à segurança no trânsito | obter informações sobre oportunidades de aprendizado relacionadas à segurança viária |
| usuário                  | inscrever-me em cursos especializados relacionados à segurança no trânsito | adquirir conhecimento adicional para uma condução mais segura |

<center>

Fonte: [Altino Arthur](https://github.com/arthurrochamoreira)

</center>

<br>

#### Feature 7: Segurança e Autenticação

Tabela 15: Segurança e Autenticação

| Como um/a...             | Eu quero...                                         | Para que eu possa...                                     |
| ------------------------ | --------------------------------------------------- | ------------------------------------------------------- |
| usuário                  | usar biometria para desbloquear minha carteira de habilitação eletrônica | aumentar a segurança do acesso à minha carteira digital |
| usuário                  | recuperar senhas perdidas                            | redefinir minha senha de forma segura em caso de perda |

<center>

Fonte: [Altino Arthur](https://github.com/arthurrochamoreira)

</center>

<br>
  
## Bibliografia
  
> SOUZA, Nicolas; MACEDO, Lucas. Backlog do Produto. Repositório do Grupo Lichess da disciplina de Requisitos de Software da Universidade de Brasília, 2022. Disponível em: <<https://requisitos-de-software.github.io/2022.2-Lichess/modelagem/agil/backlog/>>. Acesso em: 18 maio 2023.


> POPOV, Arthur Taylor de Jesus; SANTOS, Eduardo Schuindt. Backlog do Produto. Repositório do Grupo MEI da disciplina de Requisitos de Software da Universidade de Brasília, 2022. Disponível em: <<https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Agil/BacklogDoProduto/>>. Acesso em: 18 maio 2023.

> PRESSMAN, Roger S.; MAXIM, Bruce R.. Engenharia de software: uma abordagem profissional. 8 Porto Alegre: AMGH, 2016, 940 p.
  
> Bourque, P., Fairley, R. E. Guide to the Software Engineering Body of Knowledge, Version 3.0. SWEBOK. IEEE Computer Society, 2014. Disponível em: http://www.computer.org/web/swebok/v3. p. 38.

<br>

## 📑Histórico de Versões

| Versão | Data       | Descrição                              | Autor(es)                        | Revisor(es)                       |
| ------ | ---------- | -------------------------------------- | -------------------------------- | --------------------------------- |
| 1.0    | 05/11/2023 | Criação da página inicial.             | [Altino Arthur](https://github.com/arthurrochamoreira) | [Milena Baruc](https://github.com/MilenaBaruc) |
