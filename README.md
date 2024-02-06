**CodeCademy Portfolio project**

# **Biodiversity-in-National-Parks**

## **Introducción**

Este proyecto pertenece al módulo de _Data Science Foundations II_ de CodeCademy. Se realiza como cierre del módulo, por tanto abarca los siguientes bloques:

- Python Pandas for Data Science
- Exploratory Data Analysis in Python
- Statistics Fundamentals for Data Science
- Data Visualization Fundamentals with Python
- Data Wrangling, Cleaning, and Tidying
- Communicating Data Science Findings

## **Datasets**

Se adjuntan dos archivos `.csv` como datasets del proyecto:

- `observations.csv`
- `species_info.csv`

Es importante comenzar estudiando las variables y tipos de datos que contiene cada archivo para analizar como podemos combinar toda la información en un único DataFrame.

Las columnas observadas en el archivo `observations.csv` son:

- `scientific_name`: nombre científico del animal.
- `park name`: nombre del National Park donde trabaja.
- `observations`: número total de veces que se ha visto a la especie en el parque.

Por su parte, las columnas del archivo `species_info.csv` son:

- `category`: categoría animal.
- `scientific_name`: nombre científico del animal.
- `common_names`: lista de los diferentes nombres comunes del animal.
- `observation_status`: distintos grados de peligro de extinción de la especie.

### **Características**

Realizamos dos análisis sobre los datos. En primer lugar, buscamos conocer el tamaño de la muestra en cada uno de ellos mediante el `.shape` y en segundo lugar conocer cuantas especies animales distintas se han observado.

Estos datos aportan información sobre futuras comprobaciones en el manejo de los datos, como por ejemplo comprobar si hay duplicados en el dataset `species` o bien son especies animales vistas en distintos parques nacionales.

## **Data Wrangling, Cleaning and Tidying**
