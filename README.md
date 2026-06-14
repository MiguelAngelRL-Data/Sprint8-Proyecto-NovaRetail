# NovaRetail+ | Análisis de Factores Asociados al Ingreso Anual de Clientes

## Descripción del Proyecto

NovaRetail+ es una plataforma de comercio electrónico en Latinoamérica que buscaba comprender qué factores del comportamiento de sus clientes están más fuertemente asociados con el ingreso anual generado.

El objetivo de este análisis fue identificar relaciones relevantes entre variables de comportamiento, engagement, satisfacción y segmentación para apoyar futuras estrategias de crecimiento, retención y experimentación.

---

## Objetivo de Negocio

Responder la siguiente pregunta:

**¿Qué factores del comportamiento del cliente presentan la mayor asociación con el ingreso anual generado para la empresa?**

Los hallazgos obtenidos permiten identificar oportunidades para mejorar la retención, aumentar la frecuencia de compra y orientar futuras iniciativas de marketing y crecimiento.

---

## Dataset

**Fuente:** Dataset académico proporcionado por TripleTen.

**Registros analizados:** 15,000 clientes.

### Variables principales

* Edad
* Nivel de ingreso
* Visitas mensuales
* Compras mensuales
* Gasto en publicidad dirigida
* Satisfacción
* Membresía premium
* Abandono
* Tipo de dispositivo
* Región
* Ingreso anual generado

---

## Herramientas Utilizadas

* Python
* Pandas
* NumPy
* SciPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Metodología

### Exploración y preparación de datos

* Validación de estructura y tipos de datos.
* Verificación de valores faltantes.
* Selección de variables relevantes.
* Documentación de supuestos y limitaciones.

### Análisis visual

Se utilizaron:

* Heatmaps de correlación.
* Scatterplots.
* Comparaciones por segmentos.

### Análisis estadístico

Dependiendo del tipo de variable se aplicaron:

* Correlación de Pearson.
* Correlación de Spearman.
* Correlación Punto-Biserial.
* V de Cramér.

---

## Principales Hallazgos

### Hallazgo 1: La frecuencia de compra es el principal factor asociado al ingreso anual

**Evidencia numérica**

* Pearson: 0.97
* Spearman: 0.97

Fue la relación más fuerte identificada en todo el análisis.

**Interpretación**

Los clientes que realizan más compras mensuales tienden a generar mayores ingresos anuales para la empresa.

**Implicación de negocio**

NovaRetail+ podría priorizar estrategias de fidelización, promociones y retención enfocadas en aumentar la recurrencia de compra.

---

### Hallazgo 2: La actividad de los usuarios se relaciona con el ingreso generado

**Evidencia numérica**

* Visitas mensuales vs ingreso anual:

  * Pearson: 0.34
  * Spearman: 0.32

* Visitas mensuales vs gasto publicitario:

  * Pearson: 0.58
  * Spearman: 0.56

**Interpretación**

Los usuarios más activos dentro de la plataforma tienden a generar mayores ingresos y muestran una mayor relación con la exposición publicitaria.

**Implicación de negocio**

La empresa puede evaluar iniciativas orientadas a incrementar la interacción y frecuencia de visita de los usuarios.

---

### Hallazgo 3: La membresía premium muestra una relación débil con el ingreso anual

**Evidencia numérica**

* Miembro Premium vs ingreso anual: 0.09
* Abandono vs ingreso anual: -0.00

**Interpretación**

La membresía premium presenta una asociación positiva, aunque débil, mientras que el abandono no mostró una relación relevante con el ingreso anual dentro de este dataset.

**Implicación de negocio**

Se recomienda profundizar en la segmentación de usuarios premium para identificar grupos donde la membresía pueda generar mayor valor económico.

---

## Limitaciones

* Correlación no implica causalidad.
* No se puede afirmar que una variable provoque cambios directos sobre otra.
* Pueden existir factores externos no incluidos en el dataset.
* Algunas variables presentan asociaciones débiles y requieren análisis complementarios.

---

## Recomendaciones de Negocio

* Diseñar estrategias para incrementar la frecuencia de compra.
* Evaluar acciones que fomenten una mayor interacción con la plataforma.
* Analizar segmentos específicos de usuarios premium.
* Realizar experimentos controlados para validar hipótesis derivadas del análisis correlacional.
* Incorporar nuevas variables de comportamiento en futuros estudios.

---

## Habilidades Demostradas

* Análisis Exploratorio de Datos (EDA).
* Análisis correlacional.
* Correlación de Pearson y Spearman.
* Correlación Punto-Biserial.
* Asociación entre variables categóricas.
* Visualización de datos.
* Interpretación responsable de resultados estadísticos.
* Storytelling con datos.
* Traducción de hallazgos en recomendaciones de negocio.

---

## Conclusión

La frecuencia de compra fue el factor más fuertemente asociado con el ingreso anual generado por los clientes de NovaRetail+.

Los resultados sugieren que las iniciativas orientadas a aumentar la recurrencia de compra y la interacción de los usuarios podrían representar oportunidades relevantes para impulsar el crecimiento del negocio, siempre considerando que las relaciones observadas son correlacionales y no causales.
