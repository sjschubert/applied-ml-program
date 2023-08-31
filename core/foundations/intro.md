# Intro to Machine Learning

This documents provides a broad introduction to learning tasks, models and or systems that are currently employed to solve the tasks.

## A. Supervised Learning

Supervised learning is a type of machine learning where the algorithm is trained using labeled data, meaning that the correct output is already known for a given input. The goal of supervised learning is to learn a mapping between inputs and outputs, so that the algorithm can make predictions on new, unseen data.

In supervised learning, the algorithm learns by minimizing the difference between its predicted output and the actual output for a given input. This difference is called the "loss function" or "error function." The algorithm adjusts its internal parameters to reduce the loss, which allows it to improve its predictions over time.

Supervised learning can be further divided into two main categories: classification and regression. Classification algorithms are used when the output is categorical or nominal. Regression algorithms are used when the output is continuous or numerical.

#### Regression

Regression is a statistical method used to establish a relationship between two or more variables, with the goal of predicting the value of one variable based on the values of the others.

- Linear Regression: A statistical method for modeling the relationship between a dependent variable and one or more independent variables. It assumes a linear relationship between the variables and tries to fit a straight line that minimizes the sum of squared errors.
- Polynomial Regression: A variation of linear regression where the relationship between the variables is modeled using a polynomial equation instead of a straight line.
- Ridge/Lasso Regression: A regularization technique used to prevent overfitting in linear regression. Ridge regression adds a penalty term to the cost function, while Lasso regression uses L1 regularization to eliminate insignificant coefficients.
- Support Vector Machines for Regression (SVR): A type of support vector machine designed specifically for regression problems. SVR uses a kernel function to map the input data into a higher-dimensional space, where it becomes linearly separable.


#### Classification

Classification in machine learning involves training a model to assign labels or categories to new, unseen data points based on their similarities to the training data. The goal is to learn a mapping between input data and corresponding output labels, so the model can make accurate predictions on new data.

The classification task can be further divided into two main categories: binary classification and multi-class classification. Binary classification involves training a model to distinguish between two classes or labels, while multi-class classification involves training a model to distinguish among three or more classes.

- Logistic Regression: A statistical method for modeling the probability of an event occurring based on one or more predictor variables. It uses a logistic function to convert the output into a probability score between 0 and 1.
- Decision Trees: A tree-based model that splits the data into subsets based on the values of the input features. Each leaf node represents a class label or a predicted outcome.
- Random Forests: An ensemble learning method that combines multiple decision trees to improve the accuracy and robustness of the predictions.
- Support Vector Machines for Classification (SVC): A type of support vector machine designed specifically for classification problems. SVC uses a kernel function to map the input data into a higher-dimensional space, where it becomes linearly separable.
- k-Nearest Neighbors (k-NN): A simple machine learning algorithm that classifies new instances by finding the k most similar neighbors in the training data and voting on their labels.

#### Neural Networks / Deep Learning
Neural networks are a type of machine learning algorithm inspired by the structure and function of the human brain. They consist of layers of interconnected nodes (neurons) that process and transmit information. Deep learning is a subfield of neural networks that focuses on training large, complex neural networks with multiple layers to solve challenging tasks.

- Convolutional Neural Networks (CNNs): A type of neural network designed specifically for image recognition tasks. CNNs use convolutional layers to extract features from images and pooling layers to reduce the spatial dimensions.
- Recurrent Neural Networks (RNNs):
RNNs are designed to handle sequential data, such as speech, text, or time series data. They have feedback connections that allow the data to flow in a loop, enabling the network to capture temporal dependencies.
- Transformers: A type of neural network designed specifically for natural language processing tasks, such as machine translation, question answering, and text summarization. Transformers use self-attention mechanisms to weigh the importance of different words or phrases in a sentence.

#### Time-Series Forecasting

Time-series forecasting is the process of using historical data to predict future values of a time-series dataset. This technique is commonly used in various fields such as
finance, economics, engineering, and environmental science, to name a few. The main objective of time-series forecasting is to accurately predict future values of a time-series dataset, allowing organizations to make informed decisions, optimize resources, and minimize risks.

