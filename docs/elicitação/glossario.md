## Introdução
A técnica de elicitação chamada Glossário, que também pode ser usada como produto final, é uma técnica que têm como atividade identificar e definir palavras ou termos-chaves utilizadas no domínio do problema em que o sistema está sendo desenvolvido ou analisado, assim coletando um dicionário em comum dos stakeholders, e durante o processo desta atividade, é capaz de elicitar requisitos. O que torna essa técnica tão eficaz no aplicativo Carteira Digital de Trânsito, é a quantidade de termos e siglas utilizados no Código de Trânsito Brasileiro.

Conforme foi dito pelo Vazquez e Simões, em  Engenharia de Requisitos, no Cap. 7 (2016, p. 155-156  ), para identificar os termos candidatos ao glossário, temos que atentar aos termos:
- Únicos para o domínio;
- Com mais de um definição;
- Com definição local distinta do senso comum;
- Com potencial de causar dificuldades de entendimento;
- Técnicos do negócio;
- Do tipo abreviações e siglas;
- Que são sinônimos e antônimos.

## Glossário
Para auxiliar a equipe no gerenciamento de conhecimento e na consulta de termos no domínio de negócio, foram catalogados os seguintes termos em conjunto com outro membro da equipe, a [Milena](https://github.com/MilenaBaruc), onde relacionados ao domínio do Código Brasileiro de Trânsito e os seus significados, que serão representados na Tabela 1.

<p align="center"><b>Tabela 01</b> - Glossário dos termos do Código Brasileiro de Trânsito. Fonte: Autores.</p>

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

## Requisitos Elicitados
Seguido o estudo dos termos e do contexto em que os termos e que citamos na Tabela 1 foram explicados, conseguimos elicitar os requisitos apresentados na Tabela 2. Identificamos cada requisito por uma sigla formado por "GLO"  + um número, em que "GLO" é uma sigla de glossário, e para representar o tipo do requisito, será usado as siglas "RF" ou "RNF", que representam o tipo do requisito funcional ou não funcional, além disso também será representado se já há uma implementação do requisito no aplicativo.

<p align="center"><b>Tabela 02</b> - Requisitos elicitados do Glossário. Fonte: Autores.</p>

| **Identificador** | **Requisitos** | **Tipo** | **Implementado** |
|--------------|-------------|-----|-----------------|
|GL01| Deve ser possível consultar as siglas apresentadas| RF | Não implementado |
|GL02| Deve ser possível cadastrar os CRLV dos veículos | RF| Implementado |
|GL03| Deve ser possível visualizar os CRLV dos veículos | RF| Implementado |
|GL04| Deve ser possível baixar os CRLV dos veículos| RF | Implementado |
|GL05| Facilitar o usuário a chegar a funcionalidade de aderir ao SNE       | RNF | Não implementado |
|GL06| Dever ser possível consultar a classificação da infração | RF | Não implementado |

## Bibliografia
> VAZQUEZ C., SIMÕES G.  Engenharia de Requisitos. 1 ed. Brasport, 2016. Capítulo 7.<br>
> Detran-DF, disponível no [link](https://www.detran.df.gov.br/), acesso em outubro de 2023.

## Referência Bibliográfica
> VAZQUEZ C., SIMÕES G.  Engenharia de Requisitos. 1 ed. Brasport, 2016. Capítulo 7, p. 255-256. <br>
## 📑 Histórico de Versões
| **Versão**   |   **Data**   | **Descrição** | **Autor** | **Revisor** |
|--------|---------|-----------|--------|---------|
|1.0| 04/09/2023 | Criação da página de glossário | [Vinícius Mendes](https://github.com/yabamiah)| [Luís Miranda](https://github.com/LuisMiranda10) |
|1.1| 07/09/2023 | Arrumando tabela de requisitos e adicionais mais informações| [Vinícius Mendes](https://github.com/yabamiah)| [Mayara]() |
