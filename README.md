📊 Análisis de Churn - Telecom X
Análisis completo de retención de clientes para identificar factores críticos que influyen en la fuga de clientes en Telecom X.

🚀 Tecnologías Utilizadas
Este proyecto fue desarrollado completamente en Python, aprovechando las principales bibliotecas del ecosistema de Data Science:

Lenguaje Principal
Python 3.8+ - Lenguaje de programación para análisis de datos

Librerías Esenciales
Pandas - Manipulación y transformación de datos

NumPy - Cálculos numéricos y operaciones matemáticas

Matplotlib - Visualizaciones gráficas básicas

Seaborn - Visualizaciones estadísticas avanzadas

Requests - Extracción de datos desde API REST

📋 Procedimientos Clave
1. Extracción de Datos (E)
Conexión a API REST con requests

Carga de datos JSON anidados

Transformación a DataFrame de Pandas

2. Transformación (T)
Limpieza y normalización de datos

Manejo de valores nulos y tipos de datos

Creación de variables derivadas (grupos de antigüedad, valores promedios)

Codificación de variables categóricas

3. Carga y Análisis (L)
Análisis Exploratorio de Datos (EDA) completo

Visualizaciones estratégicas con Matplotlib y Seaborn

Identificación de patrones y correlaciones

Segmentación de clientes por riesgo

4. Visualizaciones
Gráficos de distribución y comparación

Análisis multivariado

Heatmaps de correlación

Análisis por segmentos

🎯 Hallazgos Principales
Identificamos que los principales factores de churn son:

Antigüedad baja (< 12 meses)

Contratos mensuales vs anuales

Falta de servicios adicionales (seguridad, soporte técnico)

Métodos de pago específicos (Electronic Check)

📁 Estructura del Proyecto
text
TelecomX-Churn-Analysis/
│
├── TelecomX_analysis.ipynb    # Notebook principal con análisis completo
├── TelecomX_processed.csv     # Dataset procesado (generado)
├── TelecomX_diccionario.md    # Diccionario de datos
└── README.md                  # Este archivo
⚡ Cómo Ejecutar
Clonar el repositorio

bash
git clone https://github.com/tu-usuario/telecomx-churn-analysis.git
Instalar dependencias

bash
pip install pandas numpy matplotlib seaborn requests
Ejecutar análisis

python
jupyter notebook TelecomX_analysis.ipynb
📈 Resultados
El análisis permitió:

Identificar segmentos de alto riesgo con 30%+ de churn

Proporcionar 5 recomendaciones estratégicas específicas

Establecer métricas clave para monitoreo continuo

Reducir potencialmente la tasa de churn en 20-30%

📄 Licencia
Este proyecto fue desarrollado como parte del desafío de Data Science para Telecom X.

🔍 Skills demostradas: Python · Pandas · ETL · Data Visualization · Statistical Analysis · Business Insights
