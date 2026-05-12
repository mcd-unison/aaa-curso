---
title: Redes Neuronales 
subtitle: Curso Aprendizaje Automático Aplicado
layout: page
hero_image: https://github.com/mcd-unison/aaa-curso/raw/main/docs/img/intro-banner.jpeg
hero_darken: true
show_sidebar: false
---

## Recursos generales y de consulta

1. El libro [Deep Learning](https://www.deeplearningbook.org) de Ian Goodfellow, Yoshua Bengio y Aaron Courville gratuito en linea con material adicional.

2. Un [excelente curso](http://introtodeeplearning.com) de introducción al aprendizaje profundo del MIT con videos. transparencias y código.

3. [NeurIPS](https://nips.cc), la conferencia más importante en redes neuronales y en general en aprendizaje automñatico.

4. [Journal of Machine Learning Research](https://jmlr.org) es una publicación libre muy completa sobre el último grito de la moda en ML. Muy buenos artículos, pero ya bastante

5. Para usar transformadores, uno de los lugares con los mejores modelos preentrenados es la compañía [*Hugging Face*](https://huggingface.co). Muchos recursos en código abierto.

6. [Un listado de conjuntos de datos](https://datasets.activeloop.ai/docs/ml/datasets/)n que se utilizan muy intensivamente en tareas de aprendizaje profundo. 

## Redes neuronales: nociones generales 
   
1. Una [presentación sobre descenso de gradiente generada](https://github.com/mcd-unison/aaa-curso/raw/main/slides/des-grad.pdf) y otra sobre el algoritmo [LION](https://github.com/mcd-unison/aaa-curso/raw/main/slides/Lion.pdf)
   
2. [A Recipe for Training Neural Networks](http://karpathy.github.io/2019/04/25/recipe/) por Andrej Karpathy.
   

## Redes Convolucionales

1. Una presentación sobre [redes convolucionales](https://github.com/mcd-unison/aaa-curso/raw/main/slides/convolucionales.pdf).

2. Una [muy buena presentación del curso del MIT](http://introtodeeplearning.com/slides/6S191_MIT_DeepLearning_L3.pdf) sobre CNN para visión por computadora, así como [un ejercicio en colab de *autocodificadores variacionales*](https://colab.research.google.com/github/aamini/introtodeeplearning/blob/2023/lab2/Part2_FaceDetection.ipynb), basado en [éste artículo de ellos mismos](http://introtodeeplearning.com/AAAI_MitigatingAlgorithmicBias.pdf).

3. Una presentación sobre [transferencia del aprendizaje](https://github.com/mcd-unison/aaa-curso/raw/main/slides/transfer_learning.pptx) (tambien [en pdf](https://github.com/mcd-unison/aaa-curso/raw/main/slides/transfer_learning.pdf)). Tambien [una entrada de Jordan Urías sobre NST](https://jjups96.github.io/fast-style-transfer/) muy bien explicado

4. [Modelos generativos](https://introtodeeplearning.com/slides/6S191_MIT_DeepLearning_L4.pdf). Una presentación muy buena del MIT.

5. [Aprendizaje auto supervisado](https://github.com/mcd-unison/aaa-curso/raw/main/slides/Self-Supervised_Learning_Decoded.pdf) ¿Qué es eso?

## Redes neuronales es series de tiempo

1. Modelos secuenciales con redes neuronales, con un [presentación de los modelos de base](https://github.com/mcd-unison/aaa-curso/raw/main/slides/RNN-slides.pptx) y [la misma presentación en pdf](https://github.com/mcd-unison/aaa-curso/raw/main/slides/RNN-slides.pdf).

2. La arquitecura de [Temporal Fusion Transformers (TFT)](https://arxiv.org/abs/1912.09363) y dos presentaciones generadas con NotebookLM. [Esta que está en español pero me parece como de vendedor](https://github.com/mcd-unison/aaa-curso/raw/main/slides/TFT_Transparent_Forecasting.pdf), y [otra en inglés que tampoco me gustó completamente](https://github.com/mcd-unison/aaa-curso/raw/main/slides/TFT_Architectural_Deconstruction.pdf) pero estan ambas mas o menos potables.

## Algunas libretas con ejemplos

1. [El hola mundo de las redes neuronales en pyTorch](https://colab.research.google.com/github/mcd-unison/aaa-curso/blob/main/ejemplos/pytorch_ejemplo_simple.ipynb)

2. [Transferencia de aprendizaje simple con pyTorch](https://colab.research.google.com/github/mcd-unison/aaa-curso/blob/main/ejemplos/transfer_pytorch.ipynb)

3. [Transferencia de estilo en imágenes con pyTorch](https://colab.research.google.com/github/mcd-unison/aaa-curso/blob/main/ejemplos/nst_pytorch.ipynb) 

4. [Detección de objetos usando YOLO](https://colab.research.google.com/github/mcd-unison/aaa-curso/blob/main/ejemplos/YOLOv12_fine_tuning.ipynb) 

5. Dos libretas ilustrativas: [Redes Neuronales Recurrentes (RNN) con numpy](https://colab.research.google.com/github/mcd-unison/aaa-curso/blob/main/ejemplos/Estados-ocultos.ipynb) y [El problema del gradiente en las RNN vainilla](https://colab.research.google.com/github/mcd-unison/aaa-curso/blob/main/ejemplos/vanish-grad.ipynb). Las dos en `numpy` para ilustrar como funcionan las redes neuronales recursivas.
