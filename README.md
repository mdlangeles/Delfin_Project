# 🐬 DELFIN_PROJECT – Análisis Exploratorio de PM2.5

Este repositorio documenta un análisis exploratorio y predictivo de la calidad del aire en **Tamaulipas, México**, con énfasis en las concentraciones de **material particulado fino (PM2.5)**. El proyecto fue desarrollado en el marco de una **Pasantía de Investigación de Verano en la Universidad Politécnica de Altamira**, combinando técnicas de *análisis de datos, visualización, imputación de valores faltantes y entrenamiento de modelos de regresión*. El objetivo principal es identificar patrones semanales de contaminación y construir modelos que permitan predecir los niveles de PM2.5 según el día de la semana.

---
## 🗂️ Estructura del proyecto
```
DELFIN_PROJECT/
├── Data/                  # Carpeta destinada a los datasets (raw, procesados, resultados)
├── Model/                 # Contiene el modelo entrenado en formato .pkl
│   └── model.pkl
├── Proyecto.ipynb         # Notebook principal con todo el flujo de análisis
└── README.md              # Este archivo
```
---
## Tecnologías utilizadas
- Python 3.11.9

- pandas, numpy

- matplotlib, seaborn

- scikit-learn

- joblib

---
## ¿Qué hace este proyecto?
🔹 Limpia y unifica datos de calidad del aire

🔹 Imputa en valores nulos con Random Hot Deck

🔹 Remueve outliers con IQR

🔹 Visualiza distribuciones, correlaciones y tendencias temporales

🔹 Crea variables categóricas (día de la semana)

🔹 Entrena tres modelos de regresión:

      - Regresión Lineal
      
      - Random Forest
      
      - Gradient Boosting
      
🔹 Evalúa su desempeño (R², MSE, MAE)

🔹 Analiza predicciones por día de la semana

---

## 📊 Resultados destacados
✅ La Regresión Lineal fue el modelo más preciso con un R² = 0.9937

📈 Viernes y sábado presentaron las mayores concentraciones de PM2.5, por encima de los niveles saludables

📉 Jueves y domingo mostraron los niveles más bajos, probablemente por menor actividad urbana

---

## Ejecución del proyecto

1. Clona este repo:
```
git clone https://github.com/tu_usuario/DELFIN_PROJECT.git

```

2. Accede a la carpeta del proyecto:
```
cd DELFIN_PROJECT
```

3. Instala las dependencias  (requirements.txt):
```
pip install -r requirements.txt
```

4. Abre el notebook y ejecútalo:
```
jupyter notebook Proyecto.ipynb
```
---
## Archivos importantes
- Proyecto.ipynb: flujo completo de análisis

- Data/: datasets originales, procesados y de predicción

- Model/model.pkl: modelo de regresión lineal entrenado

---
## 💬 Créditos

Proyecto desarrollado para análisis de calidad del aire con enfoque en PM2.5 en Tamaulipas, México.
Ideal para visualización, predicción y toma de decisiones en políticas ambientales.

Este proyecto fue desarrollado por:

- **👩‍💻María de los Ángeles Amú Moreno** [@mdlangeles](https://github.com/mdlangeles)
