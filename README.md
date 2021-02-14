# Airbnb_PrevisaoPrecoEstadia
Aplicação em Data Science - Previsão de Preços de Estadia no Rio de Janeiro

Respostas

a. Como foi a definição da sua estratégia de modelagem?

A estratégia para a elaboração da modelagem foi baseado num processo de ciclo de vida de um projeto de data science, desde o entendimento do problema até a avaliação do modelo obtido, conforme as métricas de desempenho.

b. Como foi definida a função de custo utilizada?

A função de custo definida foi a utilizada pela técnica de floresta randômica ou random forest regressor, em inglês. Esta definição foi realizada com base em comparações de técnicas comuns para o problema de regressão, onde ocorre a modelagem preditiva para valores numéricos, como foi o caso da varíavel resposta preço.

c. Qual foi o critério utilizado na seleção do modelo final?

O modelo final (random forest regressor) foi escolhido devido ao seu desempenho ter sido maior do que os demais nas etapas de validação, treinamento e teste, sobretudo sobre a baseline utilizada.

d. Qual foi o critério utilizado para validação do modelo? Por que escolheu utilizar este método?

A validação foi realizada com base nas métricas de R² (r-quadrado ou coeficiente de determinação), MSE (erro quadrático médio) e MAE (erro médio absoluto), muito comuns para avaliar o desempnheo de aprendizado supervisionado com regressão.

O R² apresenta a medida de quanto do modelo gerado representa a variabilidade da variável resposta (preço), o qual se deseja ter o maior valor possível (limitado à 1), enquanto que os MSE e MAE apresentam o erro médio mínino atingido, o qual se deseja minimizar ao máximo, utilizados em problemas de otimização. A diferença básica entre estes últimos dois é que o primeiro sofre um aumento consideravelmente maior na presença de outliers no dataset, apesar de estar representado na mesma unidade que a última se apresenta.

e. Quais evidências você possui de que seu modelo é suficientemente bom?

Apesar do modelo com maior desempenho ter obtido um R² bem menor na etapa de teste, em torno de 30%, comparado com o obtido na etapa de treinamento, em torno de 90%, este se apresentou melhor do que os demais modelos em todas as etapas e com base em todas as medidas de desempenho avaliadas, além de se mostrar mais eficaz do que a própria baseline gerada na etapa de avaliação.
