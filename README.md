# Pre-entrega 3 · Clasificador supervisado de AG News

## Justificación del modelo

El modelo seleccionado fue LinearSVC porque trabaja con matrices TF-IDF dispersas de alta dimensión y permite asignar una categoría por noticia. La elección responde al objetivo de clasificación y a las características de los datos. La comparación experimental se concentró en los parámetros de TF-IDF.

## Análisis preliminar

Se identifican a Business como la categoría con menor F1 (0,8518). El cruce principal fue Sci_Tech → Business, con 45 casos, seguido de Business → Sci_Tech, con 41. Juntas, ambas direcciones explican 86 de los 208 errores (41,3 %). La noticia sobre la oferta de Oracle por PeopleSoft ilustra cómo un mismo texto puede combinar vocabulario tecnológico y financiero.

## Archivo de Requerimientos

El archivo requirements.txt contiene las dependencias de las tres pre-entregas del
curso DataScience 3 - NLP
