# Proyecto área de imágenes
## *Content based image retrieval*
## Integrantes:
## Benjamín Castro
## Melanie Peña
## Profesor:
## Carlos Navarro
## Ayudante:
## Jorge Zambrano
## **EL5206 Laboratorio de inteligencia computacional y robótica**

### Introducción
El siguiente buscador de imágenes basado en contenido corresponde a utilizar una imagen de consulta y encontrar las imágenes más similares desde una base de datos. Se tienen dos modos de uso: utilizando extracción de características por LBP y por red neuronal VGG-16. Además, está la versión con y sin optimización PCA.

### Instrucciones de uso del buscador:
La búsqueda se realiza con la función **results** y **results_opt**, respectivamente, donde se presentan las 10 imágenes más relevantes de la búsqueda. La imagen de consulta se introduce mediante un *string* con el nombre de la imagen. Para el código es recomendable tener los paquetes .tar-gz ya descargados, sin embargo, si este no los encuentra, los descarga directamente (tarda un poco). Además, en este repositorio hay dos archivos .zip que contienen, respectivamente, diccionarios con los vectores característicos de las imágenes de *query* y de la base de datos para cada modo. Las demás instrucciones se muestran en los bloques de código del *jupyter notebook* (puede consultar sus instrucciones directamente). Además, se añade un bloque de prueba para medir tiempos de ejecución de los algoritmos.
