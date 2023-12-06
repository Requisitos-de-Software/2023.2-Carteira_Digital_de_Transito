# Cenários 

## Introdução
Os cenários são reconhecidos como uma abordagem para a compreensão da interação entre o ambiente e o sistema, além de servirem como uma maneira de identificar e detalhar o funcionamento do 
software, descrevendo as situações ocorridas no ambiente, em consonância com as principais ações executadas fora do sistema. Além disso, os cenários auxiliam a esclarecer a conexão entre 
requisitos funcionais e não funcionais <a href="#REF1">^1^</a>.

## Metodologia 
A abordagem escolhida para descrever os cenários neste projeto consiste na utilização de texto estruturado. Essa abordagem valida-se da utilização de linguagem natural semi-estruturada
para melhor entendimento de cada cenário e validação dos requisitos por parte do cliente <a href="#REF2">^2^</a>. O formato desse modelo pode ser visualizado na Tabela 1.

Os cenários identificados foram determinados a partir de um compilado dos requisitos elicitados pelo métodos [$100](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/prioriza%C3%A7%C3%A3o/100/), [First Things First](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/prioriza%C3%A7%C3%A3o/first_things_first/) e [Three Level Scale](https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/elicita%C3%A7%C3%A3o/prioriza%C3%A7%C3%A3o/three_level_scale/), documentados na seção de priorização. 
A escolha dos cenários foram feitas com base nas principais funcionalidades priorizadas, que podem ser observadas pelos Cenários de 1 a 10 descritos abaixo e identificados pela sigla Cx, onde 
C significa cenário e X o número do cenário.

<center>
<p align="center"> Tabela 1: Modelo de cenários</p>

| Elemento   | Descrição                                                                                                        |
| ---------- | ------------------------------------------------------------------------------------------                       |
| Título     | Indica a temática do cenário, a que se refere.                                                                   |
| Objetivo   | Define a finalidade ou o propósito do cenário.                                                                   |
| Contexto   | Detalha as pré-condições, o local físico e o momento em que o cenário ocorre.                                    |
| Recursos   | Identifica os objetos passivos com os quais os atores interagem durante o cenário.                               |
| Ator       | Representa a pessoa ou a estrutura organizacional envolvida no cenário.                                          |
| Episódios  | Descreve as ações realizadas pelos atores, incluindo a participação de outros atores e a utilização de recursos. |
| Restrições | Menciona quaisquer limitações ou restrições que afetam os episódios do cenário.                                  |
| Exceção    | Especifica situações excepcionais que possam impedir a realizão do cenário.                                      |


<p align="center"> Fonte: Mayara Alves</p>
</center>

## Cenários identificados
### C01 - Obter versão digital da habilitação

A tabela 2 descreve o cenário que tem como objetivo obter a versão digital da habilitação.

<center>
<p align="center"> Tabela 2: C01 - Obter versão digital da habilitação </p>

|  Elemento  |         Descrição      |
|------------|-----------------------|
| Título     |  Obter versão digital da habilitação      |
| Objetivo   |  Obter versão digital da habilitação utilizando o aplicativo da Carteira Digital de Trânsito   |
| Contexto   | - Pré condição: ter o aplicativo instalado, possuí cadastro no .gov e ter habilitação <br> - Local: No carro <br> - Tempo: Aproximadamente 5 minutos |
| Recursos   | - Celular <br> - Aplicativo <br> - Internet                                         |
| Ator       |  Usuário com habilitação                                                         |
| Episódios  | - Usuário faz login no .gov <br> - Usuário clica em "Condutor" <br> - Usuário clica em "Habilitação" |
| Restrições |  Usuário não conseguir fazer login no .gov |
| Exceção    | - Aplicativo travou <br> - Celular sem bateria <br> - Celular não estar funcionando <br> - .gov está fora do ar       

<p align="center">Fonte: Mayara Alves</p>
</center>

### C02 - Obter versão digital do CRLV 
A tabela 3 descreve o cenário que tem como objetivo obter a versão digital do CRLV. 

<center>
<p align="center"> Tabela 3: C02 - Obter versão digital do CRLV </p>

