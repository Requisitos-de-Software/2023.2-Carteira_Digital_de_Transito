# First Things First

## Introdução

Dado que a priorização de requisitos é um processo crítico que envolve a classificação e seleção dos requisitos do sistema de acordo com sua importância, impacto e viabilidade, a abordagem _First Things First_ visa enfatizar a importância de focar nas tarefas e atividades mais cruciais e significativas antes de se dedicar a tarefas menos importantes. Assim, temos como ideia central que para ter mais prosutividade deve-se identificar e dedicar tempo significativo às atividades que tem mais impacto no projeto.

## Cronograma da Reunião

| Data | Hora | Local | Assunto | Participantes |
| :--: | :--: | :---: | ------- | ------------ |
| //2023 | h | Teams | Priorização de requisitos elicitados |   | 

## Metodologia

Para elaborar uma tabela em _First Things First_ deve-se seguir oito passos:

* **Passo 1**: Fazer uma lista com todas as funcionalidades, porém se uma funcionalidade precisar de outra para funcionar colocar apenas a principal;
* **Passo 2**: Avaliar o benefício de cada funcionalidade para o cliente ou para o negócio, de 1 a 9, sendo 1 menos significativo e 9 o máximo;
* **Passo 3**: Avaliar as consequências que o negócio sofreria caso a funcionalidade não fosse incluido, de 1 a 9, sendo 1 nenhuma penalidade e 9 a máxima;
* **Passo 4**: Fazer uma coluna de Valor Total onde esta é a soma de benefício e penalidade, com seus respectivos pesos;
* **Passo 5**: Avaliar o custo relativo de implementação de cada funcionalidade, de 1 a 9, sendo 1 o mínimo e 9 o máximo;
* **Passo 6**: Avaliar o grau relativo de risco de cada funcionalidade, de 1 a 9, sendo 1 que os desenvolvedores conseguem 'programar dormindo' e 9 sérias preocupações de viabilidade;
* **Passo 7**: Calcular a prioridade para cada funcionalidade usando: valor(%) / (custo(%) * peso do custo relativo + risco(%) * peso do risco relativo);
* **Passo 8**: Classifique a lista em prioridade decrescente.

### Tabela das funcionalidades

Utilizando os passos acima foi possível produzir a Tabela 1 abaixo. Tendo os seguintes pesos: 
* **Benefício Relativo**: peso 1
* **Penalidade Relativa**: peso 1
* **Custo Relativo**: peso 1
* **Risco Relativo**: peso 1

Funcionalidades | Benefício Relativo | Penalidade Relativa | Valor Total | Custo Relativo | Risco Relativo | Prioridade
-------------- | ------------------ | ------------------- | ----------- | -------------- | --------------- | ----------
9 | 9 | 9 | 18 | 3 | 1  | 3.00
7 | 9 | 9 | 18 | 6 | 1  | 2.00
8 | 9 | 9 | 18 | 6 | 1  | 2.00
10| 3 | 3 | 9  | 2 | 1  | 1.92
6 | 9 | 9 | 18 | 5 | 6  | 1.89
1 | 9 | 7 | 16 | 4 | 5  | 1.38
5 | 6 | 4 | 10 | 1 | 7  | 1.38
2 | 4 | 2 | 5  | 6 | 3  | 0.70
4 | 3 | 1 | 4  | 3 | 9  | 0.08
3 | 1 | 1 | 2  | 1 | 9  | 0.06

### Descrição das funcionalidades

1. O aplicativo permite o cadastro e login do usuário
2. O aplicativo permite a criação de uma chave de acesso
3. O aplicativo permite sair da conta
4. O aplicativo notifica o usuário sobre atualizações
5. O aplicativo possui um tutorial de utilização
6. O aplicativo permite o usuário adicionar seus documentos
7. O usuário deve ser capaz de gerenciar sua habilitação
8. O usuário deve ser capaz de acessar os documentos de seus veículos
9. O usuário deve ser capaz de visualizar suas infrações
10. O usuário deve ser capaz conhecer as campanhas do governo

## Link da Gravação

[Priorização do First Thing First](https://youtu.be/)

## Bibliografia

> SERRANO, Milene; SERRANO, Maurício. Requisitos - Aula 07: Elicitação, Modelagem e Análise. Apresentação Power Point. Disponível em: <https://aprender3.unb.br/pluginfile.php/2692779/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf>. Acesso em: 03 out. 2023.</br>

## Histórico de versão

Versão  |   Data   | Descrição | Autor(es) | Revisor(es)
--------- | ------ | ------ | ---------- | ----------
1.0 | 19/09/2023| Criação do documento | [Milena Baruc](https://github.com/MilenaBaruc) | [Luis Eduardo](https://github.com/LuisMiranda10)|
