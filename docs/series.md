---
title: Series de tiempo con aprendizaje automñatico
subtitle: Curso Aprendizaje Automático Aplicado
layout: page
hero_image: https://github.com/mcd-unison/aaa-curso/raw/main/docs/img/intro-banner.jpeg
hero_darken: true
show_sidebar: false
---

## Presentaciones 

1. Empecemos por [esta presentación de los modelos ARIMA](https://github.com/mcd-unison/aaa-curso/raw/main/slides/ARIMA-slides.pdf) y [como podemos evaluarlos](https://github.com/mcd-unison/aaa-curso/raw/main/slides/eval-ARIMA-slides.pdf).

2. Sigamos con esta presentación de los [modelos con estacionalidad](https://github.com/mcd-unison/aaa-curso/raw/main/slides/SARIMA-slides.pdf)

3. El modelo [*prophet*](https://facebook.github.io/prophet/) de Facebook y una [breve presentación](https://github.com/mcd-unison/aaa-curso/raw/main/slides/prophet.pdf).

4. Modelos secuenciales con redes neuronales, con un [presentación de los modelos de base](https://github.com/mcd-unison/aaa-curso/raw/main/slides/RNN-slides.pptx)

## Recursos y librerías:

1. [Open Time Series](https://opentimeseries.com): Un portal con información reciente sobre series de tiempo. Librerías para python, libros, tutoriales y artículos con el estado del arte en el área.
   
2. [Nixtla](https://nixtlaverse.nixtla.io). Una serie de librerías para hacer pronóstico en series de tiempo que incluye:
   1. [StatsForcast](https://github.com/Nixtla/statsforecast): Métodos estadísticos (ARIMA y similares).
   2. [mlforcast](https://github.com/Nixtla/mlforecast): Un wraper para usar cualquier modelo con interfase tipo sklearn para realizar pronósticos en series de tiempo usando ventanas moviles.
   3. [NeuralForecast](https://github.com/Nixtla/neuralforecast): Modelos basados en redes neuronales, desde LSTM hasta TCN. 
   4. [HierarchicalForecast](https://github.com/Nixtla/hierarchicalforecast): Modelos jerárquicos para combinar con `StatsForcast`.
   5. [TimeGPT-1](https://docs.nixtla.io): Un LLM para predicción en series de tiempo basada en transformadores, usando transferencia de aprendizaje y modelos generativos.
   
3. [Neural Prophet](https://neuralprophet.com): La estructura de *Prophet* con modelos neuronales, basado en `pyTorch`.

4. La libreta [*Complete Guide on Time Series Analysis in Python*](https://www.kaggle.com/code/prashant111/complete-guide-on-time-series-analysis-in-python) en Kaggle es un buen recurso para ver el análisis y tratamiento inicial a una serie de tiempo antes de usar modelos de pronostico.
