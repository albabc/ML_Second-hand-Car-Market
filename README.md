# ML_Second-hand-Car-Market

CASTELLANO

Proyecto ML
Este repositorio contiene un modelo de machine learning desarrollado para predecir los precios de coches de segunda mano en base a diversas características.

Descripción del Problema
El precio de los coches de segunda mano puede variar ampliamente debido a una variedad de factores, como la marca, el modelo, el año de fabricación, el kilometraje, el tipo de combustible, entre otros. Predecir con precisión el precio de un coche de segunda mano es el objetivo de este proyecto.

Datos
Los datos utilizados para entrenar y evaluar el modelo se encuentran en el archivo público coches-de-segunda-mano-sample.csv. Este archivo contiene las siguientes columnas:
* url: link al portal
* company: link al anuncio
* make: marca
* model
* version
* price
* price_financed
* fuel
* year: year of production
* kms
* power
* doors: number of doors
* shift
* color
* photos: 
* is_professional: indica si el vendedor es profesional o un particular
* dealer: identificación del vendedor
* province
* country
* publish_date: fecha de publicación
* insert_date: fecha de extracción de datos

Uso del Modelo
Para utilizar el modelo entrenado, sigue estos pasos:
Abre el archivo ML_UsedCars_Final.ipynb en Jupyter Notebook.
Carga tus datos de entrada y utiliza el modelo para predecir los precios de coches de segunda mano.
Sigue las instrucciones detalladas en el Notebook para cargar y limpiar los datos, entrenar los modelos, evaluar rendimientos y seleccionar el más eficiente.

Resultados
El modelo ha sido evaluado utilizando métricas como el Mean Absolute Error (MAE), Mean Squared Error (MSE), y Root Mean Squared Error (RMSE). 

******

ENGLISH

ML Project
This repository contains a machine learning model developed to predict the prices of second-hand cars based on various features.

Problem Description
The price of second-hand cars can vary widely due to a variety of factors such as brand, model, year of manufacture, mileage, fuel type, among others. The goal of this project is to accurately predict the price of a second-hand car.

Data
The data used to train and evaluate the model is found in the public file "used-cars-sample.csv". This file contains the following columns:

url: link to the online portal
company: link to the advertisement
make: brand
model
version
price
price_financed
fuel
year: year of production
kms: kilometers driven
power
doors: number of doors
shift: type of transmission
color
photos: number of photos
is_professional: indicates if the seller is a professional or private individual
dealer: seller's identification
province
country
publish_date: publication date
insert_date: data extraction date
Model Usage
To use the trained model, follow these steps:

Open the file "ML_UsedCars_Final.ipynb" in Jupyter Notebook.
Load your input data and use the model to predict the prices of second-hand cars.
Follow the detailed instructions in the Notebook to load and clean the data, train the models, evaluate performances, and select the most efficient one.

Results
The model has been evaluated using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE).
