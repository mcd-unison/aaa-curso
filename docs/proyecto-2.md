---
title: Proyecto integrador
subtitle: Modelo de aprendizaje
layout: page
hero_image: https://github.com/mcd-unison/aaa-curso/raw/main/docs/img/intro-banner.jpeg
hero_darken: true
show_sidebar: false
---

Esta es la parte más interesante de un proyecto de aprendizaje automñatico, y vamos a proceder parte por parte.

Para este proyecto se les pide:

1. Separar un conjunto de datos de prueba. Y con el conjunto de datos de entrenamiento decidir si se va a utilizar una estrategia de *K fold validation* o solo una separación de datos de entrenamiento y validación. Hacerlo en una libreta o un script y guardar los datos en datos procesados como archivos *parquet*, o un un *data store*.

2. Desarrollar una libreta de jupyter con el desarrollo de un modelo muy sencillo (regresión lineal si es un problema de regresión o regresión logística si es un problema de clasificación). Ajustar hiperparámetros. Usar los resultados para ganar comprensión en el problema y proponer métodos de preprocesamiento y selección de variables. Realizar curvas de aprendizaje, y proponer que se necesita (más datos, modelos mñas complicados, aumentar la regularización, ...). Presentar los resultados en función de las métricas establecidas en el proyecto anterior.

3. Desarrollar una libreta donde se prueben con diferentes modelos y parámetros utilizando algun método de busqueda de hiperparámetros y modelos, tal como `gridsearch` de `sklearn`, `optuna` o `hyperopt`. Presentar los resultados en forma de una tabla con los mejores resultados por modelo. Probar al menos los siguientes modelos:
    - Regresión lineal o logística
    - Máquinas de vectores de soporte
    - Bosques aleatorios
    - *Gradient boosting*
    - K vecinos próximos (solo si aplica)
    Agregar curvas de aprendizaje y establecer porqué escogería uno un modelo. Posiblemente el modelo con menor error de pérdida podrñia no ser el mñas adecuado si se consideran otros factores.

4. Si aplica, usar un modelo profundo preentrenado para la solución, o un LLM utilizando el método de *one shoot learning* o *few shoot learning*. En muchas ocasiones este tipo de modelos no son convenientes debido a su costo, o al tiempo de latencia que tienen. Pero este es un buen momento para practicar y hacer cosas para aprender como se hacen. Si no aplica justificarlo.

5. ¿Los resultados son buenos? ¿Hay resultados de problemas similares reportados en la literatura? ¿El modelo final se podría poner en producción o que se necesitaría hacer para tener un modelo aceptable? Agrega un documento donde respondas estas preguntas, dejando claro cual va a ser el modelo a retener.
