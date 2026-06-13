# MiguelAngelRL-Data-Sprint8-Project-NovaRetail

En este proyecto realicé un análisis correlacional sobre datos de clientes de NovaRetail+, una plataforma de comercio electrónico en Latinoamérica. El objetivo fue identificar qué variables de comportamiento, satisfacción y segmentación presentan una mayor asociación con el ingreso anual generado por los clientes.

El análisis se desarrolló bajo un enfoque exploratorio, utilizando distintas técnicas estadísticas y visuales para evaluar relaciones entre variables numéricas, binarias y categóricas.

Objetivo del Proyecto
Responder la siguiente pregunta de negocio:
¿Qué factores del comportamiento del cliente están más fuertemente asociados con el ingreso anual generado para la empresa?
A partir de esta pregunta se buscó generar evidencia que ayude a orientar futuras estrategias de crecimiento, retención y experimentación.

Dataset

Fuente: Dataset académico proporcionado por TripleTen.
Registros: 15,000 clientes
Variables principales
Edad del cliente
Nivel de ingreso
Visitas mensuales
Compras mensuales
Gasto en publicidad dirigida
Satisfacción del cliente
Membresía Premium
Abandono de la plataforma
Tipo de dispositivo
Región
Ingreso anual generado

Herramientas Utilizadas
Python
Pandas
NumPy
Matplotlib
Seaborn
SciPy
Jupyter Notebook

Metodología
1. Exploración y preparación de datos
Revisión de estructura y tipos de datos
Verificación de valores faltantes
Identificación de variables relevantes para el análisis
Documentación de supuestos y limitaciones

2. Análisis visual
Se utilizaron visualizaciones para detectar patrones preliminares:
Heatmaps de correlación
Scatterplots entre variables clave
Comparaciones por segmentos de clientes

3. Análisis estadístico
Dependiendo del tipo de variable, se aplicaron diferentes métricas:
Correlación de Pearson
Para evaluar relaciones lineales entre variables numéricas.
Correlación de Spearman
Para detectar relaciones monotónicas y reducir sensibilidad a valores atípicos.
Correlación Punto-Biserial
Para analizar la relación entre variables binarias y variables numéricas.
V de Cramér
Para medir asociación entre variables categóricas.

Hallazgos Principales
Se identificaron variables con una asociación más fuerte respecto al ingreso anual generado.
Algunas relaciones observadas visualmente resultaron ser más débiles de lo esperado al validar estadísticamente.
Se detectaron posibles correlaciones engañosas que requerirían análisis adicionales antes de tomar decisiones de negocio.
Los resultados mostraron diferencias relevantes entre ciertos segmentos de clientes.

Recomendaciones
Priorizar el análisis de las variables con mayor asociación al ingreso anual.
Diseñar experimentos controlados para validar hipótesis derivadas del análisis.
Profundizar en la segmentación de clientes para identificar oportunidades de crecimiento y retención.
Incorporar nuevas variables de comportamiento en futuros estudios.

Aprendizajes

Este proyecto me permitió fortalecer habilidades en:
Análisis exploratorio de datos (EDA)
Interpretación de correlaciones
Selección de métricas estadísticas según el tipo de variable
Visualización de datos
Comunicación de hallazgos orientados al negocio
Documentación de limitaciones y recomendaciones basadas en evidencia
