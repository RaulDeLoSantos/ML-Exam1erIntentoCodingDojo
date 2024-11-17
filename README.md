# ML-Exam1erIntentoCodingDojo
ML-Exam1erIntentoCodingDojo - 17/11/2024
Examen de certificación – Intento 1
Duración: 29 horas
Fecha límite: 0 Días, 8 Horas
Descripción
Instrucciones para examen
Objetivo: Este examen tiene como objetivo evaluar la capacidad del estudiante para limpiar, explorar, implementar y evaluar modelos de clasificación en un dataset real. Utilizaremos el «Wine Quality Dataset» disponible en UCI Machine Learning Repository. Los estudiantes deben demostrar habilidades prácticas en la manipulación de datos, creación de visualizaciones y modelado predictivo, así como una comprensión de las consideraciones éticas y tecnológicas en el análisis de datos.

Contexto y Descripción del Dataset

El «Wine Quality Dataset» contiene datos sobre las características químicas y físicas de diferentes muestras de vino tinto y blanco, así como su calidad, evaluada por expertos en una escala de 0 a 10. Este dataset es ampliamente utilizado en la investigación de modelos de clasificación y regresión debido a su naturaleza multifacética y su aplicación en la industria vinícola.

Diccionario de Datos:

fixed acidity: Acidez fija en g/dm³.
volatile acidity: Acidez volátil en g/dm³.
citric acid: Ácido cítrico en g/dm³.
residual sugar: Azúcar residual en g/dm³.
chlorides: Cloruros en g/dm³.
free sulfur dioxide: Dióxido de azufre libre en mg/dm³.
total sulfur dioxide: Dióxido de azufre total en mg/dm³.
density: Densidad en g/cm³.
pH: Nivel de pH.
sulphates: Sulfatos en g/dm³.
alcohol: Porcentaje de alcohol en % vol.
quality: Calidad del vino (variable objetivo, escala de 0 a 10).
Requisitos

Limpieza de Datos:
Identificación y eliminación de valores duplicados: Asegúrate de que no haya registros duplicados que puedan sesgar los resultados del análisis.
Verificación y ajuste de tipos de datos: Verifica que cada columna tenga el tipo de dato correcto (numérico o categórico) y ajusta si es necesario.
Corrección de inconsistencias en valores categóricos: Revisa las categorías de las variables y unifica aquellos valores que puedan estar escritos de diferentes maneras pero que representen lo mismo.
Manejo de valores faltantes adecuadamente: Identifica y maneja los valores faltantes utilizando técnicas apropiadas como la imputación de la mediana, media o moda, según corresponda.
Exploración de Datos:
Visualizaciones univariadas y multivariadas: Crea histogramas, gráficos de barras, diagramas de dispersión y mapas de calor para entender la distribución y las relaciones entre las variables.
Estadísticas descriptivas: Calcula medidas de tendencia central (media, mediana, moda) y de dispersión (rango, desviación estándar) para cada característica del dataset.
Implementación de Modelos:
Modelos de Clasificación: Implementa modelos de Logistic Regression y K-Nearest Neighbors (KNN).
Evaluación de Modelos: Evalúa los modelos utilizando métricas como accuracy, precision, recall, y F1-score.
Comparación de Rendimiento: Compara los resultados de ambos modelos y discute cuál es el más adecuado para este dataset.
Entrega

Los estudiantes deben entregar un archivo .ipynb comentado que incluya:

Proceso completo de limpieza y preprocesamiento de datos.
Visualizaciones y estadísticas descriptivas.
Implementación y evaluación de los modelos de clasificación.
Análisis comparativo del rendimiento de los modelos.
Además, el archivo debe subirse a GitHub con un tag de liberación (release tag) que permita identificar la entrega final.

Consideraciones Éticas y Tecnológicas

Consideraciones Éticas:

Transparencia y Reproducibilidad: Asegúrate de que todos los pasos del análisis sean claros y reproducibles. Otros investigadores deben poder seguir tus pasos y llegar a los mismos resultados.
Imparcialidad y Sesgo: Revisa si existen sesgos en los datos que puedan afectar la imparcialidad del modelo. Es importante que los modelos no discriminen injustamente entre diferentes grupos de datos.
Consideraciones Tecnológicas:

Herramientas Utilizadas: Utiliza herramientas estándar como Python, Jupyter Notebook, Pandas, Scikit-learn, Matplotlib y Seaborn.
Escalabilidad: Considera cómo las técnicas aplicadas podrían escalarse para manejar conjuntos de datos más grandes y complejos.
Optimización de Modelos: Aunque este examen no se enfoca en la optimización de hiperparámetros, se debe tener en cuenta para futuras implementaciones y mejorar el rendimiento de los modelos.
