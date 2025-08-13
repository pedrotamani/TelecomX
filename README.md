## 📊 Objetivo del Proyecto
Este proyecto busca identificar los factores clave que influyen en la evasión de clientes (Churn) en una empresa de telecomunicaciones, mediante:

🔹 Limpieza y transformación de datos.

🔹 Análisis exploratorio (EDA) con visualizaciones.

🔹 Recomendaciones estratégicas para reducir el abandono.

---

## 🎯 Problema clave: 

   El 27% de los clientes abandona el servicio, impactando en la rentabilidad.

---

## 📂 Estructura del Proyecto
```
├── data/  
│   ├── raw/                       # Datos originales (CSV)  
│   └── processed/                 # Datos limpios  
├── notebooks/  
│   ├── 1_limpieza_datos.ipynb     # Limpieza y preprocesamiento  
│   └── 2_analisis_churn.ipynb     # EDA y visualizaciones  
├── outputs/  
│   ├── graphs/                    # Gráficos exportados  
│   └── reports/                   # Informes en PDF/Markdown  
├── README.md                      # Este archivo  
└── requirements.txt               # Dependencias  
````
---

## 🔍 Principales Hallazgos

### 📈 Visualizaciones Clave

1. **Distribución de Churn**
     - 73% permanecen vs 27% abandonan

2. **Churn por Tipo de Contrato**
      - Contratos mensuales tienen 3x mayor tasa de abandono

3. **Correlación entre Variables**
      - Antigüedad (tenure) muestra mayor correlación negativa con Churn

### 💡 Insights Principales

🔹 📉 **Clientes nuevos** (<1 año) representan 60% de los abandonos

🔹 💰 **Pagos mensuales altos** (>$75) aumentan riesgo de abandono

🔹 📅 **Contratos a largo plazo** reducen Churn en 65%

🔹 🛡️ **Servicios adicionales** disminuyen probabilidad de abandono


---

## 🛠️ Cómo Ejecutar el Proyecto

### 📌 Requisitos Previos

🔹 Python 3.8+

🔹 Jupyter Notebook

🔹 Librerías listadas en `requirements.txt`

### Instalación

```bash
git clone https://github.com/tu_usuario/telecom-churn-analysis.git
cd telecom-churn-analysis
pip install -r requirements.txt
````
---

## 📬 Contacto

Cualquier duda o sugerencia, puedes escribirme a pedro.tamani@gmail.com

