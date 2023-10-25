# Léxicos
## Introdução

O Léxico é uma notação que se utiliza da descrição de termos, ou seja, é uma técnica que se propõe descrever símbolos de uma linguagem. E com isso, o seu principal objetivo no contexto na Engenharia de Requisitos é a classificação de palavras ou frases específicas de um contexto de negócio do sistema que esta sendo estudado. E nessa técnica cada símbolo será classificado em noção e impacto, onde noção é o significado do símbolo e o impacto é o uso real do símbolo na aplicação.

## Metodologia

Para utilizar esta técnica, utilizamos o aplicativo e em conjunto com o [glossário](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/glossario/) e as outras técnicas de elicitação feitas na etapa anterior, e durante este documento. Os membros que realizaram esta tarefa foram o Vinicius Mendes e Luis Miranda, onde separamos em média 6 léxicos para cada um, onde utilizaremos a representação de usuário do aplicativo sendo o "condutor". Baseamos nossa metodologia na anotação do Léxico Ampliado a Linguagem - LAL, onde as notações e os conceitos utilizados serão explicado na Tabela 1 e o template utilizado na Tabela 2.

<p align="center"><b>Tabela 01</b> - Regras tos tipos LAL.</p>


| Tipo | Noção </br> <<Quem é o sujeito?>> | Impacto </br> <<Quais ações executa>> |
|-----|------|----------|
|Verbo| Quem realiza, quando acontece e quais o procedimentos | Quais os reflexos da ação no ambiente e quais novos estados decorrentes |
|Objeto| Definir objetos e outros objetos com quais se relaciona | Ações que podem ser aplicadas ao objeto |
|Estado| O que significa e quais ações levaram a esse estado | Identificar outros estados e ações que podem decorrer deste estado |

<p align="center"><b>Fonte</b>: Autores.</p>

<br>
  
<p align="center"><b>Tabela 02</b> - Template do LAL.</p>

| **Símbolo** | **Tipo** | **Noção** | **Impacto** | **Dicionário** |
|---------|------|--------|----------|------------|
| Nome do léxico | Verbo/Objeto/Estado | Denotação do símbolo | Conotação do símbolo | Sinônimos |

<p align="center"><b>Fonte</b>: Autores.</p>

<br>

## Tabelas de Léxicos

A seguir, serão apresentados todas as descrições de léxicos identificados na aplicação,  seguindo a seguinte ordem: 
- Léxico de Estado 
- Léxico de Objeto
- Léxico de Verbo
   
Os representamos em um template da Tabela 2.

### L01 - Cadastro positivo está inativo

<p align="center"><b>Tabela 03</b> - Léxico 01 - Cadatro positivo está inativo (L01)</p>

| **Símbolo** | **Tipo** | **Noção** | **Impacto** | **Dicionário** |
|---------|------|--------|----------|------------|
| Cadastro positivo está inativo | Estado | - O condutor autorizou participar voluntariamente no cadastro positivo </br> - Ocorre quando o condutor quebrou alguma regra do código de trânsito brasileiro  | - O condutor fica sem receber benefícios do Cadastro Positivo </br> - O cadastro só ficará ativo quando o condutor resolver a causa da situação | Cadastro positivo está desligado, Cadastro positivo está desativado|

<p align="center"><b>Fonte</b>: <a href=https://github.com/yabamiah>Vinicius Mendes </p>

### L02 - Condutor

<p align="center"><b>Tabela 04</b> - Léxico 02 - Condutor (L02)</p>

| **Símbolo** | **Tipo** | **Noção** | **Impacto** | **Dicionário** |
|---------|------|--------|----------|------------|
| Condutor | Objeto | - Pessoa que conduz um automóvel </br> - Responsável pelo veículo </br> - Responsável pelas infrações </br> - Condutor pode ser alguém que queira visualizar sua CNH digital </br> - O condutor pode ser alguém que queira visualizar a CRLV digital | - O condutor pode baixar sua CNH digital </br> - O condutor pode visualizar seu histórico de emissões da CNH  </br> - O condutor pode adicionar os seus veículos </br> - O condutor pode consultar as suas infrações| Motorista, volante, guia, piloto |

<p align="center"><b>Fonte</b>: <a href=https://github.com/yabamiah>Vinicius Mendes </p>

