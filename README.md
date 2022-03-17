# Deep-Residual-Learning-for-detection-of-facial-points-and-emotions-deployment-

summary
building 2  Deep Residual Nets from scratch for solving a problem of regression(detecting key facial points) and clustering(classify emotions), in image faces, at the end i join the two models and make the deployment  using tensorflow service for make predictions.

La inteligencia artificial emocional (o Emotion AI) es una rama de la IA que permite que los ordenadores entiendan el lenguaje no verbal humano como las posturas corporales o expresiones faciales. 

En este caso práctico construiremos 2 modelos de DL, para que se combinen y nos digan la emoción de una imagen de entrada:
CNN + resnet (bloques residuales): para predecir puntos claves de la cara. Esto puede ser aplicado a detección de vista en conductores. 
Clusterizar caras en 6 grupos de expresiones {0:'Ira', 1:'Odio', 2:'Tristeza', 3:'Felicidad', 4: 'Sorpresa'}. 
ambos modelos trabajan en paralelo para llegar a un resultado 

- Las resnet son altamente utilizadas en el campo del DL. 
- utilizaremos el poder de GPUs y TPUs de google colab.
- usaremos un dataset real 
- haremos la técnica de aumentación de imágenes que nos ayudará aumentar la generalización 
- usaremos varios KPIs para evaluar que tan bien trabaja nuestro modelo. usaremos, accuracy, matrices de confusión, recall, f1. 
- diferencia entre funciones de activación sigmoide  y relu
- tensor flow y keras será el tronco 
- haremos un deploy del proyecto con tensor flow 2.0 serving 

sera un ejercicio practico descrito en español 

proyecto basado en los dataset de kaggle: 
https://www.kaggle.com/c/facial-keypoints-detection/data
https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data


