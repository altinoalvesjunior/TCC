# An Empirical Evaluation of GitHub Copilot’s Code Suggestions

Nguyen, Nhan, and Sarah Nadi. "An Empirical Evaluation of GitHub Copilot's Code Suggestions." in 2022 IEEE/ACM 19th International Conference on Mining Software Repositories (MSR). IEEE, 2022. doi: [10.1145/3524842.3528470](https://doi.org/10.1145/3524842.3528470)

## 1. Fichamento de Conteúdo

O artigo caracteriza um estudo empírico de análise de resoluções de códigos, gerados por meio do _GitHub Copilot_. Esta, é uma ferramenta baseada em inteligência artificial que visa o _pair programming_, através do poder de análise estática, síntese de código e processamento de linguagem natural gerando código correspondente em diversas linguagens de programação por meio de uma descrição em linguagem natural. O estudo em questão, abrange o entendimento das legibilidade, compreensibilidade e corretude das soluçôes, calculando a complexidade cognitiva e complexidade ciclomática utilizando o SonarQube. Pensando-se na metodologia, selecionou-se 33 desafios de programação da plataforma _LeetCode_, onde contaram com resoluções em quatro linguagens de programação: C, Java, JavaScript e Python, totalizando assim 132 resoluções. Em relação aos resultados, nota-se que as 70% das questões resolvidas, o _Copilot_ produz uma solução a qual foi aceita em pelo menos em uma das linguagens, dessa forma Java possui a maior pontuação sendo 19 questões de 30 aceitas (57%) e JavaScript a menor 9 questões (27%). Além disso, as soluções propostas pela IA em Python apresenta a maior complidade ciclomática com 43 e complexidade cogniva de 42, sendo a solução com 43 instruções if para os números de entrada 2 a 43 e seus valores de retorno correspondentes. No geral, as sugestões do Copilot também são de baixa complexidade, sem diferenças estatisticamente significativas entre as pontuações de complexidade de uma mesma solução em diferentes idiomas.
 

## 2. Fichamento Bibliográfico 

* _GitHub Copilot_ é uma ferramenta desenvolvida pelo GitHub e OpenAI de inteligência artificial que auxilia desenvolvedores no processo de desenvolvimento, autocompletando código (páginas 1-5).
* _Pair Programming_ é uma técnica de desenvolvimento ágil, onde dois desenvolvedores trabalham juntos para resolução de código. Nessa, um desenvolvedor escreve o código enquanto o outro observa, revisando cada a solução proposta (páginas 1, 4 e 5).
* _LeetCode_ é uma plataforma ajudam pessoas interessadas por desenvolvimento de _software_ a aprimorar e expandir as habilidades de programação, principalmente para entrevistas técnicas (páginas 1-5).
* Complexidade Cognitiva  é uma medida para determinar quão difícil é entender uma unidade de código, dificultando assim sua manutenção (páginas 1-5).
* Complexidade Ciclomática é uma métrica usada para identificar a complexidade de um programa, onde, quantitativamente analisa-se número de caminhos linearmente independentes através do código-fonte de um programa (páginas 1,2 e 4).
* Inteligência Artificial (IA) refere-se a sistemas que atuam como a inteligência humana para realizar tarefas e se aprimorarem através das informações que coletam (páginas 1-5).

## 3. Fichamento de Citações 

* _"Uma possível razão é que, para realizar uma medição efetiva do software e elevar o uso de métricas para a tomada de decisão, é essencial associar a elas a definição de valores referência (do inglês, thresholds) significativos [5, 12, 13]."_
* _"JSpIRIT foi usada neste experimento para identificar a presença dos bad smells: Large Class, Long Method, Data Class, Feature Envy e Refused Bequest."_
* _"JDeodorant [36] é um plugin de código-fonte aberto para Eclipse que identifica quatro bad smells em software Java: God Class (similar a Large Class), God Method (similar a Long Method), Feature Envy e Switch Statement."_
* _"Quanto maior o valor de Recall para uma estratégia, maior é a sua capacidade de encontrar instâncias do bad smell que se propõe a achar."_
* _"Além disso, observa-se também que os resultados das estratégias de detecção são mais próximos dos resultados da JSpIRIT do que dos da JDeodorant."_
* _". Os resultados do estudo feito mostram que os valores referência foram significativamente eficazes no apoio à detecção de bad smells, com percentuais em geral altos para Recall e moderados para Precisão e F-measure."_