# NFR Framework 

## Introdução 

O Framework de Requisitos Não Funcionais (NFR, do inglês "Non-Functional Requirements") é uma abordagem essencial no desenvolvimento de software e engenharia de sistemas.O NFR Framework fornece uma estrutura organizada para coletar, analisar e documentar esses requisitos não funcionais. Isso ajuda as equipes de desenvolvimento e stakeholders a entenderem a importância de aspectos como tempo de resposta, segurança de dados, disponibilidade, entre outros, e a tomar decisões informadas durante o ciclo de vida do projeto. <br/>
Este framework também auxilia na priorização dos requisitos não funcionais, considerando as restrições e necessidades específicas do projeto, permitindo que as equipes se concentrem nos aspectos mais críticos para atender às expectativas dos usuários e aos objetivos do negócio. No NFR Framework, faz-se o uso do modelo de Softgoal Interdependency Graph (SIG).

### Softgoal Interdependency Graph

O Gráfico de Interdependência de Softgoals (SIG) é uma representação visual do NFR Framework, que registra as posições da equipe de desenvolvimento em relação aos softgoals e ilustra suas interdependências de maneira gráfica e concisa.

## Metodologia
A abordagem adotada para a concepção do artefato foi fundamentada nos requisitos não funcionais, os quais foram delineados com base no nosso documento de especificação suplementar. Que, por sua vez, se pautou no modelo FURPS+ para a criação de 13 NFRs. Para melhor entendimento de cada categoria, foi feito um SIG (Softgoal Interdependency Graph), um diagrama da propagação de impactos e um cartão de especificação, que possui informações sobre o NFR, como a descrição, a categoria, os conflitos, a origem, os critérios e outras informações, que foram divididos em 4 aspectos: Usabilidade, confiabilidade, desempenho e suportabilidade, como demonstrado na tabela 1. 

<center>
<p align="center"> Tabela 1: Requisitos Não Funcionais - RNF</p>

|   Tipo  | Requisito                                                                                       | ID  |
| ---------- | --------------------------------------------------------------------------------             | ---------       |
| Usabilidade| O sistema não deve exigir que seus usuários sejam tecnófilos. Deve ser de fácil uso, sem necessidade prévia de treinamento para utilização do sistema.                                                                   | [NFR01](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/especificacao-suplementar/) 
| Usabilidade|Os usuários devem realizar as atividades críticas em um curto período de tempo, de no máximo um minuto.                                                                   | [NFR02](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/especificacao-suplementar/) 
| Usabilidade|Os objetivos críticos deve ser alcançados por um caminho curto, necessitando uma pequena quantidade de ações do usuário, cerca de 5 ações.                                                                   | [NFR03](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/especificacao-suplementar/) 
| Usabilidade|O sistema deve possuir design minimalista, evitando que sejam mostradas infomações irrelevantes ou pouco consultadas.                                                                   | [NFR04](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/especificacao-suplementar/) 
| Usabilidade|O sistema deve conter uma linguagem simples, evitando utilização de termos ou bordões técnicos.                                                                   | [NFR05](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/especificacao-suplementar/) 
| Usabilidade|O aplicativo deve seguir as normas de acessibilidade da WCAG        .                                                | [NFR06](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/especificacao-suplementar/) 
| Confiabilidade   | O sistema deve está disponível durante os 7 dias da semana, 24 horas por dia.                                   | [NFR07](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/especificacao-suplementar/) 
| Confiabilidade   | O aplicativo deve apresentar as políticas de privacidade, descrevendo quais dados serão coletados do usuário.                               | [NFR08](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/especificacao-suplementar/) 
| Confiabilidade   | O aplicativo deve solicitar apenas o número mínimo de permissões necessárias para a compatibilidade com o caso de uso em questão.                               | [NFR09](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/especificacao-suplementar/) 
| Desempenho  | O aplicativo não deve utilizar mais do que 90MB de armazenamento interno do aplicativo. | [NFR10](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/especificacao-suplementar/) 
| Desempenho | O aplicativo deve realizar suas operações em um tempo máximo de 2 segundos, caso não seja possível deve haver um feedback com indicador de progresso.                                  | [NFR11](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/especificacao-suplementar/) 
| Desempenho  | O sistema possuir uma integração eficiente API gov.                                     | [NFR12](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/especificacao-suplementar/) 
| Suportabilidade  |O aplicativo deve está disponível nas lojas virtuais dos principais sistemas operacionais (SO) utilizados em dispositiveis móveis.                                     | [NFR13](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/especificacao-suplementar/) 

<p align="center"> Fonte: Mayara Alves</p>
</center>


## Cartão de Especificação

## NFR Geral

## NFR Usabilidade

## NFR Confiabilidade 

## NFR Desempenho

## NFR Suportabilidade

## Bibliografia

> BARBOSA, S. D. J.; SILVA, B. S. Interação Humano-Computador. Rio de Janeiro: Elsevier, 2011.'

> REQUISITOS DE SOFTWARE. Bilheteria Digital. Distrito Federal, 2023. Disponível em: <https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/>. Acesso em: 21/10/2023.


## 📑Histórico de Versões

| Versão |    Data    |      Descrição      |       Autor     | Revisor(es)  |
| ------ | ---------- | ------------------- | --------------- | ------------ |
| 1.0    | 06/11/2023 | Criação do template | [Limirio Guimarães](https://github.com/LimirioGuimaraes) |[Mayara Alves](https://github.com/Mayara-tech) |
