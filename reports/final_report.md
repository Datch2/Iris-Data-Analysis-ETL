# Iris Data Analysis – ETL Project

## Objetivo
Implementar un flujo ETL básico utilizando el dataset Iris, aplicando procesos de carga, limpieza,
validación de calidad y análisis exploratorio de datos.

## Proceso

### 1. Extracción
Se cargó el dataset original desde la carpeta `data/raw`.

### 2. Transformación
- Normalización de nombres de columnas.
- Eliminación de la columna `id`.
- Identificación y eliminación de registros duplicados.
- Validación de valores nulos y rangos lógicos.

### 3. Carga
El dataset limpio fue almacenado en `data/processed/iris_clean.csv`.

## Resultados
- El dataset final contiene datos consistentes y sin valores duplicados.
- Se observaron diferencias claras entre especies en las variables morfológicas.
- Las visualizaciones permiten comprender la distribución y variabilidad de los datos.

## Conclusiones
El proceso ETL permitió transformar datos crudos en un dataset confiable, listo para análisis
y futuros modelos de machine learning.
