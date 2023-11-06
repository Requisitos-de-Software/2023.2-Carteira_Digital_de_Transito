# NFR Framework 

## Introdução 

O Framework de Requisitos Não Funcionais (NFR, do inglês "Non-Functional Requirements") é uma abordagem essencial no desenvolvimento de software e engenharia de sistemas.O NFR Framework fornece uma estrutura organizada para coletar, analisar e documentar esses requisitos não funcionais. Isso ajuda as equipes de desenvolvimento e stakeholders a entenderem a importância de aspectos como tempo de resposta, segurança de dados, disponibilidade, entre outros, e a tomar decisões informadas durante o ciclo de vida do projeto. <br/>
Este framework também auxilia na priorização dos requisitos não funcionais, considerando as restrições e necessidades específicas do projeto, permitindo que as equipes se concentrem nos aspectos mais críticos para atender às expectativas dos usuários e aos objetivos do negócio. No NFR Framework, faz-se o uso do modelo de Softgoal Interdependency Graph (SIG), quem em tradução para o português fica gráfico de interdependência de softgoals.

### Gráfico de Interdependência de Softgoals

O Gráfico de Interdependência de Softgoals (Softgoal Interdependency Graph - SIG) é uma representação visual do NFR Framework, que registra as posições da equipe de desenvolvimento em relação aos softgoals e ilustra suas interdependências de maneira gráfica e concisa. O termo "Softgoal", amplamente discutido no contexto deste framework, refere-se a um objetivo que carece de uma definição nítida e critérios de satisfação bem definidos. Esses objetivos são usados para representar Requisitos Não Funcionais (NFRs) e podem estar interligados, exercendo influência sobre outros elementos do sistema em questão.

Os Softgoals podem ser categorizados em três tipos distintos:

- **Softgoals NFR:** São requisitos não funcionais, que incluem critérios e atributos de qualidade desejados na análise, permitindo determinar sua implementação ou não implementação.

- **Softgoals de Operacionalização:** Representam funcionalidades concretas que servem como uma maneira de viabilizar ou não as características abstratas do sistema.

- **Softgoals de Afirmação:** São declarações em linguagem natural que podem ser incorporadas ao modelo para argumentar sobre pontos específicos de modelagem.

Cada um desses tipos de Softgoals pode ser desdobrado seguindo os seguintes métodos de decomposição:

- **Decomposição de Softgoals NFR:** Refina ou divide um Softgoal NFR em subobjetivos, ajudando a segmentar problemas complexos em partes menores, o que é útil para lidar com ambiguidades e prioridades.

- **Decomposição de Operacionalização:** Subdivide um Softgoal de Operacionalização em objetivos mais específicos, permitindo a definição de soluções gerais que podem ser transformadas em soluções mais específicas.

- **Decomposição de Afirmação (Claims):** Refina um Softgoal de Afirmação em subobjetivos adicionais. Isso é útil para fornecer justificativas sólidas para as decisões de projeto, apoiando ou refutando argumentos.

- **Priorização:** Refina um Softgoal em outro com o mesmo tipo e tópico, atribuindo uma prioridade associada a cada um, o que é útil para determinar a importância relativa dos objetivos e suas contribuições para o sistema.

Esse processo de desdobramento e priorização dos Softgoals é essencial para alcançar uma modelagem precisa e eficaz, especialmente em contextos nos quais os objetivos não são facilmente quantificáveis ou têm várias nuances.
<center>
<p align="center"> Figura 1: Tipos de Decomposição </p>

 ![decomposicao](../../assets/imagem_2023-11-06_164643478.png)
 
<p align="center"> Fonte: CHUNG et al.; 2000  </p>
</center>

#### Contribuições entre Softgoals em um NFR Framework

Um aspecto fundamental é a relação de contribuição entre os Softgoals, que descreve como as mudanças nos estados de um Softgoal filho podem afetar o Softgoal pai. Essas contribuições são classificadas em diversos tipos, conforme apresentado na tabela a seguir:

