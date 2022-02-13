# MWC-2022-data
Data science challenge for mwc 2022

For this notebook we will use the next libraries:

 - Sklearn
 - Pandas 
 - matplotlib
 - seaborn

## **mwc22-client_table.csv**                                                                                        
| Variables                |  Descripción                                                                          |
|:-----                    |:-------------------------------------------------------------------------------------:|
| CLIENT ID                | Identificador único del cliente                                                       | 
| CLIENT_SEGMENT           |  Segmento de clientes                                                                 | 
| AVG CONSO                | Consumo medio mensual del cliente calculado a finales de 2020 (en piezas de fruta)    |
| AVG BASKET SIZE          | Tamaño medio de la cesta del cliente calculado a finales de 2020 (en piezas de fruta) |
| RECEIVED_COMMUNICATION   | 1 = Recibió promoción de sus productos / 0 = no la recibió                            |

## **mwc22-orders_table.csv**:

| Variables                |  Descripción                                                                          |
|:-----                    |:-------------------------------------------------------------------------------------:|
| CLIENT ID                | Identificador único del cliente                                                       | 
| NB PRODS                 | Número de 'prods' de la variedad de fruta en el pedido (1 prod = 10 piezas de fruta)  | 
| ORDER ID                 | Identificador único del pedido                                                        |
| FRUIT_PRODUCT            | Variedad de fruta                                                                     |

## Loading data

The file of the clients and orders data should be in the same folder that contains the notebook. The files names should be:
- mwc22-client_table.csv
- mwc22-orders_table.csv

## Understanding data

In this section of the notebook we see how are the data distributed, the data that are we working with, the correlation...

![download](https://user-images.githubusercontent.com/55766197/153775425-dd504a01-1ab0-4354-83f8-d1e69b085b6b.png)

![download](https://user-images.githubusercontent.com/55766197/153775442-8a064019-0fdd-40a4-b90d-9c21a5e3f17f.png)


## EDA

In this section we explore how the promotion affected the consumption, and also the activites of the clients grouped by their segments.

![download](https://user-images.githubusercontent.com/55766197/153762492-53b3d4c0-701c-4dac-8b76-9e21fc9f4031.png)


![download](https://user-images.githubusercontent.com/55766197/153762504-a6b35ffe-d2eb-4075-bf8a-9d9e157c4751.png)


![download](https://user-images.githubusercontent.com/55766197/153762521-884d7f69-bd1a-4218-acd7-089f0c729254.png)

## Models:

Along the notebook we use different types of models, the models used are:
- LogicalRegression
- RandomForest
- Knn
- DecisionTree
- SGD
- SVC
- Naive Bayes

Ensmable methos are also used:
- Gradient Boosting
- Adaboost
- Voting Classifier

## Output
The output is generated in the same folder as the notebook as results.csv.

