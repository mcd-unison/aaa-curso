---
title: Proyectos de aprendizaje automático (MLOps) 
subtitle: Curso Aprendizaje Automático Aplicado
layout: page
hero_image: https://github.com/mcd-unison/aaa-curso/raw/main/docs/img/intro-banner.jpeg
hero_darken: true
show_sidebar: false
---

## Presentaciones

1. [Introducción a las MLOps](https://github.com/mcd-unison/aaa-curso/raw/main/slides/MLOps-intro.pdf)
2. [Preprocesamiento de datos](https://github.com/mcd-unison/aaa-curso/raw/main/slides/mlops-preprocesamiento.pdf)
3. [Selección de modelos](https://github.com/mcd-unison/aaa-curso/raw/main/slides/mlops-seleccion.pdf)

## Libretas, scripts y tutoriales

## Herramientas para MLOps

1. [MLFlow](https://www.mlflow.org). La plataforma de código abierto más usada como base para esquemas de MLOps. Una versión simple de lo que puedes tener con [*DataBricks*](https://databricks.com) si estás en una compañía que esté dispuesta a pagar el precio. Existe una versión para experimentación.
2. [*Weights & Biases*](https://wandb.ai/site). Similar a DataBricks, la solucion completa. Existe una versión académica y una personal, pero no puede usarse en empresas.
3. [*Ray Serve*](https://www.ray.io/ray-serve). API simple y rápida para poner modelos en producción. Se puede integrar en el ecosistema de MLFlow. *Ray* tiene otras herramientas.
4. [*Evidently AI*](https://evidentlyai.com). Herramientas en código abierto para monitorear la calidad de los datos, la deriva de los datos y la calidad de los modelos de predicción durante la etapa de producción. Se puede integrar a MLFlow, pero están más bonitos los tableros de *Evidently*.
5. [*Whylogs*](https://github.com/whylabs/whylogs). Similar a *Evidently* al parecer, pero solo la librería, ya que es el corazón de un producto que ya no es de código abierto (*Whylabs*). 
6. [*AirFlow*](https://airflow.apache.org). No es propiamente para MLOps, pero se utiliza mucho en conjunto con otras plataformas.

## Otra información

1. [CS 329S: Machine Learning Systems Design](https://stanford-cs329s.github.io/syllabus.html). Curso de [Chip Huyen](https://huyenchip.com), quien (además de escribir novelas en vietnamita) tiene posiblemente el mejor curso sobre MLOps que conozco hasta el momento. Muchas de las presentaciones de curso son extractos de las presentaciones de ella (con el reconocimiento respectivo), sólo porque no tenemos tiempo para ver la versión completa que es buenísima.