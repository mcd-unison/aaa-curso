---
title: Operaciones de aprendizaje máquina (MLOps)
subtitle: Curso Aprendizaje Automático Aplicado
layout: page
hero_image: https://github.com/mcd-unison/aaa-curso/raw/main/docs/img/intro-banner.jpeg
hero_darken: true
show_sidebar: false
---

## Presentaciones

1. [Introducción a las MLOps](https://github.com/mcd-unison/aaa-curso/raw/main/slides/MLOps-intro.pdf)
   
2. [Preprocesamiento de datos](https://github.com/mcd-unison/aaa-curso/raw/main/slides/mlops-preprocesamiento.pdf)

3. [Selección de modelos de ML](https://github.com/mcd-unison/aaa-curso/raw/main/slides/mlops-seleccion.pdf)

4. [Despliegue de modelos de ML](https://github.com/mcd-unison/aaa-curso/raw/main/slides/mlops-deploy.pptx)

5. [Monitoreo de la calidad de los modelo](https://github.com/mcd-unison/aaa-curso/raw/main/slides/mlops-monitor.pptx)

6. [Una presentación de *Weights and Biases*](https://github.com/mcd-unison/aaa-curso/raw/main/slides/WandB-tutorial.pptx)

7. [Infraestructura y plataformas](https://github.com/mcd-unison/aaa-curso/raw/main/slides/MLOps-infraestructura.pdf)



## Libretas, scripts y tutoriales

1. [Made with ML](https://madewithml.com). Un curso muy interesante con una prespectiva industrial del aprendizaje automático. Mucho le dedica a las MLOps.

2. [Ejemplo de uso de *Ray Serve* para desplegar modelos](https://github.com/anyscale/academy/blob/main/ray-serve/e2e/tutorial.ipynb)

3. [Ejemplo de uso de *Evidently* para monitorear los datos](https://github.com/anyscale/academy/blob/main/ray-serve/e2e/tutorial.ipynb)

## Herramientas para MLOps

1. [MLFlow](https://www.mlflow.org). La plataforma de código abierto más usada como base para esquemas de MLOps. Una versión simple de lo que puedes tener con [*DataBricks*](https://databricks.com) si estás en una compañía que esté dispuesta a pagar el precio. Existe una versión para experimentación.

2. [*Weights & Biases*](https://wandb.ai/site). Similar a DataBricks, la solucion completa. Existe una versión académica y una personal, pero no puede usarse en empresas.

3. [*MLRun*](https://www.mlrun.org). Otra plataforma similar a *MLFlow* pero incluye una interfase gráfica para el manejo del ciclo de vida (como *DataBricks*). Puede instalarse *on premise*.
   
4. [*Neptune.ai](https://neptune.ai). Otra plataforma más, en la nube la orquestación, pero los modelos se pueden ejecutar *on premise*.

5. [*Ray*](https://www.ray.io/). Una plataforma de desarrollo pensando en la escalabilidad sobre todo. EN particular es muy apreciada la librería *ray serve* para poner los modelos de aprendizaje en producción.

6. [*MetaFlow*](https://metaflow.org). La solución de *Netflix* para MLOps. Al parecer muy poderoso pero tambien muy complicado de instalar *on premise*. Funciona sobre *Kubernetes*.

7. [*Facets*](https://pair-code.github.io/facets/). Otra herramienta de EDA, muy importante saber las estadísticas básicas de los datos para poder monitorearlos con [*pydantic*](https://pydantic-docs.helpmanual.io) o [*Great Expectations*](https://github.com/great-expectations/great_expectations).

8. [*pydantic*](https://pydantic-docs.helpmanual.io). Validación de datos conforme los utiliza uno, exclusivo par *python*. Similar pero para funcionar en la nube y en producción existe el proyecto [*Great Expectations*](https://github.com/great-expectations/great_expectations).

9.  [*Evidently AI*](https://evidentlyai.com). Herramientas en código abierto para monitorear la calidad de los datos, la deriva de los datos y la calidad de los modelos de predicción durante la etapa de producción. Se puede integrar a MLFlow, pero están más bonitos los tableros de *Evidently*.

10. [*Whylogs*](https://github.com/whylabs/whylogs). Similar a *Evidently* al parecer, pero solo la librería, ya que es el corazón de un producto que ya no es de código abierto (*Whylabs*). 

11. [*AirFlow*](https://airflow.apache.org). No es propiamente para MLOps, pero se utiliza mucho en conjunto con otras plataformas.


## Otra información

1. [CS 329S: Machine Learning Systems Design](https://stanford-cs329s.github.io/syllabus.html). Curso de [Chip Huyen](https://huyenchip.com), quien (además de escribir novelas en vietnamita) tiene posiblemente el mejor curso sobre MLOps que conozco hasta el momento. Muchas de las presentaciones de curso son extractos de las presentaciones de ella (con el reconocimiento respectivo), sólo porque no tenemos tiempo para ver la versión completa que es buenísima.