# Análisis de Dataset de Yelp con PySpark

Este proyecto utiliza PySpark para manipular y analizar un dataset de Yelp. Incluye pasos para extraer archivos, cargar datos en un DataFrame, optimizar tipos de datos, y particionar datos para consultas eficientes.

## Descripción

El proyecto tiene como objetivo analizar un conjunto de datos de Yelp, específicamente el archivo de reseñas en formato JSON. Se realizan los siguientes pasos:

1. Extracción de archivos desde un archivo `.tar`.
2. Carga de un archivo JSON en un DataFrame de PySpark.
3. Cuantificación del tamaño del archivo JSON en disco y del DataFrame en memoria RAM.
4. Conversión del archivo JSON a formato Parquet y comparación de tamaños.
5. Optimización de tipos de datos de columnas en el DataFrame.
6. Particionamiento del DataFrame optimizado y almacenamiento en formato Parquet.
7. Ejecución de consultas sobre el DataFrame particionado.

## Requisitos Previos

- Python 3.x
- Apache Spark
- PySpark
- Java (JDK)
- Bibliotecas Python necesarias: `tarfile`, `os`, `time`, `py4j`

## Instalación

1. **Instalar Apache Spark**: Sigue las instrucciones oficiales de [Apache Spark](https://spark.apache.org/downloads.html).
2. **Instalar PySpark**: Puedes instalar PySpark usando `pip`:

   ```bash
   pip install pyspark

