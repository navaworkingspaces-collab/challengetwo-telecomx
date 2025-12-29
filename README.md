# Telecom X – Challenge ETL

## Propósito
**Objetivo:** aplicar un proceso ETL con Python (Pandas) sobre datos de TelecomX para habilitar análisis y visualizaciones.

## Estructura del proyecto
- data/raw: datos crudos (API/JSON)
- data/processed: datos limpios transformados
- notebooks: cuadernos de análisis (TelecomX_LATAM.ipynb)
- src: scripts auxiliares (opcional)
- reports: gráficos y hallazgos (opcional)

## Flujo ETL
1. Extract: obtención desde API/JSON
2. Transform: limpieza, tipificación, normalización
3. Load: exportación a CSV/Parquet para análisis

## Instrucciones de ejecución
- Abrir `TelecomX_LATAM.ipynb` en Google Colab.
- Ejecutar celdas en orden (de arriba hacia abajo).
- Dependencias: pandas, numpy, requests, matplotlib, seaborn.
- Resultado: `data/processed/telecomx_clean.csv` (nombre tentativo).

## Visualizaciones e insights
- (Se añadirán gráficos y conclusiones al avanzar el análisis.)

## Créditos
- Cuaderno base: Alura LATAM – Challenge TelecomX.
- Repositorio del curso: alura-cursos/challenge2-data-science-LATAM.
- Ing. Hugo Alejandro Garduño Nava


## Datos relevantes
- La base de datos contiene 7267 registros actualmente.
- El primer nivel tiene 6 columnas (customerID, Churn, customer, phone, internet, account).
- El diccionario describe todas las variables originales del dataset completo de TelecomX (más de 20 columnas: género, edad, servicios, cargos, etc.).
