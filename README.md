# stat-analysis-py
Herramienta en Python para la validación de constructos y análisis estadístico avanzado (Bartlett, KMO, Alfa de Cronbach y PCA) aplicado a datos de encuestas sociales y de salud.
Análisis Estadístico de Datos de Encuesta
Este repositorio contiene un flujo de trabajo completo en Python para procesar y analizar los resultados de una encuesta piloto. El enfoque principal es validar la fiabilidad de las escalas y reducir la dimensionalidad de los datos.

📊 Funcionalidades Principales
  El notebook ejecuta los siguientes análisis detallados:

Validación de Supuestos (Normalidad):

  Test de Shapiro-Wilk: Evaluación de la distribución normal para variables clave y totales.

  Test de Kolmogorov-Smirnov (KS): Verificación de normalidad en muestras para determinar el uso de estadística paramétrica o no paramétrica.

Análisis de Correlación:

  Coeficiente de Pearson: Para medir la relación lineal entre variables continuas.

  Coeficiente de Spearman: Evaluación de relaciones monótonas (útil para datos que no siguen una distribución normal).

  Validación de Constructo y Fiabilidad:

Alfa de Cronbach: Cálculo de la consistencia interna de la escala.

  Test de Esfericidad de Bartlett: Comprobación de la intercorrelación entre ítems.

  Índice KMO (Kaiser-Meyer-Olkin): Medida de adecuación muestral para análisis factorial.

  Reducción de Dimensionalidad:

  Análisis de Componentes Principales (PCA): Extracción de factores, cálculo de autovalores (Eigenvalues) y varianza explicada.

  Rotación Varimax: Optimización de la interpretación de los componentes.

🛠️ Tecnologías utilizadas
Python 3

Pandas: Manipulación de estructuras de datos.

Scipy & Statsmodels: Pruebas de hipótesis estadísticas.

Scikit-learn: Implementación de PCA y preprocesamiento.

Matplotlib: Visualizaciones gráficas.

🚀 Cómo usarlo
Clona este repositorio.

Abre el archivo 100. PilotoAnalysis.ipynb en Google Colab o Jupyter Notebook.

Asegúrate de tener el archivo de datos en formato .xlsx requerido por el script.

Ejecuta las celdas secuencialmente para obtener el reporte estadístico.
