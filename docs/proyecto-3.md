---
title: Proyecto integrador
subtitle: Puesta en producción
layout: page
hero_image: https://github.com/mcd-unison/aaa-curso/raw/main/docs/img/intro-banner.jpeg
hero_darken: true
show_sidebar: false
---

Ahora vamos a asumir que ya se tiene un modelo, y que este se encuentra en un repositorio de *DagsHub* y registrado como modelo en producción. Si no se encuentra en *DagsHub*, asumimos que el modelo está en algún manejador de modelos como puede ser [MLflow Model Registry](https://mlflow.org/docs/latest/model-registry/), [Weights & Biases](https://wandb.ai/site/registry) o [Ray Train](https://docs.ray.io/en/latest/train/train.html).

El propósito de esta etapa final del proyecto es poner en producción el modelo. Dadas las restricciones de tiempo no se va a ver en este curso el monitoreo de modelos y datos.

Para esta etapa vamos a probar dos maneras de poner un modelo en producción: Por medio de un script que pueda ser llamado desde un *Data pipeline*, y poniendo el modelo en servicio bajo el esquema de *Model as a Service (MaaS)*.

1. Desarrollar un script o una libreta de *jupyter* con las instrucciones necesarias para que se pueda leer el modelo desde el servidor de modelos y ejecutarlo, con un ejemplo de aplicación (pueden ser datos históricos o inventados para un análisis de tipo *What if*). Si el modelo está compuesto por varios modelos es posible que tengas que usar las mismas librerías que el sistema de registro de modelos que utilizaste. Automatizar este paso usando las *Actions* de *GitHub* o algo similar (por ejemplo la sincronización con DVC).

2. Realizar una libreta de *jupyter* con la documentación necesaria de los pasos que tiene que hacer alguien para recuperar un modelo del servidor de modelos de *DagsHub* y lo ponga en servicio de forma MaaS. Esto puede ser en línea, o se puede simular sirviendo el modelo dentro de la misma computadora. Completar la libreta con un ejemplo usando `requests` para mandar llamar al modelo y resolver el mismo problema que en el inciso 1 (pero con un modelo que se encuentra en ejecución en forma permanente como MaaS). Para esto es necesario usar una plataforma para servir modelos como [MLFlow Serving](https://mlflow.org/docs/latest/deployment/), [Ray Serve](https://docs.ray.io/en/latest/serve/index.html) o [Weights & Biases](https://wandb.ai/site/automations/) entre otros.
