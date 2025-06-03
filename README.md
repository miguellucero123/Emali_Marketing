# Análisis y Optimización de Email Marketing Bancario

## Descripción General

Este proyecto analiza datos bancarios y simula campañas de email marketing para encontrar los mejores momentos de envío, generando un brochure ejecutivo para el jefe de marketing.

## Origen de los Datos

- [bank-additional-full.csv](https://raw.githubusercontent.com/MFuchs1989/Datasets-and-Miscellaneous/main/datasets/bank-additional-full.csv)

## Proceso de Transformación

1. **Carga de datos:** Se descargan desde el enlace anterior.
2. **Simulación:** Se generan métricas realistas de email marketing.
3. **Análisis:** Se identifican mejores horarios y días.
4. **Brochure:** El notebook genera gráficos y tablas listas para presentación.

## Principales Hallazgos

- **Mejor hora:** 09:00
- **Mejor día:** Jueves
- **Diferencia laboral vs. fin de semana:** Notable

## Ejecución

1. Abre el archivo `S3_G5.ipynb` en Jupyter Notebook.
2. Ejecuta todas las celdas.
3. Revisa los gráficos y tablas generados.

## Requisitos

```bash
pip install pandas numpy matplotlib seaborn ipython
