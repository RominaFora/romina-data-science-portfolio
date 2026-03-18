Forecast de Demanda – Último Trimestre 2025

Este proyecto desarrolla un modelo de predicción de demanda utilizando datos diarios de ventas del último trimestre de 2025 (octubre–diciembre).  
El objetivo es anticipar el comportamiento de ventas hacia fin de año, considerando eventos estacionales como Halloween, Black Friday, Navidad y Año Nuevo.

---

🎯 Objetivos del proyecto

- Analizar ventas diarias entre octubre y diciembre de 2025.
- Detectar patrones de tendencia, estacionalidad semanal y picos estacionales.
- Construir un modelo de forecasting con Prophet.
- Evaluar el desempeño del modelo con métricas de error.
- Generar visualizaciones claras para la toma de decisiones comerciales.

---

🧠 Tecnologías utilizadas

- Python  
- pandas, numpy  
- matplotlib, seaborn  
- Prophet  
- scikit-learn  

---

📁 Estructura del proyecto

`
forecast-demand/
├─ notebooks/
│  └─ forecast_demand.ipynb
├─ data/
│  └─ ventas.csv
└─ src/
   ├─ data_preprocessing.py
   ├─ forecasting_models.py
   └─ visualization.py
`

---

📊 Dataset utilizado

Archivo: ventas.csv  
Período: 1 de octubre al 31 de diciembre de 2025  
Frecuencia: diaria  
Columnas:

- date → fecha  
- sales → ventas diarias  

El dataset incluye:

- Tendencia creciente hacia fin de año  
- Estacionalidad semanal (fines de semana más altos)  
- Picos reales:
  - 31/10 — Halloween  
  - 28/11 — Black Friday  
  - 24–25/12 — Navidad  
  - 31/12 — Año Nuevo  

Este comportamiento lo hace ideal para entrenar modelos de forecasting con estacionalidad múltiple.

---

🚀 Cómo ejecutar el proyecto

1. Instalar dependencias:
   `
   pip install pandas numpy matplotlib seaborn prophet scikit-learn
   `

2. Colocar ventas.csv dentro de la carpeta /data.

3. Abrir el notebook:
   `
   notebooks/forecast_demand.ipynb
   `

4. Ejecutar las celdas en orden.

---

📈 Resultados esperados

- Gráficos de tendencia y estacionalidad  
- Predicción de ventas futuras  
- Identificación de picos estacionales  
- Métricas de error (MAE, MSE)  
- Insights accionables para planificación comercial  

---

✨ Autor

Romina Fora  
Data Scientist | Estrategia | Creatividad  
`

---
