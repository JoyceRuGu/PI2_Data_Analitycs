                                                                # PROYECTO INDIVIDUAL Nº2: Data Analitycs

                                                                # Siniestros viales, Ciudad de Buenos Aires


                                                                ![Alt text](image.png)

INTRODUCCIÓN

Los siniestros viales son situaciones graves que afectan principalmente a automoviles, motociclistas, peatones y que pueden comprometer seriamente la seguridad y la movilidad.

El propósito principal de este proyecto es analizar y entender los datos asociados a estos siniestros viales, con el objetivo de mejorar la seguridad y movilidad en la ciudad de Buenos Aires y evitar siniestros viales futuros. La OMSV, centro de estudios que depende de la Secretaría de Transporte del Gobierno de la Ciudad Autónoma de Buenos Aires, nos proporciona un conjunto de datos sobre homicidios en siniestros viales ocurridos en la Ciudad de Buenos Aires durante el periodo 2016-2021

Explicación ETL (Extract, Transform, Load) para la limpieza de los conjuntos de datos suministrados:

Extracción:
Se reemplazaron los valores etiquetados como 'SD' por NaN para mejorar la consistencia y facilitar el análisis. se
eliminaron las columnas redundantes e innecesarias en cada hoja del dataset.

Transformación:
Se eliminaron los espacios adicionales para garantizar la coherencia y evitar problemas en el análisis; Se realizaron cambios en los nombres de las columnas para estandarizar y mejorar la claridad del conjunto de datos, se convirtiron columnas a formatos apropiados, ajustando tipos de datos según la información contenida. y por ultimo se categorizaron las columnas con conjuntos limitados de valores para simplificar el análisis exploratorio y mejorar la comprensión de las distribuciones.

Carga:
Se generaron hojas limpias y listas para la unificación y su análisis posterior.
En resumen, estas acciones de ETL asegura que el datasets esté preparado y estandarizado, proporcionando una base sólida para análisis porteriores.

EDA (Analísis Exploratorio de los Datos)
Después de completar el proceso de Extracción, Transformación y Carga (ETL) y generar el dataset consolidado, nos embarcamos en la fase de Análisis Exploratorio de Datos (EDA). Este paso implica sumergirse en la información detallada de los eventos desafortunados que queremos comprender a fondo.

Análisis estadístico y visualización de los datos:

. Creación de gráficos y visualizaciones para identificar patrones y relaciones entre las variables.

. Identificación de variales con mas siniestros viales.

. Identificación de comuna, rol, rango etario y tipos de vehiculos con mayor cantidad de fallecidos en dichos siniestros
