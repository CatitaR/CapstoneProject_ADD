# CapstoneProject_ADD

## Integrantes
- Patricio Céspedes
- Claudia Fernandino
- Catalina Quijada

## Estructura de archivos y carpetas
1. **data**: en esta carpeta se encuentran las bases de datos utilizadas en el proyecto

    1.1. **raw**: esta carpeta contiene las bases de datos sin procesar, tal como fueron descargados
  
    1.2. **processed**: esta carpeta contiene las bases de datos procesadas, previo al análisis
  
2. **notebooks**: esta carpeta contiene los notebooks utilizados para el procesamiento de las bases de datos y el análisis

    2.1 **1_limpieza.ipynb**: este archivo contiene el procedimiento para la limpieza de los datos, previo al análisis
  
    2.2. **2_analisis.ipynb**: este notebook contiene los distintos análisis realizados con los datos ya limpios.
  
    2.3. **3_reporte.ipynb**: este notebook corresponde al informe final. Describe el contexto general de los datos, el proceso de limpieza, los modelos probados y el modelo escogido, el chequeo de supuestos y la interpretación del modelo. Por último, se presentan las conclusiones y limitaciones finales.

## Descripción del proyecto
El estudio busca responder a la pregunta ¿existe asociación entre el nivel socioeconómico y la tasa de mortalidad por traumatismos, en las comunas de la Región Metropolitana y el resto de las regiones de Chile? Para esto, se realizan análisis de regresión lineal simple y múltiple, cuya variable a explicar es la tasa de mortalidad por traumatismos y las explicativas son el promedio de ingresos por hogar, proporción de población rural, proporción de personas que se identifica con un pueblo originario y tasa de denuncia de delitos de mayor connotación social. El análisis se realiza a nivel nacional, y luego de forma separada para las comunas de la Región Metropolitana y el resto de las comunas, con la finalidad de explorar si la asociación entre las variables analizadas es diferente en ambos grupos de comunas.

## Instrucciones
Todas las bases de datos utilizadas están disponibles en este repositorio. Para replicar los resultados, se deben ejecutar los notebook en el siguiente orden: 1_limpieza.ipynb, 2_analisis.ipynb y 3_reporte.ipynb.

Las siguientes librerías son necesarias para ejecutar los notebook: 
- pandas
- numpy
- os
- statsmodels
- matplotlib
- seaborn
- typing
- zipfile
- wget
- requests
- io
- regex

Por lo tanto, es importante asegurarse de haberlas instalado antes de replicar los notebook.
