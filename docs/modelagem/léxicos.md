# Léxicos
## Introdução

O Léxico é uma notação que se utiliza da descrição de termos, ou seja, é uma técnica que se propõe descrever símbolos de uma linguagem. E com isso, o seu principal objetivo no contexto na Engenharia de Requisitos é a classificação de palavras ou frases específicas de um contexto de negócio do sistema que esta sendo estudado. E nessa técnica cada símbolo será classificado em noção e impacto, onde noção é o significado do símbolo e o impacto é o uso real do símbolo na aplicação.

## Metodologia

Para utilizar esta técnica, utilizamos o aplicativo e em conjunto com o [glossário](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/glossario/) e as outras técnicas de elicitação feitas na etapa anterior, e durante este documento. Os membros que realizaram esta tarefa foram o Vinicius Mendes e Luis Miranda, onde separamos em média 6 léxicos para cada um, onde utilizaremos a representação de usuário do aplicativo sendo o "condutor". 

O princípio da circularidade é a propriedade dos léxicos convocarem entre si, sendo percebido durante a descrição dos léxicos, onde será possível visualizar a ligação entre eles em suas descrições. Baseamos nossa metodologia na anotação do Léxico Ampliado a Linguagem - LAL, onde as notações e os conceitos utilizados serão explicado na Tabela 1 e o template utilizado na Tabela 2.

<p align="center"><b>Tabela 01</b> - Regras dos tipos LAL.</p>


| Tipo | Noção </br> <<Quem é o sujeito?>> | Impacto </br> <<Quais ações executa>> |
|-----|------|----------|
|Verbo| Quem realiza, quando acontece e quais o procedimentos | Quais os reflexos da ação no ambiente e quais novos estados decorrentes |
|Objeto| Definir objetos e outros objetos com quais se relaciona | Ações que podem ser aplicadas ao objeto |
|Estado| O que significa e quais ações levaram a esse estado | Identificar outros estados e ações que podem decorrer deste estado |

<div align="center">
<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/LuisMiranda10">Luis Miranda</a> e <a href="https://github.com/yabamiah">Vinicius Mendes</a>, 2023</p></font>
</div>


<br>
  
<p align="center"><b>Tabela 02</b> - Template do LAL.</p>

| **Símbolo** | **Tipo** | **Noção** | **Impacto** | **Dicionário** |
|---------|------|--------|----------|------------|
| Nome do léxico | Verbo/Objeto/Estado | Denotação do símbolo | Conotação do símbolo | Sinônimos |

<div align="center">
<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/LuisMiranda10">Luis Miranda</a> e <a href="https://github.com/yabamiah">Vinicius Mendes</a>, 2023</p></font>
</div>

<br>

## Tabelas de Léxicos

A seguir, serão apresentados todas as descrições de léxicos identificados na aplicação,  seguindo a seguinte ordem: 
- Léxico de Estado 
- Léxico de Objeto
- Léxico de Verbo
   
Os representamos em um template da Tabela 2.

## Estado

Na tabela 3, está verificado os principais léxicos que estão classificados como "Estado"

### <a name=""></a>Tabela 03</b> - Léxicos classificados como:  "Estado"


