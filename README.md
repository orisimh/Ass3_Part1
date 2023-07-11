# Assignment 3 - Part 1

This repository contains the revised code for Assignment 3 - Part 1. 
The main goal of the assignment is to extend the existing code to address two hidden layers instead of a single hidden layer.

## Code Revision
To view the revised code, please follow this link: [Code Revision](https://github.com/orisimh/Ass3_Part1)

## Revised Code Description
The revised code is an extension of the original code, incorporating two hidden layers in the neural network architecture. The code is implemented in Python and uses the MNIST dataset for classifying handwritten digits.

## MLP Two Hidden Layers
The  code for this task exists in independence tab "MLP Two Hidden Layers" in the notebook.
The Evalution code on macro auc metric exists in "Evalution - Macro AUC and Accuracy metric" tab under "MLP Two Hidden Layers" tab.

## fully connected ANN implemented in Keras/TensorFlow
The  code for this task exists in independence tab "fully connected ANN implemented with TensorFlow" in the notebook.
The Evalution code on macro auc metric exists in "Evalution - Macro AUC and Accuracy metric" tab under "MLP Two Hidden Layers" tab.


## Instructions
To run the revised code and evaluate its performance, follow these steps:

1. Clone the repository or download the code locally.
2. Create a local copy of the ch11.ipynb file.
3. Implement the necessary revisions in the code to incorporate two hidden layers.
4. Run the modified code to train and test the model using the MNIST dataset.
5. Evaluate the prediction performance using the macro AUC metric.
6. Compare the performance of the revised code with the original (single hidden layer) code and a fully connected ANN implemented in Keras/TensorFlow/PyTorch.

## Validation Procedure
To evaluate the prediction performance, a Train(70%)/Test(30%) validation procedure is used. The dataset is split into a 70% training set and a 30% test set. The model is trained on the training set and then evaluated on the test set to calculate the macro AUC metric.

## Comparison
Compare the 
The predictive performance of the revised code with the original (single hidden layer) code exists in One Hidden - AUC Macro title in and with a fully connected ANN implemented in Keras/TensorFlow/PyTorch. Assess the performance based on the macro AUC metric.

## License
This project is licensed under the [MIT License](LICENSE).