|  Elemento  |         Descrição      |
|------------|-----------------------|
| Título     |  Obter versão digital do CRLV      |
| Objetivo   |  Obter versão digital do CRLV utilizando o aplicativo da Carteira Digital de Trânsito   |
| Contexto   | - Pré condição: ter o aplicativo instalado, possuí cadastro no .gov e ter habilitação <br> - Local: No carro <br> - Tempo: Aproximadamente 5 minutos |
| Recursos   | - Celular <br> - Aplicativo <br> - Internet                                         |
| Ator       |  Usuário que possua Veículo                                                         |
| Episódios  | - Usuário faz login no .gov <br> - Usuário clica em "Veículo" <br> - Usuário localiza o nome do seu veículo <br> - Usuário clica em "CRLV-e" |
| Restrições |  Usuário não conseguir fazer login no .gov |
| Exceção    | - Aplicativo travou <br> - Celular sem bateria <br> - Celular não estar funcionando <br> - .gov está fora do ar       

<p align="center"> Fonte: Mayara Alves</p>
</center>

### C03 - Consultar inflações do veículo 
A tabela 4 descreve o cenário que tem como objetivo consulta as inflações de um veículo . 

<center>
<p align="center"> Tabela 4: C03 - Consultar inflações do veículo  </p>

|  Elemento  |         Descrição      |
|------------|-----------------------|
| Título     |  Consultar inflações do veículo    |
| Objetivo   |  Consultar inflações do veículo utilizando o aplicativo da Carteira Digital de Trânsito   |
| Contexto   | - Pré condição: ter o aplicativo instalado, possuí cadastro no .gov <br> - Local: No carro <br> - Tempo: Aproximadamente 5 minutos |
| Recursos   | - Celular <br> - Aplicativo <br> - Internet                                         |
| Ator       |  Usuário que possua Veículo                                                         |
| Episódios  | - Usuário faz login no .gov <br> - Usuário clica em "Inflações" <br> - Usuário clica em "Por veículo" <br> - Usuário localiza e clica no nome do seu veículo<br> |
| Restrições |  Usuário não conseguir fazer login no .gov |
| Exceção    | - Aplicativo travou <br> - Celular sem bateria <br> - Celular não estar funcionando <br> - .gov está fora do ar       

<p align="center"> Fonte: Mayara Alves</p>
</center>

###  C04 - Acessar suporte do sistema (Assistente Virtual)

A tabela 5 descreve o cenário que tem como objetivo acessar o suporte do veículo . 

<center>
<p align="center"> Tabela 5: C04 - Acessar suporte do sistema  </p>

|  Elemento  |         Descrição      |
|------------|-----------------------|
| Título     |  Acessar suporte do sistema (Assistente Virtual)    |
| Objetivo   |  Acessar suporte do sistema (Assistente Virtual) utilizando o aplicativo da Carteira Digital de Trânsito   |
| Contexto   | - Pré condição: ter o aplicativo instalado, possuí cadastro no .gov <br> - Local: No carro <br> - Tempo: Aproximadamente 2 minutos |
| Recursos   | - Celular <br> - Aplicativo <br> - Internet                                         |
| Ator       |   Usuário do aplicativo                                                          |
| Episódios  | - Usuário faz login no .gov <br> - Usuário clica no canto da tela onde se localiza 3 linhas <br> - Usuário clica em "Assistente Virtual" <br> - Usuário escreve sua dúvida <br> |
| Restrições |  Usuário não conseguir fazer login no .gov |
| Exceção    | - Aplicativo travou <br> - Celular sem bateria <br> - Celular não estar funcionando <br> - .gov está fora do ar       

<p align="center"> Fonte: Mayara Alves</p>
</center>

### C05 - Acessar tutorial do aplicativo 

A tabela 6 descreve o cenário que tem como objetivo acessar o tutorial do aplicativo. 

<center>
<p align="center"> Tabela 6: C05 - Acessar tutorial do aplicativo  </p>

|  Elemento  |         Descrição      |
|------------|-----------------------|
| Título     |  Acessar tutorial do aplicativo    |
| Objetivo   |  Acessar tutorial do aplicativo utilizando o aplicativo da Carteira Digital de Trânsito   |
| Contexto   | - Pré condição: ter o aplicativo instalado, possuí cadastro no .gov <br> - Local: No carro <br> - Tempo: Aproximadamente 2 minutos |
| Recursos   | - Celular <br> - Aplicativo <br> - Internet                                         |
| Ator       |  Usuário do aplicativo                                                          |
| Episódios  | - Usuário faz login no .gov <br> - Usuário clica no canto da tela onde se localiza 3 linhas <br> - Usuário clica em "Tutorial" <br> |
| Restrições |  Usuário não conseguir fazer login no .gov |
| Exceção    | - Aplicativo travou <br> - Celular sem bateria <br> - Celular não estar funcionando <br> - .gov está fora do ar       

<p align="center"> Fonte: Mayara Alves</p>
</center>

### C06 - Realizar Transferência do Veículo

