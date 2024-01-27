---
title: Curso Aprendizaje Automático Aplicado
subtitle: Maestría en Ciencia de Datos, Universidad de Sonora
layout: page
hero_image: https://github.com/mcd-unison/aaa-curso/raw/main/docs/img/ml-banner.jpg
hero_darken: true
show_sidebar: false
---


| **Profesor**    | Julio Waissman (julio.waissman@unison.mx)  |
| **Horarios**    | Miércoles de 18:00 a 20:00 hrs             |
|                 | Sábados de 12:00 a 14:00                   |
|                 | Jueves y viernes, 3 horas autónomas        |
| **Lugar**       | Laboratorio de Ciencia de Datos            |


[**Presentación de introducción**](https://github.com/mcd-unison/aaa-curso/raw/main/slides/intro-curso.pptx) 



## Objetivos del curso

El objetivo general de este curso es desarrollar en el estudiante las competencias necesarias para entender como aplicar 
métodos cruciales de aprendizaje automático para resolver problemas, ejecutar evaluaciones e interpretar sus resultados.

Los objetivos de este curso son:

1. Conocer y saber aplicar diferentes algoritmos de aprendizaje no supervisado.

2. Conocer y entender la teoría básica que sustenta el aprendizaje supervisado.

3. Conocer y saber cómo y en qué condiciones aplicar algoritmos de aprendizaje supervisado.

4. Entender y seleccionar los criterios y las técnicas para la medición de la calidad de un algoritmo de aprendizaje supervisado.

5. Conocer y saber aplicar los métodos de *MLOps* en el desarrollo de un modelo de aprendizaje para un problema real.

Las competencias que queremos ayudar a desarrollar en los estudiantes a lo largo del semestre son las siguientes:

1. Entender y saber utilizar métodos de aprendizaje no supervisado para un proceso de minería de datos.
   
2. Utilizar las herramientas más populares en python para el desarrollo de modelos de aprendizaje supervisado en Ciencia de Datos.

3. Saber decidir cual modelo de aprendizaje supervisado es el más adaptado para diferentes problemas y medir la calidad de éste.

4. Desarrollar un modelo de aprendizaje para un problema real, haciendo uso de herramientas de MLOps que aseguren la reproducibilidad de los resultados.


## Temario

1. **Introducción** *(1 clase)*

2. **Aprendizaje no supervisado** *(1 1/2 semanas aprox)*
   1. Reagrupamiento aglomerativo
   2. Reagrupamiento jerárquico
   3. Reducción de la dimensionalidad

3. **Introducción** *(3 semanas aprox.)*
   1. ¿Que es el aprendizaje automático?
   2. ¿El aprendizaje supervisado es posible? 
   3. Un ejemplo: regresión lineal y logística
   4. El dilema de sesgo *versus* varianza
   5. Regularización 
   6. Validación 
   7. Medición de error
   8. Curvas de aprendizaje
   9. MLOps y DataOps ¿Para qué utilizarlas?
   10. Experimentos, métricas y funciones de costo

4. **Modelos lineales de aprendizaje supervisado** *(3 semanas aprox.)*
   1. Modelos lineales generalizados
   2. Máquinas de vectores de soporte

5. **Modelos no lineales de aprendizaje supervisado** *(2 semana aprox.)*
   1. Modelos por árboles de decisión
   2. Modelos de *ensamble*

6. **Redes neuronales** *(3 semanas aprox)*
   1. Conceptos teóricos sobre ejemplos sencillos
   2. El perceptrón multicapa (MLP)
   3. Redes Convolucionales (CNN)
   4. Transfer learning y modelos preentrenados
   5. Aprendizaje autosupervisado

7. **Operaciones de aprendizaje máquina (MLOps)** *(1 semana aprox)*
   1. Despliegue y administración de modelos
   2. Supervisión de modelos de aprendizaje.

8. **Series de tiempo** *(1 semana aprox)*
   1. Métodos clásicos
   2. Redes neuronales recurrentes

## Lecturas y enlaces recomendados

1. El sitio del curso [*Learning for Data*](https://work.caltech.edu/telecourse.html) de [Yaser S.Abu-Mostafa](https://work.caltech.edu) de CalTech, es probablemente el mejor curso (no edulcorado) que conozco sobre aprendizaje supervisado. Le da un énfasis especial a entender los principios básicos antes de pasar a las técnicas particulares. El sitio incluye
  
     1. Lecturas en *youtube*
  
     2. Las presentaciones en *pdf*
  
     3. Una liga al [libro homónimo del curso](https://www.amazon.com/gp/product/1600490069)
  
     4. Tareas y proyecto
  
2. El [curso de Machine Learning en Coursera](https://www.coursera.org/learn/machine-learning) de [Andrew Ng](https://www.andrewng.org) es posiblemente el curso en linea más popular en Aprendizaje Automático. El profesor es magistral y explica los métodos sin requerir conocimientos en matemáticas, lo que hace que el curso sea a un nivel bastante superficial, pero muy recomendable.

3. [The Elements of Statistical Learning](https://hastie.su.domains/ElemStatLearn/) el cual se encuentra en la biblioteca de la DCEN y la biblioteca digital. Una buena introducción (no sencilla) a la teoría del aprendizaje y las SVM.


4. [Hands-On machine learning with scikit-learn and tensorflow : concepts, tools, and techniques to build intelligent systems](https://www.oreilly.com/library/view/hands-on-machine-learning/9781098125967/) es un texto muy aplicado, con mucho código y poca teoría. Es mi recomendación para buscar como hacer prácticamente cosas y no te gusta buscarlas en internet. Aquí dejo una liga con [libretas jupyter con los ejemplos del libro](https://github.com/ageron/handson-ml3)

5. Los [Tópicos de ML en Medium](https://medium.com/topic/machine-learning) es un buen lugar para buscar artículos de divulgación y/o tutoriales bastante claros sobre diferentes técnicas de ML. Me parece que sin subscripción, tiene uno limitado el número de artículos a leer por día en Medium.
  
## Repositorios de datos con problemas de aprendizaje automático

1. [Kaggle](https://www.kaggle.com) es la puerta de entrada a básicamente la mayor parte de las habilidades en ML que se requieren para Ciencia de Datos. El sitio incluye:

    1. Datos reales y sintéticos para practicar y aprender
    
    2. Datos reales en competencias de aprendizaje automático (con premios en efectivo algunas veces)
    
    3. Un sistema de libretas de *jupyter* en linea
    
    4. Cursos sobre diferentes temas interesantes
    
    5. Ejemplos de libretas útiles
    
2. [UCI database repository](https://archive.ics.uci.edu/ml/index.php) Es el sitio más clásico (venerable y feo, por cierto) de conjuntos de datos para tareas de Aprendizaje Automñatico. Es un poco complicada la navegación y entender la organización de los datos, pero es realmente un muy buen sitio para escoger problemas a resolver.

## Herramientas de enseñanza

Para este curso vamos a contar con diversas herramientas de enseñanza
que complementen las técnicas vistas en clases presenciales a distancia, 
y al mismo tiempo se generen una serie de evidencias de las competencias
desarrolladas a lo largo del curso.


![](https://github.com/mcd-unison/aaa-curso/raw/main/docs/img/datacamp.jpg)


Este curso tiene el soporte de [DataCamp](https://www.datacamp.com/) , una plataforma intuitiva para el aprendizaje de competencias para ciencia de datos.
DataCamp cuenta con cursos, proyectos, tutoriales y rutas de aprendizaje para aprender desde los conceptos básicos hasta los temas avanzados de
ciencia de datos usando R, python y SQL. DataCamp ofrece 350+ cursos por instructores expertos en tópicos como importación de datos, visualización 
y aprendizaje automático entre otros.

Vamos a utilizar *DataCamp for the Classroom* este semestre. DataCamp apoya la educación alrededor del muno con esta iniciativa libre. Puedes encontrar más información al respecto en
[datacamp.com/groups/education](datacamp.com/groups/education)

![](https://github.com/mcd-unison/aaa-curso/raw/main/docs/img/edx.png)

[*Online Campus Essentials*](https://campus.edx.org/es/essentials) proporciona acceso ilimitado a determinados cursos de tecnología, informática, negocios y otras temáticas. La plataforma de aprendizaje activo de edX motiva e involucra a los estudiantes para apoyar su progreso y dominio de una materia. Los estudiantes obtienen certificados verificados al completar el curso con éxito.

*Online Campus Essentials* Enriquece el aprendizaje de los estudiantes con módulos y tareas del curso con actividades de aprendizaje asíncronas y a ritmo propio en cualquier dispositivo. Las herramientas de la plataforma de edX permiten al profesorado y a los administradores hacer seguimiento de las inscripciones, la participación y medir el rendimiento.


![](https://www.nvidia.com/content/dam/en-zz/Solutions/about-nvidia/logo-and-brand/01-nvidia-logo-vert-500x200-2c50-p.png)

[*NVIDIA Deep Learning Institute (DLI)*](https://www.nvidia.com/en-us/training/). Cursos en línea principalmente sobre redes neuronales profundas. Una certificación con una buena introducción al uso de modelos de aprendizaje profundo.

![](https://static.wixstatic.com/media/e097e0_ec221f1cda5d43c68f0f44ef54b7a9c1~mv2.png/v1/fill/w_324,h_80,al_c,q_85,usm_0.66_1.00_0.01,enc_auto/Logo%20Orbitware-01.png)

