# CIFAR-10

CIFAR 10 is a smaller version of CIFAR-100, an image dataset used for classification using various machine learning algorithms in the scientific community

Details of this implementation:

1. Data Source: https://www.cs.toronto.edu/~kriz/cifar.html - Original Source (also integrated in tensorflow.keras)

2. Platform used: Jupyter Notebooks

3. Neural Network used: Tensorflow's Sequential Hyperparameters: 1.Epochs- 50 2.Batch Size- 1000

Layers Used:

A) 2-D Convolution Layer_1 Hyperparameter:  Filters- 32 of Size- 3 X 3 with Activation function- Rectified Linear Unit(relu)
B) 2-D Convolution Layer_1 Hyperparameter:  Filters- 32 of Size- 3 X 3 with Activation function- Rectified Linear Unit(relu)

C) Dropout Hyperparameter: 25% - dropout rate

C) 2-D Convolution Layer_2 Hyperparameter:  Filters- 10 of Size- 5 X 5 with Activation function- Rectified Linear Unit(relu)

D) Flatten

E) Dense Hyperparameter: Units- 10 wiht Activation function - Softmax

Model Summary:

![image](https://user-images.githubusercontent.com/31684198/114515841-6c20a300-9c5a-11eb-86fd-0e57dbadfaa6.png)

Results:
Training Accuracy: 0.912
Testing Accuracy: 0.53
