# Proyecto de Análisis de Siniestros Viales en la Ciudad de Buenos Aires: Análisis de datos para la reducción de víctimas fatales


## Contexto del problema
La ciudad de buenos aires,Argentina es una ciudad con una densidad poblacional muy alta y con un alto volumen de tráfico. Los siniestros viales son un tema a tratar con suma seriedad y compromiso de disminuirlos, ya que, estos afectan a la seguridad de la población y la infrestructura vial.

# Misión a cumplir ( detalles y datos)
Este proyecto tiene la finalidad de analizar datos, sobre los siniestros viales ocurridos en la ciudad de Buenos Aires en el periodo de los años 2016 - 2021. El analisis busca encontrar valores nuevos, información relevante, que permita a las autoridades correspondientes tomar decisiones y acciones que permitan la reducción de los siniestros viales. 
Para lograr este objetivo se nos otorgo 1 archivo xlsx, que consta de 2 hojas, HECHOS Y VICTIMAS. A su vez tambien se nos otorgo otro archivo xlsx con un diccionario de la terminologia que se ocupa y su significado para una mejor comprensión de estos archivos.

# Pasos que se utilizaron 
# ETL (Extract, Transform, Load)
Para este primer paso se ocupo la libreria de pandas

Extracción: Los datos se obtuvieron a partir de dos datasets en formato excel (HECHOS Y VICTIMAS).

Transformación: Se realizaron operaciones de limpieza, filtrado y transformación para preparar los datos para el análisis posterior. Por ejemplo:

- Eliminación de datos nulos: Se eliminaron filas completamente nulas.
- Eliminación de datos duplicados.
- Manejo de valores faltantes.
- Conversión de tipos de datos
- Eliminación de columnas con datos vacios o no necesarias para el analisis
- Creación de nuevas variables y dataframes según sea necesario para el análisis.

Carga: Los datos limpiados se cargaron a power bi para su posterior analisis y la generacion de informes

# Analisis Exploratorios de Datos (EDA)
En un analsiis, el eda nunca puede faltar, ya que, esto se considera una base fundamental del analisis. Para esto se ocuparon librerias como: Pandas, Matplotlib, seaborn y warnings para el análisis.
- Se identificaron tendencias y valores claves relacionados con las victimas de los siniestros viales.

# Power Bi Dashboard
Se creo un dashboard interactivo ("Siniestros Viales CABA.pbix") con la información mas relevante encontrada en el analisis, asi como tambien se muestran Kpi´s y medidas relevantes. En este dashboard podemos visualizar:

- Vemos la distribución de los siniestros viales conforme el tiempo (AÑO,Mes,Dia,Hora).
- Vemos la distribución de las victimas segun distintas variables como: Sexo, Edad, Tipo de calle, tipo de usuario, Tipo de vehiculo o medio.
- Identificamos comportamientos y tendencias.
- Exploramos relaciones entre variables.
- Información concisa para la toma de decisiones

#Archivos del proyecto
Datasets/: Archivos en bruto
Datasets limpios/: Datos limpios
ETL-EDA/: Notebooks con procesos de ETL y EDA.
Siniestros viales.pbix/: Dashboard interactivo



# Bibliotecas Utilizadas
- Pandas
- Matplotlib
- Searbon
- Warnings

# Resultados esperados
El proyecto tiene como finalidad, que las autoridades locales tengan un claro entendimiento de la situación, a cerca de los siniestros viales, y asu vez, sean capaces de tomar decisiones con fundamentos, que permitan la reducción de siniestros viales en la Ciudad de Buenos Aires, otorgando a la población un entorno vial mas seguro. 










