# Week 02 - Deep Learning Lab

## Program 1: Batch Gradient Descent and Stochastic Gradient Descent

### Aim
To implement Batch Gradient Descent and Stochastic Gradient Descent for training a neural network and compare their accuracy.

### Dataset
The Make Moons dataset from sklearn.datasets was used.

- Number of samples: 400
- Noise: 0.20
- Random state: 1
- The input features were standardized before training.

### Model
The neural network used:

- Input layer: 2 neurons
- Hidden layer 1: 16 neurons with ReLU
- Hidden layer 2: 16 neurons with ReLU
- Output layer: 1 neuron with sigmoid
- Learning rate: 0.5
- Epochs: 200

### Result

Batch Gradient Descent accuracy: 0.965

SGD accuracy: 0.9775

So, for this run, SGD gave slightly higher accuracy than Batch Gradient Descent.


## Program 2: Neural Network using TensorFlow/Keras

### Aim
To train a neural network using TensorFlow/Keras and compare the training using different batch sizes.

### Dataset
The same Make Moons dataset was used.

- Number of samples: 400
- Noise: 0.20
- Random state: 1

### Model
The neural network used:

- Input layer: 2 features
- Hidden layer 1: 16 neurons with ReLU
- Hidden layer 2: 16 neurons with ReLU
- Output layer: 1 neuron with sigmoid
- Loss function: Binary Cross-Entropy
- Optimizer: SGD
- Learning rate: 0.5
- Epochs: 200

The model was trained first with the full dataset as the batch and then with a batch size of 16.

### Result

Loss: 0.081144779920578

Accuracy: 96.49999737739563%

The model achieved approximately 96.5% accuracy on the dataset.
