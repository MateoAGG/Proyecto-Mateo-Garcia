# 🎮 Predicción del Éxito Comercial de Videojuegos en Steam

Proyecto aplicado — Maestría en Ciencia de Datos y Maquinas de
**Parte 2: Sistema de Análisis Predictivo o de Clasificación**

## 📌 Descripción

Este proyecto aborda una pregunta de mercado real, desde una perspectiva económica: ¿qué
características de un videojuego (precio, género, plataformas, etc.) predicen su éxito
comercial en Steam? Se desarrolla un pipeline completo de ciencia de datos: adquisición,
limpieza, análisis exploratorio, modelado de clasificación (Regresión Logística y Random
Forest) e interpretación de resultados.

## 📂 Estructura del repositorio

```
├── notebook/
│   └── proyecto_steam_analisis_predictivo.ipynb   
├── Bases_de_datos/
│   └── games.csv                                                           
├── README.md
└── requirements.txt
```

## 🎯 Objetivos

- Adquirir y limpiar datos históricos de Steam, complementados con una consulta en vivo a la
  Steam Web API.
- Realizar un análisis exploratorio con enfoque de mercado (precio, género, "owners").
- Construir y evaluar modelos de clasificación del éxito comercial.
- Interpretar los factores más relevantes y discutir límites éticos del análisis.

## 🗂️ Datos

- **Fuente histórica:** dataset ["Steam Games Dataset"](https://www.kaggle.com/datasets/fronkongames/steam-games-dataset)
  de FronkonGames (Kaggle) — generado con la Steam Web API + SteamSpy, actualizado
  periódicamente (85,000+ juegos).

## 🧪 Metodología

1. Adquisición de datos (Kaggle)
2. Limpieza y validación
3. Análisis exploratorio de datos (EDA)
4. Ingeniería de variables y definición de la variable objetivo (`exitoso`)
5. Modelado (Regresión Logística, Random Forest)
6. Evaluación (accuracy, precision, recall, F1, AUC-ROC)
7. Interpretación de resultados
8. Discusión ética y limitaciones

## ⚙️ Cómo ejecutar

1. Abre `notebook/Steam_analisis_predictivo.ipynb` en Google Colab.
2. Sube tu `kaggle.json` o el CSV del dataset
3. Ejecuta las celdas en orden.

```bash
pip install -r requirements.txt
```

## 🎥 Video explicativo

Ver [(video/enlace_video.md)](https://drive.google.com/drive/folders/1Ce_QJmCDmDlUTSm4Ip4UtyPWf6Ex_J9-?usp=sharing)

## ⚖️ Ética y privacidad

Este proyecto usa exclusivamente datos públicos y agregados a nivel de producto (no de
usuarios individuales), respeta los límites de tasa de la Steam Web API, y declara
explícitamente las limitaciones metodológicas de las estimaciones de "owners". Ver Sección 11
del notebook para el detalle completo.

## 👤 Autor

Mateo Alexander Garcìa Guerrero — Maestría en Ciencia de Datos

