# Descripción del Proyecto
En este proyecto hemos trabajado con una base de datos *escrapeada* de la API de Goodreads, con el objetivo de predecir el rating de un libro basados en determinadas variables
corelacionadas con esta variable. Hemos visto que el `autor`, el `número de páginas`, así como la `fecha de lanzamiento` son variables determinantes en el rating del libro.

Después de haber hecho limpieza de datos, vizualización y preprocesamiento de los datos, hemos entrenado dos modelos de regresión: `LinearRegression` y `LGBMRegressor`. 
El primero mostró mucha mayor rapidez de entrenamientos, sin embargo, para el segundo no tenemos que codificar las variables categóricas. Los dos mostraron rendimiento similar
con respecto a la métrica `RSME`.
