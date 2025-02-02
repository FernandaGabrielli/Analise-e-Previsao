# Previsão de Vendas com Random Forest

Este projeto tem como objetivo prever as vendas mensais de um produto utilizando aprendizado de máquina. A previsão é realizada utilizando um modelo de **Random Forest** e baseando-se em características temporais como ano, mês, dia da semana, trimestre, e a combinação ano/mês.

## Tecnologias Utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## O código realiza as seguintes etapas:
-Geração de Dados de Vendas: O código gera dados sintéticos de vendas mensais para um período de 36 meses, incorporando uma tendência crescente e sazonalidade.

-Pré-processamento dos Dados:
        Criação de novas colunas com características temporais como o ano, o mês, o dia da semana, o trimestre, e a combinação ano/mês.
        Normalização das vendas utilizando o MinMaxScaler para que as vendas fiquem no intervalo [0, 1].
-Divisão dos Dados:
        Os dados são divididos em conjuntos de treinamento (80%) e teste (20%).

-Treinamento do Modelo:
        O modelo Random Forest Regressor é treinado utilizando as características temporais como entrada e as vendas normalizadas como o alvo.

- Avaliação do Modelo:
        O modelo é avaliado utilizando métricas de erro como MAE (Erro Médio Absoluto), MSE (Erro Médio Quadrático) e R².
  
-    Previsão de Vendas:
        Uma função predict_sales é definida para prever as vendas para um determinado mês e ano, com base nas características temporais.


    



