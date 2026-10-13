# Pipeline ETL Completo con Power BI

## Descripción 

Este proyecto consiste en el desarrollo de un proceso ETL utilizando **Power BI y Power Query**, con el objetivo de transformar datos crudos en un conjunto de datos 
limpio, consistente y preparado para su análisis.
A partir de un archivo Excel con información de clientes, productos, categorías y ventas, se realizaron tareas de limpieza, transformación, validación y 
combinación de datos para construir una base confiable para futuros análisis y visualizaciones.

## Estructura de los datos

- Identificación y eliminación de registros duplicados utilizando los identificadores correspondientes.
- Eliminación de filas completamente vacías.
- Revisión y tratamiento de valores nulos.
- Corrección de tipos de datos, incluyendo fechas, identificadores, cantidades y valores de dinero.
- Analisis de datos faltantes.
- Revisión de la consistencia entre productos, categorías y ventas.
- Combinación de `Fact_Ventas` con `Dim_Productos` mediante el campo `id_producto`, utilizando una unión externa izquierda.
- Incorporación del nombre y la categoría del producto a la tabla de ventas.
