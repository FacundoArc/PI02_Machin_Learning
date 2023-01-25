![HenryLogo](https://d31uz8lwfmyn8g.cloudfront.net/Assets/logo-henry-white-lg.png)
​
# Proyecto individual 2 Facundo Gabriel Arce

## **Introducción**
Bienvenidos a mi Proyecto Individual Número 2 de la carrera de Data Science de Soy Henry. Mi nombre es Facundo Gabriel Arce y por el momento me encuentro en la etapa de Labs del curso soy Henry. A continuación voy a presentar el objetivo del proyecto orientado a Machine Learning y la conclusión final a la cual llegue luego de haberlo realizado.

## **Descripción**

Usted ha sido contactado para el área de Machine Learning de una importante empresa inversora dentro del rubro de la inmobiliaria en Estados Unidos. Se le ha sido solicitado crear un modelo que ayude a clasificar el precio de las propiedades en venta, utilizando la informacion proporcionada en formato Parquet


## **Contenido del repositorio** 

Dos archivos donde se encuentran los dataset utilizados en formato parquet:
test.parquet Y train.parquet
En el notebook de 'script.ipynb' se encuentra el proceso comentado del analisis exploratorio y la elaboración del modelo aprendizaje supervisado.
En el archivo DecisionTree_model.pkl se encuentra el modelo de árbol de decisión creado.
Archivo 'readme.md'.
FacundoArc.csv es el csv con la columna de predicciones del dataset 'test.parquet'.

## **Trabajo Realizado** 
Como primer paso realicé un análisis del dataset de train.parquet, con el objetivo de identificar valores duplicados, faltantes o errores. Procedí a intercambiar las variables categóricas para convertirlas en valores que pudiesen ser interpretados por el modelo. Continue entrenado un modelo Arbol de Desición utlizando todo el modelo excepto algunas columnas que ,gracias a un grafico de correlación de variables, me parecieron irrelevantes para el proceso. Luego analicé el resultado de Recall y Accuracy. Prosegui a crear un modelo de validación cruzada para poder visualizar la relación del Accuracy del modelo con diferentes niveles de profundidad del Arbol de Decisión.
Luego realice un pipeline del proyecto el cual exporte como DecisionTree_model.pkl.
Para finalizar corrí el modelo en el dataset de 'test.parquet' y exporte los resultados de la columna 'pred' a un archivo CSV para su evaluación.



## **Metricas Utilizadas** 

Se nos pidio priorizar las métricas de:</br> 
-Accuracy</br>
-Recall 

Tambien se utilizó El Area bajo la Curva Roc la cual sirve para modelos de clasificación.

## **Metricas Utilizadas**

-Python</br>
-Pandas</br>
-Seaborn</br>
-Sklearn</br>
-Matplotlib</br>
-Numpy</br>
-Joblib



