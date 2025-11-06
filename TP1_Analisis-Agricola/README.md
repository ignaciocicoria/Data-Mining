#  TP1 - Análisis Agrícola con Técnicas de Minería de Datos

##  Descripción
Este proyecto tiene como objetivo aplicar **técnicas de minería de datos no supervisadas** sobre un conjunto de datos agrícolas.  
El análisis busca identificar patrones y relaciones entre variables climáticas, de suelo y cultivo, con el fin de comprender la estructura del dataset y reducir su dimensionalidad.

---

##  Flujo del trabajo

1. **Análisis exploratorio de datos (EDA)**
   - Revisión de la estructura del dataset.
   - Detección de valores faltantes y análisis estadístico descriptivo.
   - Visualización de distribuciones, correlaciones y dispersión entre variables.

2. **Preprocesamiento**
   - Estandarización de variables numéricas.
   - Codificación one-hot para variables categóricas.
   - Limpieza y normalización de datos.

3. **Reducción de dimensionalidad**
   - Aplicación de **PCA (Análisis de Componentes Principales)** para identificar las variables que más explican la varianza.
   - Implementación de técnicas **Isomap** y **t-SNE** para la proyección no lineal en espacios de menor dimensión.

4. **Clustering**
   - Implementación de **K-Means** y **Clustering Jerárquico**.
   - Evaluación del número óptimo de clusters mediante el **método del codo** y el **coeficiente de silueta**.
   - Interpretación de los grupos en relación a las características del suelo y tipo de cultivo.

5. **Visualización**
   - Representación gráfica de los clusters obtenidos.
   - Visualización de componentes principales y relaciones entre grupos.

---

## 📁 Estructura del repositorio

