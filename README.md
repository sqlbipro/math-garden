# Math Garden Overview

MathGarden is a simple game which requires the user to enter a number by drawing on a canvas.  The drawing is then processed by a trained TensorFlow model which returns the digit entered, or a message if the image painted on the canvas was not recognized or was incorrect.  The web application can be found here:  https://sqlbipro.github.io/math-garden/

An image of the TensorFlow graph with the first layer expanded, as well as some performance statistics for the model, from TensorBoard, follows.  The model is a straightforward Multi Layer Perceptron Neural Network using data from the famous MNIST image dataset (https://en.wikipedia.org/wiki/MNIST_database)

![image](https://github.com/user-attachments/assets/6ec1b00a-0bc8-490d-8571-c97c4e9f8f52)

![image](https://github.com/user-attachments/assets/f516a355-30ff-4011-b431-18a0241d477c)

As you can see the model performance is quite good at over 99% accuracy with a smooth reduction in the loss function, indicating that overfitting is not a problem for this model.

This repo was initially forked from theMuellenator in order to check local work/diffs.


