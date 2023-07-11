# Assignment 3 - Part 1

This repository contains the revised code for Assignment 3 - Part 1. 
The main goal of the assignment is to extend the existing code to address two hidden layers instead of a single hidden layer.

## Code Revision
To view the revised code, please follow this link: [Code Repository](https://github.com/orisimh/Ass3_Part1)

## Revised Code Description
The revised code is an extension of the original code, incorporating two hidden layers in the neural network architecture. The code is implemented in Python and uses the MNIST dataset for classifying handwritten digits.

## MLP Two Hidden Layers
The  code for this task exists in independence tab "MLP Two Hidden Layers" in the notebook.
The Evalution code on macro auc metric exists in "Evalution - Macro AUC and Accuracy metric" tab under "MLP Two Hidden Layers" tab.

## fully connected ANN implemented in Keras/TensorFlow
The  code for this task exists in independence tab "fully connected ANN implemented with TensorFlow" in the notebook.
The Evalution code on macro auc metric exists in "Evalution - Macro AUC and Accuracy metric" tab under "MLP Two Hidden Layers" tab.

## One Hidden - AUC Macro
The  code for measure the AUC Macro value on the original single hidden layer model exists in "One Hidden - AUC Macro" tab under "Classifying handwritten digits"
 tab.
 
## Instructions
To run the revised code and evaluate its performance, follow these steps:

1. Clone the repository or download the code locally.
2. Create a local copy of the ch11.ipynb file.
3. Implement the necessary revisions in the code to incorporate two hidden layers.
4. Run the modified code to train and test the model using the MNIST dataset.
5. Evaluate the prediction performance using the macro AUC metric.
6. Compare the performance of the revised code with the original (single hidden layer) code and a fully connected ANN implemented in Keras/TensorFlow.

## Validation Procedure
To evaluate the prediction performance, a Train(70%)/Test(30%) validation procedure is used. The dataset is split into a 70% training set and a 30% test set. The model is trained on the training set and then evaluated on the test set to calculate the macro AUC metric.


# Assignment 3 - Part 2

This repository contains the code for Assignment 3 - Part 2. The goal of this task is to use at least two pretrained CNN models to identify the type of a flower appearing in an image. The chosen pretrained models for this task are YOLOv5 and VGG19.

## Code Repository
To access the code for this task, please follow this link: [Code Repository](https://github.com/orisimh/Ass3_Part2)

## Task Description
The task involves transfer learning using two pretrained CNN models to classify flower images into their corresponding categories. The objective is to identify the type of flower in an image, specifically focusing on the dandelions category in this example.

## Deep Learning Packages
The code is implemented using the Keras/TensorFlow deep-learning package. This package provides a high-level API for building and training neural networks.

## Pretrained Models
For this task, two pretrained models, YOLOv5 and VGG19, have been chosen. These models will be adapted and fine-tuned to the current flower classification task. Additionally, other pretrained models may be used to enhance the performance of the classification.

## Dataset
The image database used for training and testing is provided in the following link: [Flower Image Database](https://www.robots.ox.ac.uk/~vgg/data/flowers/102/). This database contains a collection of flower images categorized into 102 classes.

## Model Output and Probability
The trained models will classify the flower images into their respective categories. The models will provide a probabilistic output, indicating the probability of a flower belonging to each of the categories.

## Instructions
To run the code and perform the flower classification task, follow these steps:

1. Clone the repository or download the code locally.
2. Ensure that the necessary dependencies and libraries are installed (Keras, TensorFlow, etc.).
3. Prepare the flower image dataset by downloading it from the provided link.
4. Adapt and fine-tune the YOLOv5 and VGG19 models for the flower classification task.
5. Train the models on the flower dataset.
6. Test the models on a separate validation or test dataset to evaluate their performance.
7. Analyze the results and interpret the probabilities of flower categories predicted by the models.



