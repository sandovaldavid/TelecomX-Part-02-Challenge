# 🤖 Telecom X - Machine Learning Challenge

[![Python](https://img.shields.io/badge/python-3.11-blue.svg)](https://www.python.org/)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-1.3.2-orange)](https://scikit-learn.org/)
[![Pandas](https://img.shields.io/badge/pandas-2.3.1-yellow)](https://pandas.pydata.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

<p align="center">
  <img src="https://cdn1.gnarususercontent.com.br/6/409126/832d01c5-aa1f-4a72-894b-9bb18b8d2a00.png" alt="ETL Badge"/>
</p>

---

## 🔍 Descripción

**Telecom X - Parte 2** es el challenge final de la ruta **Estadísticas y Machine Learning G8 - ONE** de Alura Latam y Oracle.  
Este proyecto consiste en aplicar técnicas estadísticas, regresión y modelos de clasificación para **predecir la cancelación de clientes (churn)** en una empresa de telecomunicaciones.

---

## 🎯 Objetivos del proyecto

- Aplicar el ciclo completo de un proyecto de ciencia de datos real.
- Explorar, limpiar y preparar los datos para modelado predictivo.
- Implementar modelos de regresión logística y random forest.
- Analizar el comportamiento de clientes y generar insights para retención.

---

## 🛠️ Tecnologías y herramientas utilizadas

- **Lenguaje**: Python 3.11
- **Entorno**: Jupyter Notebook
- **Librerías**:
  - `pandas`, `numpy`, `matplotlib`, `seaborn`
  - `scikit-learn` para modelos y métricas
  - `imbalanced-learn` para balanceo de clases con SMOTE

---

## 🧠 Conocimientos aplicados

Este proyecto es la culminación de la ruta de aprendizaje **Estadística y Machine Learning - G8**, y aplica los conocimientos adquiridos en los siguientes cursos:

- 📊 **Estadística con Python**:
  - Frecuencias, medidas de dispersión, media, mediana, moda, muestreo.
- 📈 **Regresión lineal**:
  - Modelado, métricas, interpretación de coeficientes.
- 🤖 **Machine Learning - Clasificación**:
  - Modelos supervisados, validación, métricas de evaluación.
- ✈️ **IA aplicada a datos reales**:
  - Predicción de eventos como cancelación o retraso.

---

## ⚙️ Estructura del proyecto

```text
TelecomX_ML_Challenge/
├── TelecomX_Cleaned.csv         # Datos ya tratados desde la parte 1
├── TelecomX_Desafio_Parte2.ipynb  # Notebook completo y comentado
├── README.md
└── LICENSE
```

---

## 🚀 Cómo ejecutar el proyecto

1. Clona este repositorio:
   ```bash
   git clone https://github.com/sandovaldavid/TelecomX-Part-02-Challenge.git
   cd TelecomX-Part-02-Challenge
   ```

2. Crea un entorno virtual e instala dependencias:
   ```bash
   python -m venv venv
   venv\Scripts\activate  # Windows
   source venv/bin/activate  # macOS/Linux
   pip install -r requirements.txt
   ```

3. Ejecuta el notebook:
   ```bash
   jupyter lab
   ```

---

## 📊 Lo que contiene el proyecto

- ✔️ **Preprocesamiento** completo (limpieza, encoding, normalización).
- 📊 **Análisis exploratorio**: visualizaciones, correlaciones, boxplots.
- ⚖️ **Balanceo con SMOTE** para datos desbalanceados.
- 🧠 **Modelos**: Regresión Logística y Random Forest.
- 📈 **Evaluación de modelos** con `classification_report`.
- 🧪 **Predicción individual** de nuevos clientes.

---

## 📌 Conclusiones

- Se identificaron variables clave asociadas al churn como el tipo de contrato, duración y forma de pago.
- Random Forest mostró mayor robustez al captar relaciones no lineales.
- SMOTE mejoró el rendimiento del modelo para la clase minoritaria.
- Se pueden implementar estrategias de retención basadas en los insights obtenidos.

---

## 🧭 Ruta ONE G8: Estadística y Machine Learning

Este proyecto es parte del programa **Oracle Next Education (ONE)** en colaboración con **Alura Latam**, Grupo 8:

```
📘 Ruta seguida:
1. Estadística con Python: frecuencias y medidas
2. Estadística con Python: probabilidad y muestreo
3. Regresión lineal con Python
4. Técnicas avanzadas de modelado
5. Clasificación con ML y validación
6. IA aumentada y predicción
7. 🚀 Challenge Telecom X Parte 2 (este proyecto)
```

---

## 📄 Licencia

Este proyecto está bajo la Licencia MIT.  
Desarrollado para fines educativos en el Programa ONE (Alura + Oracle).
