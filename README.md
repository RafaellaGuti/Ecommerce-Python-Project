## Ecommerce Sales Analysis

![Python Dashboard Ecommerce Project](https://github.com/RafaellaGuti/Ecommerce-Python-Project/assets/138822208/9e2fee37-81c7-4fea-9793-948ab551a780)


### Table of content
### EN
- [About the project](#About-the-project)
- [Used tools, softwares and platforms](#Used-tools-softwares-and-platforms)
- [Source of Data](#Source-of-Data)
- [Data Preparation](#Data-Preparation)
- [Findings](#Findings)
- [Conclusions, Limitations and Recommendations](#Conclusions-Limitations-and-Recommendations)

### ES
- [Sobre el proyecto](#Sobre-el-proyecto)
- [Objetivos](#Objetivos)
- [Alcance](#Alcance)
- [Pasos del Proyecto](#Pasos-del-Proyecto)
- [Fuente de Datos](#Fuente-de-Datos)
- [Herramientas, Softwares y Plataformas Utilizadas](#Herramientas-Softwares-y-Plataformas-Utilizadas)
- [Preparación de Datos](#Preparación-de-Datos)
- [Descubrimientos](#Descubrimientos)
- [Conclusiones, limitaciones y recomendaciones](#Conclusiones-limitaciones-y-recomendaciones)


### About the project
This Analysis is a Exploratory Data Analytics Project that involves the data of the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail. The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers - B2B clients.

### Used tools, softwares and platforms
- Python
- Jupyter Notebooks
- Google Drive API

### Source of Data
www.Kaggle.com

### Data Preparation
Cleanse and Manipulation:
  
- Utilizing python language - pandas, numpy, panel, hvplot, holoviews libraries, Google Drive API (gspread):
- Executed the connection with our data that was placed in Google Drive with gspread by the following guide https://docs.gspread.org/en/latest/oauth2.html
- Created dataframe with all the records in the Dataset.
- Selected the Columns needed from the dataset (Stock_code, Description, Invoice_date, Unit_price)  and added 4 more (Category, Total_profit, Unit_cost, Total_invoice) that will help us provide pertinent and coherent information for our dashboard.
- For the 'Category' column, a number or keywords were selected to locate every product in the Description column in the following categories: Home Decor, Kitchen, Stationery, Accessories, Toys and Games, and Others.

### Data Analysis, Interpretation and Visualization (The visualization Dashboard is presented in english)
The Python based Interactive Dashboard includes 5 elements:
1. Interactive Filter panel called Category.
2. Interactive row of panels indicating: Total Income in the latest month, Total profit in the latest month, Total units sold in the latest month. Objetive: providing insights of the performance of sales in the last month in every category.
3. Interactive chart indicating the Total profits in USD made in every month by category. Objetive: Determine high-selling periods for strategy planification.
4. Chart indicating the performance of every category in the last year. Objetive: Fast insight of a rank from the biggest selling category to the least selling category during the year.
5. Interactive Summary table that indicates the date, product, quantity, units sold and profits. Objetive: Determine which products provided the most profit in each category, and the amount of units ordered.


### Findings

- The dashboard facilitates dynamic filtering by product category, enabling users to focus on specific segments of interest.
- Monthly insights reveal variations in sales performance, with some categories showing significant fluctuations in income, profit, and units sold.
- Yearly performance analysis highlights trends in category performance over time, aiding in identifying growth opportunities and areas for improvement.
- Detailed summary tables offer granular insights into individual product performance, assisting in strategic decision-making and inventory management.

### Conclusions, Limitations and Recommendations

The data analysis project provides valuable insights into sales performance across different product categories.
The interactive dashboard offers a user-friendly interface for exploring and interpreting data, facilitating informed decision-making.
By leveraging Python libraries and Google Drive API, the project demonstrates effective utilization of technology for data management and analysis.
Recommendations for future enhancements may include incorporating predictive analytics models to forecast sales trends and integrating additional data sources for comprehensive analysis.

  
### Sobre el proyecto
Este análisis es un Proyecto de Análisis de Datos Exploratorio que involucra los datos de las transacciones ocurridas entre el 01/12/2010 y el 09/12/2011 para una tienda minorista en línea no física registrada en el Reino Unido. La empresa principalmente vende regalos únicos para todas las ocasiones. Muchos clientes de la empresa son mayoristas: clientes B2B. Contando con datos tanto numéricos como característicos, los registros complementarios que añadiremos en el paso 3 de este proyecto nos permitirán efectuar un análisis tanto cualitativo como cuantitativo, permitiéndonos expresar las conclusiones del estudio de una manera más completa.

### Objetivos
Este análisis permitirá determinar el desempeño general de los productos, agrupados por categorías, en términos de volumen de ventas, volumen de pedidos, margen de ganancia y picos de ventas, con el fin de identificar patrones e insights que permitan al analista ubicar áreas de mejora para un uso posterior por parte de la gerencia de la empresa.

### Alcance
Este proyecto busca proporcionar un proceso de ETL efectivo que construya tablas referentes a los movimientos de ventas de un Ecommerce en Reino Unido durante el periodo de un año para su posterior visualizacion y analisis. Las tablas permitiran al analista investigar y encontrar relaciones entre el columen de ventas, categorias, precios, cantidad por orden de compra y precios. Con el fin de identificar patrones, obtener informacion clara, actualizada y accesible para la posterior toma de decisiones.

### Pasos del Proyecto
1. Obtener fuente de datos de manera online, descargarla en maquina local y almacenarla en una carpeta de Google Drive
2. Conectar con Dataset en Google Drive utilizando Google API y seleccionar la hoja y registros a utilizar.
3. Realizar una primera limpieza general y preparar los datos para crear la tabla de la cual partira el analisis agregando columnas producto de los registros de otras columnas, agregando columna 'Category' a partir de una seleccion de keywords obtenidos de la descripcion del producto, redondeamos columnas 'Float'para obtener solo 2 decimales y asignamos tipo de datos como 'datetime', 'float' y 'str' a columnas correspondientes.
4. Analizar de forma descriptiva el contenido resultantes para determinar relaciones, patrones, tendencias, insights e informacion relevante que de pie a la toma de decisiones informadas con direccion a la mejora del desesmpeño del Ecommerce. En este paso tambien definimos los elementos que formaran parte del tablero interactivo.
5. Creacion de tablero para reportar de forma visual los hallazgos de una manera facil de interpretar para audiencias con experiencia tenica y no tecnica; accesible y que apoye a la comunicacion de conclusiones obtenidas a partir de los hallazgos

### Fuente de Datos
Fuente : https://www.kaggle.com/datasets/carrie1/ecommerce-data?resource=download
El dataset fue descargado en maquina local y posteriormente subido a Google Drive con el nombre de "data"
   
### Herramientas, Softwares y Plataformas Utilizadas
- Lenguaje Python
- Jupyter Notebooks
- Google Drive API

### Preparación de Datos
Limpieza y Manipulación:
- Utilizando el lenguaje Python - bibliotecas pandas, numpy, panel, hvplot, holoviews, Google Drive API (gspread):
- Se realizó la conexión con nuestros datos que se encontraban en Google Drive con gspread siguiendo la guía https://docs.gspread.org/en/latest/oauth2.html
- Se creó un dataframe con todos los registros en el conjunto de datos.
- Se seleccionaron las columnas necesarias del conjunto de datos (Stock_code, Description, Invoice_date, Unit_price) y se agregaron 4 más (Category, Total_profit, Unit_cost, Total_invoice) que nos ayudarán a proporcionar información pertinente y coherente para nuestro panel de control.
- Para la columna 'Category', se seleccionó un número o palabras clave para ubicar cada producto en la columna Descripción en las siguientes categorías: Home Deco, Kitchen, Stationey, Accessories, Toys and Games, y Otros.
  
### Análisis de Datos, Interpretación y Visualización (El tablero de visualización se presenta en inglés)
El Panel de Control Interactivo basado en Python incluye 5 elementos:

1. Panel de Filtro Interactivo llamado Categoría.
2. Fila interactiva de paneles que indican: Ingresos Totales en el último mes, Beneficio Total en el último mes, Unidades Totales vendidas en el último mes.
3. Gráfico interactivo que indica los Beneficios Totales en USD realizados en cada mes por categoría.
4. Gráfico que indica el rendimiento de cada categoría en el último año.
5. Tabla Resumen Interactiva que indica la fecha, producto, cantidad, unidades vendidas y beneficios.

### Descubrimientos

- El panel facilita el filtrado dinámico por categoría de producto, permitiendo a los usuarios centrarse en segmentos específicos de interés.
- Los insights mensuales revelan variaciones en el rendimiento de las ventas, con algunas categorías mostrando fluctuaciones significativas en ingresos, beneficios y unidades vendidas.
- El análisis de rendimiento anual destaca las tendencias en el rendimiento de la categoría con el tiempo, ayudando a identificar oportunidades de crecimiento y áreas de mejora.
- Las tablas de resumen detalladas ofrecen insights detallados sobre el rendimiento individual del producto, ayudando en la toma de decisiones estratégicas y la gestión de inventario.


### Conclusiones, limitaciones y recomendaciones

El proyecto de análisis de datos proporciona valiosos insights sobre el rendimiento de ventas en diferentes categorías de productos.
El panel interactivo ofrece una interfaz fácil de usar para explorar e interpretar datos, facilitando la toma de decisiones informadas.

Al aprovechar las bibliotecas de Python y la API de Google Drive, el proyecto demuestra la utilización efectiva de la tecnología para la gestión y análisis de datos.

Las recomendaciones para futuras mejoras pueden incluir la incorporación de modelos de análisis predictivo para pronosticar tendencias de ventas e integrar fuentes de datos adicionales para un análisis integral
