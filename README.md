# Clasificación
En este proyecto, se busca desarrollar un modelo de clasificación para predecir qué pasajeros fueron transportados a una dimensión alterna durante la colisión del Spaceship Titanic con una anomalía espaciotemporal. Los datos utilizados provienen de la competencia Spaceship Titanic de Kaggle, y el objetivo es predecir si un pasajero fue transportado, basado en varias características del pasajero y el viaje.

Los datos fueron proporcionados por Kaggle como parte del desafío. Los detalles y los datos de la competencia se pueden encontrar en la página oficial de Kaggle: [Spaceship Titanic](https://www.kaggle.com/competitions/spaceship-titanic/overview)

La base de datos cuenta con la siguiente información:
train.csv - Personal records for about two-thirds (~8700) of the passengers, to be used as training data.
* PassengerId - A unique Id for each passenger. Each Id takes the form gggg_pp where gggg indicates a group the passenger is travelling with and pp is their number within the group. People in a group are often family members, but not always.
* HomePlanet - The planet the passenger departed from, typically their planet of permanent residence.
* CryoSleep - Indicates whether the passenger elected to be put into suspended animation for the duration of the voyage. Passengers in cryosleep are confined to their cabins.
* Cabin - The cabin number where the passenger is staying. Takes the form deck/num/side, where side can be either P for Port or S for Starboard.
* Destination - The planet the passenger will be debarking to.
* Age - The age of the passenger.
* VIP - Whether the passenger has paid for special VIP service during the voyage.
* RoomService, FoodCourt, ShoppingMall, Spa, VRDeck - Amount the passenger has billed at each of the Spaceship Titanic's many luxury amenities.
* Name - The first and last names of the passenger.
* Transported - Whether the passenger was transported to another dimension. This is the target, the column you are trying to predict.
  
test.csv - Personal records for the remaining one-third (~4300) of the passengers, to be used as test data. Your task is to predict the value of Transported for the passengers in this set.

Este proyecto incluye los siguientes documentos:
- [Reporte en formato ipynb](./PP2.ipynb)
- [Reporte en formato html](./PP2.html)
- [Base de datos train](./train.csv)
- [Base de datos test](./test.csv)
