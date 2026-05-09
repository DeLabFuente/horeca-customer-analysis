🇬🇧 \[English version](README\_EN.md) | 🇪🇸 Versión en español



\# 🍺 Análisis de Clientes HORECA — Python



\## Descripción

Análisis de segmentación de clientes de un distribuidor 

mayorista de bebidas usando técnicas de clustering con 

Python. Desarrollado como parte de mi portafolio de 

análisis de datos orientado al sector HORECA y gran 

consumo.



\## Objetivo

Identificar patrones de comportamiento de compra entre 

clientes HORECA y Retail, segmentarlos en grupos 

comerciales accionables y extraer insights para la 

toma de decisiones comerciales.



\## Dataset

\- \*\*Fuente:\*\* Kaggle — Wholesale Customers Dataset

\- \*\*Licencia:\*\* UCI Machine Learning Repository

\- \*\*Tamaño:\*\* 440 clientes × 8 columnas

\- \*\*Categorías:\*\* Fresh, Milk, Grocery, Frozen, 

&#x20; Detergents\_Paper, Delicassen



\## Herramientas y Tecnologías

\- \*\*Python\*\* — análisis y modelado

\- \*\*Pandas \& NumPy\*\* — manipulación de datos

\- \*\*Matplotlib \& Seaborn\*\* — visualización

\- \*\*Scikit-learn\*\* — clustering K-Means



\## Proceso de Análisis

\- Carga y exploración del dataset

\- Verificación de calidad: 0 nulos, 0 duplicados

\- Transformación de variables categóricas

\- Análisis exploratorio por canal

\- Mapa de correlaciones entre categorías

\- Normalización con StandardScaler

\- Determinación de K óptimo (método del codo)

\- Clustering K-Means con K=5

\- Asignación de nombres comerciales a segmentos



\## Insights Clave

\- 🍽️ HORECA representa el 67,7% de los clientes

\- 🛒 Retail supera a HORECA en gasto medio general

\- 🥩 HORECA domina en Fresh y Frozen

\- 🔗 Alta correlación entre Grocery y 

&#x20; Detergents\_Paper (perfil Retail)

\- ⭐ Identificado 1 cliente VIP con consumo 

&#x20; extraordinario de productos frescos



\## Segmentación de Clientes

| Segmento | Clientes | Perfil |

|---|---|---|

| Cliente Estándar | 270 | Consumo moderado general |

| Cliente Retail | 96 | Alto gasto en Grocery |

| Cliente Medio | 63 | Perfil equilibrado |

| Cliente Especializado | 10 | Nicho específico |

| Cliente VIP | 1 | Consumo extraordinario Fresh |



\## Visualizaciones

!\[Distribución por Canal](03\_Documentacion/Imagenes/distribucion\_canal.png)

!\[Gasto Medio por Canal](03\_Documentacion/Imagenes/gasto\_medio\_canal.png)

!\[Correlaciones](03\_Documentacion/Imagenes/correlaciones.png)

!\[Método del Codo](03\_Documentacion/Imagenes/metodo\_codo.png)

!\[Clusters](03\_Documentacion/Imagenes/clusters.png)

!\[Segmentación Comercial](03\_Documentacion/Imagenes/segmentacion\_comercial.png)



\## Autor

\*\*Daniel Díaz De La Fuente\*\*  

Analista de Datos en formación |

Python · Power BI · SQL · R  

Certificado Google Data Analytics (media 94,85%) ·

Business Analytics with Excel — Johns Hopkins  

📍 Sevilla, España  

\[LinkedIn](https://www.linkedin.com/in/danieldiazdelafuente/) | \[GitHub](https://github.com/DeLabFuente)



> 📥 Notebook completo disponible en este repositorio:

> HORECA\_Customer\_Analysis.ipynb

