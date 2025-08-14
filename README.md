# Análisis de Cancelación de Clientes – TelecomX LATAM

Este proyecto tiene como objetivo identificar los factores que más influyen en la cancelación de clientes (**Churn**) en la empresa de telecomunicaciones **TelecomX LATAM**, utilizando análisis exploratorio de datos y modelos de Machine Learning.

## 📂 Archivos del proyecto

- **Challenge_TelecomX_LATAM_Parte_2.ipynb**  
  Notebook de Google Colab con todo el flujo de trabajo:
  - Carga y preprocesamiento de datos
  - Análisis exploratorio
  - Entrenamiento y evaluación de modelos
  - Interpretación de resultados

- **df_normalizado2.csv**  
  Dataset preprocesado con variables numéricas y categóricas listas para el modelado.

## 🎯 Objetivo

Determinar las variables más relevantes que explican la cancelación de clientes, y evaluar el rendimiento de diferentes modelos de predicción.

## 📊 Flujo de trabajo

1. **Carga de datos**  
   - Importación del dataset preprocesado (`df_normalizado2.csv`).

2. **Preprocesamiento**  
   - Codificación de variables categóricas (`One-Hot Encoding`).
   - Imputación de valores faltantes.
   - Escalado de variables numéricas.

3. **Análisis exploratorio (EDA)**  
   - Tasas de churn generales y por categorías.
   - Relación entre variables como:
     - Antigüedad del cliente (tenure)
     - Tipo de contrato
     - Servicio de internet
     - Cargos mensuales
     - Soporte técnico y seguridad online

4. **Modelado**  
   - Entrenamiento de modelos de clasificación (ej. Regresión Logística, Árboles de Decisión, Random Forest).
   - Evaluación con métricas: **Accuracy, Precision, Recall, F1-score, ROC-AUC**.
   - Selección del mejor modelo y análisis de importancia de variables.

5. **Interpretación de resultados**  
   - Identificación de factores clave para la retención de clientes.
   - Recomendaciones estratégicas.

## 📈 Principales hallazgos

- Clientes con **contrato mensual**, **altos cargos mensuales** y **baja antigüedad** presentan mayores tasas de cancelación.
- La ausencia de servicios como **seguridad online** y **soporte técnico** aumenta la probabilidad de churn.
- Métodos de pago automáticos reducen la tasa de cancelación frente a pagos manuales.

## 🛠️ Tecnologías utilizadas

- **Python 3**
- **Pandas**, **NumPy**
- **Scikit-learn**
- **Matplotlib**, **Seaborn**
- **Google Colab**

## 🚀 Ejecución

- Abrir el archivo Challenge_TelecomX_LATAM_Parte_2.ipynb en Google Colab.
- Ejecutar las celdas secuencialmente.
- Revisar el informe final y las métricas de cada modelo.
