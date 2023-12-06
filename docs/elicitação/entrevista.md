# Entrevista

## Introdução 
A entrevista é uma das técnicas mais utilizadas de coleta de dados e levantamento de requisitos. Trata-se de uma conversa guiada por um roteiro de perguntas ou tópicos, na qual um entrevistador busca obter informação de um entrevistado (Seidman^1^, 1998). A entrevista permite uma interação direta com os usuários para compreender suas necessidades e expectativas em relação ao sistema.

## Metodologia

A metodologia adotada para a elaboração deste artefato envolveu uma combinação de métodos de coleta e análise de dados, com foco na compreensão da experiência do usuário com o aplicativo da Carteira Digital de Trânsito e na elicitação de requisitos para aprimoramento do mesmo.

A entrevista foi realizada no dia 20/10/2023 e contou com a participação de um usuário do aplicativo da Carteira Digital de Trânsito - Wycthor da Silva do Nascimento, tendo como entrevistadora [Mayara Alves](https://github.com/Mayara-tech) como pode ser visto na tabela 1 que diz respeito ao cronograma executado na entrevista. Antes do início da entrevista, o participante foi apresentado ao [Termo de Consentimento](https://github.com/Requisitos-de-Software/2023.2-Carteira_Digital_de_Transito/blob/main/docs/elicita%C3%A7%C3%A3o/Termo%20de%20Consentimento.pdf) ao Participante e recebeu uma breve explicação sobre o objetivo do projeto.

Para coletar dados, foi realizada uma revisão de literatura abrangente relacionada ao tema da Carteira Digital de Trânsito. Isso incluiu a análise de estudos anteriores, relatórios governamentais, documentos técnicos e artigos acadêmicos relevantes. Essa revisão permitiu a obtenção de uma base sólida de conhecimento sobre o assunto para elaboração das perguntas realizadas na entrevista.

Foi conduzida uma entrevista semiestruturada com Wycthor da Silva do Nascimento. A entrevista foi projetada com um roteiro de 9 perguntas abertas, elaborado para explorar a experiência do usuário e suas necessidades em relação ao aplicativo. A plataforma Meet foi utilizada para a gravação e condução da entrevista.

Após a coleta de dados, as respostas fornecidas pelo participante durante a entrevista foram transcritas e submetidas a uma análise rigorosa. O objetivo dessa análise foi identificar padrões, tendências e insights relevantes relacionados ao uso da Carteira Digital de Trânsito. Esses insights serviram como base para a elicitação de requisitos funcionais e não funcionais que podem contribuir para o aprimoramento do aplicativo.

### Cronograma executado

<center>

**Tabela 1** - Cronograma executado - Entrevista (Elicitação de Requisitos)

| Data | Descrição | entrevistadora |  Entrevistado | Horário | Entrevista
| --- | ---------------------| ---------------------- |---------------------| ---------------------- | ---------------------------- |
| 20/10/2023 | Entrevista (Elicitação de Requisitos)  | [Mayara Alves](https://github.com/Mayara-tech) | Wycthor da Silva do Nascimento | 20h10/20h28  | [link](https://www.youtube.com/embed/8tAfHlzLwtk?si=nHRmftMY9v9X2Yhy)

Fonte: [Mayara Alves](https://github.com/Mayara-tech) 
</center>

## Entrevista

<p style="text-align: center"><a href="https://www.youtube.com/watch?v=e7p8hn9R-GQ" target="blanket">Vídeo da Entrevista</a></p>

<p style="text-align: center"><iframe width="560" height="315" src="https://www.youtube.com/embed/8tAfHlzLwtk?si=nHRmftMY9v9X2Yhy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe></p>


## Roteiro 
A estrutura de entrevista utilizada foi a de:

- Apresentação - na qual a entrevistadora se apresenta e explica o objetivo da entrevista
- Período de aquecimento -  no qual são feitas perguntas de fácil resposta, como dados demográficos e perfil do usuário;
- Parte principal da entrevista - na qual o roteiro é explorado;
- Um período de quebra gelo - para desfazer alguma tensão que tenha surgido;
- Conclusão - na qual a entrevistadora agradece ao participante pelo seu tempo, desliga a gravação indicando que a entrevista terminou.

Na Tabela 1, é possível contemplar o roteiro empregado para a condução da entrevista.

<p align="center"><b>Tabela 1.</b> Roteiro da entrevista  </p>
  
Página  | Pergunta 
:---------: | :------
Requisitos Funcionais | 1. O que você acha das funcionalidades do aplicativo de carteira digital de trânsito? <br> 2. Quais funcionalidades você acredita que um aplicativo de carteira digital de trânsito deve incluir? <br> 3. Quais tipos de documentos e informações você gostaria de poder armazenar na carteira digital de trânsito? <br> 4. Você gostaria que o aplicativo oferecesse notificações ou lembretes relacionados a prazos de renovação, pagamento de multas, ou outros eventos importantes de trânsito?
Requisitos de Usabilidade | 5. Como você descreveria a experiência de usuário ideal ao usar a carteira digital de trânsito? <br> 6. . Que tipo de informações ou guias você gostaria que o aplicativo fornecesse para ajudar os usuários a entender como usá-lo? <br> 7. Você acha importante que o aplicativo seja fácil de usar para pessoas de todas as idades?
Requisitos da Plataforma | 8. Deve haver uma versão para desktop/web do aplicativo, ou apenas uma versão móvel é suficiente?
Considerações finais | 9. Você tem alguma outra consideração importante em relação aos requisitos do aplicativo de carteira digital de trânsito? <br>


## Requisitos Elicitados 
Após a realização da entrevista com o usuário do aplicativo da Carteira Digital de Trânsito, foi possível elicitar os requisitos apresentados na Tabela 2. Onde cada requisito é classificado por um sigla formada por "ENT" + um número, em que "ENT" é um sigla de entrevista, e para representar o tipo do requisito, será usado as siglas "RF" ou "RNF", que representam o tipo do requisito funcional ou não funcional, além disso também será representado se já há uma implementação do requisito no aplicativo.

<p align="center"><b>Tabela 2</b> - Requisitos elicitados na Entrevista.</p>


| **Identificador** | **Requisitos** | **Tipo** | **Implementado** |
|-------------------|----------------|---------|------------------|
| ENT01             | O aplicativo deve fornecer uma versão digital da carteira nacional de habilitação (CNH). | RF | Implementado |  
| ENT02             | O aplicativo deve incluir um FAQ de perguntas frequentes. | RF | Implementado |
| ENT03             | O aplicativo deve permitir a pesquisa de informações sobre veículos por meio do número da placa. | RF | Não implementado |
| ENT04             | Deve ser possível cadastrar e gerenciar múltiplos veículos na carteira digital. | RF | Implementado |
| ENT05             | O aplicativo deve disponibilizar informações em tempo real sobre condições de tráfego, acidentes e congestionamentos. | RF | Não implementado |
| ENT06             | Deve ser possível configurar alertas de vencimento da CNH e do licenciamento do veículo. | RF | Não implementado |
| ENT07             | O aplicativo deve oferecer uma opção de backup seguro de todos os documentos e dados do usuário. | RF | Não implementado |
| ENT08             | Deve ser possível compartilhar documentos digitais da CNH com terceiros, como autoridades de trânsito. | RF | Não implementado |
| ENT09             | Deve ser possível realizar o agendamento de serviços de manutenção e inspeção veicular. | RF | Não implementado |
| ENT10             | O aplicativo deve notificar o usuário sobre recalls e informações importantes do fabricante do veículo. | RF | Não implementado |
| ENT11             | Deve ser possível obter informações sobre as normas de trânsito, regulamentações e penalidades em vigor. | RF | Não implementado |
| ENT12             | O aplicativo deve incluir um chat com atendente para eventuais dúvidas | RF | Não implementado |
| ENT13             | O aplicativo deve mostrar informações sobre a pontuação e penalidade da multa | RF | Não implementado |


<p align="center"><b>Fonte</b>: <a href="https://github.com/Mayara-tech">Mayara Alves.</a></p>


## Referência Bibliográfica
>SEIDMAN, I. Interviewing as Qualitative Research: a guide for researchers in Education
and the Social Sciences. New York, NY: Teachers College Press, 1998

## Bibliografia
>ELICITAÇÃO DE REQUISITOS, PUC-Rio.  Disponível em: https://www.maxwell.vrac.puc-rio.br/15760/15760_3.PDF <br>
> MARTINS L.E.G. Uma Metodologia de Elicitação de Requisitos de Software Baseada na Teoria da Atividade.  Unicamp, 2001. Disponível em: file://home/yaba/Downloads/Martins_LuizEduardoGalvao_D.pdf. <br>
>MEDEIROS M. E. Aula 5 - Requisitos de Software - Conceitos e Técnicas de Elicitação.  Universidade de São Paulo, 2006. Disponível em: https://edisciplinas.usp.br/pluginfile.php/7993139/mod_resource/content/1/05%20-%20Requisitos%20de%20Software%20-%20Conceitos%20e%20T%C3%A9cnicas%20de%20Elicita%C3%A7%C3%A3o.PDF <br>


## 📑 Histórico de versões 

Versão  |   Data   | Descrição | Autor(es) | Revisor(es)
--------- | ------ | ------ | ---------- | ----------
| `1.0` | 20/10/2023| Entrevista  | [Mayara Alves](https://github.com/Mayara-tech)  | [Vinícius Mendes](https://github.com/yabamiah) |
| `1.1` | 21/11/2023 |Correção Verificação Grupo1 - Correção da Metodologia | [Altino Arthur](https://github.com/arthurrochamoreira) | [Vinícius Mendes](https://github.com/yabamiah) |
| `1.2` | 06/12/2023 |Correção do Artefato | [Mayara Alves](https://github.com/Mayara-tech) | [Vinícius Mendes](https://github.com/yabamiah) |
