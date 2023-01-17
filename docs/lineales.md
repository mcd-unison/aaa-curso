---
title: Modelos lineales de aprendizaje 
subtitle: Curso Aprendizaje Automático Aplicado
layout: page
hero_image: https://github.com/mcd-unison/aaa-curso/raw/main/docs/img/intro-banner.jpeg
hero_darken: true
show_sidebar: false
---

## Modelos lineales generativos

1. Naive bayes. [Una presentación de CMU](https://www.cs.cmu.edu/~10601b/slides/NBayes.pdf) y [otra de NYU, MIT-CSAIL](https://people.csail.mit.edu/dsontag/courses/ml12/slides/lecture17.pdf). 


## Modelos lineales generalizados (GLM)

1. [Documento sobre GLM](https://see.stanford.edu/materials/aimlcs229/cs229-notes1.pdf) del curso de Andrew Ng de Stanford.

2. La página de wikipedia de [la familia exponencial de distribuciones de probabilidad](https://en.wikipedia.org/wiki/Exponential_family).

3. El modulo [statmodels](https://www.statsmodels.org/stable/index.html) para python, así como un [libro de Peter K. Dunn y Gordon K. Smyth](https://d1wqtxts1xzle7.cloudfront.net/61444643/Generalized_Linear_Models_With_Examples_in_R_-_Dunn20191206-26902-1wyc454.pdf?1575666085=&response-content-disposition=inline%3B+filename%3DSpringer_Texts_in_Statistics_Generalized.pdf&Expires=1644976171&Signature=XAljoYucQiNFVSvkjfXLhJLCK2my2VYBI4zXuekqBNZzgH8hKv1suPVXVBU8pX48nWSQ9fobuh9zfMGd9qnZfo7cINvdpCxiOukHD2RpYodnTDtmQf~~P2oEE1hcX6y2OlPLr4UekzaSeQpVfL4RjelZ3u7Xjn3lMrGEKab5-7s8qw7mIqCXCteT2Rd-Xpyjp7QuYP7VkO6di1eiuL3c4cwdjhQD4u4By0LmHjDOpkUTWsBqA1VY68TtyTBMm8qXdLqr2GqaJTV~XvNWxE~Rxtwd-Z7sx9ll7xES4zD1D4ni52RKWayQJwGoeNG~jF2o0gIfQkWbwv5L1exk9n4pFg__&Key-Pair-Id=APKAJLOHF5GGSLRBV4ZA) sobre GLM en R.


## Maquinas de vectores de soporte

1. [Una presentación bien viejita](https://github.com/mcd-unison/aaa-curso/raw/main/slides/svm_presentacion.pdf) pero que sigue estando decente.

2. [Una entrada de medium](https://towardsdatascience.com/an-introduction-to-support-vector-regression-svr-a3ebc1672c2) muy sencilla para explicar la idea base de la regresión con máquinas de vectores de soporte.

3. Un tutorial muy completo sobre la teoría y los algoritmos de [regresión con máquinas de vectores de soporte](https://alex.smola.org/papers/2004/SmoSch04.pdf).

4. Unas libretas de ejemplo para ejecutar en Kaggle. Un [tutorial de SVM para clasificación](https://www.kaggle.com/prashant111/svm-classifier-tutorial), [otro de múltiples clases, usando búsqueda exhaustiva sobre los valores de los parámetros](https://www.kaggle.com/pranathichunduru/svm-for-multiclass-classification/notebook). Por último [otro tutorial](https://www.kaggle.com/faressayah/support-vector-machine-pca-tutorial-for-beginner/notebook) que usa algunas de las bases de datos más usadas en los tutoriales y cursos de aprendizaje automático.


## Libretas *jupyter*

1. [Regresión lineal](https://colab.research.google.com/github/mcd-unison/aaa-curso/blob/main/ejemplos/reg_lineal.ipynb)

2. [Regresión logística](https://colab.research.google.com/github/mcd-unison/aaa-curso/blob/main/ejemplos/reg_logistica.ipynb)

3. [Regularización](https://colab.research.google.com/github/mcd-unison/aaa-curso/blob/main/ejemplos/regularizacion_logistica.ipynb)

4. [Una libreta sobre Naive Bayes](https://colab.research.google.com/github/jakevdp/PythonDataScienceHandbook/blob/master/notebooks/05.05-Naive-Bayes.ipynb).

3. [Una libreta en colab](https://colab.research.google.com/github/aamini/introtodeeplearning/blob/master/lab1/Part1_TensorFlow.ipynb) de introducción a Tensorflow, de un curso del MIT.
4. [Una libreta en microsoft learn](https://docs.microsoft.com/es-mx/learn/modules/intro-machine-learning-pytorch/2-tensors?WT.mc_id=aiml-7486-cxa) sobre tensores en *pyTorch* y sobre [diferenciación automática](https://docs.microsoft.com/es-mx/learn/modules/intro-machine-learning-pytorch/6-autograd?WT.mc_id=aiml-7486-cxa).
5. [Una libreta en colab del `hola mundo` de las redes neuronales](https://colab.research.google.com/github/aamini/introtodeeplearning/blob/master/lab2/Part1_MNIST.ipynb).
6. [Una libreta para jugar con modelos pre-entrenados de TensorFlow Hub](https://colab.research.google.com/github/mcd-unison/aaa-curso/blob/main/ejemplos/transfer.ipynb)






## Redes neuronales (multicapa por el momento)

1. [Una presentación sobre las nociones básicas de redes neuronales](https://github.com/mcd-unison/aaa-curso/raw/main/slides/neural-networks.pdf) así como el [importante algoritmo de *backpropagation*](https://github.com/mcd-unison/aaa-curso/raw/main/slides/backpropagation.pdf). Tambien un [video muy bueno](https://www.youtube.com/watch?v=eNIqz_noix8&t=1s) sobre +b-prop* hecho por *Dot CSV* un youtuber muy recomendable sobre redes neuronales profundas.
2. Un [excelente curso](http://introtodeeplearning.com) de introducción al aprendizaje profundo del MIT con videos. transparencias y código.
3. [*An overview of gradient descent optimization algorithms*](https://ruder.io/optimizing-gradient-descent/index.html) de Sebastian Ruder.
4. [A Recipe for Training Neural Networks](http://karpathy.github.io/2019/04/25/recipe/) por Andrej Karpathy.
5. El libro [Deep Learning](https://www.deeplearningbook.org) de Ian Goodfellow, Yoshua Bengio y Aaron Courville gratuito en linea con material adicional.
6. Una presentación sobre [redes convolucionales](https://github.com/mcd-unison/aaa-curso/raw/main/slides/convolucionales.pdf) y un [ejemplo en colab del `hola mundo` de las redes neuronales](https://colab.research.google.com/github/aamini/introtodeeplearning/blob/master/lab2/Part1_MNIST.ipynb).
7. Una presentación sobre [transferencia del aprendizaje](https://github.com/mcd-unison/aaa-curso/raw/main/slides/transfer_learning.pptx) (tambien [en pdf](https://github.com/mcd-unison/aaa-curso/raw/main/slides/transfer_learning.pdf)) y [una libreta para jugar con modelos preentrenados](https://colab.research.google.com/github/mcd-unison/aaa-curso/blob/main/ejemplos/transfer.ipynb)

