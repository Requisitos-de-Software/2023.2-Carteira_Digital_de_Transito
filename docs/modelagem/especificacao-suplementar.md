# Especificação Suplementar

## Introdução

Esse documento tem por objetivo descrever os requisitos não funcionais, *non-functional requirements*
(NFR), do software Carteira Digital de Trânsito. Os requisitos analisados foram classificados utilizado
o modelo FURPS+, que classifica os requisitos em funcionais, de usabilidade, de confiabilidade, de
suportabilidade, de desempenho, e de restrições. 

## Metodologia

Para a realizar a classificação dos requisitos fora utilizado a modelo FURPS+ de maneira adaptada. Não foi
utilizado a classifica Funcional do modelo, já que esse requisitos foram modelados em outros documentos
presentes no projeto.

## Funcionais

Os requisitos funcionais estão disponíveis no documento de [Casos de uso]()

## Usabilidade

Os requisitos de usabilidade contemplam as seguintes atividades:

1. Facilidade do uso do sistema pelo usuário.
1. Atividades críticas devem ser executas com um número mínimo de ações.
1. Atividades típicas devem ser executadas em um curto período de tempo.
1. O sistema deve possuir um interface minimalista.
1. O sistema deve possuir um linguagem simples.
1. Acessibilidade

### Requisito de Usabilidade 1

O sistema não deve exigir que seus usuários sejam tecnófilos. Ou seja, deve ser de fácil uso e sem
necessidade prévia de treinamento para utilização do sistema.

### Requisito de Usabilidade 2 e 3

Os usuários devem realizar as atividades críticas em um curto período de tempo, de no máximo
um minuto. Além disso, os objetivos críticos deve ser alcançados por um caminho curto, necessitando
uma pequena quantidade de ações do usuário.

### Requisito de usabilidade 4 e 5

O sistema deve possuir design minimalista, evitando que sejam mostradas infomações irrelevantes
ou pouco consultadas. Também deve conter uma linguagem simples, evitando utilização de termos
ou bordões técnicos.

### Requisito de usabilidade 6

- Áreas de toque precisam ter pelo menos 48 pixel de espaçamento(dp)[1].
- A razão de contraste deve seguir o padrão recomendado pela World Wide Web Consortium(W3C) 3:1 para textos
grandes e 4.5:1 para textos pequenos[2].

## Confiabilidade

0. Disponibilidade integral.
1. políticas de privacidade.

### Requisito de confiabilidade 1

O sistema deve está disponível durante os 7 dias da semana, 24 horas por dia.

### Requisito de confiabilidade 2

- O aplicativo deve apresentar as políticas de privacidade, descrevendo quais dados serão coletados
do usuário.
- O app solicita apenas o número mínimo absoluto de permissões necessárias para a compatibilidade
com o caso de uso em questão[1].

## Desempenho

0. O aplicativo deve consumir poucos recursos do celular.
0. Velocidade nas operações.
0. Eficiência na disponibilidade de dados.

### Requisito de desempenho 1

- O aplicativo não deve utilizar mais do que 90MB de armazenamento interno do aplicativo.

### Requisito de desempenho 2

- O aplicativo deve realizar suas operações em um tempo máximo de 2 segundos, caso não seja
possível deve haver um feedback com indicador de progresso. [1]

### Requisito de desempenho 3

O sistema possuir uma integração eficiente com o sistema de banco de dados, para que dados
como novas infrações, compartilhamento de documentos, sejam disponibilizadas de maneira rápida.

## Suportabilidade

1. O aplicativo deve está disponível nos princiáis sistemas operacionais(SO).
1. Testabilidade

### Requisito de suportabilidade 1

O aplicativo deve está disponpivel para IOS e Android, inclusive em versões mais antigas dos
SOs. De forma que 90% dos dispositivos ativos de cada SO sejam atendidos[3].

### Requisto de suportabilidade 2


## Restrições

### Restrições de design