### L03 - Infração

<p align="center"><b>Tabela 05</b> - Léxico 03 - Infração (L03)</p>

| **Símbolo** | **Tipo** | **Noção** | **Impacto** | **Dicionário** |
|---------|------|--------|----------|------------|
| Infração | Objeto | - Violação de alguma lei de trânsito </br> - A infração é visualizada pelo condutor | - O condutor pode visualizar as infrações cometidas filtrando infrator ou veículo </br> - O condutor pode visualizar a situação da infração </br> - O condutor pode visualizar o motivo da infração </br> - O condutor pode consultar o valor da infração a ser paga| Desobediência, Violação |

<p align="center"><b>Fonte</b>: <a href=https://github.com/LuisMiranda10>Luis Miranda </p>

 ### L04 - Sistema de Notificação Eletrônica

<p align="center"><b>Tabela 06</b> - Léxico 04 -Sistema de Notificação Eletrônica (L04)</p>

| **Símbolo** | **Tipo** | **Noção** | **Impacto** | **Dicionário** |
|---------|------|--------|----------|------------|
| Sistema de Notificação Eletrônica | Objeto | - Sistema de responsável por notificar infrações de trânsito aos proprietários de veículos | - Sistema que dá o direito a descontos no pagamento de multas de trânsitos | Sistema de Intimação Eletrônica |

<p align="center"><b>Fonte</b>: <a href=https://github.com/yabamiah>Vinicius Mendes </p>

### L05 - Restrições e Indicadores

<p align="center"><b>Tabela 07</b> - Léxico 05 - Restrições e Indicadores do veículo do condutor(L05)</p>

| **Símbolo** | **Tipo** | **Noção** | **Impacto** | **Dicionário** |
|---------|------|--------|----------|------------|
| Restrições e Indicadores |Objeto | - Responsável por mostrar se existe multa, restrição judicial, ocorrência de roubo, novo padrão na placa, comunicações de venda ativa e restrições do seu próprio veículo | - O propietário do veiculo pode consultar os indicadores e restrições de seu veiculo  | Limitações, Indicativos |

<p align="center"><b>Fonte</b>: <a href=https://github.com/LuisMiranda10>Luis Miranda </p>

### L06 - Tutorial

<p align="center"><b>Tabela 08</b> - Léxico 06 - Tutorial (L06)</p>

| **Símbolo** | **Tipo** | **Noção** | **Impacto** | **Dicionário** |
|---------|------|--------|----------|------------|
| Tutorial | Objeto | - Documentação para orientar o condutor ao utilizar o app | - Aumenta a eficiência de aprendizado do condutor  | Auxílio, Orientação, Documentação |

<p align="center"><b>Fonte</b>: <a href=https://github.com/LuisMiranda10>Luis Miranda </p>

### L07 - Cadastrar CNH

<p align="center"><b>Tabela 09</b> - Léxico 07 - Cadastrar CNH (L07)</p>

| **Símbolo** | **Tipo** | **Noção** | **Impacto** | **Dicionário** |
|---------|------|--------|----------|------------|
| Cadastrar CNH | Verbo | - Tarefa realizada pelo conduor </br> - Acontece quando o condutor precisa visualizar sua CNH pela primeira vez </br> - Condutor valida o cadastro com uma foto de sua CNH  | - O condutor consegue visualizar a sua CNH  | Registrar CNH, Inscrever CNH, Fichar CNH |

<p align="center"><b>Fonte</b>: <a href=https://github.com/yabamiah>Vinicius Mendes </p>

### L08 - Consultar infrações

<p align="center"><b>Tabela 10</b> - Léxico 08- - Consultar infrações (L08)</p>

| **Símbolo** | **Tipo** | **Noção** | **Impacto** | **Dicionário** |
|---------|------|--------|----------|------------|
| Consultar infrações | Verbo | - Tarefa realizada pelo condutor </br> - Acontece quando o condutor quer visualizar alguma infração </br> - Condutor pode escolher consultar infrações por condutor ou por veículo </br> - O sistema divide as infrações em categorias de vencidas, a vencer e pagas | - O condutor consegue verificar infrações vencidas e as não pagas </br> - O condutor pode visualizar uma infração </br> - O sistema pode gerar o boleto da infração </br> - O sistema pode gerar PDF da infração|  Examinar infrações, Estudar infrações, Ler infrações|

