# ✈️ EX2 — Remaining Useful Life (RUL) Estimation · Aircraft Engines

**Problema:** Predecir la **vida útil remanente (RUL)** de motores usando registros por **ciclos** con **26 variables** (settings + sensores).

## 🧩 Pipeline
1. **EDA & Preprocesamiento:** limpieza, eliminación de sensores redundantes, normalización.
2. **Modeling (base):** **XGBoost** con split recomendado (train: units 41–100, val: 21–40).
3. **Optimización Bayesiana:** **Optuna** para `n_estimators`, `learning_rate`, `max_depth`.
4. **Validación Cruzada:** 4 escenarios con RMSE promedio.
5. **Predicción final:** `submission.csv` para units 1–20 (estilo Kaggle).

## 🧠 Resultados (resumen)
| Modelo                 | RMSE (avg) |
|------------------------|-----------:|
| **XGBoost + Optuna**   | **≈35.8**  |
| XGBoost (base)         | ≈37.9      |
| Random Forest          | ≈41.3      |

## ▶️ Ejecución
- `Examen2_1MTR19_20201296_codigo.ipynb`

## 🧰 Librerías
`pandas`, `numpy`, `scikit-learn`, `xgboost`, `optuna`, `matplotlib`
