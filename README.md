                     
### TP-final-analisis-de-datos 📒

Curso: Herramientas básicas para Análisis de Datos - Centro UTN E-Learning
                                       
### Descripción general: Evolución del mercado argentino de peróxido de hidrógeno (2021-2026) 

Siendo uno de los mayores fabricantes de este insumo,es primordial monitorear nuestra posición en el mercado analizando periódicamente las importaciones de la posición arancelaria correspondiente, así como incluir con la mayor precisión posible las cantidades fabricadas en el país.  

📂DATASET: (https://app.penta-transaction.com/login) se requiere contraseña pero ya se descargaron los datos en el archivo H2O2... xlsx presente en este repositorio.

### Estructura de datos

├── H2O2 2021-Sep 2026_sucio(1).xlsx          : dataset estructurado obtenido de servicios aduaneros

├── MercadoPeroxlimpio(5).xlsx                : dataset limpio de filas nulas y anómalas luego de tratamiento en Colab con Python

├── Mkt perox Ene-Sep comparación.png         : Gráfica con cantidades del mercado con detalle de cada proveedor, para ver evolución y tendencia del mercado

├── Mkt share vs competencia directa.png      : Gráfica para ver nuestra posición frente a competidores

├── README.md                                 : Resumen de los puntos más importantes y acciones para mejorar

├── TP Final Dashboard.pbix                   : Principales KPIs respondiendo a los objetivos 

├── TP final.ipynb                            : Notebook en plataforma Colab utilizando Python para clasificar y extraer datos útiles para analizar las estadísticas de mercado

├── requirements.txt                          : Librerías para correr este modelado de datos con Python


🎯Objetivos principales: Hacer el seguimiento a lo largo de los últimos 5 años de los siguientes indicadores

#### 1) Monitorear la evolución del tamaño del mercado en toneladas y participación de cada empresa y conocer en cualquier año si cumplimos con la meta del 15%

#### 2) Seguir la evolución de los precios y comparación frente a la competencia

#### 3) Medir la incidencia del costo logístico en el precio del producto, que no sea mayor a 150 usd/tn y su comparación frente a competidores directos.

### Instrucciones de uso

Para ver criterios de clasificación y limpieza del dataset, junto con gráficas correr el siguiente enlace
* [Analisis Python via Colab](https://github.com/PADelucchi/herramientas-basicas-analisis-de-datos-Delucchi-Pablo/blob/main/TP%20final%20.ipynb)

Para ver KPIs

 * [PowerBI Dashboard](https://app.powerbi.com/groups/me/reports/98037350-6f8a-49dd-a79e-037e0111255c/9684fd06026c94b4c3b1?experience=power-bi)

El siguiente gráfico muestra el mercado discriminado por empresa proveedora

![Mkt Share y volumen](https://github.com/PADelucchi/herramientas-basicas-analisis-de-datos-Delucchi-Pablo/blob/ae49daa78437e15001ca436db86dd8befbbdc1df/images/Mkt%20perox%20Ene-Sep%20comparaci%C3%B3n.png)


### 🔍Resultados  

Es prioritario renegociar nuestros servicios logísticos, logrando una reducción mínima del 10%, así como también nuestros costos de producción, para ser más competitivos y adaptarnos a la realidad del mercado actual. Con estas medidas, volveremos al nivel mínimo de un Mkt Share del 15%


🛠️Herramientas utilizadas: entorno Google Colab, Python, pandas, matplotlib, plotly, Power BI

Autor: Pablo Delucchi
