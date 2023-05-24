# Data Analytics de Accidentes de Aviones

Este proyecto de Data Analytics se centra en el análisis de un dataset de accidentes de aviones. El objetivo principal es extraer información relevante y obtener insights sobre la tasa de mortalidad, la distribución geográfica de los accidentes y la tendencia a lo largo del tiempo.

##

Dataset
El dataset utilizado contiene información detallada sobre los accidentes de aviones y se encuentra en el archivo "AccidentesAviones_clean.csv". Las columnas del dataset incluyen:

datetime: Fecha y hora del accidente.

location: Ubicación del accidente.

operator: Operador de la aeronave.

route: Ruta del vuelo.

type: Tipo de aeronave.

all_aboard: Número total de personas a bordo del vuelo involucrado en el accidente.

passengers_aboard: Número de pasajeros a bordo.

crew_aboard: Número de tripulantes a bordo.

total_fatalities: Número total de fallecidos en el accidente.

passengers_fatalities: Número de pasajeros fallecidos.

crew_fatalities: Número de tripulantes fallecidos.

ground: Número de personas en tierra fallecidas.

summary: Resumen o descripción del accidente.

category: Categoría del accidente.

flight_type: Tipo de vuelo (Militar, Civil grande, Civil chico).

mortality_rate: Tasa de mortalidad en el accidente.


## KPIs Calculados

El análisis se basó en tres KPIs principales:

Tasa de mortalidad promedio: Calcula el promedio de la tasa de mortalidad en todos los accidentes registrados en el conjunto de datos.

Distribución geográfica de accidentes: Identifica las regiones o países con la mayor cantidad de accidentes de aviones.

Tendencia de accidentes a lo largo del tiempo: Analiza la cantidad de accidentes de aviones registrados por año o por mes para detectar posibles patrones o cambios significativos.

Reducción del 5% en la tasa de mortalidad anual: Establece como objetivo reducir en un 5% la tasa de mortalidad anual en comparación con el año anterior. Esta métrica muestra el progreso en la mejora de la seguridad y prevención de accidentes aéreos.

## Herramientas Utilizadas

Python: Se utilizó Python para realizar el análisis de datos, el cálculo de KPIs y la limpieza del dataset.
Power BI: Se empleó Power BI para crear visualizaciones interactivas y un dashboard para presentar los resultados.

## Archivos del Proyecto

AccidentesAviones_clean.csv: Archivo CSV que contiene el dataset limpio utilizado en el análisis.
AccidentesAviones_Analisis.ipynb: Jupyter Notebook que contiene el código de Python utilizado para el análisis de datos.
AccidentesAviones_Reporte.pbix: Archivo Power BI con el dashboard interactivo y las visualizaciones generadas.
