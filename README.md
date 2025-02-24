# 📌 Proyecto de Moderación de Productos en eCommerce

## 📋 Descripción
Este repositorio contiene el análisis de moderación de productos en plataformas de comercio electrónico. Se exploran técnicas para la detección de productos falsificados mediante modelado de precios, procesamiento de lenguaje natural (NLP) y estrategias de clustering.

## 📂 Estructura del Proyecto
El repositorio se divide en las siguientes carpetas:

- **📁 data_moderation/** → Contiene el archivo `data_moderaciones.csv`, que almacena la información de los productos moderados.
- **📁 model_moderation/** → Contiene el notebook `modeling_moderation_analysis.ipynb`, donde se implementan modelos de clasificación para los títulos de los productos.
- **📁 moderation_insights/** → Contiene `ecommerce_moderation_insights.ipynb`, con hallazgos y visualización de tendencias en moderaciones.
- **📁 moderation_interview_analysis/** → Contiene `Análisis de Información-DAAB.pdf`, con respuestas a preguntas técnicas y estratégicas.

## 📊 Técnicas Utilizadas
- **📌 Procesamiento de Lenguaje Natural (TF-IDF)**: Para identificar términos clave en títulos y descripciones.
- **📌 Clustering (K-Means, t-SNE)**: Para identificar patrones en productos legítimos y falsificados.
- **📌 Análisis de Moderaciones**: Evaluación de reglas aplicadas y detección de falsos positivos con estadísticas descriptivas.

## 🚀 Hallazgos Clave
1. **El precio es un fuerte indicador de falsificación**: Los productos falsificados son en promedio un **30-40%** más baratos.
2. **Algunas reglas de moderación generan falsos positivos**: Se identificaron moderaciones sin falsificación real.
3. **Los vendedores con altos rollbacks requieren monitoreo**: Algunos intentan evadir detección mediante cambios en listados.
4. **Análisis de términos en descripciones**: Palabras como *reacondicionado* o *refinado* pueden indicar irregularidades.

## 📅 Fecha y Autor
- **📌 Fecha de creación:** 24 de febrero de 2025  
- **✍ Autor:** Danilo Andrés Alfonso Bohórquez

---