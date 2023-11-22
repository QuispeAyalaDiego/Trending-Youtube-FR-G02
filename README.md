# Trending-Youtube-FR-G02
# Proyecto de Analítica de YouTube en Francia

## I. INTRODUCCIÓN

Debido al aumento significativo de lo que hoy se conoce como “Big Data”, las empresas buscan la forma de tener una visión más detallada de esta información, para aprovechar dichos datos. Es por este motivo que en este proyecto nos enfocaremos en lograr utilizar dicha información para realizar un análisis completo brindando una visión detallada de las preferencias de las personas de Francia que utilizan la plataforma Youtube.

### Objetivo:

El objetivo principal del proyecto de analítica es analizar las tendencias de los videos de YouTube del país de Francia, mediante el conjunto de datos "Trending YouTube Video Statistics". Así mismo, se busca extraer conocimientos significativos y patrones que ayuden a comprender el comportamiento de los usuarios, las preferencias de contenido y otros aspectos relevantes en el ámbito de los videos en YouTube.

### Alcance del Problema:

El alcance de este proyecto abarca un análisis exhaustivo de las tendencias de videos en YouTube en Francia, utilizando el conjunto de datos "Trending YouTube Video Statistics". Se delimita a las siguientes áreas de interés:

- **Categorías y Preferencias de Contenido:** Explorar las categorías de vídeos más populares y evaluar las preferencias del público francés.
- **Evolución Temporal de Tendencias:** Investigar cómo ha cambiado el volumen y la popularidad de los videos a lo largo del tiempo, identificando patrones y tendencias temporales.
- **Identificación de Canales Relevantes:** Destacar los canales de YouTube que son tendencia con mayor frecuencia y aquellos que tienen una presencia menos destacada.

### Conocimiento a Extraer:

El análisis del conjunto de datos para el proyecto de analítica de tendencia de YouTube para el país de Francia nos permitirá aprender y aplicar varios conceptos aprendidos y aplicados a lo largo del curso de ciencia de datos, como son:

- **Análisis Exploratorio de Datos (EDA):**
  - Comprender la estructura y características del conjunto de datos, el cual en este caso sería el dataset de Francia.
  - Identificar patrones y outliers del dataset de Francia, así mismo identificar datos faltantes y posibles cambios de filas o columnas del dataset.

- **Manipulación y Limpieza de Datos:**
  - Se debe realizar la limpieza de datos arreglando cualquier fallo detectado con anterioridad, así mismo realizar los cambios de filas o columnas respectivas en este caso dentro de un dataset nuevo el cual llamaremos clean FR.

- **Visualización de Datos:**
  - Responder a las preguntas planteadas anteriormente y representar los resultados de manera gráfica.

- **Análisis Geoespacial:**
  - Emplear las columnas de latitud, longitud, estado, etc., para visualizar los estados a través de la biblioteca Folium.

- **Modelado Predictivo:**
  - Hacer uso de regresión logística para responder las dos últimas preguntas dadas con anterioridad, lo cual nos permitirá conocer y aprender más sobre los modelos predictivos.

## II. INTEGRANTES DEL GRUPO Y ROLES

Describir cómo fueron asignados los roles a cada integrante del grupo, así como la relación de las tareas asignadas a cada uno, especificado en qué fase/etapa del proyecto se deben ejecutar durante la vigencia del proyecto.

| NOMBRE  | ROLES               |
|---------|---------------------|
| Pedro   | Data Science        |
|         | - Desarrollar y aplicar modelos predictivos para identificar tendencias. |
|         | - Realizar análisis de sentimiento en los comentarios de los videos.      |
|         | - Presentar hallazgos clave y recomendaciones estratégicas.                |
| Diego   | Data Analytics      |
|         | - Encargado de gestionar la recopilación y preparación de datos.          |
|         | - Utilizar la API de YouTube para recopilar datos relevantes de videos.   |
|         | - Limpiar y preprocesar los datos para su análisis.                         |
|         | - Garantizar la calidad de los datos.                                      |
| Cristian| Data Engineer        |
|         | - Encargado de gestionar la recopilación y preparación de datos.          |
|         | - Utilizar la API de YouTube para recopilar datos relevantes de videos.   |
|         | - Limpiar y preprocesar los datos para su análisis.                         |
|         | - Garantizar la calidad de los datos.                                      |
| Daniel  | Business Project Sponsor |
|         | - Encargado de liderar el proyecto.                                       |
|         | - Definir los objetivos generales del proyecto.                            |
|         | - Asegurarse de que el proyecto esté alineado con los objetivos estratégicos de la consultora. |
|         | - Facilitar la comunicación entre el equipo de proyecto y los interesados. |
## III. METODOLOGÍA CRISP-DM

