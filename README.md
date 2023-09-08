# TFMUnir
Trabajo de fin de master - Estudio comparativo de técnicas de machine learning para identificación de pagos fraudulentos en tarjetas de crédito.

En este repositorio se almacenan los documentos que contiene desarrollo de la comparativa y se encuentra estructurado de la siguiente manera:

- Procesamiento de los datos.
- Técnica de oversampling SMOTE para balancear fuentes de datos.
- Arquitectura de los modelos.
- Métricas de evaluación de los modelos entrenados.
- Interpretabilidad de los modelos.

El archivo desarrollado en python creditCardFraudTFM.ipynb tiene el código fuente.

Se han creado varias carpetas para separar ejemplos de instancias, métricas e información de los modelos entrenados.

/instances - Gráficos de ejemplo de instancias validadas con LIME aplicadas a los modelos Random Forest, Naive Bayes y Artificial Neural Network.  

/metrics - Archivos csv con la información de las métricas exactitud, precisión, AUC y MCC para los modelos Random Forest, Naive Bayes y Artificial Neural Network.  

/models - modelos entrenados.

El dataset Credit Card Fraud Detection se lo obtuvo de Kaggle y se lo puede encontrar en la siguiente dirección: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud
