# TelecomX Data Science Challenge - LATAM

## 🎯 Propósito del Análisis
Este proyecto tiene como objetivo analizar el fenómeno de la evasión de clientes (**Churn**) en la empresa TelecomX. El análisis busca identificar patrones de comportamiento, perfiles de clientes con mayor riesgo y factores críticos que influyen en la decisión de cancelar el servicio. El resultado final es un dataset procesado y un informe de hallazgos listo para ser utilizado por el equipo de Machine Learning.

## Abre en Google Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Gaby46Pe/challenge2-data-science-LATAM-gap/blob/main/TelecomX_LATAM.ipynb)

## 📂 Estructura del Proyecto
La organización de los archivos es la siguiente:
- `TelecomX_LATAM.ipynb`: Notebook principal con todo el flujo de Extracción, Transformación y Análisis (EDA).
- `TelecomX_Data.json`: Archivo fuente con los datos originales de los clientes.
- `TelecomX_diccionario.md`: Guía de referencia que explica el significado de cada columna del dataset.
- `.gitignore`: Archivo para evitar la subida de archivos temporales de Python y entornos virtuales.
- `README.md`: Este archivo, con la descripción general del proyecto.

## Descripción del Proyecto

Este proyecto analiza datos de clientes de TelecomX para entender y predecir la evasión de clientes (churn).

### Secciones:
1. **Extracción** - Carga y exploración inicial de datos
2. **Transformación** - Limpieza y normalización de datos
3. **Carga y análisis** - Estadísticas descriptivas y visualizaciones

## 📊 Gráficos e Insights Obtenidos
Durante el análisis exploratorio se destacaron los siguientes puntos:

1. **Relación Contrato-Churn:** Se observó mediante gráficos de barras que los clientes con contratos **"Month-to-month"** (mes a mes) presentan una tasa de evasión drásticamente superior a los de contratos anuales.
2. **Distribución de Cargos:** El gráfico de densidad (KDE) reveló que los clientes que abandonan la empresa suelen tener cargos totales acumulados bajos, lo que sugiere que el Churn ocurre mayoritariamente en los **primeros meses** de relación con la empresa.
3. **Variable Objetivo:** Se normalizaron los datos de Churn a valores numéricos (0 y 1) para permitir análisis de correlación estadística.

## 🚀 Instrucciones de Ejecución

### Requisitos Previos
Asegúrate de tener instalado Python 3.x y las siguientes librerías:
```bash
pip install pandas numpy matplotlib seaborn

##  Uso

1. Abre el notebook en Google Colab usando el botón arriba
2. O ejecuta localmente: `jupyter notebook TelecomX_LATAM.ipynb`

---

*Proyecto de Data Science - Challenge LATAM*


