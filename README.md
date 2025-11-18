# Telco Customer Churn Analysis 📊

Este proyecto combina **Python (Machine Learning & Data Exploration)** y **Power BI (Dashboard visual)** para analizar el comportamiento de los clientes de una empresa de telecomunicaciones y detectar patrones asociados a la **pérdida de clientes (Churn)**.

---

## 📁 Descripción del proyecto

El análisis se basa en un dataset de clientes con información sobre servicios contratados, historial de pagos, duración del contrato y características demográficas.  
El objetivo fue **predecir la probabilidad de abandono** y visualizar los resultados en un dashboard interactivo.

---

## 🧠 Objetivos del análisis

- Explorar los datos con **Python** y detectar las variables con mayor impacto en el churn.  
- Construir un modelo predictivo con técnicas de **Machine Learning**.  
- Visualizar las métricas clave y los resultados del modelo en **Power BI**.  
- Obtener insights para mejorar la retención de clientes.

---

## ⚙️ Proceso de trabajo

### 1. Exploración y modelado (Python)
- Limpieza y codificación de variables.  
- Entrenamiento de un modelo de árbol de decisión.  
- Cálculo de **importancia de variables** (`feature_importances_`).  
- Análisis de las principales variables que explican el churn:
  - `tenure` (tiempo de permanencia del cliente)  
  - `InternetService_Fiber optic`  
  - `TotalCharges`  
  - `MonthlyCharges`  
  - `Contract_One year` y `Contract_Two year`

### 2. Visualización (Power BI)
- Creación de un dashboard con indicadores clave:  
  - Total de clientes  
  - Clientes que se fueron y permanecen  
  - Tasa de churn (%)  
  - Comparativa por tipo de contrato  
  - Segmentadores interactivos

---

## 📈 Métricas principales (Power BI)

| Métrica | Valor |
|----------|--------|
| **Clientes Totales** | 7,043 |
| **Clientes con Churn** | 1,869 |
| **Clientes sin Churn** | 5,174 |
| **Tasa de Churn** | 26.54% |

---

## 🧩 Herramientas utilizadas

- **Python** (pandas, scikit-learn, matplotlib, Jupyter)  
- **Power BI Desktop**  
- **Power Query** para transformación de datos  
- **GitHub** para documentación y control de versiones

---

## 💡 Insights clave

- Los clientes con contrato **Month-to-month** presentan la tasa de abandono más alta.  
- Los contratos **de 1 o 2 años** reducen considerablemente la probabilidad de churn.  
- La variable **tenure** (antigüedad del cliente) es el factor más influyente.  

---

## 🧑‍💻 Autor

**Alan De Pedro**  
Data Analyst | Power BI | Python | SQL  
📍 [LinkedIn](https://www.linkedin.com/in/alandepedro22)

---

## 🗂️ Estructura del proyecto

