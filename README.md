# Medical Data Classification with Machine Learning

Proyecto desarrollado en Python/Jupyter Notebook.
El objetivo del proyecto es aplicar modelos de clasificación supervisada sobre datasets médicos utilizando técnicas de Machine Learning.

El repositorio contiene dos experimentos independientes dentro de la misma práctica:

- Clasificación binaria aplicada a un dataset de diabetes.
- Clasificación multiclase aplicada a un dataset de dermatología.

## Ejecutar online

### Diabetes - Binary Classification

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HugoSolisHompanera/medical-data-classification-ml/blob/main/notebooks/diabetes_binary_classification.ipynb)

### Dermatology - Multiclass Classification

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HugoSolisHompanera/medical-data-classification-ml/blob/main/notebooks/dermatology_multiclass_classification.ipynb)

## Descripción

Este proyecto trabaja con problemas de clasificación en el ámbito médico mediante modelos supervisados.  
Se realiza la carga y preparación de datos, la división en entrenamiento y prueba, el entrenamiento de modelos, la búsqueda de hiperparámetros y la evaluación del rendimiento mediante métricas de clasificación.

## Experimentos incluidos

### 1. Diabetes - Clasificación binaria

Notebook: `notebooks/diabetes_binary_classification.ipynb`

Este experimento utiliza un dataset de diabetes con variables médicas como glucosa, presión arterial, índice de masa corporal, edad, insulina y otras características clínicas.

El objetivo es predecir si una persona presenta diabetes o no.

Tareas realizadas:

- Carga y limpieza del dataset
- Preparación de variables predictoras y variable objetivo
- División en conjunto de entrenamiento y prueba
- Entrenamiento de modelos SVM y MLP
- Ajuste de hiperparámetros mediante GridSearchCV
- Evaluación con accuracy, matriz de confusión, precision, recall y F1-score
- Interpretación de resultados

### 2. Dermatology - Clasificación multiclase

Notebook: `notebooks/dermatology_multiclass_classification.ipynb`

Este experimento utiliza un dataset de dermatología compuesto por 34 atributos y 6 clases diferentes relacionadas con subtipos de enfermedades dermatológicas.

El objetivo es clasificar correctamente el subtipo de enfermedad a partir de las características clínicas e histopatológicas disponibles.

Tareas realizadas:

- Carga y limpieza del dataset
- Preparación de características y etiquetas
- Clasificación multiclase
- Entrenamiento de modelos SVM y MLP
- Ajuste de hiperparámetros mediante GridSearchCV
- Evaluación con accuracy, matriz de confusión, precision, recall y F1-score
- Interpretación de resultados

## Modelos utilizados

- Support Vector Machine (SVM)
- Multi-Layer Perceptron (MLP)

## Tecnologías utilizadas

- Python
- Jupyter Notebook
- pandas
- NumPy
- scikit-learn

## Estructura del repositorio

```text
medical-data-classification-ml/
│
├── README.md
├── requirements.txt
│
├── notebooks/
│   ├── diabetes_binary_classification.ipynb
│   └── dermatology_multiclass_classification.ipynb
│
└── data/
    ├── diabetes_dataset.csv
    └── dermatology_database_1.csv