<p align="center"><b>Fonte</b>: <a href=https://github.com/yabamiah>Vinicius Mendes </p>
  
### L09 - Exames Toxicológicos

<p align="center"><b>Tabela 11</b> - Léxico 09- Consultar Exames Toxicológicos (L09)</p>

| **Símbolo** | **Tipo** | **Noção** | **Impacto** | **Dicionário** |
|---------|------|--------|----------|------------|
| Consultar Exames Toxicológicos | Verbo | - Tarefa realizada pelo condutor </br> - Acontece quando o condutor quer visualizar algum exame toxicológico feito pelo mesmo </br> - O sistema divide as informações sobre os exames toxicológicos em categorias de Data de Coleta, Prazo para nova realização de exame e Laboratórios credenciados| - O condutor consegue verificar infrações sobre os exames | Inspecionar Data de Coleta e Prazos para novo exame |

<p align="center"><b>Fonte</b>: <a href=https://github.com/LuisMiranda10>Luis Miranda </p>
  
### L010 - Visualizar recall

<p align="center"><b>Tabela 12</b> - Léxico 10 - Visualizar recall (L10)</p>

| **Símbolo** | **Tipo** | **Noção** | **Impacto** | **Dicionário** |
|---------|------|--------|----------|------------|
| Visualizar recall | Verbo | - Tarefa realizada pelo condutor </br> - Ocorre quando o condutor quer consultar se foi feita uma notificação de regularização do seu veículo | - O condutor consegue visualizar se o seu veículo recebeu algum recall </br>  | Verificar recall, Constatar recall, Captar recall |

<p align="center"><b>Fonte</b>: <a href=https://github.com/yabamiah>Vinicius Mendes </p>

### L11 - Visualizar CRLV

<p align="center"><b>Tabela 13</b> - Léxico 11 - Visualizar CRLV (L11)</p>

| **Símbolo** | **Tipo** | **Noção** | **Impacto** | **Dicionário** |
|---------|------|--------|----------|------------|
| Visualizar Licenciamento | Verbo | - Tarefa realizada pelo condutor </br> - Ocorre quando o condutor quer consultar o CRLV do seu veículo | - O condutor consegue visualizar as informações do licenciamento do seu carro </br> - O condutor consegue compartilhar seu licenciamento com outras pessoas </br> - O condutor consegue exportar seu licenciamento para algum tipo de arquivo selecionado </br> | Analisar informações sobre o veículo |

<p align="center"><b>Fonte</b>: <a href=https://github.com/LuisMiranda10>Luis Miranda </p>

### L12 - Transferência

<p align="center"><b>Tabela 14</b> - Léxico 12 - Transferência (L12)</p>

| **Símbolo** | **Tipo** | **Noção** | **Impacto** | **Dicionário** |
|---------|------|--------|----------|------------|
| Transferência | Verbo | - Tarefa realizada pelo condutor </br> - Ocorre quando o condutor quer transferir a propriedade de um veículo para outra pessoa | - O veículo se torna propriedade de outra pessoa  | Realiza troca de proprietário |

<p align="center"><b>Fonte</b>: <a href=https://github.com/LuisMiranda10>Luis Miranda </p>


## Bibliografia
> SERRANO, Milene. Requisitos – Aula 10. 2017. Apresentação de slides. Disponível em: [https://aprender3.unb.br/pluginfile.php/2523091/mod_resource/content/1/Aula%2010.pdf](https://aprender3.unb.br/pluginfile.php/2523091/mod_resource/content/1/Aula%2010.pdf). 

## Histórico de Versões

| **Versão** | **Data** | **Descrição** | **Autor** | **Revisor** |
|--------|------|------------|--------|--------|
|`1.0` | 20/10/2023 | Criação da página de Léxicos | [Vinícius Mendes](https://github.com/yabamiah) e [Luis Miranda](https://github.com/LuisMiranda10) | |
|`1.1` | 22/10/2023 | Modificação na tabela de Léxicos | [Vinícius Mendes](https://github.com/yabamiah) e [Luis Miranda](https://github.com/LuisMiranda10) | |