| Contribuição | Representação | Descrição |
| :----------: | :-----------: | :-------: |
| AND | AND | O Softgoal pai é satisfeito somente se todos os Softgoals filhos forem satisfeitos, de acordo com a perspectiva dos envolvidos. |
| OR | OR | O Softgoal pai é satisfeito se pelo menos um dos Softgoals filhos for satisfeito, de acordo com a perspectiva dos envolvidos. |
| MAKE | ++ | Um Softgoal filho contribui de forma tão positiva que, sozinho, é capaz de satisfazer o Softgoal pai, de acordo com a perspectiva dos envolvidos. |
| HELP | + | Um Softgoal filho contribui de forma positiva, mas parcial, de modo que sozinho não é capaz de satisfazer o Softgoal pai, de acordo com a perspectiva dos envolvidos. |
| BREAK | -- | Um Softgoal filho contribui de forma tão negativa que, sozinho, nega o Softgoal pai, de acordo com a perspectiva dos envolvidos. |
| HURT | - | Um Softgoal filho contribui de forma negativa, mas parcial, de modo que sozinho não nega o Softgoal pai, de acordo com a perspectiva dos envolvidos. |
| UNKNOWN | ? | O Softgoal filho não afeta o Softgoal pai, e a relação é incerta. |
| EQUALS | = | Ambos compartilham o mesmo rótulo e estão intrinsecamente relacionados. |
| SOME | SOME - | Um Softgoal filho contribui de forma negativa, mas a intensidade dessa contribuição é desconhecida. |
| SOME | SOME + | Um Softgoal filho contribui de forma positiva, mas a intensidade dessa contribuição é desconhecida.

Esses conceitos de contribuição entre Softgoals são essenciais para a compreensão e modelagem de sistemas complexos, especialmente quando se lida com requisitos não funcionais e objetivos de qualidade. Eles proporcionam um meio preciso de descrever como as relações entre os Softgoals afetam o sistema como um todo.


### Propagação de Impactos 

Ao considerar a propagação de impactos, os engenheiros de requisitos podem tomar decisões informadas sobre mudanças e gerenciar eficazmente os possíveis efeitos colaterais. Para representar as relações de impacto, são utilizados diversos tipos de Softgoals de Impacto, cada um com sua notação específica:

✓ (satisfeito): Essa notação indica que um requisito não funcional contribui positivamente para a satisfação de outro requisito. Em outras palavras, atender a um requisito tem um efeito benéfico em relação ao outro.

𝒲+ (fracamente satisfeito): Similar à notação ✓, porém representa uma relação de impacto positiva, embora menos intensa do que a representada por ✓.

X (negado): Essa notação denota que um requisito não funcional tem um efeito negativo sobre outro requisito, negando ou contradizendo sua realização. Em outras palavras, atender a um requisito pode prejudicar o atendimento do outro.

𝒲- (fracamente negado): Semelhante à notação X, mas representa uma relação de negação mais fraca. Isso significa que um requisito afeta negativamente outro, mas de forma menos intensa do que a notação X.

🗲 (conflitante): Essa notação indica uma relação de conflito entre requisitos não funcionais. Significa que os requisitos em questão têm características positivas e negativas, o que pode resultar em uma competição entre eles.

u (indeterminado): Esta notação representa uma relação indeterminada ou desconhecida entre requisitos não funcionais. Isso ocorre quando não há informações suficientes para determinar o impacto de um requisito em outro, tornando a relação incerta.

A compreensão e uso dessas notações são essenciais para a análise de impacto e a tomada de decisões informadas na gestão de requisitos não funcionais, garantindo que as mudanças planejadas não causem efeitos colaterais indesejados no sistema como um todo.
 
  
</center>

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

Usabilidade, de acordo com a definição de Jakob Nielsen, é a medida que avalia quão fácil e agradável é a interação dos usuários com um sistema, seja um site, aplicativo ou software, no contexto de alcançar seus objetivos e realizar tarefas com eficácia. Na tabela 2 podemos observar os requisitos de usabilidade de o grupo elicitou, e nas figuras 2 e 3 podemos observar Softgoal Interdependency Grap do softgoal "Usabilidade" e a Propagação de impactos do softgoal "Usabilidade" 

<center>
<p align="center"> Tabela 2: Requisitos de Usabilidade - RNF</p>

| Requisito                                                                                       | ID  |
| --------------------------------------------------------------------------------             | ---------       |
| O sistema não deve exigir que seus usuários sejam tecnófilos. Deve ser de fácil uso, sem necessidade prévia de treinamento para utilização do sistema.                                                                   | [NFR01](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/especificacao-suplementar/) 
|Os usuários devem realizar as atividades críticas em um curto período de tempo, de no máximo um minuto.                                                                   | [NFR02](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/especificacao-suplementar/) 
|Os objetivos críticos deve ser alcançados por um caminho curto, necessitando uma pequena quantidade de ações do usuário, cerca de 5 ações.                                                                   | [NFR03](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/especificacao-suplementar/) 
|O sistema deve possuir design minimalista, evitando que sejam mostradas infomações irrelevantes ou pouco consultadas.                                                                   | [NFR04](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/especificacao-suplementar/) 
|O sistema deve conter uma linguagem simples, evitando utilização de termos ou bordões técnicos.                                                                   | [NFR05](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/especificacao-suplementar/) 
|O aplicativo deve seguir as normas de acessibilidade da WCAG        .                                                | [NFR06](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/especificacao-suplementar/) 

