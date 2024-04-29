# Sistema_de_recomendacion_Machine_Learning
Ultimo entregable para la Icaro (Diplomatura en Machine Learning)


Este proyecto consiste en el desarrollo de un sistema de recomendación de machine learning para la institución Icaro, perteneciente a la Universidad Tecnológica Nacional de Córdoba. Utilizaremos datos de visualizaciones de Amazon, específicamente del conjunto de datos ratings_electronics. 

# Objetivo 

El objetivo principal de este trabajo es desarrollar un sistema de recomendación que utilice las valoraciones previas de los usuarios en una variedad de productos para sugerirles nuevos artículos. A través del análisis de las reseñas de los productos, buscamos proporcionar recomendaciones personalizadas que mejoren la experiencia del usuario en la plataforma, asignándole los mejores productos de acuerdo con sus preferencias. 

#Proceso 

# 1. Preparación de los datos 

Dividimos el conjunto de datos en conjuntos de entrenamiento y prueba, tomando como datos de entrenamiento aquellos que van desde el 1 de enero de 2013 hasta el 31 de diciembre de 2013 , y reservando los datos para las pruebas el primer mes del 2014.


Realizamos un proceso de ETL (Extract, Transform, Load) para limpiar y preparar los datos para su posterior análisis. 

# 2. Desarrollo del sistema de recomendación 

Implementamos un algoritmo de recomendación capaz de generar 20 recomendaciones por usuario, incluyendo aquellos usuarios que no tienen visualizaciones en el conjunto de entrenamiento (cold start). 

Las recomendaciones se generan para cada account_id, recomendando content_id (NO asset_id). 

Filtramos los contenidos que ya han sido vistos por los usuarios en el conjunto de entrenamiento. 
