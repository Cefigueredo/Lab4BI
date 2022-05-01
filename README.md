# Laboratorio 4 - Inteligencia de Negocios

## Miembros

Carlos Figueredo - 201813445
Carlos Ballén -
Simón Guzmán - 

Este laboratorio tiene como objetivo profundizar en la construcción de pipelines con el fin de llevar modelos de machine learning a producción. Además, se busca construir un API para montar el modelo y realizar predicciones mediante peticiones HTTP.

## Instalar dependencias

Para empezar, se necesita instalar las dependencias que se utilizan en el proyecto, para esto se usa:

`pip install -r requirements.txt`

## Despliegue

El API se ejecuta con el comando:

`uvicorn main:app --reload`

## Funcionamiento API

Para el funcionamiento del API haremos uso de dos endpoints:

- localhost:8000/predict  -   Este realiza la predicción para un solo caso.

- localhost:8000/predictMany  -   Realiza la predicción R^2 del modelo.
