# stat-analysis-py
Herramienta en Python para la validación de constructos y análisis estadístico avanzado (Bartlett, KMO, Alfa de Cronbach y PCA) aplicado a datos de encuestas sociales y de salud.
Análisis Estadístico de Datos de Encuesta
Este repositorio contiene un flujo de trabajo completo en Python para procesar y analizar los resultados de una encuesta piloto. El enfoque principal es validar la fiabilidad de las escalas y reducir la dimensionalidad de los datos.

# Análisis Estadístico de Datos de Encuesta (Piloto)

Este repositorio contiene un flujo de trabajo desarrollado en Python para el procesamiento y validación estadística de instrumentos de medición. El proyecto abarca desde la limpieza de datos hasta el análisis multivariante para asegurar la fiabilidad de los resultados.

## 📊 Funcionalidades Principales

El notebook ejecuta los siguientes análisis detallados:

* **Validación de Supuestos (Normalidad):**
    * **Test de Shapiro-Wilk:** Evaluación de la distribución normal para variables clave y totales.
    * **Test de Kolmogorov-Smirnov (KS):** Verificación de normalidad en muestras para determinar el uso de estadística paramétrica o no paramétrica.
* **Análisis de Correlación:**
    * **Coeficiente de Pearson:** Para medir la relación lineal entre variables continuas.
    * **Coeficiente de Spearman:** Evaluación de relaciones monótonas para datos que no siguen una distribución normal.
* **Validación de Constructo y Fiabilidad:**
    * **Alfa de Cronbach:** Cálculo de la consistencia interna de la escala.
    * **Test de Esfericidad de Bartlett:** Comprobación de la intercorrelación entre ítems.
    * **Índice KMO (Kaiser-Meyer-Olkin):** Medida de adecuación muestral para análisis factorial.
* **Reducción de Dimensionalidad:**
    * **Análisis de Componentes Principales (PCA):** Extracción de factores, cálculo de autovalores (Eigenvalues) y varianza explicada.
    * **Rotación Varimax:** Optimización de la interpretación de los componentes.

## 🛠️ Tecnologías Utilizadas

* **Python 3**
* **Pandas & Numpy:** Gestión y transformación de matrices de datos.
* **Scipy & Statsmodels:** Ejecución de pruebas de hipótesis y tests estadísticos.
* **Factor Analyzer:** Específicamente para los tests de KMO y Bartlett.
* **Scikit-learn:** Escalado de datos y ejecución de PCA.
* **Matplotlib & Seaborn:** Generación de *Scree plots* y mapas de calor.

## 🚀 Instrucciones de Uso

1. **Preparación:** Asegúrate de tener tu archivo de datos que contenga las encuestas en formato `.xlsx`.
2. **Ejecución:** Abre el archivo `PilotoAnalysis.ipynb` en Google Colab o un entorno Jupyter local.
3. **Carga:** Sube el archivo de la encuesta cuando el script lo solicite.
4. **Resultados:** El notebook generará automáticamente las tablas de validación y los gráficos correspondientes al final de cada sección.

---
*Este proyecto está diseñado para automatizar la validación psicométrica y estadística de instrumentos de recolección de datos.*
