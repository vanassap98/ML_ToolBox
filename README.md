# 🧰 ML_ToolBox

Este repositorio contiene el módulo `toolbox_ML.py`, desarrollado por el equipo 7 durante el Team Challenge nº 3 del bootcamp de Data Science en The Bridge. El objetivo es construir un conjunto de funciones reutilizables para el análisis y la selección de variables en modelos de regresión, tanto desde el punto de vista estadístico como visual.

---

## 🚀 Funciones implementadas

| Función                         | Descripción |
|--------------------------------|-------------|
| `describe_df`                  | Describe las variables del DataFrame: tipo, nulos, únicos, cardinalidad |
| `tipifica_variables`           | Clasifica automáticamente las variables como binaria, categórica, numérica discreta o continua |
| `get_features_num_regression`  | Selecciona variables numéricas correlacionadas con el target según un umbral y p-value |
| `plot_features_num_regression` | Visualiza variables numéricas correlacionadas con el target usando pairplots |
| `get_features_cat_regression`  | Selecciona variables categóricas relacionadas con el target mediante ANOVA, Kruskal o Mann-Whitney |
| `plot_features_cat_regression`| Visualiza la relación entre variables categóricas y el target mediante histogramas agrupados |

---

## 🧪 Uso del módulo

Todas las funciones están definidas en `toolbox_ML.py`. Puedes importarlas en tu entorno de trabajo o usarlas directamente en un notebook:

```python
from toolbox_ML import get_features_num_regression, plot_features_num_regression
```

Consulta el notebook test_toolbox.ipynb para ver ejemplos prácticos.

---

👥 Equipo
Este proyecto ha sido desarrollado por el equipo de estudiantes del bootcamp de Data Science en The Bridge:

Antonio (AntGV)
Ceci (vanassap98)
Estefany (EstefanyAmesty)
Hugo (chucklesmon)