### 1. COMPRENSIÓN DEL NEGOCIO

El análisis se centra en varios aspectos clave para mejorar la estrategia de marketing del cliente o empresa. La identificación de tendencias, basada en las categorías de vídeos más populares, sugiere la alineación estratégica con temas de alta demanda. Esto se traduce en la creación de contenido relevante para mejorar la visibilidad y el compromiso.

El entendimiento de las preferencias del público a través del análisis de categorías de vídeos más y menos populares proporciona información crucial para adaptar el contenido según las demandas del mercado objetivo. La optimización del contenido, evaluando las proporciones de "Me gusta" / "No me gusta" y "Vistas" / "Comentarios" en diferentes categorías, guía la creación de contenido más efectivo, maximizando la interacción positiva.

La identificación de canales de YouTube en tendencia y la frecuencia de su presencia permiten a la empresa asociarse estratégicamente con creadores de contenido populares, generando colaboraciones exitosas y aumentando la visibilidad de la marca. Además, el conocimiento de la segmentación geográfica, incluyendo los estados con mayor participación, proporciona una base sólida para personalizar estrategias de marketing según las preferencias regionales.

La capacidad de prever el rendimiento futuro, ya sea en términos de vistas, "Me gusta" o "No me gusta", brinda a la empresa una ventaja estratégica para planificar campañas de manera más efectiva, asignar recursos de manera óptima y anticiparse a las tendencias emergentes. En resumen, este enfoque analítico dinámico no solo facilita la adaptación a las preferencias del público, sino que también permite una mejora continua en la efectividad de las campañas de marketing a lo largo del tiempo.

#### Objetivos del Proyecto

El proyecto tiene como objetivo principal explorar y comprender las dinámicas de los videos de tendencia en YouTube específicamente en Francia. Se busca analizar el conjunto de datos proporcionado, responder preguntas clave sobre preferencias de contenido, cambios temporales en las tendencias, destacar canales de YouTube frecuentemente tendenciales y examinar la distribución geográfica de las interacciones.

El alcance incluye el uso de herramientas de ciencia de datos para realizar un análisis exploratorio detallado, manipulación y limpieza efectiva de datos, visualización gráfica de resultados, análisis geoespacial utilizando la biblioteca Folium, y la aplicación de modelos predictivos, como la regresión logística, para evaluar la posibilidad de predecir métricas clave como "Vistas", "Me gusta" o "No me gusta".

Por lo que, el proyecto busca proporcionar una visión completa de las preferencias y comportamientos de los usuarios de YouTube en Francia, aprovechando la riqueza de datos disponibles para obtener información valiosa y aplicar técnicas avanzadas de análisis de datos.

##### Por Categoría de Videos
1. ¿Qué categorías de videos son las de mayor tendencia?
2. ¿Qué categorías de videos son los que más gustan? ¿Y las que menos gustan?
3. ¿Qué categorías de videos tienen la mejor proporción (ratio) de “Me gusta” / “No me gusta”?
4. ¿Qué categorías de videos tienen la mejor proporción (ratio) de “Vistas” /“Comentarios”?

##### Por el tiempo transcurrido
5. ¿Cómo ha cambiado el volumen de los videos en tendencia a lo largo del tiempo?

##### Por Canales de YouTube
6. ¿Qué Canales de YouTube son tendencia más frecuentemente? ¿Y cuáles con menos frecuencia?

##### Por la geografía del país
7. ¿En qué Estados se presenta el mayor número de “Vistas”, “Me gusta” y “No me gusta”?

##### Adicionalmente, al cliente le gustaría conocer si
8. ¿Es factible predecir el número de “Vistas” o “Me gusta” o “No me gusta”?
9. ¿Los videos en tendencia son los que mayor cantidad de comentarios positivos reciben?

#### Objetivos de Data Science

- Lograr identificar patrones de tendencia en las visualizaciones de los videos de Youtube Francia.
- Recolectar los suficientes datos de las estadísticas de los videos para poder darles un valor.
- Realizar modelos predictivos para informar a la empresa de marketing sobre las categorías más influyentes.

### 2. COMPRENSIÓN DE LOS DATOS

