# PROYECTO INDIVIDUAL Nº2: Data Analitycs
## Siniestros viales, Ciudad de Buenos Aires

![siniestro-viales-3](https://github.com/JoyceRuGu/PI2_Data_Analitycs/assets/134313088/3dc04ea5-6b27-45f7-9890-79c72c17998b)

## INTRODUCCIÓN

Los siniestros viales son situaciones graves que afectan principalmente a automoviles, motociclistas, peatones y que pueden comprometer seriamente la seguridad y la movilidad.

El propósito principal de este proyecto es analizar y entender los datos asociados a estos siniestros viales, con el objetivo de mejorar la seguridad y movilidad en la ciudad de Buenos Aires y evitar siniestros viales futuros. La OMSV, centro de estudios que depende de la Secretaría de Transporte del Gobierno de la Ciudad Autónoma de Buenos Aires, nos proporciona un conjunto de datos sobre homicidios en siniestros viales ocurridos en la Ciudad de Buenos Aires durante el periodo 2016-2021

### Explicación ETL (Extract, Transform, Load) para la limpieza de los conjuntos de datos suministrados:

Extracción:
Se reemplazaron los valores etiquetados como 'SD' por NaN para mejorar la consistencia y facilitar el análisis. se
eliminaron las columnas redundantes e innecesarias en cada hoja del dataset.

Transformación:
Se eliminaron los espacios adicionales para garantizar la coherencia y evitar problemas en el análisis; Se realizaron cambios en los nombres de las columnas para estandarizar y mejorar la claridad del conjunto de datos, se convirtiron columnas a formatos apropiados, ajustando tipos de datos según la información contenida. y por ultimo se categorizaron las columnas con conjuntos limitados de valores para simplificar el análisis exploratorio y mejorar la comprensión de las distribuciones.

Carga:
Se generaron hojas limpias y listas para la unificación y su análisis posterior.
En resumen, estas acciones de ETL asegura que el datasets esté preparado y estandarizado, proporcionando una base sólida para análisis porteriores.

### EDA (Analísis Exploratorio de los Datos)
Después de completar el proceso de Extracción, Transformación y Carga (ETL) y generar el dataset consolidado, nos embarcamos en la fase de Análisis Exploratorio de Datos (EDA). Este paso implica sumergirse en la información detallada de los eventos desafortunados que queremos comprender a fondo.

Análisis estadístico y visualización de los datos:

. Creación de gráficos y visualizaciones para identificar patrones y relaciones entre las variables.

. Identificación de variales con mas siniestros viales.

. Identificación de comuna, rol, rango etario y tipos de vehiculos con mayor cantidad de fallecidos en dichos siniestros

### Dashboard

![image](https://github.com/JoyceRuGu/PI2_Data_Analitycs/assets/134313088/3ae08dda-6807-4d1b-9a8c-bcb61accfb93)

Para finalizar con el proyecto, se realizo un dashboard interactivo en PowerBI para presentar el proyecto. El cual se encuentra en este mismo repositorio y se puede descargar y utilizar. Cuenta con 1 portada y 5 páginas.

### Analisis General 
En este análisis , aplicamos filtros tanto por año como por comuna. Esta configuración nos permite examinar los siniestros de manera detallada, segmentándolos por año, trimestre y mes. Además, hemos incluido un panel que proporciona una visión rápida de la cantidad de víctimas y siniestros por mes, junto con un resumen total de víctimas y siniestros en otro panel.

![image](https://github.com/JoyceRuGu/PI2_Data_Analitycs/assets/134313088/0504cf22-9e17-4fd0-a50a-1ed07683bdcf)

###### Analisis por Vehículos, Rol, Genero y Edad

Este análisis no solo nos brinda una visión general de los vehículos que están involucrados en la mayor cantidad de siniestros y los vehículos que más sufren estos incidentes, sino que también nos permite profundizar en el papel de cada participante en el siniestro. Además, exploramos la edad promedio de los involucrados y analizamos la participación por género para obtener una comprensión más completa del panorama.

![image](https://github.com/JoyceRuGu/PI2_Data_Analitycs/assets/134313088/18cad4dc-bdbc-4860-ac64-db852e7d26c0)

##### Analisis de geocalización


En este análisis, recurrimos a la aplicación de filtros por comuna, tipo de calle y franja horaria con el propósito de identificar las calles con un riesgo más elevado de siniestros viales. tambien examinar las horas del día y las comunas con una probabilidad más alta de siniestros, con la finalidad de emprender acciones preventivas para los próximos años.

![image](https://github.com/JoyceRuGu/PI2_Data_Analitycs/assets/134313088/3e696eac-aad3-42a2-9980-f182fad1d2c2)

### KPIS

#### N° 1 Reducir en un 10% la tasa de homicidios en siniestros viales de los últimos seis meses, en CABA, en comparación con la tasa de homicidios en siniestros viales del semestre anterior.
 
Desarrollo del primer KPI 
Se tomaron como datos de refencia las proyecciones nacionales realizadas en CABA para el año 2021, teniendo en cuenta que la segmentación de la proyección anual es ejecutada a corte primero de julio. Se calcula la tasa de homicidio por semestres del año 2021, teniendo en cuenta el número total de la población para el semestre 1 del año 2021 y el semestre 2 del mismo año así: no. total de homicidios semestre/Población total 2021 * 100.000.

Se identificó el total de homicidios durante el año y se presentaron los datos totales por semestres, finalmente se determinó el target como la tasa de homicidios esperada con una reducción del 10%.
Ref https://www.indec.gob.ar/indec/web/Nivel4-Tema-2-24-84

![image](https://github.com/JoyceRuGu/PI2_Data_Analitycs/assets/134313088/6f1273da-5f0d-4e74-9d27-33f26ea543ec)

#### N° 2  Reducir en un 7% la cantidad de accidentes mortales de motociclistas en el último año, en CABA, respecto al año anterior.

Desarrollo del segundo KPI
Se tomaron los datos de los siniestro viales que involucraban motocicleta, se calculó el total de víctimas (moto 2021). Posteriormente, se calculó la reducción porcentual esperada (7%) con respecto a la cantidad de siniestros mortales del año anterior. Hallando la variación porcentual entre años.

![image](https://github.com/JoyceRuGu/PI2_Data_Analitycs/assets/134313088/f05cab8f-ab43-4551-a3bd-d68f903fbcbe)

### Conclusión 


Después de analizar los datos proporcionados por el Observatorio de Movilidad y Seguridad Vial (OMSV), podemos llegar a las siguientes conclusiones:

A pesar de un aumento en comparación con el año anterior, se observa una marcada reducción en la tasa de mortalidad en comparación con años anteriores. Es importante destacar que, aunque se experimentó un incremento respecto al año anterior, la tendencia general ha sido positiva en comparación con años previos.

En cuanto a los siniestros de motocicletas, se ha registrado un aumento del 2.9% en comparación con 2016 y un incremento del 5.44% con respecto a 2020.

Se destaca la necesidad de prestar especial atención a los siniestros que involucran motocicletas, ya que son los vehículos que presentan una mayor incidencia en siniestros fatales.




