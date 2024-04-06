---
title: Proyecto integrador
subtitle: Diseño
layout: page
hero_image: https://github.com/mcd-unison/aaa-curso/raw/main/docs/img/intro-banner.jpeg
hero_darken: true
show_sidebar: false
---

El diseño del proyecto de ML suele ser una etapa que se la saltan normalmente las personas que tenemos una tendencia a resolver problemas técnicos. Sin embargo si no entendemos bien nuestros datos, el negocio (o los objetivos de la empresa o la institución) y definimos un problema que esté alineado a dichos intereses, podemos quedarnos haciendo cosas muy bonitas, pero sin aportar ningun beneficio a nadie. 

Vamos a hacer estos pasos aunque sea de manera más o menos simple. Recuerda que estos pasos suelen darse con el [*Subject-matter expert*](https://en.wikipedia.org/wiki/Subject-matter_expert) y con algun responsable de la empresa o institruciñón que asegure que los objetivos del proyecto se encuentren alineados con los de la institución/organización/empresa.

## Esturctura de proyecto

La estructura del proyecto es muy importante para mantener un espacio donde trabajar y colaborar con todo el equipo. Existen varas maneras de establecer un proyecto, aunque todas van mñas o menos por el mismo camino.

En [Cookiecutter Data Science](http://drivendata.github.io/cookiecutter-data-science/) se porpone una plantilla razonablemente flexible y bastante completa para proyectos de ciencia de datos y de aprendizaje automñatico. Vamos a tratar de mantener este esquema. Vienen las instrucciones para henerar el proyecto en Github, pero eso implica que no podras usar MLFlow desde un servidor de *DagsHub* y tendras que usarlo en local o con un servidor compartido. Igual el repositorio luego lo pueses sincronizar en *DagsHub* y tener el servicio de MLOps.

Si quieren usar *DagsHub* con control de datos con DVC puedes usar [este template](https://dagshub.com/DAGsHub-Official/Cookiecutter-DVC) y si quieres uno que incluye *MLOps* directamente con *DVC* puesdes usar [este otro template](https://dagshub.com/DagsHub/Cookiecutter-MLOps). Recuerda que ambos son basados en `Cookiecutter Data Science`.

- Generar un proyecto y tenerlo compartido con todo el equipo. Si se utilizan datos de empresa o privados y los resultados van a ser privados, entonces compartir conmigo el repositorio provado. Pero de preferencia tener proyectos públicos para que queden en su portafolio de proyectos.

## Análisis exploratorio de datos

- En la seccion de `references` agregar los diccionarios de datos de los datos crudos que van a utilizar, y alguna información o enlaces sobre el tema a tratar.

- Realizar una o varias libretas `jupyter`  en `notebooks` con un EDA en el cual utilicen *al menos* dos métodos de aprendizaje no supervisado para extraer información de los datos. Si son varias libretas, que cada una sea una idea diferente explorada. Evitar poner dos libretas con lo mismo, porque un compañero del equipo hizo una y el otro otra. Para eso es mejor trabajar en forma colaborativa con Git.

## Establecer un problema de aprendizaje

- A partir de el análisis exploratorio de datos y de discutir con un *Subject-matter expert* y posiblemente con un usuario interesado, determinar cual es el problema a resolver, justificando lo siguiente:
    - ¿Que problema se plantea resolver? En términos que todo mundo entienda.
    - ¿Porqué es un problema importante para la institución/organización/empresa?
    - ¿Cuales son las métricas para medir el impacto de la solución una vez obtenida?
    - ¿Que problema de aprendizaje implica resolver? Si es clasificación, especificar cuales serían las clases.
    - ¿Qué metricas permiten medir la calidad del modelo de aprendizaje? ¿Cuales son sus valores deseables?
    - ¿Como están alineadas las métricas de la calidad del modelo con las métricas de impacto de la solución? De preferencia tratar de cuantificar.

## Procesamiento de variables (ETLs)

- Realizar el procesamiento de `raw data` a processed data (puede haber etapas intermedias) con un ETL en `src/data/make_dataset.py` y/o `src/data/features/build_features.py`.

- Agregar el diccionario de datos de los datos procesados en `references`.
