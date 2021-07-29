# CNN-model-for-MNIST-Fashion

I built a multi-class classification model using a convolutional neural network with at least 90% validation accuracy for Fashion-MNIST dataset. Fashion-MNIST is a dataset of Zalando's article images— consisting of a training set of 60,000 examples and a test set of 10,000 examples. 

Each example is a 28x28 grayscale image, associated with a label from 10.

The Fashion-MNIST dataset can be obtained as follows.

fashion_mnist = tf.keras.datasets.fashion_mnist
(train_images, train_labels), (test_images, test_labels) = fashion_mnist.load_data()