A tabela 7 descreve o cenário que tem como objetivo realizar transferência do veículo. 

<center>
<p align="center"> Tabela 7: C06 - Realizar Transferência do Veículo  </p>

|  Elemento  |         Descrição      |
|------------|-----------------------|
| Título     |  Realizar Transferência do Veículo    |
| Objetivo   |  Realizar Transferência do Veículo utilizando o aplicativo da Carteira Digital de Trânsito   |
| Contexto   | - Pré condição: ter o aplicativo instalado, possuí cadastro no .gov <br> - Local: No carro <br> - Tempo: Aproximadamente 5 minutos |
| Recursos   | - Celular <br> - Aplicativo <br> - Internet                                         |
| Ator       |  Usuário que possua veículo                                                         |
| Episódios  | - Usuário faz login no .gov <br> - Usuário clica em "Veículo" <br> - Usuário localiza e clica no nome do seu veículo<br> - Usuário clica em "Transferência"|
| Restrições | - Usuário não conseguir fazer login no .gov <br> - Usuário não está em uma UF que permite tal funcionalidade |
| Exceção    | - Aplicativo travou <br> - Celular sem bateria <br> - Celular não estar funcionando <br> - .gov está fora do ar       

<p align="center"> Fonte: Mayara Alves</p>
</center>

### C07 - Consultar histórico de inflações por inflator 

A tabela 8 descreve o cenário que tem como objetivo consultar histórico de inflação por inflator. 

<center>
<p align="center"> Tabela 8: C07 - Consultar histórico de inflações por inflator  </p>

|  Elemento  |         Descrição      |
|------------|-----------------------|
| Título     |  Consultar histórico de inflações por inflator    |
| Objetivo   |  Consultar histórico de inflações por inflator utilizando o aplicativo da Carteira Digital de Trânsito   |
| Contexto   | - Pré condição: ter o aplicativo instalado, possuí cadastro no .gov <br> - Local: No carro <br> - Tempo: Aproximadamente 5 minutos |
| Recursos   | - Celular <br> - Aplicativo <br> - Internet                                         |
| Ator       |  Usuário que possua veículo                                                         |
| Episódios  | - Usuário faz login no .gov <br> - Usuário clica em "Inflação" <br> - Usuário clica em "Por inflator" <br> - Usuário adiciona os filtros de sua preferência <br> - Usuário seleciona período da busca <br> - Usuário clica em "filtrar"|
| Restrições |  Usuário não conseguir fazer login no .gov <br> |
| Exceção    | - Aplicativo travou <br> - Celular sem bateria <br> - Celular não estar funcionando <br> - .gov está fora do ar       

<p align="center"> Fonte: Mayara Alves</p>
</center>

### C08 - Pesquisar informações sobre veículos por meio do número da placa. 

A tabela 9 descreve o cenário que tem como objetivo permitir a pesquisa de informações sobre veículos por meio do número da placa, este é um requisito que ainda não está implementado então o cenário visa mostrar uma simulação de como seria o cenário de uso com essa implementação. 

<center>
<p align="center"> Tabela 9: C08 - Pesquisar informações sobre veículos por meio do número da placa.  </p>

|  Elemento  |         Descrição      |
|------------|-----------------------|
| Título     |  Pesquisar informações sobre veículos por meio do número da placa.    |
| Objetivo   |   permitir a pesquisa de informações sobre veículos por meio do número da placa.  |
| Contexto   | - Pré condição: ter o aplicativo instalado, possuí cadastro no .gov <br> - Local: Em casa <br> - Tempo: Aproximadamente 5 minutos |
| Recursos   | - Celular <br> - Aplicativo <br> - Internet                                         |
| Ator       |  Usuário do aplicativo                                                       |
| Episódios  | - Usuário faz login no .gov <br> - Usuário clica em "Consultar Veículo" <br> - Usuário clica em "Pesquisar veículo por placa" <br> - Usuário inserir o número da placa do veículo <br> - Usuário clica em "pesquisar"|
| Restrições |  Usuário não conseguir fazer login no .gov <br> |
| Exceção    | - Aplicativo travou <br> - Celular sem bateria <br> - Celular não estar funcionando <br> - .gov está fora do ar       

<p align="center"> Fonte: Mayara Alves</p>
</center>

### C09 - Realizar o agendamento de serviços de manutenção e inspeção veicular. 

A tabela 10 descreve o cenário que tem como objetivo ser possível realizar o agendamento de serviços de manutenção e inspeção veicular, este é um requisito que ainda não está implementado então o cenário visa mostrar uma simulação de como seria o cenário de uso com essa implementação. 

