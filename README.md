# 🛒 Proyecto Final: Predicción de Precios en E-commerce

> **Asignatura:** Ciencia de Datos con Python  
> **Tema:** Análisis y predicción de precios de productos — Books to Scrape  
> **Integrantes:** Esleider Salas, Omar Lacar, Keyber David, Maria Cabarcas  

---

## 📁 Estructura del Repositorio

```
proyecto-ciencia-datos/
│
├── 📓 Proyecto_Final_Ciencia_Datos.ipynb   ← Notebook principal (Google Colab)
│
├── 📊 data/
│   ├── books_raw.csv       ← Dataset crudo extraído por scraping
│   └── books_clean.csv     ← Dataset limpio y procesado
│
├── 🖼️ outputs/
│   ├── eda_01_distribucion_precios.png
│   ├── eda_02_distribucion_rating.png
│   ├── eda_03_boxplot_precio_rating.png
│   ├── eda_04_top_categorias.png
│   ├── eda_05_heatmap_correlaciones.png
│   ├── eda_06_outliers.png
│   ├── eda_07_rangos_stock.png
│   ├── ml_01_comparativa_base.png
│   ├── ml_02_gridsearch_resultados.png
│   ├── ml_03_feature_importance.png
│   └── ml_04_cross_validation.png
│
├── 📋 README.md                            ← Este archivo
└── 📄 requirements.txt                    ← Dependencias del proyecto
```

---

## 🚀 Cómo Ejecutar

### Opción A: Google Colab (recomendado)
1. Abrir [Google Colab](https://colab.research.google.com)
2. `Archivo → Subir cuaderno` → seleccionar `Proyecto_Final_Ciencia_Datos.ipynb`
3. `Runtime → Run all` (ejecutar todo)
4. La primera celda instala las dependencias automáticamente

### Opción B: Local
```bash
pip install -r requirements.txt
jupyter notebook Proyecto_Final_Ciencia_Datos.ipynb
```

---

## 📋 Resumen de Fases

| Fase | Descripción | Tecnologías |
|------|-------------|-------------|
| I    | Web Scraping de 50 páginas | `requests`, `BeautifulSoup`, `pandas` |
| II   | Limpieza y transformación avanzada | `pandas`, `numpy` |
| III  | EDA y visualización (8 gráficos) | `matplotlib`, `seaborn` |
| IV   | Modelos ML base (RF, SVR, GB) | `scikit-learn` |
| V    | Optimización GridSearchCV | `GridSearchCV` |
| VI   | Validación Cruzada 5-folds | `cross_val_score` |

---

## 📊 Resultados Clave

- **1.000 productos** extraídos de 50 páginas con scraping dinámico
- **50 categorías** de productos identificadas
- **Mejor modelo:** Random Forest Optimizado
- **Validación Cruzada:** R² promedio (5-folds) con baja desviación estándar
- **Variable más importante:** Categoría del producto

---

## 🔗 Entregables
- 📓 https://colab.research.google.com/drive/1DntHeFoKgpIhWS_uDZy003tfL7ZlmlzM?usp=sharing(#) 
- 🎥 (#) 