Los datos recolectados a través de las estadísticas proporcionadas van a proceder a ser limpiados y analizados, para posteriormente conseguir la versión más ideal de estos mismos, que logren generar una mejor información sobre las tendencias en la red social Youtube Francia.

#### Recolectar los datos iniciales

Para recolectar los datos iniciales se descargaron del aula virtual los cuales son un dataset de Kaggle el cual fue modificado con nuevos apartados los cuales son:

- **state:** nombre del Estado perteneciente al país.
- **Lat:** latitud geográfica de ubicación del Estado.
- **lon:** longitud geográfica de ubicación del Estado.
- **Geometry:** (opcional) registra las coordenadas de las geometrías donde se ubica.

Este dataset se llama "FRvideos_cc50_202101.csv" el cual es un CSV con la información de los distintos campos. Después contamos con "FR_category_id.json", el cual es un archivo tipo JSON que nos es útil cuando estás trabajando con datos de YouTube para comprender las preferencias de los usuarios por medio de categorías.

Luego de la descarga se importaron al proyecto por medio de visual studio code en la carpeta code.


Con respecto a los datos con los cuales contamos en el dataset original son los siguientes:


## Descripción de los Campos en el Dataset
- Este proceso implica la identificación y la descripción de cada campo/columna

| Campo                | Descripción                                             |
|----------------------|---------------------------------------------------------|
| video_id             | Identificador único de cada video                       |
| trending_date        | Fecha en la que el video se volvió tendencia            |
| Title                | Título del video de YouTube                             |
| Channel_title        | Nombre del canal de YouTube                             |
| Category_id          | Identificador de la categoría del video                 |
| Publish_time         | Fecha y hora de publicación                              |
| Tags                 | Etiquetas del video                                     |
| Views                | Cantidad de vistas del video                             |
| Likes                | Cantidad de “likes” del video                            |
| Dislikes             | Cantidad de “dislikes” del video                         |
| Comment_count        | Cantidad de comentarios del video                        |
| Thumbnail_link       | Enlace de la miniatura del video                         |
| Comments_disabled    | Verificación si los comentarios están activados o desactivados |
| Ratings_disabled     | Verificación si los "likes" están activados o desactivados |
| Video_error_or_removed| Verificación si el video ha sido eliminado o sufrido un error |
| Description          | Descripción del video                                   |
| State                | Estado del país donde se publicó el video                |
| Lat                  | Latitud del estado                                      |
| Lon                  | Longitud del estado                                     |
| Geometry             | Geometría del estado                                    |

#### Exploración de los Datos

## Inspeccionar los datos

### Importación de bibliotecas

Se importan las bibliotecas necesarias para el análisis de datos, como NumPy para operaciones numéricas, Pandas para manipulación de datos, Statsmodels para modelado estadístico, y las bibliotecas de visualización Matplotlib y Seaborn. `%matplotlib inline` se utiliza para mostrar gráficos directamente en el cuaderno si estás utilizando Jupyter Notebook.

### Importación de datos desde un archivo CSV:

Se lee un archivo CSV ("FRvideos_cc50_202101.csv") y se carga en un DataFrame de Pandas llamado FR_df. Este DataFrame probablemente contiene datos sobre videos de YouTube en Francia.

### Importación de datos desde un archivo JSON:

Se lee un archivo JSON ("FR_category_id.json") que probablemente contiene información sobre las categorías de videos de YouTube en Francia. Los datos relevantes se extraen y se almacenan en el diccionario FR_category.

## Configuración de opciones de visualización de Pandas:
Se configuran las opciones de visualización de Pandas para mostrar todas las columnas, todas las filas y desplegar el contenido completo de las columnas.


## VISUALIZAR LOS DATOS

### Visualización de una muestra de datos

Se imprime una muestra aleatoria de 3 filas del DataFrame FR_df para examinar la estructura y el contenido de los datos. Esto puede ayudar a entender cómo se ven los datos y qué información contienen.

## Verificar la calidad de los datos

Para verificar la calidad de los datos se realizaron los siguientes análisis:

### Valores nulos en cada columna:
Este código muestra la cantidad de valores nulos en cada columna del DataFrame FR_df.

### Análisis estadístico básico:
Calcula estadísticas descriptivas como la media, la moda, la desviación estándar, etc., para las columnas numéricas del DataFrame.

### Identificación y análisis de valores atípicos:
Calcula los valores atípicos (outliers) en las columnas especificadas y muestra cuántos valores atípicos hay en cada columna.

