# ETL-EDA-TITANIC
ETL CON EDA DEL DASHBOARD DEL TITANIC 
🛎️ Proyecto ETL & EDA – Titanic Dataset
ETL Pipeline | Data Cleaning | Feature Engineering | Data Visualization | Exploratory Data Analysis (EDA)
📘 Descripción general del proyecto

Este proyecto implementa un pipeline completo de ETL (Extract, Transform, Load) y un Análisis Exploratorio de Datos (EDA) utilizando Python.
El objetivo es demostrar habilidades clave para roles de Data Analyst, Data Analytics, Business Intelligence (BI) y Machine Learning, aplicando:

#Data Cleaning

#Data Wrangling


#Feature Engineering

#Estándarización y normalización de datos

#Análisis de variables categóricas y numéricas

#Visualización de datos orientada a insights de negocio

El dataset final queda listo para modelado predictivo (Machine Learning Ready Dataset).

🛠️ Tecnologías, herramientas y habilidades clave

Lenguaje y librerías:

Python

Pandas

NumPy

Matplotlib

Seaborn

Habilidades técnicas aplicadas (palabras clave para reclutadores):

ETL Pipeline

Data Cleaning

Data Transformation

Data Preprocessing

Missing Value Treatment

Feature Engineering

Data Quality Validation

Exploratory Data Analysis (EDA)

Data Visualization

Business Insights

KPI Analysis

Dataset Documentation

CSV Export Automation

Outlier Detection

1. 🔍 ETL: Extract — Transform — Load
📥 Extract

Carga del dataset original desde fuente externa para iniciar el proceso de análisis.

df = pd.read_csv('/content/drive/MyDrive/ETL practica/Titanic/Titanic-Dataset.csv')

🔧 Transform

Se realiza un proceso completo de Data Cleaning + Data Wrangling, incluyendo:

✔️ Renombrado de columnas (Data Standardization)

Se reemplazan nombres originales por nombres legibles, consistentes y orientados a negocio.

Mejora la calidad semántica del dataset.

✔️ Normalización y recategorización de variables

Transformación de códigos a valores descriptivos.

Conversión de atributos numéricos en categorías necesarias para análisis segmentado.

✔️ Tratamiento de valores faltantes (Missing Value Imputation)

Imputación con la media para Edad

Sustitución por “Sin datos” en Cabina y Lugar de embarque

✔️ Feature Engineering

Se crean variables estratégicas para enriquecer el análisis:

Grupo de edad (Segmentación demográfica)

Familia total (Tamaño del grupo familiar)

Estas variables mejoran el análisis y permiten preparar el dataset para modelos de clasificación.

✔️ Validaciones del dataset

Revisión de duplicados (Data Quality Check)

Revisión de tipos de datos

Confirmación de calidad post-procesamiento

📤 Load

Se exporta el dataset limpio y transformado:

Titanic_ETL.csv


Esto completa el ETL Pipeline.

2. 📊 EDA – Exploratory Data Analysis

El EDA se centra en detectar patrones críticos y variables que influyeron en la supervivencia.

🔎 Outlier Detection

Se analizan variables numéricas clave como Edad y Tarifa para evaluar dispersión y valores extremos.

👩‍🦱 Análisis de supervivencia por sexo

Insight clave: las mujeres presentan una tasa de supervivencia sustancialmente superior.
Keyword: Gender-based survival analysis

🎫 Supervivencia por clase (Socioeconomic Insights)

Primera clase → mayor tasa de supervivencia

Tercera clase → menor supervivencia
Keywords: Socioeconomic segmentation, Class-based survival rate

👶 Supervivencia por grupo etario (Age Segmentation)

Niños → mayor supervivencia

Adultos y ancianos → menor supervivencia

🔎 Triple análisis (Sexo + Clase + Supervivencia)

Este análisis permite explicar la interacción entre factores sociales, económicos y demográficos.
Keywords: Multivariate analysis, categorical data insights

📌 Conclusiones clave del análisis

(Todas aptas para incluir en entrevistas o CV)

El sexo fue el factor más determinante en la probabilidad de supervivencia.

La clase social impactó directamente en las posibilidades de vivir, mostrando desigualdades estructurales.

Los niños tuvieron prioridad, confirmando patrones históricos de evacuación.

Las tarifas pagadas reflejan nivel socioeconómico, correlacionado con acceso a recursos.

La creación de nuevas variables (Feature Engineering) permitió análisis más profundos.

El dataset resultante es Machine Learning-Ready, apto para modelos predictivos de clasificación.
