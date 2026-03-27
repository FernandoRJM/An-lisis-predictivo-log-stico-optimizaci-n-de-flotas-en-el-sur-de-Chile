# Análisis predictivo logístico: optimización de flotas en el sur de Chile

🚢 Este proyecto aplica Ciencia de Datos y Machine Learning para optimizar la logística de transporte de víveres para la industria del salmón (Región de Aysén, Chile). A partir de datos reales de operación de las embarcaciones Sol Pacífico y Costa Pacífico, el sistema predice el riesgo de incidentes en las entregas.

📋 Contexto del Negocio: La operación logística en los canales del sur de Chile enfrenta desafíos constantes: condiciones climáticas variables, ventanas de tiempo reducidas y fragilidad de la carga. La falta de métricas históricas impedía identificar patrones de falla. Este proyecto transforma registros operativos en decisiones inteligentes.

🚀 Características Principales
Análisis de Flota: Comparativa de eficiencia y tiempos de descarga entre diferentes embarcaciones.
Modelado Predictivo: Uso de un clasificador de Árbol de Decisión para estimar la gravedad de posibles incidentes (0-5) antes del zarpe.
Ingeniería de Variables (Feature Engineering): Transformación de variables temporales (hora, día de la semana) y geográficas para mejorar la precisión.
Asistente de Despacho: Interfaz de consola que permite al usuario consultar el riesgo de una ruta específica.

🛠️ Stack Tecnológico
Lenguaje: Python 3.x
Librerías: * Pandas: Limpieza y manipulación de datos (Tidy Data).
Scikit-Learn: Entrenamiento y evaluación del modelo de Machine Learning.
Seaborn & Matplotlib: Visualización de patrones y análisis exploratorio (EDA).
Joblib: Persistencia del modelo para uso en producción.

📊 Resultados e Insights
A través del análisis, se identificaron factores críticos para la operación:

Ventanas Horarias: La gravedad de los incidentes tiende a aumentar en entregas después de las 16:00 hrs.
Puntos Críticos: Identificación de centros de cultivo específicos con tasas de falla un 9% superiores al promedio.
Eficiencia de Flota: Determinación de la "línea base" de tiempo de descarga, permitiendo detectar retrasos anómalos en tiempo real.
