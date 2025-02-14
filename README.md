### Iris Flower Classification Using Artificial Neural Network (ANN)
#### Overview:
In this project, an Artificial Neural Network (ANN) was implemented to classify iris flowers into three species based on their features. The process involved loading the iris dataset, preprocessing the data through scaling and one-hot encoding, and training the ANN model. The model was then evaluated on a test set, achieving a perfect accuracy of 1.
#### Objectives:
a. To classify iris flowers into three species using an ANN.
b. To achieve high classification accuracy through effective data preprocessing and model training.
#### STEPS CARRIED OUT:
1. Dataset Loading:
The iris dataset, containing attributes like sepal length, sepal width, petal length, and petal width, was loaded for analysis and model training.

2. Data Preprocessing:
Feature Scaling: Standardization was applied to scale the features, ensuring the ANN model processed them efficiently.
One-Hot Encoding: The target variable (species) was converted into a binary matrix using one-hot encoding to make it compatible with the neural network.

3. Splitting Data:
The dataset was divided into training and testing sets, enabling the model to learn from one part of the data and be tested on the other.

4. Model Training:
A feedforward Artificial Neural Network (ANN) was constructed with input, hidden, and output layers. The network was trained on the training set using backpropagation to minimize prediction error.

5. Model Evaluation:
After training, the model was tested on unseen data, achieving perfect accuracy of 1, indicating flawless classification of iris flowers.
