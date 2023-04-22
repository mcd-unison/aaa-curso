---
title: Proyecto integrador
subtitle: Aprendizaje Automático Aplicado (2023-1)
layout: page
hero_image: https://github.com/mcd-unison/aaa-curso/raw/main/docs/img/intro-banner.jpeg
hero_darken: true
show_sidebar: false
---

## Equipos

Vamos a hacer 4 equipos de 4 personas y 1 equipo de 2 personas:

### Equipo 1: 

- Maria Elena
- Jordan

### Equipo 2:

- Elaine
- Daniela
- Aaron
- Ariel

### Equipo 3:

- Martin
- Melissa
- Yanet
- Estefania

### Equipo 4:

- Diana
- Eliud
- Osiris
- Kevin

### Equipo 5:

- Santiago
- Rodrigo
- Fernando
- Javier
- Daniel

## Proyectos

Los proyectos entre los que se pueden elegir son los siguientes:

### Proyecto 1: Predicción de incendios forestales mediante el uso de técnicas de aprendizaje automatizado

Los incendios forestales son un gran problema ambiental que va en aumento año con año en su frecuencia y severidad. El impacto que causa en los ecosistemas es grave, elimina flora y fauna local, volviendo susceptibles a especies invasoras, interrumpe los ciclos hidrológicos lo cual afecta en la recarga de acuíferos, entre otros. El impacto social de los incendios forestales repercute en económicamente en las zonas urbanas aledañas, causas perdidas de inmuebles (como en California y Australia), como también pérdida de vidas humanas y deterioro de la salud.

Distintas investigaciones se han realizado para predecir incendios forestales utilizando machine learning, sin embargo, ningún sistema que se ha publicado esta de acceso al público y en la mayoría de los casos, el acceso a los códigos para dicho sistema no está publicado junto con los artículos científicos.

Se les otorgara una constancia con valor curricular expedida por el Laboratorio de Ciencias de la Sostenibilidad del Instituto de Ecología de la UNAM al equipo que vaya a trabajar con el proyecto.

#### Datos

Para elaborar dicho proyecto, se proveerá con 19 imágenes en formato TIFF, las cuales son variables bioclimáticas de acceso al público de WorldClim, las cuales están asociadas a los incendios forestales. Se les proveerá también con otra imagen de NDVI el cual es un índice de vegetación, indica en pocas palabras el estado de salud de la vegetación en una zona y también de NBR, el cual indica las zonas afectadas por incendios forestales registradas por el satélite de MODIS de la NASA.

Los datos y los modelos resultantes serían de carácter público.


## Criterios de evaluación

1. Un estudio inicial (puede ser una libreta jupyter) que incluya:
   1. Un análisis exploratorio de los datos
   2. Una limpieza y generación *a priori* de nuevas características
   3. Establecer con claridad cual es el problema a resolver desde el punto de vista de aprendizaje automático
2. Una breve revisión bibliográfica sobre que existe y que se puede utilizar para el problema 
3. Un modelo simple y un análisis de los resultados para una mejor comprensión del problema
4. Manejo del ciclo de vida de un producto de aprendizaje automático usando una herramienta (*MLFlow*, *MLRun*, *Neptune.ai*, ....)
   1. Establecer claramente las métricas y los artefactos y documentarlos.
   2. Mantener un registro de experimentos
   3. Mantener un registro de modelos
   4. Usar métodos de búsqueda de hiperparámetros (`hyperopts`, `optuna`, `gridsearch` de `sklearn`, ...)
   5. Mostrar la calidad de los modelos y asegurar de alguna manera la generalización del modelo seleccionado
   6. Poner el modelo en producción (ejemplo) usando una REST API, y un ejemplo de uso