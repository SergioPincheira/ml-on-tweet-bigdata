# Clasificación de Mensajes Ofensivos en Twitter Utilizando Big Data y Machine Learning

Este proyecto utiliza técnicas de Big Data y Machine Learning para clasificar tweets en tres categorías: mensajes de odio, mensajes ofensivos y mensajes neutrales. El análisis se realiza mediante herramientas como  Apache Sqoop, Apache Hive y Apache Spark.

## Descripción

El propósito de este proyecto es desarrollar un modelo predictivo para clasificar automáticamente mensajes en la plataforma Twitter, con un enfoque en la detección de mensajes ofensivos o de odio. Las redes sociales, como Twitter, están interesadas en esta clasificación para reducir la difusión de mensajes ofensivos y prevenir posibles conflictos.

## Dataset
El dataset usado es el Hate Speech and Offensive Language Dataset de Kaggle (https://www.kaggle.com/datasets/mrmorj/hate-speech-and-offensive-language-dataset), que contiene mensajes clasificados en tres clases:

- Clase 0: Mensaje de odio (hate speech)
- Clase 1: Mensaje ofensivo (offensive language)
- Clase 2: Ninguno de los anteriores (neither)
  
Cada tweet ha sido clasificado por múltiples personas, y se asigna una clase final basada en la mayoría de votos.

## Herramientas y Librerías

MySQL: Base de datos inicial donde se aloja el dataset para el proyecto.
Apache Sqoop: Para importar datos desde MySQL hacia Hive.
Apache Hive: Para el almacenamiento y consulta de grandes volúmenes de datos.
Apache Spark: Procesamiento de datos y entrenamiento de modelos de Machine Learning con Spark MLlib.
