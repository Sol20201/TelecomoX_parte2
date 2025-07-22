# 📊 Predicción de Cancelación de Clientes — TelecomX

## 🚀 Descripción General

Este proyecto tiene como objetivo anticipar qué clientes tienen mayor probabilidad de cancelar sus servicios en TelecomX, utilizando modelos de machine learning. El análisis parte de datos históricos de clientes y construye un pipeline completo para el tratamiento de datos, modelado, evaluación y generación de estrategias de retención.

---

## 🎯 Objetivos del Proyecto

- Preprocesar y codificar los datos.
- Realizar análisis de correlación y selección de variables.
- Aplicar técnicas de balanceo como SMOTE.
- Entrenar y comparar múltiples modelos de clasificación.
- Evaluar el rendimiento de los modelos con métricas interpretables.
- Identificar variables clave que influyen en la cancelación.
- Proponer acciones estratégicas para mitigar el abandono.

---

## 🧰 Herramientas Utilizadas

- **Python**
- **Google Colab**
- **Pandas**, **NumPy** — manipulación de datos
- **scikit-learn** — modelos y preprocesamiento
- **imblearn** — balanceo de clases con SMOTE
- **Seaborn**, **Matplotlib** — visualización
- **XGBoost** *(opcional)* — técnica de boosting

---

## 📁 Estructura del Proyecto

- `df_final.csv` — Base de datos original de clientes.
- `TelecomXpte2.ipynb` — Notebook con todo el desarrollo.
- `README.md` — Documento explicativo del proyecto.
- *Gráficos y visualizaciones* — insertados directamente en el notebook.

---

## 🧪 Modelos Implementados

1. **Dummy Classifier** — modelo base de referencia.
2. **Random Forest** — mejor desempeño general.
3. **KNN** — basado en proximidad, sensible a escalado.
4. **Regresión Logística** — interpretabilidad por coeficientes.
5. **SVM** — separación geométrica entre clases.
6. *(Opcional)* **XGBoost** — mayor precisión para escenarios complejos.

---

## 📈 Principales Resultados

| Modelo            | Accuracy | Recall Cancelación | F1-Score Cancelación |
|-------------------|----------|---------------------|------------------------|
| Random Forest      | 77.7%    | ✅ 72%              | ✅ 62%                 |
| KNN                | 67.7%    | 70%                 | 53%                   |
| Dummy Classifier   | 74.3%    | 0%                  | 0%                    |

---

## 🔍 Variables más relevantes

Según el análisis conjunto de coeficientes, correlación y importancia relativa:

- **Antigüedad**
- **Tipo de contrato (mensual)**
- **Método de pago (electronic check)**
- **Servicio de internet (Fiber optic)**
- **Cargos mensuales y totales**
- **Facturación sin papel**

---

## 🎯 Estrategias de Retención Propuestas

- Fidelización temprana para clientes nuevos.
- Incentivos para contratos largos.
- Mejora del servicio de fibra óptica.
- Personalización de planes para altos cargos mensuales.
- Simplificación o asistencia en métodos de pago electrónicos.

---

## 📌 Conclusión

El proyecto permite no solo anticipar el abandono de clientes, sino también actuar de forma proactiva. Gracias al pipeline construido, TelecomX podría implementar alertas, campañas personalizadas y ajustes en su modelo de negocio para mejorar la retención de usuarios.

