# TP2 - Modelos Predictivos de Clasificación y Regresión

##  Descripción
En este trabajo se desarrollan y comparan distintos **modelos predictivos supervisados** aplicados sobre un conjunto de datos agrícolas.  
El objetivo es evaluar la capacidad de predicción de diferentes algoritmos, optimizar sus hiperparámetros y analizar sus métricas de desempeño para seleccionar el modelo más adecuado.

---

##  Flujo del trabajo

1. **Preprocesamiento de datos**
   - Limpieza del dataset y manejo de valores faltantes.
   - Codificación de variables categóricas mediante **One-Hot Encoding**.
   - Estandarización y normalización de variables numéricas.
   - Separación en conjuntos de entrenamiento y prueba (80/20 y 70/30).

2. **Modelos implementados**
   - **Árboles de Decisión**: análisis de profundidad, criterio de división y sobreajuste.  
   - **Naive Bayes**: aplicación sobre variables categóricas y numéricas.  
   - **Regresión Lineal y Regresión Logística**: modelos de base para comparación.  
   - **Optimización de hiperparámetros** mediante `RandomizedSearchCV` y validación cruzada.

3. **Evaluación del desempeño**
   - Cálculo de métricas: **MAE**, **MSE**, **RMSE**, **MAPE**, **Accuracy**, **Recall**, **Precision** y **F1-score**.  
   - Análisis del error y visualización de resultados.  
   - Comparación de modelos en términos de sesgo, varianza y generalización.

4. **Visualización**
   - Gráficos de dispersión entre predicciones y valores reales.  
   - Curvas de aprendizaje y matrices de confusión.  
   - Visualización de la estructura de los árboles de decisión.

---