- Autoregressive Integrated Moving Average (ARIMA): ARIMA models are used to forecast future values in a time-series dataset by analyzing past trends, seasonality, and residuals.
- Bayesian Methods: Bayesian methods, such as Bayesian Linear Regression and Bayesian Time-Series Models, are used to forecast future values by estimating the probability distribution of the time-series data.
- Long Short-Term Memory (LSTM) Networks.


## Unsupervised Learning Tasks

Unsupervised learning tasks are a type of machine learning where the algorithm tries to find patterns or structure in the data without the use of labeled examples. The goal is to identify interesting or meaningful features or clusters in the data, or to reduce the dimensionality of the data.

#### Dimensionality Reduction
Dimensionality reduction is a technique used in machine learning and data analysis to reduce the number of features or dimensions in a dataset while retaining as much relevant information as possible. The goal is to simplify the data while preserving the most important relationships and patterns.

- Principal Component Analysis (PCA): PCA is a dimension reduction technique that transforms a set of correlated variables into a set of linearly uncorrelated variables called principal components. The first principal component has the largest possible variance, explaining the most variation in the data, and each subsequent component explains a progressively smaller amount of variance, capturing subtler variations in the data.
- t-SNE: t-Distributed Stochastic Neighbor Embedding (t-SNE) is a dimension reduction technique that is similar to Principal Component Analysis (PCA) but is non-linear and tries to preserve local structure in the data. It is a popular method for visualizing high-dimensional data and for identifying clusters and patterns in the data.
The goal of t-SNE is to map the high-dimensional data to a lower-dimensional space (typically 2D or 3D) in a way that tries to preserve the local relationships between the data points.

#### Clustering

Clustering is a technique in machine learning and data mining that involves dividing a dataset into distinct groups or clusters, such that the data points in each cluster are as similar as possible to each other, and as dissimilar as possible to those in other clusters. The main objective of clustering is to identify patterns or structures in the data that are not obvious by looking at individual data points.

- K-means clustering: This is a widely used method for clustering data into a fixed number of clusters. The algorithm iteratively updates the centroids of the clusters and reassigns the data points to the nearest cluster.
- Hierarchical Clustering:  a type of clustering method that builds a hierarchy of clusters from a set of data. In contrast to k-means clustering, which divides the data into a fixed number of clusters, hierarchical clustering creates a nested series of clusters, where each cluster is a subset of the previous one. This allows for a more flexible and dynamic approach to clustering, as the number of clusters can be varied by changing the level of granularity in the hierarchy.

#### Deep Unsupervised Learning
Deep unsupervised learning models are trained using large amounts of unlabelled data, and they learn to extract features and patterns from the data without any supervision or guidance. The models are designed to reconstruct the input data or predict future states of the data, which helps them learn useful representations.

- Autoencoders: Autoencoders are a type of neural network architecture that is trained to copy its input to its output. They are called "auto" because they do not require labeled data, and "encoder" because they compress the input data into a lower-dimensional representation, called the bottleneck or latent representation, and then decode it back to the original space.
- Generative Adversarial Networks (GANs): - Train two neural networks, a generator and a discriminator, to compete with each other, generating new data samples that are indistinguishable from real data, and detecting whether a sample is real or generated.


## Ensemble Learning Methods
Ensemble learning methods are a class of machine learning techniques that combine the predictions of multiple base models to produce improved results. These methods exploit the diversity of the base models to achieve better generalization, robustness, and accuracy than any single model

- Bagging (Bootstrap Aggregating): Bagging combines multiple instances of the same base model, each trained on a random subset of the training data. By reducing the variance of the model, bagging improves the accuracy and robustness of the model.
- Boosting: Boosting combines multiple weak models to create a strong predictor. Each iteration adds a new model to correct the errors made by the previous models. Popular boosting algorithms include Gradient Boosting and XGBoost.
- Random Forest: Random Forest creates multiple decision trees and aggregates their predictions. Each tree is built using a random subset of features and a random subset of the data. This reduces overfitting and improves the generalization of the model.

## Other Networks
- Deep Belief Networks (DBNs)
- Radial Basis Function Networks (RBFNs)