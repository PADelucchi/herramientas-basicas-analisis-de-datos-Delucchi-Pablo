                     
## Proyectos

## TP-final-analisis-de-datos 📊

Curso: Herramientas básicas para Análisis de Datos - Centro UTN E-Learning
                                       
## Descripción general: Evolución del mercado argentino de peróxido de hidrógeno (2021-2026) 

Siendo uno de los mayores fabricantes de este insumo,es primordial monitorear nuestra posición en el mercado analizando periódicamente las importaciones de la posición arancelaria correspondiente, así como incluir con la mayor precisión posible las cantidades fabricadas en el país.   

🎯Objetivos principales: Hacer el seguimiento a lo largo de los últimos 5 años de los siguientes indicadores

## 1) Evolución del tamaño del mercado en toneladas y participación de cada empresa

## 2) Evolución de los precios y comparación frente a la competencia

## 3) Incidencia del costo logístico en el precio del producto y su comparación frente a competidores directos.

📂DATASET: (https://app.penta-transaction.com/login) se requiere contraseña pero ya se descargaron los datos en el archivo H2O2... xlsx presente en este repositorio.

🔍Resultados:  Es prioritario renegociar nuestros servicios logísticos, logrando una reducción mínima del 10%, así como también nuestros costos de producción, para ser más competitivos y adaptarnos a la realidad del mercado actual. Con estas medidas, volveremos al nivel mínimo de un Mkt Share del 15%

## Estructura de datos

├── Images/                             : contains images
├── static/                             : plots to show gauge chart, hazard and survival curve, shap values in Flask App  
├── templates/                          : contains html template for flask app
│   └── index.html
├── Customer Survival Analysis.ipynb    : Survival Analysis kaplan-Meier curve, log-rank test and Cox-proportional Hazard model
├── Exploratory Data Analysis.ipynb     : Data Analysis to understand customer data
├── Churn Prediction Model.ipynb        : Random Forest model to predict customer churn
├── app.py                              : Flask App
├── app-pic.png                         : Final App image  
├── explainer.bz2                       : Shap Explainer
├── model.pkl                           : Random Forest model
├── survivemodel.pkl                    : Cox-proportional Hazard model
├── requirements.txt                    : requirements to run this model
├── Procfile                            : procfile for app deployment
├── LICENSE.md                          : MIT License
└── README.md                           : Report
```


🛠️Herramientas utilizadas: entorno Google Colab, Python, pandas, matplotlib, plotly, Power BI

Autor: Pablo Delucchi
