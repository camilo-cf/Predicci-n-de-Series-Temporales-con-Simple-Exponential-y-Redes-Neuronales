# Predicción de una serie temporal utilizando Simple Exponential Smoothing (SES) y Redes Neuronales Artificiales 

Utilizando tensorflow 2.x

En este trabajo se busca que una red neuronal elija el mejor valor de <img src="https://render.githubusercontent.com/render/math?math=\alpha"> de acuerdo a los valores de la serie tempora. Siguiendo la ecuacion:

<img src="https://render.githubusercontent.com/render/math?math=Y_{T} = \alpha y_{T-1} + (1-\alpha)y_{T-1}">


En donde, <img src="https://render.githubusercontent.com/render/math?math=0<=\alpha<=1"> es el valor de suavización (smoothing), <img src="https://render.githubusercontent.com/render/math?math=y"> son las observaciones de la serie temporal, <img src="https://render.githubusercontent.com/render/math?math=$Y_{T}$"> es el valor ponderado de las observaciones <img src="https://render.githubusercontent.com/render/math?math=$y_1, ..., y_T"> en la serie.

Ejemplo de la predicción:

<img src="Example_pred.png">


