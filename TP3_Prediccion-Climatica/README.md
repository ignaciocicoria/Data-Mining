# TP3 - Predicción de Estaciones del Año 

Este proyecto corresponde al **Trabajo Práctico N°3**.  
El objetivo es desarrollar un modelo de **clasificación supervisada** capaz de predecir la **estación del año (verano, otoño, invierno o primavera)** a partir de variables meteorológicas.

Se comparan tres enfoques de modelado:  
- **SVM lineal**  
- **SVM con kernel gaussiano (RBF)**  
- **Random Forest**

---

##  Descripción del proyecto

El notebook implementa el flujo completo de un proyecto de Machine Learning:

1. **Carga y exploración de datos**
   - Inspección del dataset meteorológico.
   - Análisis exploratorio y visualización de las variables.
   - Evaluación del balance de clases entre estaciones.

2. **Preprocesamiento**
   - Manejo de valores faltantes.
   - Estandarización de variables numéricas.
   - Codificación de variables categóricas.
   - División del dataset en entrenamiento y prueba.

3. **Modelado**
   - Entrenamiento y ajuste de modelos:
     - SVM lineal  
     - SVM gaussiano (RBF)  
     - Random Forest
   - Búsqueda de hiperparámetros y comparación de resultados.

4. **Evaluación**
   - Matriz de confusión.  
   - Reporte de métricas: *accuracy, precision, recall, f1-score*.  
   - Comparación visual del desempeño de los tres modelos.

5. **Conclusión**
   - Análisis del modelo con mejor desempeño y sus posibles aplicaciones.

---




