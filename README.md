# IA-PracticaCalificada2
Inteligencia Artificial, César Lara, Práctica Calificada 2, 2021-I
Predicción de tarifas de taxis.

El objetivo de esta evaluación es construir un modelo de aprendizaje que sea capaz de
predecir la tarifa que cobra un taxi.

El conjunto de datos contiene alrededor de 55 millones de registros de viajes en taxi. 

Cada registro contiene la siguiente información:

1. ID: cadena que identifica de manera única a cada registro.

2. pickup_datetime: timestamp indicando cuando el viaje a empezado.

3. pickup_longitude: número real indicando la ubicación en longitud en donde el viaje empezó.

4. pickup_latitude: número real indicando la ubicación en latitud en donde el viaje empezó.

5. dropoff_longitude: número real indicando la ubicación en longitud en donde el viaje término.

6. dropoff_latitude: número real indicando la ubicación en latitud en donde el viaje término.

7. passenger_count: número entero indicando el número de pasajeros en el servicio de taxi.

8. fare_amount: número real indicando el costo del taxi. Esta es la variable a predecir.

El documento Presente Predicción de tarifas de taxi limpia el conjunto de datos eliminando duplicados y nulos,
asi mismo se creo nuevos atributos como : 

1. diferencia de longitud

2. diferencia de latitud.

3. dia de la semana

4. mes 

5. año 

Se visualizó la correlación entre estas nuevas variables y se visualizó el conjunto de datos.


En este repositorio utilizamos el 4% del conjunto total:
Entrenamos modelos de :

## 1. Random Forest Regressor

#### RMSE :

## 2. Gradient Boosting Tree Regressor
El modelo de gradient Boosting Tree regressor utilizo una muesta del 4% del conjunto de datos.
Separamos la data en 0.7 para entrenamiento y 0.3 para prueba. Definimos un modulo con 
maxima profundidad de 12, maxima iteraciones 10 y max Bins = 24 y un crossValidator de 3 Folds


#### RMSE: 4.3879360043846

## 3. AFTSurvivalRegressión

#### RMSE:

## 4. LinearRegressor


#### RMSE:

## Grupo 9 
### Integrantes:
+ Peralta Haro Katheryn Ximena
+ Quispe Amao Renzo Renato
+ Campó Beraún José Javier
+ Jara Ocas Franklin Hamer