| **Símbolo** | **Tipo** | **Noção** | **Impacto** | **Dicionário** | **Autor** |
|---------|------|--------|----------|------------|------------|
| <a id="L01">Cadastro positivo está inativo - (L01)</a> | Estado | - O <a href="#L02">condutor</a> autorizou participar voluntariamente no cadastro positivo </br> - Ocorre quando o condutor quebrou alguma regra do código de trânsito brasileiro  | - O <a href="#L02">condutor</a> fica sem receber benefícios do Cadastro Positivo </br> - O cadastro só ficará ativo quando o <a href="#L02">condutor</a> resolver a causa da situação | Cadastro positivo está desligado, Cadastro positivo está desativado|[Vinícius Mendes](https://github.com/yabamiah) | 

<font size="3"><p style="text-align: center"><b>Fonte:</b> Autor da descrição do léxico classificado como Estado, 2023</p></font>

## Objeto

Na tabela 4, está verificado os principais léxicos que estão classificados como "Objeto"

### <a name=""></a>Tabela 04</b> - Léxicos classificados como:  "Objeto"

| **Símbolo** | **Tipo** | **Noção** | **Impacto** | **Dicionário** | **Autor** |
|---------|------|--------|----------|------------|------------|
|<a id="L02"> Condutor (Usuário) - (L02)</a> | Objeto | - Pessoa que conduz um automóvel </br> - Responsável pelo veículo </br> - Responsável pelas [infrações](#L03) </br> - Condutor pode ser alguém que queira visualizar sua CNH digital </br> - O condutor pode ser alguém que queira visualizar a CRLV digital | - O condutor pode baixar sua CNH digital </br> - O condutor pode visualizar seu histórico de emissões da CNH  </br> - O condutor pode adicionar os seus veículos </br> - O condutor pode consultar as suas [infrações](#L03) | Motorista, volante, guia, piloto | [Vinícius Mendes](https://github.com/yabamiah) | 
| <a id="L03">Infração - (L03)</a> | Objeto | - Violação de alguma lei de trânsito </br> - A infração é visualizada pelo [condutor](#L02) | - O [condutor](#L02) pode visualizar as infrações cometidas filtrando infrator ou veículo </br> - O [condutor](#L02) pode visualizar a situação da infração </br> - O [condutor](#L02) pode visualizar o motivo da infração </br> - O [condutor](#L02) pode consultar o valor da infração a ser paga| Desobediência, Violação |[Luis Miranda](https://github.com/LuisMiranda10) |
| <a id="L04">Sistema de Notificação Eletrônica - (L04) </a>| Objeto | - Sistema responsável por notificar [infrações](#L03) de trânsito aos proprietários de veículos | - Sistema que dá o direito a descontos no pagamento de multas de trânsitos | Sistema de Intimação Eletrônica |[Vinícius Mendes](https://github.com/yabamiah) | 
| <a id="L05">Restrições e Indicadores do veículo do condutor - (L05) </a> |Objeto | - Responsável por mostrar ao [condutor](#L02) se existe multa, [infrações](#L03), restrição judicial, ocorrência de roubo, novo padrão na placa, comunicações de venda ativa e restrições do seu próprio veículo | - O [condutor](#L02) do veiculo pode consultar os indicadores e restrições de seu veiculo  | Limitações, Indicativos | [Luis Miranda](https://github.com/LuisMiranda10) |
| <a id="L06">Tutorial - (L06)</a> | Objeto | - Documentação para orientar o [condutor](#L02) ao utilizar o app | - Aumenta a eficiência de aprendizado do [condutor](#L02)  | Auxílio, Orientação, Documentação | [Luis Miranda](https://github.com/LuisMiranda10) |

<font size="3"><p style="text-align: center"><b>Fonte:</b> Autores das descrições dos léxicos classificados como Objeto, 2023</p></font>

## Verbo

Na tabela 5, está verificado os principais léxicos que estão classificados como "Verbo"

### <a name="">Tabela 05</a> - Léxicos classificados como:  "Verbo"

| **Símbolo** | **Tipo** | **Noção** | **Impacto** | **Dicionário** | **Autor** |
|---------|------|--------|----------|------------|------------|
| <a id="L07">Cadastrar CNH - (L07)</a> | Verbo | - Tarefa realizada pelo [condutor](#L02) </br> - Acontece quando o [condutor](#L02) precisa visualizar sua CNH pela primeira vez </br> - [condutor](#L02) valida o cadastro com uma foto de sua CNH  | - O [condutor](#L02) consegue visualizar a sua CNH  | Registrar CNH, Inscrever CNH, Fichar CNH | [Vinícius Mendes](https://github.com/yabamiah) | 
|<a id="L08"> Consultar infrações - (L08)</a> | Verbo | - Tarefa realizada pelo [condutor](#L02) </br> - Acontece quando o [condutor](#L02) quer visualizar alguma [infrações](#L03) </br> - [condutor](#L02) pode escolher consultar [infrações](#L03) por condutor ou por veículo </br> - O sistema divide as [infrações](#L03) em categorias de vencidas, a vencer e pagas | - O [condutor](#L02) consegue verificar [infrações](#L03) vencidas e as não pagas </br> - O [condutor](#L02) pode visualizar uma [infrações](#L03) </br> - O sistema pode gerar o boleto da [infrações](#L03) </br> - O sistema pode gerar PDF da [infrações](#L03) |  Examinar infrações, Estudar infrações, Ler infrações| [Vinícius Mendes](https://github.com/yabamiah) | 
| <a id="L09">Consultar Exames Toxicológicos - (L09)</a> | Verbo | - Tarefa realizada pelo [condutor](#L02) </br> - Acontece quando o [condutor](#L02) quer visualizar algum exame toxicológico feito pelo mesmo </br> - O sistema divide as informações sobre os exames toxicológicos em categorias de Data de Coleta, Prazo para nova realização de exame e Laboratórios credenciados| - O [condutor](#L02) consegue verificar [infrações](#L03) sobre os exames | Inspecionar exames toxicológicos | [Luis Miranda](https://github.com/LuisMiranda10) |
| <a id="L10">Visualizar recall - (L10)</a> | Verbo | - Tarefa realizada pelo [condutor](#L02) </br> - Ocorre quando o [condutor](#L02) quer consultar se foi feita uma notificação de regularização do seu veículo | - O [condutor](#L02) consegue visualizar se o seu veículo recebeu algum recall </br>  | Verificar recall, Constatar recall, Captar recall | [Vinícius Mendes](https://github.com/yabamiah) | 
| <a id="L11">Visualizar Licenciamento - (L11)</a> | Verbo | - Tarefa realizada pelo [condutor](#L02) </br> - Ocorre quando o [condutor](#L02) quer consultar o CRLV do seu veículo | - O [condutor](#L02) consegue visualizar as informações do licenciamento do seu carro </br> - O [condutor](#L02) consegue compartilhar seu licenciamento com outras pessoas </br> - O [condutor](#L02) consegue exportar seu licenciamento para algum tipo de arquivo selecionado </br> | Analisar informações sobre o veículo | [Luis Miranda](https://github.com/LuisMiranda10) |
| <a id="L12">Transferência - (L12)| Verbo</a> | - Tarefa realizada pelo [condutor](#L02) </br> - Ocorre quando o [condutor](#L02) quer transferir a propriedade de um veículo para outra pessoa | - O veículo se torna propriedade de outra pessoa  | Realiza troca de proprietário | [Luis Miranda](https://github.com/LuisMiranda10) |

<font size="3"><p style="text-align: center"><b>Fonte:</b> Autores das descrições dos léxicos classificados como Verbo, 2023</p></font>

## Bibliografia
> SERRANO, Milene. Requisitos – Aula 10. 2017. Apresentação de slides. Disponível em: [https://aprender3.unb.br/pluginfile.php/2523091/mod_resource/content/1/Aula%2010.pdf](https://aprender3.unb.br/pluginfile.php/2523091/mod_resource/content/1/Aula%2010.pdf). 

## Histórico de Versões

| **Versão** | **Data** | **Descrição** | **Autor** | **Revisor** |
|--------|------|------------|--------|--------|
|`1.0` | 20/10/2023 | Criação da página de Léxicos | [Vinícius Mendes](https://github.com/yabamiah) e [Luis Miranda](https://github.com/LuisMiranda10) |[Breno Queiroz](https://github.com/brenob6) |
|`1.1` | 22/10/2023 | Modificação na tabela de Léxicos | [Vinícius Mendes](https://github.com/yabamiah) e [Luis Miranda](https://github.com/LuisMiranda10) |[Breno Queiroz](https://github.com/brenob6)|
|`1.2` | 13/11/2023 | Atualizando a tabela de Léxicos | [Vinícius Mendes](https://github.com/yabamiah)  | [Luis Miranda](https://github.com/LuisMiranda10) |
|`1.3` | 05/12/2023 | Correção da página de Léxicos | [Luis Miranda](https://github.com/LuisMiranda10)  |  |
