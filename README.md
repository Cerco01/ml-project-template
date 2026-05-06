# [Título del Proyecto]

## Contexto

[Descripción del problema de negocio y objetivo del modelo.]

## Variables del dataset

| Variable | Descripción | Tipo |
|----------|-------------|------|
| `variable_1` | Descripción de la variable 1 | Numérico/Categórico |
| `variable_2` | Descripción de la variable 2 | Numérico/Categórico |
| `target` | Variable objetivo | Numérico/Categórico |

## Cómo usar este proyecto

1. Clonar el repositorio.
2. Instalar las dependencias: `pip install -r requirements.txt`
3. Descargar el dataset y guardarlo en `data/raw/`.
4. Abrir y ejecutar el notebook `src/explore.ipynb`.
5. Al ejecutar el notebook se generan los datasets procesados en `data/processed/`.

## Qué incluye el proyecto

- Carga y exploración del dataset.
- Análisis Exploratorio de Datos (EDA): distribuciones, correlaciones, outliers.
- Preprocesamiento: feature engineering, split train-test, encoding, escalado.
- Modelado base y optimización con GridSearchCV.
- Comparación de modelos y visualización de resultados.
- Guardado de datasets procesados en `data/processed/`.

## Archivos principales

- `src/explore.ipynb`: notebook principal con EDA, modelado y conclusiones.
- `src/apple.mplstyle`: estilo personalizado para las visualizaciones.
- `data/raw/`: carpeta para el dataset original.
- `data/processed/`: carpeta para los datasets procesados.
- `models/`: carpeta para guardar modelos entrenados.
- Los datos no se suben a Git.

## Créditos

Este proyecto fue realizado como parte del [Bootcamp de Data Science y Machine Learning](https://4geeksacademy.com/us/coding-bootcamps/datascience-machine-learning) de 4Geeks Academy.
