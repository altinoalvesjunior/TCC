# Applying Software Metric Thresholds for Detection of Bad Smells

Souza, P. P., Sousa, B. L., Ferreira, K. A., & Bigonha, M. A. (2017, September). Applying software metric thresholds for detection of bad smells. In Proceedings of the 11th Brazilian Symposium on Software Components, Architectures, and Reuse (pp. 1-10). doi: [10.1145/3132498.3134268](https://doi.org/10.1145/3132498.3134268)

## 1. Fichamento de Conteúdo

Inicialmente, o artigo retrata como as métricas de software são medidas quantitativas que permitem avaliar a qualidade dos projetos de software, permitindo com que, ocrram alterações durante o processo de desenvolvimento e/ ou manutenção do software, promovendo um sistemas com maior qualidade. Dessa forma, caracteriza-se estratégias na avaliação da qualidade de 12 sistemas orientados à objetos, dessa forma, utiliza-se um carálogo de 18 métricas de _software_, como por exemplo o _DIT_, originadas de 100 sistemas de _software_ para definir as estratégias de detecção de cinco _bad smells_, respectivamente: _Large Class_, _Long Method_, _Data Class_, _Feature Envy_ e _Refused Bequest_. O objetivo principal deste estudo é entender a eficácia da detecção de _bad smells_ utilizando-se estratégias fundamentada em valores de referência, além de ter como base os resultados gerados por ferramentas de detecção de bad smells, assim, comparando-se os resultados com aqueles obtidos pelas ferramentas JDeodorant e JSPiRIT. Nota-se então que, os resultados obtidos por meio das estratégias de detecção não são desarmònicos em relação àqueles obtidos pelas ferramentas de detecção de _bad smells_, ademais, notando maior proximidade de valores com a ferramenta JSpIRIT.

## 2. Fichamento Bibliográfico 

* _Bad Smells_ (Maus Cheiros) são estruturas de código as quaisprecisam ser refatoradas, ou seja, tem de ser melhorada sem alterar o comportamento externo observável, a fim de tornar o sistema de software mais fácil de evoluir e incluir novas funcionalidades.
* _Large Class_ (Classe Grandes) são classes de código que possuem muitas responsabilidades, processamentos e atributos. Normalmente, essas tendem a centralizar a inteligência do sistema.
* _Long Method_ (Método Longo) são métodos complexos, extensos e/ ou com diversas responsabilidades. Estes, durante o processo de evolução recebem mais e mais funcionalidades, tornando-os de difícil compreensão e manutenção.
* _Refused Request_ (Solicitação Recusada) são a subclasses que possuem herança de métodos e dados mas que os usam pouco. Assim, a classe filha despreza os atributos e métodos da superclasse.
* _Data Class_ (Classe de Dados) são classes que contém somente atributos e métodos _get()_ e _set()_. São classes que funcionam como um agregador de dados, geralmente sem processamento complexo. 
* _Feature Envy_ ("Inveja de Recurso") é um trecho de código pertencente a uma classe que está mais interessado nos dados e/ou processamentos de
outra classe. 

## 3. Fichamento de Citações 

* _"To evaluate the understandability of Copilot’s suggestions, we use SonarQube[28] to calculate cogni- tive complexity and cyclomatic complexity, which been shown to positively correlate with code understandability [9]."_
* _"Overall, we evaluate Copilot on 33 LeetCode questions in four different languages, totaling 132 queries. Out of Copilot’s 132 sug- gestions, our results show that Java suggestions have the highest likelihood to be correct."_
* _"Per language, 14 (42%), 19 (57%), 9 (27%), and 13 (39%) of Copilot solu- tions for Python, Java, JavaScript, and C respectively are accepted (i.e., pass all tests)."_
* _"GitHub’s internal evaluation of Copilot Python sug- gestions shows that Copilot achieved 43% correctness on the first try [11], which is similar to our Python results (42%)."_
* _"Copilot’s suggestions also have low complexity with no statistically significant differences between the complexity scores of the same solution in different languages. "_