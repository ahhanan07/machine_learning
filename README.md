# Machine Learning

In this repository we find different Machine learning activities performed in sintetic datasets. They were developed on the unit Machine Learning on the Master of Data Science from Monash University. Some of the topics covered were the following:

### Model Complexity and Model Selection

- `Model Complexity and Model Selection.ipynb:` Develop a KNN regression algorithm and a cross-validation technique used to select the models with the most effective complexity.
- `Leave-One-Out Cross Validation.ipynb:`  We run Leave-One-Out CV changing the of K=1,..,15 in the KNN regressor, and for each K compute the average of error values got for folds. 

### Prediction Uncertainty with Bootstrapping

- `Prediction Uncertainty with Bootstrapping.ipynb:` We use bootstrapping to quantify the uncertainty of predictions for the KNN regressor implemented in Section A. 

### Ridge Regression

- `Ridge Regression.ipynb:` Developed a Ridge Regression by adding the L2 norm regularization a linear regression and studied the effect of the L2 norm regularization on the training and testing errors.

### Multiclass Perceptron

- `Multiclass Perceptron.ipynb:`Develop from scratch a Multiclass Perceptron which is the simplest form of a Neural Network. Made a study on the effect of the learning rate on the error rate.

### Logistic Regression vs. Bayesian Classifier

- `Discriminative vs Generative Models.ipynb:` Using the first 5 data points from the training set, we train a BC and a LR model, and compute their training and testing errors. In a “for loop”, increase the size of training set (5 data points at a time), retrain the models and calculate their training and testing errors until all training data points are used. 

### Expectation Maximization - Document Clustering

- `Expectation_Maximization.ipynb:` Implement the hard-EM and soft-EM for document clustering. Perform a PCA on the clusterings that you get based on the hard-EM and soft-EM and visualize the obtained clusters with different colors where x and y axes are the first two principal components.

### Neural Network

- `Neural Network_ Perceptron.ipynb:` We develop a Neural Network from scratch to make classifications on a Radial dataset. We compare the results with a perceptron (linear classification).  

### Autoencoder - Self-taught Learning

- `Self-Taught Learning_Autoencoder.ipynb:` We use H2O to create autoencoders. The goal is to help in the classification process of a Neural Network extracting information from the part of the dataset that has unlabeled data. 

## Interesting Visualisations

![Imgur](https://i.imgur.com/XfCBh6N.png)
