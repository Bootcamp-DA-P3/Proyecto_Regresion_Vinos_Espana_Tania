# Proyecto_Regresion_Vinos_Espana_Tania

## Descripción del Proyecto
Este repositorio contiene el flujo completo de análisis de datos, limpieza, preprocesamiento y modelado predictivo de regresión para estimar los precios de los vinos en el mercado español utilizando el dataset *Spanish Wine Quality* (obtenido directamente desde Kaggle mediante `kagglehub`).

## Estructura del Repositorio y Notebooks
* **`01_eda_y_modelado.ipynb`**: Notebook principal desarrollado en Google Colab / entorno local que incluye:
  - Carga directa y automatizada del dataset desde Kaggle.
  - Traducción y mapeo estructurado de nombres de columnas del inglés al español (`winery` -> `bodega`, `wine` -> `nombre_vino`, `year` -> `anio`, `rating` -> `puntuacion`, `num_reviews` -> `num_reseñas`, `price` -> `precio`, etc.).
  - Limpieza de datos y tratamiento robusto de valores nulos en variables clave.
  - Análisis Exploratorio de Datos (EDA) y visualizaciones estadísticas con Seaborn y Matplotlib.
  - Entrenamiento, optimización de hiperparámetros (*GridSearchCV*) y evaluación de modelos de regresión (*Random Forest Regressor*).
  - Evaluación detallada de métricas ($R^2$, RMSE, MAE) y análisis gráfico de residuos.

## Requisitos e Instalación
El entorno requiere Python 3.11+ y las siguientes librerías principales:
* `pandas`, `numpy`
* `matplotlib`, `seaborn`
* `scikit-learn`
* `joblib`, `kagglehub`, `tqdm`

## Autor/a
* **Tania** (IT Project Manager & Data Analyst Student)