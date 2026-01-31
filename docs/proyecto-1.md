---
title: Proyecto integrador
subtitle: Diseño
layout: page
hero_image: https://github.com/mcd-unison/aaa-curso/raw/main/docs/img/intro-banner.jpeg
hero_darken: true
show_sidebar: false
---

El diseño del proyecto de ML suele ser una etapa que se la saltan normalmente las personas que tenemos una tendencia a resolver problemas técnicos. Sin embargo si no entendemos bien nuestros datos, el negocio (o los objetivos de la empresa o la institución) y definimos un problema que esté alineado a dichos intereses, podemos quedarnos haciendo cosas muy bonitas, pero sin aportar ningún beneficio a nadie. 

Vamos a hacer estos pasos aunque sea de manera más o menos simple. Recuerda que estos pasos suelen darse con el [*Subject-matter expert*](https://en.wikipedia.org/wiki/Subject-matter_expert) y con algún responsable de la empresa o institución que asegure que los objetivos del proyecto se encuentren alineados con los de la institución/organización/empresa.

Para los equipos, los vamos a general aleatoriamente. Al ser 18 estudiantes, pues vamos a hacer 6 equipos de 3 personas por equipo. [Aquí está el código en una libreta jupyter](https://github.com/mcd-unison/aaa-curso/raw/main/ejemplos/equipos.ipynb) que genera los equipos.

## Estructura de proyecto

La estructura del proyecto es muy importante para mantener un espacio donde trabajar y colaborar con todo el equipo. Existen varas maneras de establecer un proyecto, aunque todas van más o menos por el mismo camino.

En [Cookiecutter Data Science](http://drivendata.github.io/cookiecutter-data-science/) se propone una plantilla razonablemente flexible y bastante completa para proyectos de ciencia de datos y de aprendizaje automático. Vamos a tratar de mantener este esquema. Vienen las instrucciones para generar el proyecto en Github.

## Actividades a realizar

1. Generar un proyecto y tenerlo compartido con todo el equipo. Si se utilizan datos de empresa o privados y los resultados van a ser privados, entonces compartir conmigo el repositorio privado. 

2. En la sección de `references` agregar los diccionarios de datos de los datos crudos que van a utilizar, y alguna información o enlaces sobre el tema a tratar.

3. Realizar una o varias libretas `jupyter`  en `notebooks` con un EDA en el cual utilicen *al menos* dos métodos de aprendizaje no supervisado para extraer información de los datos. Si son varias libretas, que cada una sea una idea diferente explorada. Evitar poner dos libretas con lo mismo, porque un compañero del equipo hizo una y el otro otra. Para eso es mejor trabajar en forma colaborativa con Git.

4. A partir de el análisis exploratorio de datos y de discutir con un *Subject-matter expert* y/o un usuario interesado, escribir en el `README.md` cual es el problema a resolver, justificando lo siguiente: 
    - ¿Que problema se plantea resolver? En términos que todo mundo entienda.
    - ¿Porqué es un problema importante para la institución/organización/empresa/usuario?
    - ¿Que problema de aprendizaje implica resolver? Si es clasificación, especificar cuales serían las clases.
    - ¿Qué métricas permiten medir la calidad del modelo de aprendizaje? ¿Cuales son sus valores deseables?
    - ¿Como están alineadas las métricas de la calidad del modelo con los objetivos de la institución/organización/empresa/usuario?

5. Realizar el procesamiento de `raw data` a processed data (puede haber etapas intermedias) con un ETL en `src/data/make_dataset.py` y/o `src/data/features/build_features.py`.

6. Agregar el diccionario de datos de los datos procesados en `references`.
