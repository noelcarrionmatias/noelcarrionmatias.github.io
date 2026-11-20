---
title: Earthquakes Analysis
date: 2026-11-20
categories: [Data Analytics, Geospatial Analytics]
tags: [Python, Pandas, GeoPandas, SQLite, SQL, Power BI, API]
image:
  path: /assets/img/projects/earthquakes/dashboard.png
---

## Resumen

Proyecto de análisis sísmico global basado en más de 3 millones de registros obtenidos desde la API oficial de USGS entre los años 2000 y 2025.

El objetivo fue construir un pipeline completo de datos capaz de extraer, transformar, almacenar y analizar información sísmica para estudiar la distribución geográfica de los terremotos, su evolución temporal y los patrones asociados a eventos de gran magnitud.

## Tecnologías utilizadas

- Python
- Pandas
- GeoPandas
- SQLite
- Power BI
- Matplotlib
- Seaborn
- API USGS

## Arquitectura del proyecto

1. Extracción de datos desde la API de USGS.
2. Limpieza y transformación de registros.
3. Enriquecimiento geoespacial mediante GeoPandas.
4. Almacenamiento en SQLite.
5. Análisis exploratorio en Python.
6. Construcción de dashboard en Power BI.

## Desafío principal

La API de USGS impone un límite máximo de 20.000 registros por consulta.

Para evitar pérdidas de información se desarrolló una estrategia de particionado temporal por rangos semanales junto con validaciones y procesos de recuperación de consultas fallidas.

## Principales hallazgos

### Distribución por magnitud

Más del 70% de los terremotos registrados presentan una magnitud inferior a 2.

### Distribución geográfica

La mayor concentración de actividad sísmica se localiza en el Anillo de Fuego del Pacífico y en otras regiones asociadas a límites de placas tectónicas.

### Evolución temporal

El incremento de registros observados a lo largo de los años parece estar relacionado principalmente con la mejora de los sistemas de detección y monitorización y no con un aumento de la actividad sísmica.

### Terremotos de alta magnitud

Los eventos más intensos se concentran especialmente en países como Indonesia, Chile, Japón, Perú y México.

## Dashboard

[Imagen principal del dashboard]

## Valor técnico del proyecto

Este proyecto demuestra experiencia en:

- Desarrollo de pipelines ETL.
- Consumo de APIs con restricciones de consulta.
- Gestión de grandes volúmenes de datos (>3 millones de registros).
- Modelado y almacenamiento en SQLite.
- Análisis geoespacial.
- Visualización de datos en Python y Power BI.

## Repositorio

GitHub:
https://github.com/noelcarrionmatias/Earthquakes-analysis
