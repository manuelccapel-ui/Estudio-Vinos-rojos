# Estudio-Vinos-rojos 🍷📊

Proyecto de análisis estadístico y modelado sobre un dataset de **vinos tintos** (*winequality-red*).  
Incluye exploración de datos (EDA), modelos de regresión y clasificación, reducción de dimensionalidad (PCA) y clustering (K-Means).

---

## Estructura recomendada del repositorio
Estudio-Vinos-rojos/
├─ README.md
├─ notebooks/
│ └─ vinos_examen.ipynb
└─ data/
└─ winequality-red.csv

## Dataset

# Archivo: data/winequality-red.csv

1599 filas y 12 columnas

11 variables fisicoquímicas (features) + 1 objetivo (quality)

quality toma valores entre 3 y 8

# Variables:

fixed acidity

volatile acidity

citric acid

residual sugar

chlorides

free sulfur dioxide

total sulfur dioxide

density

pH

sulphates

alcohol

quality (objetivo)


## Contenido del notebook (notebooks/vinos_examen.ipynb)
# 1) Análisis exploratorio (EDA)

Valores faltantes

Estadísticos descriptivos

Histogramas y boxplots

Matriz de correlaciones

# 2) Regresión (ejemplo + regularización)

Regresión lineal

Análisis de residuos (histograma, QQ-plot)

Test de heterocedasticidad (Breusch–Pagan)

Ridge / Lasso / Elastic Net con validación cruzada

# 3) Clasificación (predicción de quality)

Logistic Regression (multiclase)

KNN

Árbol de decisión (max depth = 5) + plot del árbol

Bagging y Pasting

Random Forest

AdaBoost

Gradient Boosting

Métricas: accuracy, F1, recall + matriz de confusión

# 4) PCA + visualización

Selección de componentes (codo / varianza acumulada)

Gráfico 2D con las dos primeras componentes

Clasificador tras PCA

# 5) Clustering (K-Means)

Elección de k (inercia + silhouette)

Evaluación y comparación con clases (alineación de clusters)

## Requisitos

Probado con Python 3.x. Librerías usadas:

numpy, pandas, matplotlib

scikit-learn

scipy

statsmodels

jupyter
