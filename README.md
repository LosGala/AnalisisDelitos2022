# Análisis de Delitos en la Ciudad de Buenos Aires (2022)

Este proyecto analiza datos de delitos ocurridos en la Ciudad de Buenos Aires durante el año 2022, obtenidos del portal [Buenos Aires Data](https://data.buenosaires.gob.ar/dataset/delitos).

## Descripción del Dataset
El dataset contiene 132,098 registros con 15 columnas que incluyen información sobre:
- Ubicación (barrio, comuna, coordenadas geográficas)
- Fecha y hora del delito
- Tipo y subtipo de delito
- Características del hecho (uso de arma, uso de moto)
- Cantidad de casos

## Requisitos
- Python 3.x
- Bibliotecas:
  - pandas
  - plotly
  - plotly.graph_objects

## Instalación
```bash
pip install pandas plotly
```

## Análisis Realizados
El proyecto incluye los siguientes análisis y visualizaciones:

### 1. Distribución temporal de delitos
- Por mes del año
- Por día de la semana
- Por franja horaria

### 2. Distribución geográfica
- Por barrio
- Por comuna
- Mapa interactivo con densidad de delitos

### 3. Tipos de delitos
- Frecuencia por categoría (Robo, Hurto, Vialidad, etc.)
- Subtipos más comunes

### 4. Características de los delitos
- Uso de armas
- Uso de motos

## Visualizaciones
El proyecto genera múltiples gráficos interactivos usando Plotly, incluyendo:
- Gráficos de barras para distribución temporal
- Mapas de calor geográficos
- Gráficos comparativos por categorías

## Ejecución
Para ejecutar el análisis completo, simplemente ejecute el script Python proporcionado. Asegúrese de tener el archivo `delitos_2022.csv` en el mismo directorio o actualice la ruta en el código.

## Resultados Destacados
1. Los tipos de delitos más frecuentes son Robo (56,114 casos) y Hurto (54,111 casos)
2. Los meses con mayor criminalidad son octubre, noviembre y diciembre
3. Los viernes son el día con más delitos registrados
4. Palermo es el barrio con mayor cantidad de delitos registrados (10,895 casos)

## Licencia
Los datos son proporcionados por el Gobierno de la Ciudad de Buenos Aires bajo la licencia de datos abiertos. El código de este proyecto es de uso libre.

