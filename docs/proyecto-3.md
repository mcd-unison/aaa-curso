---
title: Proyecto integrador
subtitle: Puesta en producción
layout: page
hero_image: https://github.com/mcd-unison/aaa-curso/raw/main/docs/img/intro-banner.jpeg
hero_darken: true
show_sidebar: false
---

Ahora vamos a asumir que ya se tiene un modelo, y que este se encuentra en un repositorio de *DagsHub* y registrado como modelo en producción. El propósito de este miniproyecto final es poner en producción el modelo. Dadas las restricciones de tiempo no se va a ver en este curso el monitoreo de modelos y datos.

Para este miniproyecto vamos a probar dos maneras de poner un modelo en producción: Por medio de un script que pueda ser llamado desde un *Data pipeline*, y poniendo el modelo en servicio bajo el esquema de *Model as a Service (MaaS).

1. Desarrollar una libreta de *jupyter* con las instrucciones necesarias para que se pueda leer el modelo en producción desde el servidor de modelos de *DagsHub* y ejecutarlo, con un ejemplo de aplicación (pueden ser datos históricos o inventados para un análisis de tipo *What if*)

2. Realizar una libreta de *jupyter* con la documentación necesaria de los pasos que tiene que hacer alguien para recuperar un modelo del servidor de modelos de *DagsHub* y lo ponga *localmente* en servicio de forma MaaS. Completar la libreta con un ejemplo usando `requests` para mandar llamar al modelo y resolver el mismo problema que en el inciso 1 (pero con un modelo que se encuentra en ejecución en forma permanente como MaaS)

Dada la huelga y el poco tiempo, vamos a dejar este proyecto solo en esbozar como usar los modelos a partir de un servidor de modelos.


