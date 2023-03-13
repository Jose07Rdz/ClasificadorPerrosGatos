# ClasificadorPerrosGatos
Es un modelo de redes neuronales convolucionales con automento de datos entrenado con TensorFlow Datasets para poder predecir entre la imagen de un perro o un gato

El modelo es cargado en una pagina web, dicha pagina web debe ser lanzada utilizando el servicio de htpp de python

Dicho servicio puede ser lanzado utilizando el siguiente comando en la carpeta donde se encuentra el proyecto:

Linux: **python3 -m http.server port**

Windows: **py -m http.server port**


*port* debe ser cambiado por el puerto en el que quiera lanzar el servicio

En el caso ejemplo utilizamos el puerto *8000* y la url para entrar a nuestra pagina fue: *localhost:8000/index.html*
![](https://i.imgur.com/YnCXiuw.png)

Esta puede variar dependiendo de el puerto que eliga.

La pagina trata de predecir en todo momento si la imagen pertenece a un perro o a un gato, por eso es que aunque en nuestro ejemplo la camara esta en negro dice que la imagen pertenece a la de un gato

# Ejemplo Practico
Perro:
![](https://i.imgur.com/EyZjAX7.png)

# Cosas a considerar
Este proyecto fue mas que nada para adentrarme en el mundo de las redes neuronales convolucionales por lo que puede terner cierto grado de error (90% de presicion segun el mismo TensorFlow)
