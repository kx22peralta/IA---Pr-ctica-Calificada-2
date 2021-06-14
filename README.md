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


#### RMSE:
## 3. AFTSurvivalRegressión
Es un modelo de regresión por supervivencia con datos censurados,
es por ello que lleva una columna censor, 1 para no censurar,
0 para censurar, realiza una función  llamada de riesgo para 
agilizar la velocidad del aprendizaje, a diferencia de otros
modelos de riesgo el modelo AFT es más fácil de paralelizar 
porque cada instancia contribuye a la función objetivo de 
forma independiente.Generalmente se usa la distribución 
de Weibull con función logaritmica de verosimilitud, la rapidez
radica en que envés de poner en peligro al modelo pone como
supervivencia la vida util hallada con la función.

#### RMSE:

## 4. LinearRegressor


#### RMSE:

## Grupo 9 
### Integrantes:
+ Peralta Haro Katheryn Ximena
+ Quispe Amao Renzo Renato
+ Campó Beraún José Javier
+ Jara Ocas Franklin Hamer

