# Master Big Data - Text_mining
## Ejercicio 1 - Resumen del enunciado
### Objetivo: detectar contenido de odio en Tweeter
Dataset de tweeter con con tweets clasificados con las siguientes variables:
religion
age
ethnicity
gender
other_cyberbullying
not_cyberbullying
El objetivo inicial del dataset era su uso para entrenar un modelo capaz de detectar el tipo de contenido de odio presente en internet según el colectivo al que se atacaba. En este caso, para simplificar el ejercicio, se ha generado una función load_prepare_data() que cambia las categorías del dataset obteníendose al final 2 categorías con valor 1 o 0, indicando si el tweet tiene contenido de odio

Para el ejercicio debéis entrenar diferentes modelos de clasificación que permitan clasificar correctamente los tweets. Para ello será necesario crear y utilizar funciones de preprocesado de datos similares a las vistas en clase, aplicar estrategias de vectorización de trextos como TF-IDF o embeddings, y entrenar/evaluar modelos de clasificación. Para que os sirva de orientación, los criterios de evaluación del ejercicio serán los siguientes:

**Análisis exploratorio, pre-procesado y normalización de los datos** (30%): - El ejercicio deberá contener un análisis exploratorio de los datos como número de documentos, gráficas de distribución de longitudes y/o wordclouds, entre otros análisis que se os pudieran ocurrir. Vuestros ejercicios deberán incorporar al menos los análisis exploratorios vistos en clase.

También tendréis que tener funciones para **normalizar textos** que permitan eliminar palabras vacías, quitar símbolos de puntuación y lematizar o hacer stemming.
Vectorización de textos (40%)

En clase hemos visto diferentes **estrategias de vectorización como TF-IDF y Word Embeddings**. Será necesario incorporar características adicionales como el sentimiento o características léxicas.

**Entrenamiento y validación del sistema** (30%)

## Ejercicio 2 - Resumen del enunciado
### Objetivo: detectar contenido de odio en Tweeter
