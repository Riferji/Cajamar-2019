# Introducción

Este proyecto es el resumen de la participación en el concurso universityhack anual que presenta cajamar (*https://www.cajamardatalab.com/datathon-cajamar-universityhack-2019/*).

En este concurso exitían dos variantes en las que poder participar: la de visualizacion y la de predicción. Y dado que no se podía participar en ambas, este proyecto expone los resultados y modelado de la parte de predicción.


El objetivo del proyecto de predicción es estimar el tiempo medio que un usuario permanecerá en una determinada página de un inmueble anunciado por *https://www.idealista.com/*

## Conjunto de datos

Los datos disponibles para el modelado están formados por variables propias de la página web como comentarios, imágenes, precio de venta o alquiler, etc. Otras variables pertenecientes a la zona del inmueble, como antigüedad, porcentaje de edifificios pertenecientes a industria, educación, etc. dentro de la zona del inmueble.


## Librerías empleadas
  
+ pandas  
+ numpy  
+ matplotlib  
+ sklearn  
+ xgboost  


# Notebooks
  
+ EDA_HY, EDA_IDEA $\longrightarrow$ Son los notebooks en los que se ha realizado la exploración de las variables.  
+ ImputacionNans $\longrightarrow$ Notebook donde se imputan los Nans de las variables IDEA.  
+ PreprocesadoTrainRaw $\longrightarrow$ Notebook donde se realiza un primer preprocesamiento del conjunto Train para un primer entrenamiento.  
+ Modelos2_TestingsModelos $\longrightarrow$ Notebook donde se definen los primeros modelos.  
+ Modelos3_featureSelection $\longrightarrow$ Notebook donde se realiza una feature selection y se definen varias transformaciones PCA.  
+ Modelos4_ForwardAndEnsemble $\longrightarrow$ Notebook donde se inicia la optimización de los parámetros de los modelos, se presentan varios ensemble y donde se define un método forward para la selección de variables (Llegando a combinar ensemble y forward).  
+ NotebookFinalTrainTest $\longrightarrow$ Notebook donde se encuentra **todo** el procesado de train y test, así como la elección del mejor modelo (Con un error estimado de 17.37 evaluado en (Median Absolute Error)) y la predicción en test.  



