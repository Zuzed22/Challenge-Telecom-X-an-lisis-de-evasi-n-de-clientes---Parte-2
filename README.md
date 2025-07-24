# Challenge-Telecom-X-an-lisis-de-evasi-n-de-clientes---Parte-2
Telecom X – Parte 2: Predicción de Cancelación (Churn).   

# 📊 Predicción de Churn en Clientes de TelecomX

Este repositorio contiene un proyecto de Machine Learning desarrollado para predecir la pérdida de clientes (**churn**) en una empresa de telecomunicaciones ficticia llamada **TelecomX**. El objetivo es identificar con anticipación qué clientes tienen mayor probabilidad de cancelar el servicio, permitiendo estrategias efectivas de retención.

---

## 🤖 Tecnologías utilizadas

- Python 3.10+
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

---

## 🗃️ Estructura del Proyecto
telecom_churn_ml_prediction/
│
├── telecom_churn_ml_prediction.ipynb # Notebook principal del análisis y modelado
├── README.md # Este archivo
└── data/ # (Opcional) Carpeta para dataset limpio/procesado

---

## 📌 Objetivos del Proyecto

- Analizar los factores que influyen en la deserción de clientes.
- Preprocesar y seleccionar las variables más relevantes.
- Entrenar y comparar diferentes modelos de clasificación.
- Evaluar el desempeño con métricas como **ROC-AUC**, **Recall**, **F1-score**.
- Proponer estrategias de acción basadas en los resultados del modelo.

---

## 🖥 Modelos Entrenados

Se evaluaron 7 modelos de clasificación:

- Regresión Logística
- K-Nearest Neighbors
- Support Vector Machine (RBF)
- Naive Bayes
- Árbol de Decisión
- Random Forest
- Gradient Boosting

> Los modelos fueron entrenados usando validación cruzada y balanceo de clases.

---

## 📈 Resultados

Los mejores modelos alcanzaron una precisión (Accuracy) superior al 85%, siendo **Gradient Boosting** y **Random Forest** los más efectivos. Se utilizaron gráficos de curva ROC y análisis de importancia de variables para interpretar los resultados.

---

## 💻 Variables Más Relevantes

- Tipo de contrato (`Contract_Month-to-month`, `Contract_Two year`)
- Servicios adicionales (`TechSupport`, `OnlineSecurity`)
- Tiempo de permanencia (`tenure`)
- Cargos mensuales (`MonthlyCharges`)

---

## 🧭 Conclusiones

- La mayoría de los clientes que desertan tienen contrato mensual y no usan servicios de soporte técnico.
- El modelo puede integrarse en campañas de retención para actuar antes de que el cliente cancele.

---

## 📝 Cómo usar este repositorio

- Clona el repositorio:
   git clone https://github.com/Zuzed22/Challenge-Telecom-X-an-lisis-de-evasi-n-de-clientes---Parte-2.git

- Instala los requerimientos:
pip install -r requirements.txt

- Ejecuta el notebook en Jupyter:
jupyter notebook TelecomX_LATAM_parte2.ipynb


Este proyecto fue desarrollado por [Zuleika González].