Os aplicativos do governo seguem um conjuntos de padrões de interface *design system*(DS) para os
Adispositivos móveis. Esse DS possui as seguintes diretrizes:

- Experiência Única
- Eficiência e Clareza
- Acessibilidade
- Reutilização
- Colaboração

O aplicativo também deve seguir a identidade visual proposta pelo DS do governo. Os fundamentos visuais
especificados pelo governo está disposta na tabela 01.

<center>

**Tabela 01**: Fundamentos Visuais

|Web |	Web Responsivo| 	Material| Design| 	iOS|
|:-|:-|:-|:-|:-|
|Cores          | 	Fundamentos DS| 	Fundamentos DS| 	Fundamentos DS  | 	Fundamentos DS  |
|Iconografia    | 	Fundamentos DS| 	Fundamentos DS| 	Opcional        | 	Opcional        |
|Espaçamento    | 	Fundamentos DS| 	Fundamentos DS| 	Fundamentos DS  | 	Fundamentos DS  |
|Estados        | 	Fundamentos DS| 	Fundamentos DS| 	Fundamentos DS  | 	Fundamentos DS  |
|Ilustração     | 	Fundamentos DS| 	Fundamentos DS| 	Fundamentos DS  | 	Fundamentos DS  |
|Sistema de Grid| 	Fundamentos DS| 	Fundamentos DS| 	Nativo          | 	Nativo          |
|Superfície     | 	Fundamentos DS| 	Fundamentos DS| 	Nativo          | 	Nativo          |
|Elevação       | 	Fundamentos DS| 	Fundamentos DS| 	Nativo          | 	Nativo          |
|Movimento      | 	Fundamentos DS| 	Fundamentos DS| 	Opcional        | 	Opcional        |
|Tipografia     | 	Fundamentos DS| 	Fundamentos DS| 	Fundamentos DS  | 	Fundamentos DS  |

 Fonte: gov.br

</center>

**Legenda**

- **Fundamentos DS**: Os fundamentos do DS deverão ser utilizadas independente da sua versão nativa
(Android ou iOS). Esta característica é aplicada em: cores, espaçamento, estados, ilustração e tipografia.
- **Nativo**: As características da versão nativa (Android ou iOS) deverão ser mantidas
independente do que foi determinado nos fundamentos. Exemplos: sistemas de grids, superfície e elevação.
- **Opcional**: Os fundamentos podem ser utilizados, porém a prioridade será a versão nativa (Android ou iOS).
Exemplos: iconografia e movimento.

### Restrições de implementação



### Restrições de interface



### Requisitos físicos

O aplitivo deve está disponível *smartphones*, *tablets*

## Referências

> 1. Developers **Principais critérios de qualidade do app**; Disponível em: <https://developer.android.com/docs/quality-guidelines/core-app-quality?hl=pt_br#ux>; Acesso: 22 de Outubro 2023
> 1. MATERIAL DESIGN **Accessibility** <https://m2.material.io/design/usability/accessibility.html#color-and-contrast>; Acesso: 22 de Outubro 2023.
> 1. Developers **Compatibilidade com diferentes versões da plataforma**; Disponível em: <https://developer.android.com/training/basics/supporting-devices/platforms?hl=pt-br>; Acesso: 22 de Outubro 2023

## Bibliografia
> BARBOSA, S. D. J.; SILVA, B. S. Interação Humano-Computador. Rio de Janeiro: Elsevier, 2011.
> gov.br; **Padrão Digital de Governo** Disponível em><https://www.gov.br/ds/padroes/mobile/android-e-ios> Acessoem: 22 de Outubro 2023.

## 📑 Histórico de versões:

 Versão  |    Data    |Descrição|Autor(es)|Revisor(es)|                 
 :-----: | :--------: | :-----: | :-----: | :--------:| 
  `1.0`  |  |Criação do documento| [Breno](https://github.com/brenob6) | [](https://github.com/)
