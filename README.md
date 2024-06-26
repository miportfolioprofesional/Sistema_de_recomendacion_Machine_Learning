# Sistema_de_recomendacion_Machine_Learning

Ultimo entregable para la ICARO (Diplomatura en Machine Learning).


Este proyecto consiste en el desarrollo de un sistema de recomendación de machine learning para la institución Icaro, perteneciente a la Universidad Tecnológica Nacional de Córdoba. Utilizaremos datos de visualizaciones de Amazon, específicamente del conjunto de datos ratings_electronics. 

# Objetivo 

El objetivo principal de este trabajo es desarrollar un sistema de recomendación que utilice las valoraciones previas de los usuarios en una variedad de productos para sugerirles nuevos artículos. A través del análisis de las reseñas de los productos, buscamos proporcionar recomendaciones personalizadas que mejoren la experiencia del usuario en la plataforma, asignándole los mejores productos de acuerdo con sus preferencias. 

# Procesos 

# 1. Preparación de los datos 

Dividimos el conjunto de datos en conjuntos de entrenamiento y prueba, tomando como datos de entrenamiento aquellos que van desde el 1 de enero de 2013 hasta el 31 de diciembre de 2013 , y reservando los datos para las pruebas el primer mes del 2014.


Realizamos un proceso de ETL (Extract, Transform, Load) para limpiar y preparar los datos para su posterior análisis. 

# 2. Desarrollo del sistema de recomendación 

Implementamos un algoritmo de recomendación capaz de generar 20 recomendaciones por usuario, incluyendo aquellos usuarios que no tienen visualizaciones en el conjunto de entrenamiento (cold start). 

Las recomendaciones se generan para cada account_id, recomendando content_id (NO asset_id). 

Filtramos los contenidos que ya han sido vistos por los usuarios en el conjunto de entrenamiento. 


# Conclusión final: 

El modelo de recomendación tiene un rendimiento extremadamente deficiente en la tarea de recomendación. Sin embargo, La forma en que gestionamos los usuarios "cold start", la creación del conjunto "ideal" y la generación de recomendaciones pueden tener un impacto significativo en la evaluación del rendimiento del modelo de recomendación.


# Colaboradores del proyecto.


# Endrek Matias: [![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/https://www.linkedin.com/in/matias-endrek-7a9680255/) [![Gmail: matiasjavierendrek@gmail.com](https://img.shields.io/badge/Gmail-matiasjavierendrek@gmail.com-red)](mailto:matiasjavierendrek@gmail.com)

# Camila Arregui: [![Gmail: arreguicamila@gmail.com](https://img.shields.io/badge/Gmail-arreguicamila@gmail.com-red)](mailto:arreguicamila@gmail.com)


# Lucas Pedraza: [![Gmail: inside255@gmail.com](https://img.shields.io/badge/Gmail-inside255@gmail.com-red)](mailto:inside255@gmail.com)






