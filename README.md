# Credit_Predict
Modelagem para classificação de risco de crédito.

Informações Gerais:

Versão 1:
-  Tratamento dos valores faltantes.
- Classificação da variável target (0 = sem atrasos; 1 = atrasos de 30 dias ou mais).
- Conversão dos valores em dias para ano.
- Tratamento das variáveis binárias (transformando para 0 e 1)
- Dataset de saída: df.credit.csv

Versão 2:
- Tratamento de valores faltantes.
- Remoção de valores duplicados.
- Remoção da constante (coluna inteira com o mesmo valor).
- Classificação da variável target (0 = sem atrasos; 1 = atrasos de 30 dias ou mais).
- Criação de uma variável que representa o tempo em meses de relacionamento, a partir do dataset dfy.
- Conversão dos valores em dias para ano.
- Tratamento das variáveis binárias (transformando para 0 e 1)
- Dataset de saída: df.creditII.csv

Versão 3:
- Classificação da variável target (0 = sem atrasos; 1 = atrasos de 60 dias ou mais).
- Tratamento das variáveis binárias (transformando para 0 e 1)
- Categorização das variáveis quantitativas em faixas de valores e transformação em dummies (n-1).
- Dataset de saída: df.creditIII.csv

Versão 4: 
- Tratamento de valores faltantes.
- Classificação da variável target (0 = sem atrasos; 1 = atrasos de 30 dias ou mais).
- Criação de uma variável que representa o tempo em meses de relacionamento, a partir do dataset dfy.
- Conversão dos valores em dias para ano.
- Tratamento das variáveis binárias (transformando para 0 e 1).
- Dataset de saída: df.creditIV.csv

Modelagem:
- Regressão logística binária (statsmodels)
- Apesar da acurácia ter se mostrado alta em todas as versões (acima de 80%), o modelo aprsentou baixo índice de sensitividade, dificultando a classificaçao dos maus pagadores (categoria 1).
