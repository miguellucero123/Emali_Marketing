Análisis y Optimización de Email Marketing Bancario
Descripción General
Este proyecto realiza un análisis avanzado de datos bancarios y simula campañas de email marketing para optimizar el rendimiento de envíos. El objetivo es proporcionar recomendaciones claras y visualmente atractivas para el jefe de marketing, usando un enfoque basado en evidencia y facilitando la toma de decisiones mediante un brochure ejecutivo generado directamente desde el notebook.

Origen de los Datos
Los datos utilizados provienen de un archivo CSV público hospedado en GitHub:

bank-additional-full.csv (raw)
El notebook S3_G5.ipynb carga estos datos automáticamente para su análisis y simulación.

Proceso de Transformación
Carga de Datos
Se extraen los datos bancarios desde el enlace RAW de GitHub usando Pandas.

Simulación de Métricas de Email Marketing

A partir de los datos bancarios, se generan variables que simulan una campaña real de email marketing:
Emails enviados
Emails abiertos (según perfil y engagement)
Clics en emails
Hora y día del envío (basados en patrones de comportamiento bancario)
Se segmentan los clientes y se aplican tasas de apertura/clic realistas según su perfil.
Análisis Estadístico y Visual

Se calculan tasas de apertura, clic y CTR para cada segmento, hora y día.
Se identifican los mejores momentos para enviar correos (mayor probabilidad de éxito).
Se generan gráficos y tablas resumen que resumen los hallazgos principales.
Brochure Ejecutivo

El notebook está diseñado para generar páginas estilo brochure, ideales para presentaciones ejecutivas.
El objetivo es convencer con evidencia al jefe de marketing sobre la eficacia del enfoque analítico.
Principales Hallazgos
Mejor hora para envío: 09:00 (mayor tasa de apertura y clic).
Mejor día para envío: Jueves (mayor tasa de apertura y clic).
Diferencia entre días laborales y fines de semana: Notable ventaja en días laborales respecto al engagement.
Ejecución y Uso
Abre el archivo S3_G5.ipynb en Jupyter Notebook.
Ejecuta todas las celdas en orden. El notebook descargará los datos y realizará todo el análisis automáticamente.
Los gráficos y tablas generadas pueden usarse directamente para presentaciones o para la toma de decisiones en el área de marketing.
Requisitos
Python 3.8+
Bibliotecas utilizadas: pandas, numpy, matplotlib, seaborn, IPython
Instala los paquetes requeridos con:

bash
pip install pandas numpy matplotlib seaborn ipython
Objetivo del Proyecto
El propósito fundamental es demostrar, mediante un análisis reproducible y visualmente persuasivo, que la estrategia de segmentación y envío de campañas de email marketing propuesta es óptima para el banco. El brochure generado puede ser presentado directamente a la gerencia de marketing como soporte para la toma de decisiones.

Créditos
Departamento de Analítica — Grupo 5, Taller de Analítica Comercial
- Compatible con todos los navegadores modernos
- No requiere conexión a internet para visualizar

---
*"Los datos no son solo números, son oportunidades para conectar mejor con sus clientes"*
