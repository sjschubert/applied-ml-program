
### Data Handling and Preprocessing

1. **Data Collection and Sourcing**:
    - **Types of Data**: Understanding various types of data like structured, unstructured, and semi-structured data.
    - **Sources**: Identifying where to collect data from, including databases, APIs, web scraping, sensors, etc.
    - **Data Formats**: Understanding common data formats like JSON, XML, CSV, and Parquet.
    - **Data Storage**: Intro to database management systems, data lakes, and data warehouses.
    - **Legal and Ethical Considerations**: Issues like user consent, data anonymization, and GDPR compliance.

2. **Exploratory Data Analysis (EDA)**:
    - **Data Profiling**: Initial data inspection to summarize main characteristics using statistics and visualization.
    - **Data Distributions**: Examining the distribution of individual variables, looking for outliers, and assessing normality.
    - **Correlation Analysis**: Checking for relationships between variables that could affect the model.
    - **Visualizations**: Utilizing graphs and charts to visualize complex data relations.

3. **Data Cleaning and Preprocessing**:
    - **Handling Missing Values**: Strategies for imputing or removing missing data.
    - **Data Transformation**: Techniques like normalization, standardization, and encoding categorical variables.
    - **Handling Imbalanced Data**: Techniques like resampling, weighted loss functions, etc.
    - **Text Preprocessing**: For NLP tasks, techniques like tokenization, stemming, lemmatization, and dealing with stop words.
    - **Image Preprocessing**: For image tasks, techniques like image normalization, resizing, data augmentation.

4. **Feature Engineering** (Minimized):
    - **Automated Feature Selection**: Although less critical with deep learning, a brief overview of automatic feature selection techniques can be useful.
    - **Embeddings**: As deep learning often handles feature engineering implicitly, it's worth introducing embeddings as a way to understand how models learn representations.





Framing in Applied Machine Learning
Understanding Business Objectives:

Translating business goals into machine learning tasks
Stakeholder analysis
Problem Formulation:

Defining the target variable
Identifying Relevant Data:

Instead of "input features," a more general approach would be to identify the types of data that could be relevant for the problem at hand. This could be as broad as "text data from customer reviews" or "image data from sensors," without needing to specify the exact feature set.

Specifying Constraints:
Limitations on data usage, real-time requirements, computational resource limitations, etc.

Choice of Machine Learning Task:
Classification vs. Regression vs. Clustering vs. Reinforcement Learning, etc.
Time-series forecasting
Anomaly detection
Natural Language Processing tasks like sentiment analysis, machine translation, etc.


Benchmarking and Existing Solutions:
Analysis of existing models, algorithms, or services that could solve the problem or part of the problem.
Identifying open-source implementations, pre-trained models, or commercial services.
Cost-benefit analysis of using off-the-shelf solutions vs. custom development.

Data Considerations:
Data availability and collection methods
Identifying potential sources of bias in the data
Evaluating the quality and quantity of available data
Cost Function Design:

Choosing or designing an objective function that the algorithm will optimize
Understanding the trade-offs involved (e.g., precision vs. recall)
Performance Metrics:

Defining what success looks like in the context of the business problem
Choosing appropriate evaluation metrics like accuracy, F1-score, AUC-ROC for classification problems; MSE, RMSE for regression problems, etc.
Feasibility Analysis:

Technical feasibility (Do we have the computational resources?)
Time feasibility (Is the timeframe for developing the solution realistic?)
Cost-benefit analysis
Ethical and Legal Considerations:

Data privacy and ethics
Understanding the societal impact of the machine learning application
Fairness, accountability, and transparency in ML
Pilot Study & Prototyping:

Conducting small-scale experiments to assess the viability of the chosen framing