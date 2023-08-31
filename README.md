![Preliminary](https://img.shields.io/badge/Status-Preliminary-yellow)

# Applied Machine Learning Curriculum
This document is a prelimnary definition of a curriculum to support development of a applied machine learning program with a focus on engineering for state-of-the-art methods, deep neural networks.

This document serves as an outline for a two-year curriculum with an example schedule, noting prerequesities and summarizing educational content.

Note: Students who already have taken Calculus / Linear Algebra / Probability & Statistics are in a much better position to handle the schedule.
## Year 1

Provides an introudction to machine learning, with a focus on neural networks. Students will cover the foundational mathematics needed to work with and understand model development, and conclude the year focusing on end to end training.

### Semester 1

This semester introduces machine learning, learning tasks, models, model selection, in addition to the foundational mathematics of machine learning.

#### [Intro to Machine Learning](./core/foundations/intro.md)
- Topics: High-level coverage of types of learning tasks (supervised, unsupervised, etc.), types of models (neural networks, decision trees, regression, etc.), and introduction to model selection.
- Prerequisites: None
#### [Calculus for ML](./core/maths/calculus.md)
- Topics: Limits and Continuity, Derivatives, Chain Rule, Integrals, Partial Derivatives, Vector Calculus
- Prerequisites: Math placement
#### [Linear Algebra for ML](./core/maths/linear-algebra.md)
- Topics: Systems of linear equations, Matrix operations, Inverses and Determinants, Eigenvalues / Eigenvectors, Matrix Decomposition, SVD, PCA, LDA
- Prerequisites: Math placement

### Semester 2

This semester continues the mathematical foundations for ML, and introduces students to all apsects of training and building models end to end, in addition to an introduction to a focus on neural networks.

#### [Introduction to Neural Networks](./core/foundations/neural-nets.md)
- Topics: Perceptron, Activations, Layers, Cost Function, Back-propegation, Gradient-Descent, Traning: Learning rates / batching, Regularization, Architectures and hyper-parameters
- Prerequisites: Calc, Linear Algebra, Intro to Machine Learning
#### [Training Models End-to-End](./core/foundations/methods.md)
- Topics: Framing, Problem Structuring, Data Handling / Preprocessing, Model Selection, Training, and Performance Metrics.
- Prerequisites: Intro to Machine Learning
#### [Probability, Stats, and Information Theory for ML](./core/maths/statistics.md)
- Topics: Random Variables, Probability Distributions, Marginal / Conditional Probability, Independence, Expectation, Variance and Covariance
- Prerequisites: Calc

## Year 2
This year utilizes the foundations acquired in the first year to focus on deep learning covering specific models and applications, challenges in systems engineering, and completes with a cap-stone project in which the student delivers an ened-to-end state-of-the-art system, preferably in the context of an internship.

### Semester 1
This semester focuses on a survey of deep learning and its applications, advanced techniques and focused topics in training deep networks,  and systems engineering focused on the computational challenges in the domain of deep learning.

#### [Deep Learning](./core/foundations/deep-nets.md)
- Topics: CNNs, RNNs, Deep RL/HRL, Transformers & LLMs, AutoEncoders, GANs
- Prerequisites: Intro to Neural Nets, Training End-to-End, Calc, Linear Algebra, Probability & Stats
#### [Advanced Techniques and Special Topics](./core/foundations/deep-nets.md)
- Topics: Transfer Learning, Fine-Tuning, Hyper Parameter tuning
- Prerequisites: Calculus, Linear Algebra, Probability & Stats, Intro to Neural Nets, Training End-to-End
#### [Systems Engineering for ML](./core/foundations/systems.md)
- Topics: GPU/TPU acceleration, distributed training, cloud platforms, large datasets, data / model parallelism, MLOps, Versioning, Inference on Edge / constrained compute.
- Prerequisites: Introduction to Neural Networks, Training End-to-End

#### Semester 2
This semester is focused on applying the foundational knowledge to design and train a state-of-the-art system end to end. Students will also take a survey covering the interdisciplinary applications of machine learning systems in order to gain awareness of industrial demand for machine learning systems.  In addition, students will be introduced to the ethical concerns and societal impacts of machine learning and AI.

#### [Capstone Project](./support/captstone.md)
- Topic: Design and deliver state of the art system.
- Prerequisites: Deep Learning, Systems Engineering

#### [Interdisciplinary Applications / Survey](./support/survey.md)
- Topics: Healthcare, Finance, Smart Cities, IoT, Robotics & Autnomous Platforms
- Prerequisites: Intro to Machine Learning

#### [Ethics and Societal Impacts](./support/ethics.md)
- Topics: Bias and Fairness, Transparency and Accountability, Considerations in data collection
- Prerequisites: Intro to Machine Learning

