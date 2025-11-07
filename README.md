# 🏭 Inteligencia Artificial Industrial (PUCP)

Repositorio con dos casos de estudio del curso **Inteligencia Artificial Industrial (1MTR19)**:
- **EX1:** Detección de válvulas defectuosas en un sistema de **propulsión espacial** (clasificación).
- **EX2:** Estimación de **RUL (Remaining Useful Life)** en **motores de avión** (regresión).

## 📦 Proyectos incluidos
1. `EXAM1_Spacecraft_Fault_Detection/` — Clasificación de válvulas defectuosas (Spacecraft 1/2 entrenan; 3 valida).
2. `EXAM2_RUL_Estimation/` — Predicción de vida útil remanente (NASA C-MAPSS/PHM 2008).

## 🧩 Habilidades aplicadas
- EDA & preprocesamiento · limpieza · selección de variables
- Modelado (XGBoost, Random Forest, Regresión) y **optimización bayesiana (Optuna)**
- Validación cruzada y **comparación con Baselines**
- Preparación de **submissions Kaggle** (formato, métricas)

## 🧠 Resultados destacados
- **EX1 (Clasificación):** XGBoost alcanzó Accuracy **≈0.89**; baseline constante quedó muy por debajo.  
- **EX2 (RUL):** XGBoost con Optuna redujo RMSE de **≈37.9** a **≈35.8** en promedio (CV).

> Detalles y gráficos en los README de cada proyecto.
