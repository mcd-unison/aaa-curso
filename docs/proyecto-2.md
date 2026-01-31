---
title: Proyecto integrador
subtitle: Modelo de aprendizaje
layout: page
hero_image: https://github.com/mcd-unison/aaa-curso/raw/main/docs/img/intro-banner.jpeg
hero_darken: true
show_sidebar: false
---


Esta es la parte más interesante de un proyecto de aprendizaje automático, y vamos a proceder parte por parte.

Para este proyecto se les pide:

1. Establecer en todo momento un método de trabajo integrando MLOps. Una manera de realizarlo es utilizando DagsHub, pero si tienen otra manera de hacerlo, adelante. Lo importante es que se mantenga un buen control de versiones, y que se registren los experimentos realizados con *mlflow* o con cualquier otro sistema de registro de experimentos. Existen otras opciones comerciales como *Weights & Biases*, *Neptune.ai*, *Comet.ml*, *ray.io*, etc. Si utilizan alguna de estas plataformas, asegúrense de que todo el equipo pueda acceder a los resultados. Igualmente pueden usar la versión abierta de *mlflow* y guardar la base de datos de experimentos en un servidor compartido con versionado de datos con DVC (en combinación con *git*).

2. Decidir que datos y que procesamiento de va a usar para entrada del algoritmo de aprendizaje. Aplicar toda la etapa de preprocesamiento de manera algorítmica a los datos de entrenamiento y guardarlos en un *data store* o en uno o varios archivos tipo *parquet*. Muy probablemente tengas que decidir en este momento como realizar la validación, si por *K fold validation* o solo una separación de datos de entrenamiento y validación 


3. Realizar un modelo muy sencillo (regresión lineal si es un problema de regresión o regresión logística si es un problema de clasificación). Ajustar hiperparámetros. Usar los resultados para ganar comprensión en el problema y proponer métodos de preprocesamiento y selección de variables. Realizar curvas de aprendizaje, y proponer que se necesita (más datos, modelos más complicados, aumentar la regularización, ...). Presentar los resultados en función de las métricas establecidas en el proyecto anterior. 

4. Probar diferentes modelos y parámetros utilizando algún método de búsqueda de hiperparámetros y modelos, tal como `gridsearch` de `sklearn` u `optuna`. Presentar los resultados en forma de una tabla con los mejores resultados por modelo. Probar al menos los siguientes modelos:
    - Regresión lineal o logística
    - Máquinas de vectores de soporte
    - Bosques aleatorios
    - *Gradient boosting*
  
    Guardar toda la información en el registro de experimentos. Agregar métricas significativas y curvas de aprendizaje.

5. ¿Los resultados son buenos? ¿Hay resultados de problemas similares reportados en la literatura? ¿Porqué escoger un modelo sobre otro? ¿El modelo final se podría poner en producción? Agregar un documento de tipo *markdown* con la respuesta a estas preguntas basandose en los resultados que se pueden consultar de tus experimentos registrados, dejando claro cual va a ser el modelo a retener.

6. ¿Es suficiente o hay justificación para implementar un modelo neuronal con transferencia de aprendizaje? ¿Justificaría el uso de una LLM? Si fuera el caso, revisa en la literatura y propón cual arquitectura, cual modelo base, y como habría que proceder de ser el caso. Si no es necesario, justifica las razones para quedarse con la solución obtenida. Escribe todo en un documento de tipo *markdown*.
