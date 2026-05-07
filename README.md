🇬🇧 [English version](README_EN.md) | 🇪🇸 Versión en español

# 🍺 Análisis de Clientes HORECA — Python

## Descripción
Análisis de segmentación de clientes de un distribuidor 
mayorista de bebidas usando técnicas de clustering con 
Python. Desarrollado como parte de mi portafolio de 
análisis de datos orientado al sector HORECA y gran 
consumo.

## Objetivo
Identificar patrones de comportamiento de compra entre 
clientes HORECA y Retail, segmentarlos en grupos 
comerciales accionables y extraer insights para la 
toma de decisiones comerciales.

## Dataset
- **Fuente:** Kaggle — Wholesale Customers Dataset
- **Licencia:** UCI Machine Learning Repository
- **Tamaño:** 440 clientes × 8 columnas
- **Categorías:** Fresh, Milk, Grocery, Frozen, 
  Detergents_Paper, Delicassen

## Herramientas y Tecnologías
- **Python** — análisis y modelado
- **Pandas & NumPy** — manipulación de datos
- **Matplotlib & Seaborn** — visualización
- **Scikit-learn** — clustering K-Means

## Proceso de Análisis
- Carga y exploración del dataset
- Verificación de calidad: 0 nulos, 0 duplicados
- Transformación de variables categóricas
- Análisis exploratorio por canal
- Mapa de correlaciones entre categorías
- Normalización con StandardScaler
- Determinación de K óptimo (método del codo)
- Clustering K-Means con K=5
- Asignación de nombres comerciale