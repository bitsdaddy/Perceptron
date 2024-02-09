# Perceptron

### Perceptron Model Implementation

The Perceptron is a fundamental building block of artificial neural networks and serves as a binary classifier, separating data points into two classes based on a linear decision boundary. Below is an overview of the implementation of the Perceptron model:

#### Overview:

1. **Perceptron Class**:
    - Defines a Perceptron class encapsulating the functionality for training and making predictions.

2. **Methods**:
    - `__init__`: Initializes the Perceptron with None weights and bias.
    - `sigmoid`: Defines the sigmoid activation function.
    - `initialize_weights`: Initializes weights and bias using small random values.
    - `linear_prediction`: Calculates the linear prediction based on input features.
    - `fit`: Trains the Perceptron using gradient descent to minimize the loss function.
    - `predict`: Predicts the class labels based on input features.
    - `accuracy`: Calculates the accuracy of predictions.
    - `loss`: Calculates the mean squared error loss.
    - `print_weights_and_bias`: Prints the weights and bias of the trained Perceptron.

#### Workflow:

1. **Initialization and Training**:
    - Create an instance of the Perceptron class.
    - Train the Perceptron model using the `fit` method with training data.

2. **Prediction**:
    - Make predictions on the test data using the `predict` method.

3. **Evaluation**:
    - Calculate the accuracy of the predictions using the `accuracy` method.
    - Compute the loss of the predictions using the `loss` method.

4. **Visualization**:
    - Visualize the confusion matrix to compare actual and predicted labels.

#### Conclusion:

The Perceptron model is a simple yet powerful algorithm for binary classification tasks. It learns a linear decision boundary separating the classes in the feature space. Although it has limitations, such as only being able to classify linearly separable data, it forms the basis for more complex neural network architectures and is still used in various applications. Understanding its implementation and workflow is essential for beginners in machine learning.
