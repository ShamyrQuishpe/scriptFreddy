# scriptFreddy
Proyecto_analisis Este repositorio contiene los scripts utilizados para la extracción, tratamiento y almacenamiento de los datos utilizados en el caso de estudio de Freddy Villavicencio para la materia de análisis.

Pasos realizados dentro del código Búsqueda de datos en bruto en Kaggle: Se utilizó Kaggle para buscar datasets con información relevante para el proyecto. Se seleccionaron conjuntos de datos que contenían información detallada sobre canciones, artistas y métricas de popularidad.

Subida de datos a Firebase: Una vez obtenidos los datasets, se procedió a subirlos a una base de datos NoSQL llamada Firebase. Cada dataset se almacenó en una colección dentro de Firebase.

Extracción de datos en Jupyter Notebook: Se extrajeron los datasets de Firebase en un entorno de Jupyter Notebook para poder realizar el tratamiento y limpieza de los datos.

Limpieza y concatenación de los datos: Se realizó la limpieza de los cuatro datasets, lo cual incluyó la eliminación de valores nulos, corrección de errores de formato y cualquier otro tipo de limpieza necesaria para garantizar la calidad de los datos. Luego, se procedió a realizar una concatenación en base a las columnas necesarias de cada dataset, generando un inner join en base al nombre del artista. Esto permitió obtener un dataset uniforme y completo con más de 500 datos para un análisis adecuado.

Transformación del dataset en CSV: Una vez obtenido el dataset limpio y concatenado, se transformó en formato CSV para facilitar su manipulación y posterior análisis.

Subida del dataset a MongoDB Atlas: Finalmente, el dataset en formato CSV se subió al MongoDB Atlas, que funcionó como nuestro data lake, donde se almacenaron todos los datos de manera centralizada y segura para su posterior acceso y análisis.

Estos pasos detallados aseguraron un flujo de trabajo eficiente y organizado para obtener, limpiar y almacenar los datos necesarios para el análisis del proyecto.
