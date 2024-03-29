# Regresion Lineal: Prediccion nivel de glucosa

El Instituto Nacional de la Diabetes y las Enfermedades Digestivas y Renales (EE.UU.) realizó un 
estudio sobre 768 mujeres indias Pima adultas que vivían cerca de Phoenix. Se registraron las 
siguientes variables: 

• número de embarazos

• concentración de glucosa en plasma a las 2 horas en una prueba de tolerancia a la glucosa 
oral

• presión arterial diastólica (mm Hg)

• grosor del pliegue cutáneo del tríceps (mm)

• insulina sérica a las 2 horas (mu U/ml)

• índice de masa corporal (peso en kg/(altura en m2))

• función de pedigrí de la diabetes

• edad (años) 

• una prueba de si la paciente muestra signos de diabetes (codificada como 0 si es negativa, 
1 si es positiva). 

Los datos pueden obtenerse en el repositorio de bases de datos de aprendizaje automático de 
la UCI en http://www.ics.uci.edu/˜mlearn/MLRepository.html. El correspondiente dataset está 
disponible en el conjunto de datos pima del paquete faraway.
Se solicita utilizar la información anterior para construir un modelo de regresión lineal que 
permita predecir la concentración de glucosa en plasma a las 2 horas en una prueba de 
tolerancia a la glucosa oral. En concreto, se solicita:

a) Importar y preparar las variables (variables categóricas como factors y poner etiquetas para 
los posibles valores de las variables categóricas).

b) Hacer un estudio de estadística descriptiva sobre las variables disponibles, incluyendo el 
análisis de valores ausentes y atípicos.

c) Analizar en primer lugar un modelo de regresión que incluya todas las variables disponibles
(describir el modelo ajustado y sus residuos, contrastar la significatividad individual de los 
parámetros y la calidad del modelo, verificar las hipótesis del modelo, análisis de datos 
influyentes y atípicos).

d) Identificar el mejor modelo de regresión lineal y analizarlo.

e) Analizar el modelo de regresión lineal tras la eliminación de valores influentes y atípicos.


# Aplicar ACP

Aplicar la técnica de análisis componentes principales al conjunto de variables anterior y 
volver a construir un modelo de regresión sobre las componentes principales, comparando su 
calidad con el obtenido en el ejercicio 1.

# PREDICCION RECAUDACION IMPUESTOS MEDIANTE ARIMA 

En el fichero IVA.xlsx hay disponible una serie temporal con datos mensuales de los impuestos 
recaudados por el Estado en concepto de IVA desde enero de 1988 hasta noviembre de 2010. 
Se solicita:

a) Analizar la estacionariedad de la serie y transformarla en caso de fuese necesario para 
alcanzar la estacionariedad y tratar la estacionalidad.

b) Analizar a partir del PCF y PACF los modelos ARIMA generalizados que mejor se ajustan y 
analizar sus residuos.

c) Identificar el modelo matemático que mejor se ajusta a la serie, mostrar gráficamente el 
ajuste del modelo con los datos y analizar sus residuos.

d) Predecir la recaudación para los próximos 5 meses