<p align="center"> Fonte: Mayara Alves</p>
</center>

### Cartão de especificação 

#### Cartão especificação NFR1 - Facilidade no uso. 

<center>
<p align="center"> Cartão especificação NFR1 - Facilidade no uso</p>
 
| Classificação         | Fácil Aprendizagem / Usabilidade | 
| ----------------------|--|
| Descrição             | O sistema não deve exigir que seus usuários sejam tecnófilos. Deve ser de fácil uso, sem necessidade prévia de treinamento para utilização do sistema.           |
| Justificativa         | Com um sistema simples o usuario não vai ter dificuldade em aprender a usar o aplicativo, assim terá menos chances dele abandonar o uso e te uma experiencia melhor com o app. |
| Origem do requisito   | RNF01 - Especificação suplementar |
| Critério de aceitação | Nenhum |
| Prioridade            | Alta prioridade. Fonte: [TLS](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/prioriza%C3%A7%C3%A3o/three_level_scale/)|
| Conflito              | Nenhum |
| Historia              | 06 de novembro de 2023 |

<p align="center"> Fonte: Mayara Alves</p>
</center>

## NFR Confiabilidade 
<p align="center"> Cartão especificação NFRX - O sistema deve está disponível durante os 7 dias da semana, 24 horas por dia.</p>
 
| Classificação         |Disponibilidade Contínua | 
| ----------------------|--|
| Descrição             | O sistema deve manter-se disponível ininterruptamente, durante os 7 dias da semana, 24 horas por dia, para atender às necessidades dos usuários e garantir um serviço confiável.           |
| Justificativa         | A disponibilidade ininterrupta é crucial para atender às expectativas dos usuários e garantir a confiabilidade do sistema. Os usuários podem precisar acessar o sistema a qualquer momento, independentemente do dia da semana ou da hora do dia. Portanto, é essencial que o sistema esteja sempre disponível para evitar interrupções nos serviços e proporcionar uma experiência satisfatória aos usuários. |
| Origem do requisito   | RNFX - Especificação suplementar |
| Critério de aceitação |- O sistema deve estar disponível 24 horas por dia, 7 dias por semana, com exceções permitidas apenas para manutenções programadas e devidamente comunicadas com antecedência aos usuários.<br/>- Durante qualquer período de manutenção programada, o sistema deve exibir uma mensagem de aviso aos usuários informando a data e a duração estimada da interrupção.<br/>- A disponibilidade do sistema deve ser monitorada continuamente, e quaisquer interrupções não programadas devem ser tratadas prontamente, com um tempo máximo de recuperação estabelecido para cada incidente.<br/>- Os registros de disponibilidade do sistema devem ser mantidos e periodicamente avaliados para garantir o cumprimento deste requisito.<br/>- A equipe de suporte e manutenção do sistema deve estar disponível para resolver problemas relacionados à disponibilidade 24 horas por dia, 7 dias por semana. |
| Prioridade            | Alta prioridade|
| Conflito              | Nenhum |
| Historia              | 06 de novembro de 2023 |

<p align="center"> Fonte: [Limirio Guimarães](https://github.com/LimirioGuimaraes)</p>

<center>
<p align="center"> Figura 5: SIG Disponibilidade Contínua </p>

 ![decomposicao](../../assets/confiabilidadeDiagrama1)
 
<p align="center"> Fonte: CHUNG et al.; 2000  </p>
</center>


## NFR Desempenho

## NFR Suportabilidade

## Bibliografia

> BARBOSA, S. D. J.; SILVA, B. S. Interação Humano-Computador. Rio de Janeiro: Elsevier, 2011.'

> REQUISITOS DE SOFTWARE. Bilheteria Digital. Distrito Federal, 2023. Disponível em: <https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/>. Acesso em: 06/11/2023.

> REQUISITOS DE SOFTWARE. MEI - Microempreendedor Individual. Distrito Federal, 2022. Disponível em:  <https://requisitos-de-software.github.io/2022.2-MEI/>. Acesso em: 06/11/2023

> CHUNG, L.; NIXON, B. A.; YU, E.; MYLOPOULOS, J. Non-functional requirements in software engineering. Springer Science & Business Media: [s.n.], 2000. v. 5.

> SILVA, R. NFR4ES: Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados. Tese (Mestrado em Engenharia de Software) - Centro de Informática, Universidade Federal de Pernambuco. Recife, p. 155. 2019.


## 📑Histórico de Versões

| Versão |    Data    |      Descrição      |       Autor     | Revisor(es)  |
| ------ | ---------- | ------------------- | --------------- | ------------ |
| 1.0    | 06/11/2023 | Criação do template | [Limirio Guimarães](https://github.com/LimirioGuimaraes) |[Mayara Alves](https://github.com/Mayara-tech) |
