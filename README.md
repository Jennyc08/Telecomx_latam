# Análisis de Evasión de Clientes (Churn) — Telecom X

## 📌 Descripción del Proyecto
Este proyecto tiene como objetivo analizar los factores que influyen en la evasión de clientes (churn) en **Telecom X**.  
A través de la recolección, limpieza, procesamiento y análisis de datos, se busca identificar patrones y relaciones que permitan implementar estrategias efectivas de retención y apoyar el desarrollo de modelos predictivos.

El análisis se desarrolla en Python, empleando bibliotecas como **Pandas**, **NumPy**, **Matplotlib** y **Seaborn**, siguiendo un flujo de trabajo ETL (Extracción, Transformación y Carga).

---

## 🎯 Objetivos
- Cargar y procesar datos desde una fuente JSON externa.
- Realizar un análisis exploratorio de datos (EDA) con métricas y visualizaciones.
- Detectar y corregir inconsistencias, valores nulos y duplicados.
- Generar nuevas variables relevantes para el análisis:
  - **Cuentas_Diarias**: estimación del cargo diario del cliente.
  - **num_servicios**: cantidad de servicios contratados.
- Evaluar la correlación de variables con el churn.
- Elaborar un informe final en formato HTML con resultados, conclusiones y recomendaciones.

---

## 📂 Estructura del Proyecto
TelecomX-Churn/
├── data/ # Almacenamiento de datos (raw y procesados)
├── notebooks/ # Notebooks de análisis
├── reports/ # Informes generados (HTML, Markdown)
├── src/ # Scripts de ETL, limpieza y funciones auxiliares
├── requirements.txt # Dependencias del proyecto
└── README.md # Descripción del proyecto

---

## ⚙️ Requisitos
- Python 3.10 o superior
- Bibliotecas:
  ```bash
  pandas
  numpy
  matplotlib
  seaborn
---
## Instalación de dependencias:
pip install -r requirements.txt

---
## Ejecución
### 1. Abrir el Notebook principal (notebooks/01_eda.ipynb) y ejecutar todas las celdas:

Carga y limpieza de datos.
Creación de variables derivadas.
Análisis exploratorio y visualizaciones.
Generación del informe final en reports/informe_final.html.

### 2. Abrir el informe final:
## En Jupyter local:
import webbrowser
webbrowser.open("reports/informe_final.html")

## En Google Colab:
from google.colab import files
files.download("reports/informe_final.html")
---
##  Resultados del Análisis
El informe final incluye:
Tasa global de churn.
Distribución de churn por variables categóricas y numéricas.
Principales correlaciones con la variable de evasión.
Patrones relevantes (ej.: relación entre tipo de contrato y cancelación).
Visualizaciones de apoyo para la toma de decisiones.

---
##  Conclusiones y Recomendaciones
Clientes con contratos más cortos presentan mayor tasa de churn.
Altos cargos diarios/mensuales se asocian con mayor probabilidad de cancelación.
La retención es más alta en clientes con mayor número de servicios contratados.

## Se recomienda:

Ofrecer beneficios para contratos de largo plazo.
Revisar política de precios para clientes con cargos elevados.
Implementar estrategias de fidelización en los primeros meses de servicio.

---
## Licencia
Este proyecto se distribuye bajo licencia MIT.

Autor: Jenny Carolina Finol Hernandez 