### Información sobre tipos de datos y cantidad de filas duplicadas:
FR_df.info() proporciona información sobre los tipos de datos y la cantidad de valores no nulos en cada columna.

FR_df[FR_df.duplicated()].shape[0] cuenta la cantidad de filas duplicadas en el DataFrame.

### Verificación de comentarios deshabilitados y videos con errores o removidos:
Muestra la cantidad de videos con comentarios deshabilitados y la cantidad de videos con errores o que han sido removidos.

## Problemas reportados y consideraciones:

**Problemas Reportados:**
1. El tipo de dato de `category_id` debe ser objeto y no entero.
2. El tipo de dato de `trending_date` y `publish_time` deben ser datetime en vez de object.
3. Hay datos atípicos, especialmente en las columnas `views`, `likes`, `dislikes`, y `comment_count`, por lo que es necesario aplicarles una transformación.
4. Hay columnas innecesarias como 'thumbnail_link', 'tags', 'description'.

**Consideraciones:**
1. La única columna con valores NA es `description`.
2. No hay columnas duplicadas.
3. Hay videos removidos, likes deshabilitados y comentarios deshabilitados, los cuales deben tenerse en cuenta al realizar el análisis.
4. No hay datos vacíos.

### 3. PREPARACIÓN DE LOS DATOS
Primero que todo creamos un nuevo dataframe el cual llamaremos “copy_FR” en el cual haremos los cambios respectivos.

#### Limpiar los Datos

### Eliminar columnas innecesarias ('thumbnail_link', 'tags', 'tags', 'description').
Este código elimina las columnas innecesarias ('thumbnail_link', 'tags', 'tags', 'description') del DataFrame copy_FR.

### Cambio del tipo de dato de 'category_id':
-Se cambia el tipo de dato de la columna 'category_id' a tipo de dato de cadena (str) para que sea un categórico nominal y se nos facilite trabajar con futuras bibliotecas

#### Transformación de las columnas de fechas:

Estos códigos convierten las columnas de fecha ('trending_date' y 'publish_time') al formato de fecha y hora adecuado para un manejo más adecuado de los datos.

Verificamos los resultados  en cuestión

#### Aplicación de transformación logarítmica:
Aplica la transformación logarítmica a las columnas seleccionadas ('views', 'likes', 'dislikes', 'comment_count') para reducir el sesgo en los datos.

#### Visualización de los resultados de la transformación logarítmica:
Muestra gráficos de caja (boxplots) para visualizar los resultados de la transformación logarítmica en las columnas seleccionadas.

#### Construir Nuevos Datos:

### Resetear el índice del DataFrame:
Esta línea de código restablece el índice del DataFrame copy_FR y descarta el índice anterior.

### Guardar el DataFrame en un archivo CSV:
Guarda el DataFrame copy_FR en un archivo CSV llamado 'clean_FR.csv'.

### Cargar el archivo CSV y realizar ajustes: 
Carga el archivo CSV en un nuevo DataFrame llamado clean_FR y elimina la columna 'Unnamed: 0', que parece ser un índice adicional guardado en el archivo CSV.

### Convertir columnas de fechas a tipo datetime:
Convierte las columnas 'publish_time' y 'trending_date' a tipos de datos datetime64.

### Mostrar información del DataFrame clean_FR: 
Muestra información sobre el DataFrame clean_FR después de realizar las operaciones anteriores.

#### Requerimientos

1. ¿Qué categorías de videos son las de mayor tendencia?

   - Se puede apreciar que las categorías con mayor cantidad de vistas son la: 24,22,23,17,10
     
2. ¿Qué categorías de videos son los que más gustan? ¿Y las que menos te gustan?
   - Las categorías con mayor cantidad de “me gusta” son la 24,23,22,10,17; respectivamente.
   - Las categorías con mayor cantidad de “no me gusta” son la 24,22,23,10,17; respectivamente
     
3. ¿Qué categorías de videos tienen la mejor proporción (ratio) de“Me gusta” / “No me gusta"?
   - La proporción demuestra que la categoría que tiene una mejor valoración de “me gusta” frente a “no me gusta” es la categoría 44.
     
4. ¿Qué categorías de videos tienen la mejor proporción (ratio) de “Vistas” /“Comentarios”?
   - Se puede evidenciar que la categoría con mayor cantidad de comentarios es la número 29.
  
5. ¿Cómo ha cambiado el volumen de los videos en tendencia a lo largo del tiempo?
   - Se puede verificar que la cantidad de números en tendencia se ha visto reducida con el paso de los años.
     
