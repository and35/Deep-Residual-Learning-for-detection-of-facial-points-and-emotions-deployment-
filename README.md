# Deep-Residual-Learning-for-detection-of-facial-points-and-emotions-deployment-
building 2  Deep Residual Nets from scratch for solving a problem of regression(detecting key facial points) and clustering(classify emotions), in image faces, at the end i join the two models and make the deployment  using tensorflow service for make predictions.


La inteligencia artificial emocional (o Emotion AI) es una rama de la IA que permite que los ordenadores entiendan el lenguaje no verbal humano como las posturas corporales o expresiones faciales. 
en este caso construiremos 2 modelos de DL, para que se convinen y nos digan la emocion de una imagen input:
CNN + resnet (bloques residuales): para predecir puntos claves de la cara. esto es puede ser aplicado a deteccion de vista en conductores. 
clusterizar caras en 6 gupos de expresiones. 
ambos modelos trabajaran en paralelo para llegar a un resultado
