## 2.a) Proyecto: **EXAM1_Spacecraft_Fault_Detection**  
**Archivo:** `EXAM1_Spacecraft_Fault_Detection/README.md`

# 🚀 EX1 — Spacecraft Propulsion System · Fault Detection

**Problema:** Identificar la **válvula defectuosa (0–3)** en un sistema de propulsión a partir de señales de **presión (P2)**.

## 🧩 Pipeline
1. **Data preprocessing:** lectura, EDA, extracción de features de P2, unión con `labels`.
2. **Modeling:** **XGBoost**, Random Forest, Regresión Logística.
3. **Evaluación:** Accuracy y Matriz de Confusión vs **Baseline de Valor Constante (BVC)**.
4. **Entrega Kaggle:** generación de `submission.csv` para Spacecraft 3.

## 🧠 Resultados (resumen)
| Modelo        | Accuracy | Comentario                 |
|---------------|---------:|----------------------------|
| **XGBoost**   | **0.89** | Mejor desempeño global     |
| RandomForest  | 0.84     | Menor sobreajuste          |
| **BVC**       | 0.42     | Solo referencia (baseline) |

## ▶️ Ejecución
- `EX1_1MTR19_20201296_codigo.ipynb`

## 🧰 Librerías
`pandas`, `numpy`, `scikit-learn`, `xgboost`, `matplotlib`