<center>
<p align="center"> Tabela 10: C09 - Realizar o agendamento de serviços de manutenção e inspeção veicular.  </p>

|  Elemento  |         Descrição      |
|------------|-----------------------|
| Título     |  Realizar o agendamento de serviços de manutenção e inspeção veicular.   |
| Objetivo   |  Ser possível realizar o agendamento de serviços de manutenção e inspeção veicular  |
| Contexto   | - Pré condição: ter o aplicativo instalado, possuí cadastro no .gov <br> - Local: Em casa <br> - Tempo: Aproximadamente 5 minutos |
| Recursos   | - Celular <br> - Aplicativo <br> - Internet                                         |
| Ator       |  Usuário que possua CNH ou veículo                                                      |
| Episódios  | - Usuário faz login no .gov <br> - Usuário clica em "Serviços" <br> - Usuário clica em "Agendar um serviço" <br> - Usuário seleciona UF <br> - Usuário seleciona local de atendimento <br> - Usuário seleciona serviço que irá realizar <br> - Usuário clica em "pesquisar" <br> - Usuário seleciona data disponível <br> - Usuário clica em "agendar"|
| Restrições |  Usuário não conseguir fazer login no .gov <br> |
| Exceção    | - Aplicativo travou <br> - Celular sem bateria <br> - Celular não estar funcionando <br> - .gov está fora do ar       

<p align="center"> Fonte: Mayara Alves</p>
</center>

### C10 - Acessar a CNH(digital) mesmo sem acesso a internet. 

A tabela 11 descreve o cenário que tem como objetivo acessar a CNH(digital) mesmo sem acesso a internet, este é um requisito que ainda não está implementado então o cenário visa mostrar uma simulação de como seria o cenário de uso com essa implementação. 

<center>
<p align="center"> Tabela 11: C10 - Acessar a CNH(digital) mesmo sem acesso a internet. </p>

|  Elemento  |         Descrição      |
|------------|-----------------------|
| Título     | Acessar a CNH(digital) mesmo sem acesso a internet.   |
| Objetivo   | Ser possivel acessar a CNH(digital) mesmo sem acesso a internet.  |
| Contexto   | - Pré condição: ter o aplicativo instalado - Local: no carro <br> - Tempo: Aproximadamente 5 minutos |
| Recursos   | - Celular <br> - Aplicativo <br>                                        |
| Ator       |  Usuário que possua CNH                                                  |
| Episódios  | - Usuário clica em "Acesso sem internet" <br> - Usuário clica em "Documentos baixado" <br> - Usuário seleciona CNH <br>  Usuário clica em "pesquisar"|
| Restrições |  Usuário não ter baixado o documento. <br> |
| Exceção    | - Aplicativo travou <br> - Celular sem bateria <br> - Celular não estar funcionando     

<p align="center"> Fonte: Mayara Alves</p>
</center>

## Referências Bibliográfica
> 1. <a id="REF1"></a> ENHANCING A REQUIREMENTS BASELINE WITH SCENARIOS, Leite, Julio & Rossi, Gustavo & Balaguer, Federico & Maiorana, Vanesa & Kaplan, Gladys & Hadad, Graciela & Oliveros, Alejandro. (1997).. Requirements Engineering. 2. 184-198.
>
> 2. <a id="REF2"></a> CENÁRIOS: Rastreamento de Cenários. [S. l.]. Disponível em: <http://www-di.inf.puc-rio.br/~julio/bnncap3.pdf>.

## Bibliografia
> BARBOSA, Simone; DINIZ, Bruno. Interação Humano-Computador. Editora Elsevier, Rio de Janeiro, 2010.
>
> SIMPLENOTE. Cenários. Grupo Simplenote da disciplina Requisitos de Software, dispoível em: <https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/cenarios/>. Acesso em: 25 de outubro de 2023.


## 📑 Histórico de versões 

Versão  |   Data   | Descrição | Autor(es) | Revisor(es)
--------- | ------ | ------ | ---------- | ----------
`1.0` | 25/10/2023| Criação dos cenários  | [Mayara Alves](https://github.com/Mayara-tech) |[Breno Queiroz](https://github.com/brenob6)  |
`1.1` | 06/11/2023| Adicionando cenários de funcionalidade não implementadas  | [Mayara Alves](https://github.com/Mayara-tech) |[Breno Queiroz](https://github.com/brenob6)  |
`1.2` | 06/12/2023| Correção do artefato  | [Mayara Alves](https://github.com/Mayara-tech) |[Vinícius Mendes](https://github.com/Yaba)  |
