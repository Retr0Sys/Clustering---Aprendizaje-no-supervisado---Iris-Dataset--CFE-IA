# Clustering---Aprendizaje-no-supervisado---Iris-Dataset--CFE-IA
## Modelo de  aprendizaje no supervisado de IA simple creado y entrenado en python (Clustering) aplicado a la identificación de flores.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

<img src="https://github.com/user-attachments/assets/4fd93ca6-9f7d-448a-ac31-917b2518b52b" alt="IA" width="600" height="auto">


-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Este proyecto se centra en la aplicación del algoritmo de agrupamiento K-Means para la clasificación de las especies de flores del conjunto de datos Iris. El objetivo principal es agrupar las instancias de flores en clústeres, basándose en sus características morfológicas, para demostrar la efectividad de un modelo de aprendizaje no supervisado en la identificación y diferenciación de especies.

Para este análisis, se utilizaron cuatro variables clave: largo del sépalo, ancho del sépalo, largo del pétalo y ancho del pétalo. Tras un proceso de normalización de los datos, se procedió a la evaluación de la variabilidad interclase con diferentes valores de k. La selección final de k=3 se justificó por la coherencia interna de los grupos identificados, que se corresponden directamente con las tres especies conocidas en el conjunto de datos.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## Variables utilizadas:
Las variables utilizadas en este análisis, que corresponden a las especies de flores del conjunto de datos Iris, son:

Iris-setosa

Iris-versicolor

Iris-virginica

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Comparación entre especies y resultados del modelo entrenado
<img width="190" height="174" alt="image" src="https://github.com/user-attachments/assets/4b73cdeb-dba4-4514-a9d2-da235ae555df">

## Conclusiones

Los resultados del modelo de clustering revelaron una fuerte correlación entre los clústeres generados y las especies de flores originales. La asignación fue la siguiente:

Iris-setosa: Se agrupa consistentemente en el Clúster 1. 

Iris-versicolor: Se asigna al Clúster 0.

Iris-virginica: Se agrupa en el Clúster 2.

La coincidencia entre la clasificación del modelo y la especie real fue superior al 98% en la mayoría de los casos, alcanzando el 100% en varios de ellos.

Para las especies Iris-versicolor e Iris-virginica, la tasa de coincidencia varió entre el 75% y 81%, lo que demuestra la capacidad del modelo para diferenciar entre estas especies, aunque con una precisión ligeramente menor que con Iris-setosa.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Ejemplos de los resultados en porcentaje.

<img width="326" height="137" alt="image" src="https://github.com/user-attachments/assets/b16267b0-baba-4b41-ab39-b21262084519">

La visualización de las distribuciones de las flores, corroboró la capacidad del modelo de clustering para segmentar de  una manera generalmente efectiva las especies de acuerdo con sus características morfológicas. 
