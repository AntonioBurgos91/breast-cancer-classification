# 🧬 Breast Cancer Classification

Este proyecto aplica algoritmos de Machine Learning para predecir si una muestra de tejido mamario es benigna o maligna, utilizando características clínicas extraídas de imágenes. Se realiza un flujo completo de análisis, desde la obtención de los datos hasta la evaluación y optimización de modelos.


---

## 📊 Dataset

Se emplea un dataset disponible en Kaggle que contiene características extraídas de imágenes digitalizadas de biopsias de mama.

### Variables clave:

- Características estadísticas: `mean_radius`, `mean_texture`, `mean_area`, etc.
- Etiqueta de diagnóstico (`diagnosis`):  
  - **B**: Benigno  
  - **M**: Maligno

---

## ⚙️ Tecnologías utilizadas

- **Lenguaje**: Python 3.x
- **Manipulación de datos**: pandas, numpy
- **Visualización**: matplotlib, seaborn
- **Modelado y evaluación**: scikit-learn, xgboost
- **Manejo de clases desbalanceadas**: imbalanced-learn
- **Descarga de datos**: Kaggle API

---

## 🔍 Flujo de trabajo

1. **Importación de librerías**
2. **Adquisición de datos desde Kaggle**
3. **Exploración y limpieza de datos**
4. **Análisis exploratorio de datos (EDA)**
5. **Preprocesamiento**
   - Imputación de valores nulos
   - Escalado de variables
   - Codificación de variables categóricas
6. **División del conjunto de datos**
7. **Entrenamiento de modelos**
   - Regresión Logística
   - Random Forest
   - Soporte Vectorial (SVM)
   - XGBoost
8. **Evaluación**
   - Precisión, Recall, F1-Score
   - Matriz de confusión
   - Curvas ROC y Precision-Recall
9. **Optimización de hiperparámetros**
   - GridSearchCV
   - RandomizedSearchCV

---

## 🚀 Cómo ejecutar

### 1. Clonar el repositorio

```bash
git clone https://github.com/AntonioBurgos91/breast-cancer-classification.git
cd breast-cancer-classification
