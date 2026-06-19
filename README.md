# 🐧 Clasificación de Especies de Pingüinos mediante Modelos de Machine Learning

## Universidad Nacional Autónoma de México (UNAM)

**Diplomado:** Introducción Analítica a la Ciencia de Datos  
**Módulo 5:** Aprendizaje Supervisado

### Profesores
- Jorge Ignacio González Cázare
- Alan Riva Palacio Cohen

---

## Introducción

El análisis de datos y los modelos de Machine Learning son herramientas fundamentales para identificar patrones en la información y apoyar la toma de decisiones. Una de las tareas más comunes dentro de este campo es la clasificación, la cual consiste en asignar una categoría a una observación a partir de un conjunto de características o variables.

En este proyecto se utiliza el conjunto de datos **Palmer Penguins**, recopilado por la Dra. Kristen Gorman en la Estación Palmer, Antártida. La base de datos contiene 344 registros correspondientes a tres especies de pingüinos: **Adelie, Chinstrap y Gentoo**, junto con diversas características morfológicas de cada individuo.

Este dataset es ampliamente utilizado dentro de la comunidad de ciencia de datos como una alternativa moderna al clásico conjunto de datos Iris, ya que representa un problema de clasificación multiclase con variables biológicas reales y relaciones interesantes entre ellas.

---

## Objetivo

Construir y comparar distintos modelos de clasificación para determinar cuál es el más adecuado para identificar la especie de un pingüino a partir de sus características morfológicas.

---

## Metodología

Antes de desarrollar los modelos, se realizó una etapa de limpieza y preparación de los datos, donde se revisó la calidad de la información y se trataron los valores faltantes. Posteriormente, se llevó a cabo un Análisis Exploratorio de Datos (EDA) para comprender el comportamiento de las variables, identificar relaciones entre ellas y obtener una visión general de la base de datos.

Una vez completadas estas etapas, se implementaron y evaluaron los siguientes algoritmos de clasificación:

- Modelos Lineales
  - Modelo Baseline
  - Regresión Logística
  - Lasso
  - Ridge
  - Modelo Lineal Generalizado (GLM)

- LDA y QDA

- Random Forest

- AdaBoost

- XGBoost

- Perceptrón Multicapa (MLP)

Todos los modelos fueron entrenados utilizando las mismas variables predictoras para garantizar una comparación objetiva de su desempeño.

---

## Resultados Esperados

Los modelos serán comparados mediante distintas métricas de evaluación, principalmente Accuracy, Precision, Recall, F1-Score y matrices de confusión. El objetivo es identificar qué algoritmo ofrece la mejor capacidad de clasificación para distinguir correctamente entre las diferentes especies de pingüinos.



## Integrantes del Equipo

- María Fernanda Argumedo Sandoval
- Norma Arely De la Cruz Salazar
- Rodolfo Fuentes Cacho
- Víctor Manuel Lugo Cruz
- Karla Fernanda Mora Gutiérrez
- Luz Lorena Sánchez Aguirre
