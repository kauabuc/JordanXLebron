# JordanXLebron
 O relatório feito dentro do power BI está disponível [aqui](https://app.powerbi.com/view?r=eyJrIjoiNzc2YjY3NDUtODRmOS00OTUwLTk3MzgtY2JkYTU3ODIwNGE1IiwidCI6IjBjMzkwMzgzLTc1NTQtNDdkOC05YmVkLTgxMDI3YzBjMjE4OCJ9).
## Processos 
Para esse projeto fiz os seguintes passos para chegar em uma conclusão. <br>
- Entender o problema (Debate)
- Coletar os dados
- Preparar e Transformar os dados
- Exploração incial das variáveis disponíveis
- Visualização dos Dados


## O problema 
Em meio a debate sobre NBA com um grande amigo meu, voltamos aquela velha discussão sobre quem foi melhor Michael Jordan ou Lebron James, pensando nisso, a motivaçao de ir atras de umas respostas para entender quem é o melhor através das estatisticas disponiveis dentro da Nba dos dois, utilizei os dados da NBA que estavam disponíveis dentro do site do [Basketball Reference](https://www.basketball-reference.com). 

## O que fez 
Entendi que para chegar a algum lugar seria necessário criar algumas perguntas sobre as métricas mais interessantes dentro da NBA, as que utilizei para chegar em minha conclusão foi. <br>
-Quem jogou mais?
-Quem tem mais vitórias?
-Quem tem mais títulos e prêmios?
-Quem performa melhor durante a temporada regular?
-Quem tem o melhor aproveitamento na temporada regular?
-Quem se sai melhor durante os playoffs?
-Quem tem as melhores/maiores marcas e feitos?


## Como fez
Dados são sempre necessários, para isso utilizei a fonte do Basketball Reference, que conta com os prêmios, jogos, totais e médias por temporada e o gamelog ao longo de suas carreiras. 
Para obter os mesmo, fiz uso de web scrapping utilizando python, que esta disponível dentro dos arquivos .ipnyb do jupyter notebook. <br>
Alguns tratamentos fiz diretamente em Python junto a biblioteca do pandas e outros eu fiz a limpeza e transformação dentro do Power BI. <br>
Após as transformaçoes foi necessario analisar tipos de dados e entender o que estava disponivel para trabalharmos com isso, caso fosse necessário a criaçao de alguma métrica a mais, foi criado utilizando o proprio power query.
No final montei um relatório com tudo que estava disponivel para isso utilizei o figma junto do Power bi. <br>
Montei minha analise baseada a partir das mensuracoes que obtive junto as metricas atraves dos dados.

## Conclusão
 - Mesmo o Lebron tendo mais temporadas que o Jordan, nao obteve a mesma quantidade que jordan mesmo nos principais como MVP, Finals MVP e o Campeonato da NBA com Jordan sendo superior em todos eles.
  - Puxando o quesito de longevidade, quem se sobresai é o lebron, visto que o mesmo já acumula mais de 20 temporadas e também conta com os maiores numeros em pontos, assistencias, rebotes e blocks perdendo apenas em roubos de bola (optei por não utilizar a atual juntos dos dados).
  - Tanto na temporada regular quanto nos playoffs, o Jordan conta um melhor aproveitamento tanto em pontos, como em vitórias o que mostra como no tempos de liga o quanto ele foi decisivo para o time dele.
  - Na questão das top marcos, Jordan conta apenas com a maior pontuação, mais arremessos convertidos e lances livres em uma partida, onde o Lebron leva a melhor em todo o resto. <br>
  - Apesar de todos dados, mensuração e análise é dficil definir quem é o melhor, e possivelmente sempre haverá um debate entre entre os dois. Visto que eles conseguiram atingir um nível de impacto dentro da liga que ninguem até o momento atingiu, porém com todo esse resultado e como respostas das minhas perguntas: Eu fico com o Michael Jordan como o melhor da Liga, por conta que ele realmente conta com números impressionantes, mais titulos, mais premios, melhor aproveitamento dentro do jogo e em finais mesmo tendo uma quantidade bem significativa a menos de jogos e temporadas em relação ao Lebron.
