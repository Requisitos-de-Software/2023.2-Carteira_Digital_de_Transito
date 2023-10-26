# First Things First

## Introdução

Dado que a priorização de requisitos é um processo crítico que envolve a classificação e seleção dos requisitos do sistema de acordo com sua importância, impacto e viabilidade, a abordagem _First Things First_ visa enfatizar a importância de focar nas tarefas e atividades mais cruciais e significativas antes de se dedicar a tarefas menos importantes. Assim, temos como ideia central que para ter mais prosutividade deve-se identificar e dedicar tempo significativo às atividades que tem mais impacto no projeto.

## Metodologia

A seguir, apresentamos as pessoas que contribuíram para o desenvolvimento desta abordagem, com seus nomes relacionados na Tabela 1:

- *Mediador*: Encarregado de expor os requisitos listados;
-  *Usuário*: Encarregado de classificar benefícios e penalidades na implementação de cada requisito;
- *Desenvolvedor*: Encarregado de classificar custos e riscos na implementação de cada requisito.

<center>

Tabela 1 - Participantes

|**Nome**                                        |**Função**          |
|:----------------------------------------------:| :----------------: |
|[Milena Baruc](https://github.com/MilenaBaruc)  | Mediador           |
|[Luis Eduardo](https://github.com/LuisMiranda10)| Desenvolvedor      |
|[Victor Hugo](https://github.com/ViictorHugoo)  | Usuário            |

**Fonte:** [Milena Baruc](https://github.com/MilenaBaruc)
 
</center>

Foram realizadas duas reuniões na plataforma Teams, como podemos ver na tabela 2:
- Entre a Mediadora e o Desenvolvedor, na data de 25/10/23 às 20h. [Gravação da reunião](https://youtu.be/hrjwQEOtv-c).
- Entre a Mediadora e o Cliente, na data de 25/10/23 às 20:30. [Gravação da reunião](https://youtu.be/K3dSjsBsxDA).

<center>

Tabela 2 - Cronograma reuniões

| Data | Hora | Local | Assunto | Participantes |
| :--: | :--: | :---: | ------- | ------------ |
| 25/10/2023 | 21:20h | Teams | Classificar benefícios e penalidades na implementação de cada requisito | [Milena Baruc](https://github.com/MilenaBaruc) e [Victor Hugo](https://github.com/ViictorHugoo)| 
| 25/10/2023 | 21:40h | Teams | Classificar custos e riscos na implementação de cada requisito | [Milena Baruc](https://github.com/MilenaBaruc) e [Luis Eduardo](https://github.com/LuisMiranda10)| 

**Fonte:** [Milena Baruc](https://github.com/MilenaBaruc)
 
</center>

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
* **Benefício Relativo**: peso 2
* **Penalidade Relativa**: peso 1
* **Custo Relativo**: peso 1
* **Risco Relativo**: peso 0,5

Para a produção da tabela 3, foi utilizado os dados da tabela 2 em <a href="../requisitos_elicitados.md"> requisitos elicitados </a>.

<center>

Tabela 3 - Resultado da priorização

![Tabela FTF](/docs/assets/TabelaFTF.jpg)

**Fonte:** [Milena Baruc](https://github.com/MilenaBaruc)

</center>

## Bibliografia

> SERRANO, Milene; SERRANO, Maurício. Requisitos - Aula 07: Elicitação, Modelagem e Análise. Apresentação Power Point. Disponível em: <https://aprender3.unb.br/pluginfile.php/2692779/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf>. Acesso em: 03 out. 2023.</br>

## 📑 Histórico de versões:

| Versão |    Data    |    Descrição         | Autor(es)  |    Revisor(es) |                  
|:-----: | :--------: | :-------------:      | :--------: | :-------------:| 
| `1.0` | 19/09/2023| Criação do documento | [Milena Baruc](https://github.com/MilenaBaruc) | [Luis Eduardo](https://github.com/LuisMiranda10)|
| `2.0` | 20/10/2023| Adição do Cronograma e Link da gravação | [Luis Eduardo](https://github.com/LuisMiranda10) | [Mayara Alves](https://github.com/Mayara-tech) |
| `2.1` | 25/10/2023| Arrumando erros apresentação | [Milena Baruc](https://github.com/MilenaBaruc) | [Mayara Alves](https://github.com/Mayara-tech) |
| `2.2` | 25/10/2023| Adicionando reuniões e cronograma | [Milena Baruc](https://github.com/MilenaBaruc) | [Mayara Alves](https://github.com/Mayara-tech)|
| `2.3` | 25/10/2023| Adicionando tabela priorização | [Milena Baruc](https://github.com/MilenaBaruc) | [Mayara Alves](https://github.com/Mayara-tech)|

