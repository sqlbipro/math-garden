# math-garden initially forked from theMuellenator in order to check local work/diffs

MathGarden is a simple game which requires the user to enter a number by drawing on a canvas.  The drawing is then processed by a trained TensorFlow model which returns the digit entered, or a message if the image painted on the canvas was not recognized.  The web application can be found here:  https://sqlbipro.github.io/math-garden/

An image of the TensorFlow graph with the first layer expanded, from TensorBoard.  The model is a straightforward Multi Layer Perceptron Neural Network using data from the famous MNIST image dataset (https://en.wikipedia.org/wiki/MNIST_database)

![image](https://github.com/user-attachments/assets/6ec1b00a-0bc8-490d-8571-c97c4e9f8f52)

