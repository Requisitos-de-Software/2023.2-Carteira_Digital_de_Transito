## Introdução
A técnica de elicitação chamada Glossário, que também pode ser usada como produto final, é uma técnica que têm como atividade identificar e definir palavras ou termos-chaves utilizadas no domínio do problema em que o sistema está sendo desenvolvido ou analisado, assim coletando um dicionário em comum dos stakeholders, e durante o processo desta atividade, é capaz de elicitar requisitos. O que torna essa técnica tão eficaz no aplicativo Carteira Digital de Trânsito, é a quantidade de termos e siglas utilizados no Código de Trânsito Brasileiro.

Conforme foi dito pelo Vazquez e Simões^1^, em  Engenharia de Requisitos, no Cap. 7 (2016, p. 155-156  ), para identificar os termos candidatos ao glossário, temos que atentar aos termos:
- Únicos para o domínio;
- Com mais de um definição;
- Com definição local distinta do senso comum;
- Com potencial de causar dificuldades de entendimento;
- Técnicos do negócio;
- Do tipo abreviações e siglas;
- Que são sinônimos e antônimos.

## Metodologia
Para auxiliar a equipe no gerenciamento de conhecimento e na consulta de termos no domínio de negócio, foram catalogados os seguintes termos utilizando a persona secundária [Steve Vobes](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/personas/), que foi encenada pelo membro [Vinícius Mendes](https://github.com/yabamiah) para ter uma maior imersão na atividade de glossário, assim tendo uma imersão maior para descobrir quais termos se caixam no critérios acima para termos candidatos ao glossário, para a realização da atividade também foi preciso da ajuda de um membro que possuia uma conta no aplicativo que se aproximava da Persona, e a membro da equipe [Milena](https://github.com/MilenaBaruc) ajudou nisso, dando acesso a algumas funcionalidades da conta do aplicativo de seu celular (Pois ela tem mais tempo de uso e mais acesso a diversas funcionalidades). Os termos catalogados eram relacionados ao domínio do Código Brasileiro de Trânsito e os seus significados estarão representados na Tabela 1.

**Tabela 1** - Glossário dos termos do Código Brasileiro de Trânsito

| **Termo** | **Definição** |
|-------|-----------|
|Condutor|É o motorista que conduz um automóvel e que responde pelas multas de tráfego de seu veículo |
|Infrações|É a inobservância a qualquer preceito da legislação de trânsito|
|Infrator|É o responsável por uma infração |
|CNH|Uma sigla que significa Carteira Nacional de Habilitação, que atesta a aptidão das pessoas de conduzir um veículo |
|ACC|Uma sigla que significa Autorização para Conduzir Ciclomotor, habilita o condutor a dirigir apenas ciclomotor |
|PPD|É o processo de emissão da Permissão para Dirigir |
|Categoria| Há tipos diferentes de autorizações para conduzir veículos diferentes, e a categoria defini as categorias de autorizações |
|Cadastro Positivo| Um sistema de pontuação que registra o histórico de conduta dos motoristas |
|CRLV| Uma sigla que significa Certificado de Registro e Licenciamento do Veículo, um documento que permite a circulação do veículo |
|RENAVAM| Uma sigla que significa Registro Nacional de Veículos Automotores, é um código de identidade do veículo |
|CLA|Uma sigla que significa Certificado de Licenciamento Anual, que é o documento que comprova a regularidade do veículo |
|SNE|Uma sigla que significa Sistema de Notificação Eletrônica, que dá o direito a descontos no pagamento de multas de trânsito |
|Habilitação| É a permissão de poder dirigir um veículo |

 Fonte: [Vinícius Mendes](https://github.com/yabamiah).

## Requisitos Elicitados
Seguido o estudo dos termos e do contexto em que os termos e que citamos na Tabela 1 foram explicados, conseguimos elicitar os requisitos apresentados na Tabela 2. Identificamos cada requisito por uma sigla formado por "GLO"  + um número, em que "GLO" é uma sigla de glossário, e para representar o tipo do requisito, será usado as siglas "RF" ou "RNF", que representam o tipo do requisito funcional ou não funcional, além disso também será representado se já há uma implementação do requisito no aplicativo.

**Tabela 2** - Requisitos elicitados do Glossário

| **Identificador** | **Requisitos** | **Tipo** | **Implementado** |
|--------------|-------------|-----|-----------------|
|GL01| Deve ser possível consultar as siglas apresentadas| RF | Não implementado |
|GL02| Deve ser possível cadastrar os CRLV dos veículos | RF| Implementado |
|GL03| Deve ser possível visualizar os CRLV dos veículos | RF| Implementado |
|GL04| Deve ser possível baixar os CRLV dos veículos| RF | Implementado |
|GL05| Facilitar o usuário a chegar a funcionalidade de aderir ao SNE       | RNF | Não implementado |
|GL06| Dever ser possível consultar a classificação da infração | RF | Não implementado |
|GL07| Deve ser possível visualizar as infrações do condutor | RF | Implementado |
|GL08| Deve ser possível cadastrar a CNH do condutor | RF | Implementado |
|GL09| Deve ser possível participar no Cadastro Positivo | RF | Implementado |

Fonte: [Vinícius Mendes](https://github.com/yabamiah).

## Referência Bibliográfica
> 1. VAZQUEZ C., SIMÕES G.  Engenharia de Requisitos. 1 ed. Brasport, 2016. Capítulo 7, p. 255-256. <br>

## Bibliografia
> DETRAN-DF, disponível no [link](https://www.detran.df.gov.br/), acesso em outubro de 2023.

## 📑 Histórico de Versões
| **Versão**   |   **Data**   | **Descrição** | **Autor** | **Revisor** |
|--------|---------|-----------|--------|---------|
|`1.0`| 04/09/2023 | Criação da página de glossário | [Vinícius Mendes](https://github.com/yabamiah)| [Luís Miranda](https://github.com/LuisMiranda10) |
|`1.1`| 07/09/2023 | Arrumando tabela de requisitos e adicionais mais informações| [Vinícius Mendes](https://github.com/yabamiah)| [Mayara Alves](https://github.com/Mayara-tech) |
|`1.2`| 07/09/2023 | Arrumando a seção de metodologia | [Vinícius Mendes](https://github.com/yabamiah)| [Luís Miranda](https://github.com/LuisMiranda10) |
|`1.3`| 22/10/2023| Atualizando req elicitados na Tabela 2 | [Vinícius Mendes](https://github.com/yabamiah) | [Mayara Alves](https://github.com/Mayara-tech) |
|`2.0` | 05/10/2023 | Correção final do artefato |  [Vinícius Mendes](https://github.com/yabamiah) | [Altino Arthur](https://github.com/arthurrochamoreira) | 