6. ¿Qué canales de YouTube son tendencia más frecuentemente? ¿Y cuáles con menos frecuencia?
   - Acorde al gráfico se puede verificar que el canal más visto según los datos es Troom.
   - Acorde al gráfico se puede verificar que el canal menos visto según los datos es LeSurvivaliste.
     
7. ¿En qué Estados se presenta el mayor número de “Vistas”, “Me gusta” y “No me gusta”?
   - El estado donde la gente da más “me gusta” es Provence Alpes.
   - El estado donde la gente da más “no me gusta” es de igual forma Provence Alpes.
   - El estado donde la gente mira más videos de Youtube es Provence Alpes.
     
8. ¿Es factible predecir el número de “Vistas” o “Me gusta” o “No me gusta”?
   - En este modelo se ha realizado un modelo predictivo de la cantidad de “dislikes” a futuro por cada cantidad de vistas.
  
9. ¿Los videos en tendencia son los que mayor cantidad de comentarios positivos reciben?
    - No necesariamente los videos en tendencia son los que mayor cantidad de comentarios positivos reciben.



### 4. MODELIZAR Y EVALUAR LOS RESULTADOS

#### Escoger la Técnica de Modelado
En este caso se ha utilizado tanto la regresión lineal, como la regresión logística.
La regresión lineal fue utilizada para predecir la cantidad de “no me gusta” basado en las estadísticas actuales.
La regresión logística fue utilizada para modelar los comentarios positivos que recibirán los videos futuros acorde a los ”me gusta”, “no me gusta” y las visitas.	

#### Generar el Plan de Prueba
En este caso hemos utilizado tanto los dislikes, como las visitas para realizar el modelado del entrenamiento de los “no me gusta” a futuro que tendrán los videos de Youtube.

#### Construir el Modelo
A continuación, se ejecuta la técnica seleccionada sobre los datos previamente preparados para generar uno o más modelos.

#### Evaluar el Modelo
Se puede apreciar que los modelos han alcanzado una precisión de más de 0.9, por lo que a largo plazo los datos serán correctos.

### 5. CONCLUSIONES

En síntesis, mediante la aplicación de la metodología CRISP-DM en el análisis de datos, se ha adquirido información valiosa acerca de las tendencias de videos en Francia. Estos insights posibilitará la implementación de estrategias de marketing más eficaces y la personalización de productos para adecuarse a las necesidades y preferencias de distintos segmentos de clientes. Es fundamental resaltar la importancia de la constancia y la reflexión en cada fase del proyecto de Ciencia de Datos, con el fin de potenciar los resultados obtenidos y perfeccionar las decisiones adoptadas.

Sabiendo que la categoría 24 tiene mayor tendencia a ser visto en Francias, esto nos permite ofrece una perspectiva valiosa sobre el comportamiento del consumidor. Además que también otorga a las empresas de Marketing la posibilidad de tomar decisiones más fundamentadas y ajustarse de manera efectiva a las cambiantes dinámicas del mercado. 

Identificar las categorías de vídeos más populares ofrece a una empresa de marketing la oportunidad de crear contenido atractivo, segmentar audiencias específicas y optimizar la colocación de anuncios para maximizar la visibilidad. Por otro lado, comprender las categorías menos populares permite evitar inversiones en contenido con menor atractivo, identificar oportunidades de nicho y diversificar estrategias para sorprender y atraer audiencias específicas. En conjunto, esta información proporciona a la empresa la flexibilidad necesaria para adaptarse a las preferencias del público, maximizar la efectividad de sus campañas y posicionarse de manera más estratégica en el mercado.


### 6. BIBLIOGRAFÍA

1. [Trending YouTube France Group 2](https://github.com/QuispeAyalaDiego/Trending-Youtube-FR-G02) - Quispe Ayala, D.
2. [Regresión Lineal](https://ebac.mx/blog/regreson-lineal) - Escuela de Negocios Europea de Barcelona.
3. [What Is Logistic Regression?](https://aws.amazon.com/es/what-is/logistic-regression/) - Amazon Web Services.
4. [Análisis y Modelado con Pandas](https://www.diegocalvo.es/pandas-analisis-y-modelado/) - Calvo, D.
5. [Regresión Lineal Simple](https://bitsandbricks.github.io/ciencia_de_datos_gente_sociable/5-1-regresi%C3%B3n-lineal-simple.html) - Bits & Bricks.
