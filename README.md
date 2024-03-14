# TP 01: Manejo de datos y su visualización

En este repositorio se presenta el primer Trabajo Práctico para la materia Laboratorio de Datos de la carrera de Licenciatura en Ciencia de Datos.

Los temas evaluados, de la materia, son:
- Diagramas de Entidad-Relación (DER)
- Modelos relacionales
- Calidad de los datos
- Manipulación y limpieza de los datos
- Análisis y visualización de los datos

## Sobre el Proyecto

### Objetivo del proyecto:
Saber si existe cierta relación entre el PBI (Producto Bruto Interno) por persona de cada
país (año 2022) y la cantidad de sedes en el exterior que tiene Argentina en dicho país,
mediante la utilización de datos del Banco Mundial y Ministerio de Relaciones Exteriores,
Comercio Internacional y Culto.

### Fuentes

- PBI per cápita de los países (PBI en inglés es GDP, por Gross Domestic Product). Se puede obtener del sitio del Banco Mundial: https://data.worldbank.org/indicator/NY.GDP.PCAP.CD, descargando los csv y accediendo al archivo API_NY.GDP.PCAP.CD_DS2_en_csv_v2_6298251.csv

<p align=center> <img src='img\descarga.png' style = 'width:300px'></p>

- Representaciones Argentinas. El responsable de estas fuentes de datos es el actual
Ministerio de Relaciones Exteriores, Comercio Internacional y Culto, y pueden ser obtenidas
del sitio que se detalla a continuación:
https://datos.gob.ar/dataset/exterior-representaciones-argentinas. En dicho sitio podrán
acceder a los siguientes datos:
    - Datos básicos de las sedes
    - Datos completos de las sedes
    - Datos completos de las secciones de las sedes

<p align=center> <img src='img\min_relac.exter.y.culto.jpg' style = 'width:300px' > </p>

## Información del Repositorio

### Descripción de los archivos

- tp1.pdf: es el informe del proyecto, tanto el analisis como las concluciones realizadas.
- tp1.py: codigo utilizado para el analisis de los datos.

### Descripción de las carpetas

- TablasOriginales: se encuentra los archivos descargados de las fuentes en formato csv.
- TablasLimpias: se encuenrta las tablas normalizadas y limpias de la información selecionada pra realizar el informe.

- img: se encuentran las imagenes usadas para README.md

## Stack
<p align=center>  <img src = 'img\Python_logo_and_wordmark.svg.png' style="width:300px"> <img src='img\Sql_data_base_with_logo.png' style = 'width:200px' > <img src='img\Pandas_logo.svg.png' style = 'width:300px'>  <img src='img\2560px-NumPy_logo_2020.svg.png' style = 'width:300px'> <img src='img\seaborn.png' style = 'width:300px'> <img src='img\matplot_title_logo.png' style ='width:300px'> </p>


## Información sobre las librerias

### Versiones de los modulos/librerias 

inline_sql==0.1.2<br>
matplotlib==3.7.1<br>
numpy==1.25.2<br>
pandas==1.5.3<br>
seaborn==0.13.1

### Comando para intalar todas las librerias:
Luego de clonar el repositorio.
```
pip install -r requirements.txt
```
**Aconsejamos usar un entorno virtual.**