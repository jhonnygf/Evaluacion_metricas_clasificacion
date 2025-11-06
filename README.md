# Evaluación de métricas de clasificación

Este repositorio contiene el notebook de la tarea "Evaluación de métricas de clasificación". El objetivo del notebook es guiar el análisis y la interpretación de las métricas más relevantes para problemas de clasificación supervisada, comparar modelos y visualizar el comportamiento de los clasificadores frente a distintos umbrales y desequilibrios de clases.

## Contenido del notebook
El notebook incluye las siguientes secciones y resultados:

- Descripción del problema y del conjunto de datos utilizado (preprocesamiento breve).
- Entrenamiento de uno o varios modelos de clasificación (por ejemplo: Logistic Regression, Random Forest, etc.).
- Cálculo y comparación de métricas de evaluación:
  - Accuracy (exactitud)
  - Precision (precisión)
  - Recall / Sensitivity (recobrado / sensibilidad)
  - F1-score
  - Matriz de confusión (confusion matrix)
  - Curva ROC y AUC (Receiver Operating Characteristic / Area Under Curve)
  - Curva Precision-Recall
- Análisis del efecto del umbral de decisión sobre precisión/recall y sobre la matriz de confusión.
- Visualizaciones para interpretar resultados: matriz de confusión con heatmap, curvas ROC y Precision-Recall, histogramas de probabilidades, etc.
- Recomendaciones y conclusiones sobre qué métricas priorizar según el contexto del problema (clases desbalanceadas, coste de falsos positivos vs falsos negativos, etc.).
