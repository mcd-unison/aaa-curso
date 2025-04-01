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

1. Decidir que datos y que procesamiento de va a usar para entrada del algoritmo de aprendizaje. Aplicar toda la etapa de preprocesamiento de manera algoritmica a los datos de entrenamiento y guardarlos en un *data store* o en uno o varios archivos tipo *parquet*. Muy probablemente tengas que decidir en este momento como realizar la validación, si por *K fold validation* o solo una separación de datos de entrenamiento y validación 


2. Realizar una libreta de jupyter con el desarrollo de un modelo muy sencillo (regresión lineal si es un problema de regresión o regresión logística si es un problema de clasificación). Ajustar hiperparámetros. Usar los resultados para ganar comprensión en el problema y proponer métodos de preprocesamiento y selección de variables. Realizar curvas de aprendizaje, y proponer que se necesita (más datos, modelos más complicados, aumentar la regularización, ...). Presentar los resultados en función de las métricas establecidas en el proyecto anterior. 

3. Desarrollar una libreta donde se prueben con diferentes modelos y parámetros utilizando algún método de búsqueda de hiperparámetros y modelos, tal como `gridsearch` de `sklearn`, `optuna` o `hyperopt`. Presentar los resultados en forma de una tabla con los mejores resultados por modelo. Probar al menos los siguientes modelos:
    - Regresión lineal o logística
    - Máquinas de vectores de soporte
    - Bosques aleatorios
    - *Gradient boosting*
  
    Utilizar DagsHub si es un equipo de varios y definir claramente una nomenclatura para experimentos y para corridas de *mlflow*, así como los parámetros, métricas y artefactos que se van a guardar. Documentar el proceso, ya sea en la misma libreta o en un documento de información del proyecto, para que, si alguien continua con el proyecto, siga con los linemientos establecidos como buenas prácticas de desarrollo de modelos.
    
    Agregar curvas de aprendizaje y establecer porqué escoger un modelo sobre otro. Posiblemente el modelo con menor error de pérdida podría no ser el más adecuado si se consideran otros factores. 


4. ¿Los resultados son buenos? ¿Hay resultados de problemas similares reportados en la literatura? ¿El modelo final se podría poner en producción o que se necesitaría hacer para tener un modelo aceptable? Agrega un documento de tipo *markdown* donde respondas estas preguntas basandote en los resultados que se pueden consultar de tus experimentos registrados en *mlflow*, dejando claro cual va a ser el modelo a retener.

5. ¿Es suficiente o hay justificación para implementar un modelo neuronal con transferencia de aprendizaje? Si fuera el caso, revisa en la literatura y propón cual arquitectura, cual modelo base, y como habría que proceder de ser el caso. Si no es necesario, justifica las razones para quedarse con la solución obtenida. Escribe todo en un documento de tipo *markdown*.
