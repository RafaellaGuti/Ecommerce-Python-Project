# EN - Ecommerce Analysis
This Analysis is a Personal Exploratory Data Analytics Project that involves the data of the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail. The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers - B2B clients.

# Used tools and platforms
- Python
- Jupyter Notebooks
- Google Drive API

# Source of Data
www.Kaggle.com

# Other Visualization tools sources

# Data Preparation
- Cleanse and Manipulation:
  Utilizing python language - pandas and numpy libraries, Google Drive API (gspread):
  -Executed the connection with our data that was placed in Google Drive with gspread by the following guide https://docs.gspread.org/en/latest/oauth2.html
  -Created dataframe with all the records in the Dataset.
  -Selected the Columns needed from the dataset (Stock_code, Description, Invoice_date, Unit_price)  and added 4 more (Category, Total_profit, Unit_cost, Total_invoice) that will help us provide pertinent and coherent information for our dashboard.
  -For the 'Category' column, a number or keywords were selected to locate every product in the Description column in the following categories: Home Decor, Kitchen, Stationery, Accessories, Toys and Games, and Others.

# Data Analysis, Interpretation and Visualization (The visualization Dashboard is presented in english)
The Python based Interactive Dashboard includes 5 elements:
1. Interactive Filter panel called Category.
2. Interactive row of panels indicating: Total Income in the latest month, Total profit in the latest month, Total units sold in the latest month. Objetive: providing insights of the performance of sales in the last month in every category.
3. Interactive chart indicating the Total profits in USD made in every month by category. Objetive: Determine high-selling periods for strategy planification.
4. Chart indicating the performance of every category in the last year. Objetive: Fast insight of a rank from the biggest selling category to the least selling category during the year.
5. Interactive Summary table that indicates the date, product, quantity, units sold and profits. Objetive: Determine which products provided the most profit in each category, and the amount of units ordered.


# Findings

Category with the highest profit in the latest month (December 2011)
Home Decor $77.176

Category with the lowest profit in the latest month (December 2011)
Toys and Games $30.797


3 highest-selling categories: 

1. Kitchen
2. Home Decor
3. Stationery

Months with higher sales:

a. Kitchen
   1. December
   2. November
   3. September

b. Home Decor
   1. November
   2. December
   3. October

c. Stationery
   1. November
   2. December
   3. October


# Conclusions:


  
# ES - Análisis de Ecommerce
Este análisis es un Proyecto Personal de Análisis de Datos Exploratorio que involucra los datos de las transacciones ocurridas entre el 01/12/2010 y el 09/12/2011 para una tienda minorista en línea no física registrada en el Reino Unido. La empresa principalmente vende regalos únicos para todas las ocasiones. Muchos clientes de la empresa son mayoristas: clientes B2B.

# Herramientas y Plataformas Utilizadas
- Lenguaje Python
- Jupyter Notebooks
- Google Drive API

# Fuente de Datos
www.Kaggle.com

# Otras Fuentes de Herramientas de Visualización

# Preparación de Datos
Limpieza y Manipulación:
Utilizando el lenguaje Python - bibliotecas pandas y numpy, Google Drive API (gspread):
-Se realizó la conexión con nuestros datos que se encontraban en Google Drive con gspread siguiendo la guía https://docs.gspread.org/en/latest/oauth2.html
-Se creó un dataframe con todos los registros en el conjunto de datos.
-Se seleccionaron las columnas necesarias del conjunto de datos (Stock_code, Description, Invoice_date, Unit_price) y se agregaron 4 más (Category, Total_profit, Unit_cost, Total_invoice) que nos ayudarán a proporcionar información pertinente y coherente para nuestro panel de control.
-Para la columna 'Category', se seleccionó un número o palabras clave para ubicar cada producto en la columna Descripción en las siguientes categorías: Home Deco, Kitchen, Stationey, Accessories, Toys and Games, y Otros.
  
# Análisis de Datos, Interpretación y Visualización (El tablero de visualización se presenta en inglés)
El Panel de Control Interactivo basado en Python incluye 5 elementos:

1. Panel de Filtro Interactivo llamado Categoría.
2. Fila interactiva de paneles que indican: Ingresos Totales en el último mes, Beneficio Total en el último mes, Unidades Totales vendidas en el último mes.
3. Gráfico interactivo que indica los Beneficios Totales en USD realizados en cada mes por categoría.
4. Gráfico que indica el rendimiento de cada categoría en el último año.
5. Tabla Resumen Interactiva que indica la fecha, producto, cantidad, unidades vendidas y beneficios.

# Descubrimientos

Categoria con mayores ganancias en el ultimo mes  (December 2011)
Home Decor $77.176

Categoria con menores ganancias en el ultimo mes (December 2011)
Toys and Games $30.797

3 categorias con mas ventas reportadas: 
1. Kitchen
2. Home Decor
3. Stationery

Meses de mayor volumen de ventas en las principales categorias:

a. Kitchen
   1. Diciembre
   2. Noviembre
   3. Septiembre

b. Home Decor
   1. Noviembre
   2. Diciembre
   3. Octubre

c. Stationery
   1. Noviembre
   2. Diciembre
   3. Octubre


# Conclusiones
