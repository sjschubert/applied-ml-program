# Intro to Neural Networks

Neural networks are powerful machine learning models inspired by the structure and function of the human brain. They consist of interconnected nodes (neurons) that process inputs, learn from data, and make predictions or decisions.


### Basics of Neural Networks and Deep Learning Foundations

#### 1. Introduction to Neural Networks
- **What is a Neuron?**: Biological inspiration and the artificial counterpart.
- **Perceptrons**: The simplest neural network unit.
- **Activation Functions**: Understanding step, sigmoid, ReLU, tanh, and other functions.

#### 2. Feed-Forward Neural Networks
- **Input Layer, Hidden Layers, and Output Layer**: Understanding the architecture.
- **Weights and Biases**: What they are and their role in the network.
- **Forward Propagation**: How inputs are transformed into outputs.

#### 3. Learning in Neural Networks
- **Cost Function**: Objective functions like MSE for regression and cross-entropy for classification.
- **Gradient Descent**: How neural networks "learn" by minimizing the cost function.
- **Backpropagation**: Calculating gradients efficiently and updating weights.

#### 4. Practical Aspects of Neural Network Training
- **Batch vs. Mini-batch vs. Stochastic Gradient Descent**: Understanding different training methods.
- **Learning Rate**: What it is and how to select it.
- **Learning Rate Scheduling**: Adapting the learning rate during training.

#### 5. Regularization and Generalization
- **Overfitting vs. Underfitting**: Understanding the bias-variance tradeoff.
- **L1 and L2 Regularization**: Regularization techniques to prevent overfitting.
- **Dropout**: Temporarily removing neurons during training as a form of regularization.
- **Early Stopping**: Terminating training early based on validation performance.

#### 6. Advanced Topics
- **Initialization Techniques**: Xavier, He-initialization, etc.
- **Optimization Algorithms**: SGD, Momentum, RMSprop, Adam, etc.
- **Batch Normalization**: Normalizing activations within a layer for better performance and stability.

#### 7. Architectural Choices
- **Number of Hidden Layers and Neurons**: How to decide the architecture of your neural network.
- **Choosing Activation Functions**: Sigmoid, tanh, ReLU, Leaky ReLU, Swish, etc.

#### 8. Performance Metrics
- **Accuracy, Precision, Recall, F1-Score**: Metrics for classification tasks.
- **Mean Squared Error, Mean Absolute Error**: Metrics for regression tasks.
- **Confusion Matrix**: Understanding True Positives, False Positives, True Negatives, and False Negatives.

#### 9. Debugging and Troubleshooting
- **Vanishing and Exploding Gradients**: What these problems are and how to deal with them.
- **Model Inspections**: Understanding the learned weights, activations, and feature maps.

#### 10. Neural Network Frameworks
- **TensorFlow, PyTorch, Keras**: Brief introduction to popular deep learning libraries.

This foundation will allow students to understand the inner workings of neural networks, enabling them to not only use pre-existing libraries and models but also develop their own.

11. Transfer Learning and Fine-tuning
What is Transfer Learning?: Understanding the reuse of pre-trained models on a new problem.
Types of Transfer Learning: Domain adaptation, task adaptation, etc.
Fine-tuning Techniques: How to adapt a pre-trained model to a new task with few samples.
When to Use Transfer Learning: Practical considerations and use-cases.
Limitations and Challenges: Understanding when transfer learning may not be suitable.
