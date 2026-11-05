# data_science_utn_clusterai2026_rasines

Trabajo Práctico Final — Ciencia de Datos (ClusterAI, UTN FRBA) — **Bank Subscription**

Ignacio Rasines — Legajo 2026223 — Grupo 3 (Galdames, González, Molina, Rasines)

## Contenido
| Archivo | Descripción |
|---|---|
| `clusterai_ignacio_rasines_eda.ipynb` | Análisis exploratorio de datos |
| `clusterai_ignacio_rasines_preprocesamiento.ipynb` | Limpieza, imputación, encoding, escalado y split train/test |
| `clusterai_ignacio_rasines_machine_learning.ipynb` | Modelos (Regresión Logística, KNN, Árbol, Random Forest, XGBoost, MLP), ajuste de umbral, PCA |
| `clusterai_reporte_Rasines.pdf` | Reporte técnico |
| `datos/bank_subscription.csv` | Dataset original |

## Cómo ejecutar
Ejecutar los notebooks en este orden (desde esta carpeta):
1. `clusterai_ignacio_rasines_eda.ipynb`
2. `clusterai_ignacio_rasines_preprocesamiento.ipynb` (genera `datos/bank_train.csv` y `datos/bank_test.csv`)
3. `clusterai_ignacio_rasines_machine_learning.ipynb`

Librerías: pandas, numpy, matplotlib, seaborn, scipy, scikit-learn (>= 1.2), xgboost (>= 2.1.4).
