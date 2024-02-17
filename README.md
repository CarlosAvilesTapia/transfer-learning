# transfer-learning
Entrenamiento de un clasificador de imágenes usando aprendizaje por transferencia y ajuste fino.

El aprendizaje por transferencia (**Transfer Learning**) es un método de aprendizaje automático en el que un modelo desarrollado para una tarea se reutiliza como punto de partida para un modelo en una segunda tarea.

Es un enfoque popular en el aprendizaje profundo en el que los modelos previamente entrenados se utilizan como punto de partida para resolver problemas de visión computacional y tareas de procesamiento del lenguaje natural, dados los vastos recursos informáticos y de tiempo necesarios para desarrollar modelos de redes neuronales para estos problemas.

Este caso consiste en entrenar un modelo para clasificar imágenes de perros y gatos. Para ello se utilizó transfer learning y fine tuning (ajuste fino)para construir el clasificador. Para crear este modelo de deep learning, se seguieron los siguientes pasos:

1. **Selección del modelo de origen**. Modelo de origen entrenado previamente basdo en **inceptionv3**.

2. **Modelo de reutilización**. El modelo se utiliza como punto de partida para un modelo en la segunda tarea de interés, en este caso para construir el clasificador de perros y gatos.

3. **Sintonizar modelo**. El modelo se adapta en los datos del par de entrada-salida disponibles para la tarea de interés.


Una vez construido el clasificador, se entregan las métricas de performance. En este caso, matriz de confusión, accuracy, precisión y recall sobre el conjunto de prueba.
