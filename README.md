# Análisis Exploratorio de Datos Financieros

Este es un proyecto de análisis exploratorio de datos **ficticios** proporcionados por una entidad financiera. 
El objetivo de este análisis es comprender las transacciones realizadas, los montos, los barrios desde donde se realizaron y los canales más utilizados. 
Los datos proporcionados se combinan con datos gubernamentales de estratificación investigados con el fin de proporcionar una perspectiva más amplia del contexto socioeconómico.

## Fuentes de Datos

Este proyecto utiliza los siguientes conjuntos de datos:

- Conjunto de datos de transacciones (proporcionado).
- Datos gubernamentales de estratificación (consultados en sitios oficiales).

## Estructura del Repositorio

- `AnalisisExploratorio_prueba.ipynb`: el script de análisis exploratorio de datos.
- `Bases_insumo/`: carpeta que contiene los archivos proporcionados por la entidad sobre las transacciones, los barrios implicados y los dospositivos.
- `df_join.csv`: archivo que contiene los datos de las transacciones consolidados
- `estratificacion_cali.csv`: Archivo con la estratificación de la ciudad de Cali descargado de plataformas oficiales.
- `estratificacion_cali_clean.csv`: Archivo con la estratificación procesado para hacer merge con los datos principales.
- `README.md`: este archivo README.

## Librerías utilizadas

El análisis exploratorio de datos se realizó utilizando las siguientes librerías de Python:

- Pandas
- Numpy
- matplotlib.pyplot
- seaborn
- pandasql
- statsmodels.api
- reverse_geocoder

## Conclusiones

Las conclusiones del análisis exploratorio de datos se encuentran en el archivo `AnalisisExploratorio_prueba.ipynb`.
Es importante aclarar que **así como los datos son ficticios, las conclusiones también lo son**.

## Autoría

Este proyecto fue creado por **Miguel Sosa**.
