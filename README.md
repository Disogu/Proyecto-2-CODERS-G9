# Deep Learning Text Classification

## 🎯 Objetivo del Proyecto
Clasificar reseñas de películas como positivas o negativas usando una red neuronal LSTM y MLflow para experimentación.

## 📂 Dataset
Se usa el dataset IMDB disponible en `tensorflow.keras.datasets`.

## ⚖️ Decisiones
- Se usa embedding + LSTM.
- Padding hasta longitud 500.
- Se usa MLflow para logging.
- Se guarda el modelo en formato `.keras`.

## 📈 Resultados
- Accuracy: ~0.85
- Métricas obtenidas mediante `classification_report`.

## ▶️ Cómo ejecutar

1. Clonar repositorio
2. Instalar dependencias
3. Ejecutar en orden los notebooks:
    - `1_EDA.ipynb`
    - `2_preprocessing.ipynb`
    - `3_train_validate_model.ipynb`
    - `4_evaluation_export.ipynb`

Opcional: iniciar MLflow UI
```bash
mlflow ui
```
Ver en `http://localhost:5000`.
