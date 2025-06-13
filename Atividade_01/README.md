![image-20250607111725849](/home/marcio/snap/typora/96/.config/Typora/typora-user-images/image-20250607111725849.png)

Atividade 01

*Nome:* Márcio Constâncio Junior

1. Explique, com suas palavras, o que é _machine learning_?

Resposta: _Machine Learning_ é o campo da inteligência artificial na qual os sistemas são capazes de aprender sem ser programados diretamente, ou seja, ao invés de programar as instruções diretamente ao computador, este analisa os dados e aprende como deve operar com a finalidade de generalizar suas análises para novos dados. 


2. Explique o conceito de conjunto de treinamento, conjunto de validação e conjunto de teste em machine learning.

Resposta: O conjunto de treinamento é aquele usado com a finalidade de treinar um modelo, ou seja, o modelo usa este conjunto de dados para criar padrões. O conjunto de validação, por outro lado, é aquele usado para validar o modelo e avaliar as métricas para verificar o desempenho do modelo. Por fim, os dados de teste são aqueles no qual o modelo deve ser capaz de fazer previsões. Estes são dados nunca vistos pelo modelos anteriormente. 


3. Explique como você lidaria com dados ausentes em um conjunto de dados de treinamento.

Resposta: Depende do contexto. É importante investigar a razão para a existência desses dados ausentes. Às vezes o dado faltante pode decorrer de outra variável do conjunto de dados, dessa forma pode ser possível trabalhar com imputação de novos dados. Para esta abordagem existem vários métodos possíveis de serem usados, desde imputação da média, mediana, moda ou até mesmo um valor constante. Se a coluna com as variáveis faltantes não apresentar grande relação com a variável alvo, a exclusão dessa coluna também pode ser feita.


4. O que é uma matriz de confusão e como ela é usada para avaliar o desempenho de um modelo preditivo?

Resposta: A matriz de confusão é uma matriz que mostra a quantidade de erros e acertos de um modelo de classificação. De maneira bem genérica (para uma matriz com duas classes: positiva e o negativa) temos um campo para indicar o número de casos que são verdadeiros e foram previstos corretamente como verdadeiros (Verdadeiro Positivo), o número de casos que são verdadeiros mas foram previstos como falso (Falso Negativo), o número de casos que são falsos e foram corretamente previstos como falso (Verdadeiro Negativo) e o número de casos que são falsos mas foram previstos como verdadeiros (falso Positivo). 
A partir da matriz de confusão é possível obter novas métricas, tais como a acurácia, precisão, sensibilidade (_Recall_) e _F-Score_.

A acurácia mede a quantidade de acertos sobre o total de previsões.

A precisão mede a proporção de verdadeiros que foram corretamente indicados como verdadeiros dentre todas as indicações verdadeiras, ou seja, quantos desses verdadeiros realmente estão corretos. Suponha um exemplo em que 50 dados são verdadeiros, mas o modelos previu que 40 deles são verdadeiros, logo, a precisão é 40/50 = 80%

A sensibilidade mede a proporção de verdadeiros que foram corretamente indicados como verdadeiros dentre todas as indicações verdadeiras. Suponha o mesmo caso anterior em que 50 casos são verdadeiros, o modelo acertou 40 desses valores, errou 10 mas avaliou que 15 falsos eram verdadeiros. Ou seja, ele acertou 40 dentre os 55 que disse ser verdadeiros, logo, a sensibilidade é 40/55 = 72,7%

Por fim, o _f-score_ é a média harmônica entre as duas anteriores, adequado principalmente quando há desbalanceamento entre as classes. 


1. Em quais áreas (tais como construção civil, agricultura, saúde, manufatura, entre outras) você acha mais interessante aplicar algoritmos de machine learning?

Resposta: Eu tenho particular interesse em aplicar _Machine Learning_ na área de educação. Acredito que ter modelos capazes de avaliar o desempenho de cada aluno possibilitará a individualização do ensino para que cada aluno possa trabalhar baseado em suas dificuldades.