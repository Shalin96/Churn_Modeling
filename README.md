# Customer_Churn

Project Title:

Predicting Customer Churn with Neural Networks

Problem Statement:

I aimed to create a neural network classification model to predict customer churn based on various factors such as age, tenure, balance, number of products, credit card status, and activity.

Introduction:

Customer churn, or the loss of customers, is a critical concern for businesses. In this project, I leveraged neural network classification to predict customer churn. The dataset includes customer information, and my objective was to build an accurate model to identify customers at risk of leaving.

Dataset:

The dataset comprises customer information, including features like 'Age,' 'Tenure,' 'Balance,' 'NumOfProducts,' 'HasCrCard,' 'IsActiveMember,' and 'EstimatedSalary.' The target variable is 'Exited,' indicating whether a customer has churned (1) or not (0).

Tools and Statistical Methods:

Programming Language: Python
Environment: Google Colab
Libraries: NumPy, Matplotlib, Seaborn, Pandas, Keras

Data Exploration and Insights:

Data Overview: 

I loaded the dataset, which contains customer records with essential information for analysis.
Data Summary: Descriptive statistics provided insights, including the mean age, average balance, and distribution of other features. These statistics helped me understand the data's characteristics.


Data Split: 

I divided the dataset into training (80%) and testing (20%) sets to train and evaluate my neural network model.
Neural Network Modeling:

Model Architecture: 

I created a neural network with three layers: an input layer with 64 units and 'sigmoid' activation, a hidden layer with 32 units and 'sigmoid' activation, and an output layer with 1 unit and 'sigmoid' activation.


Model Compilation: 

I compiled the model using 'adam' optimizer and 'binary_crossentropy' loss, with accuracy as the metric.


Model Training: 

The model underwent training for 12 epochs with a batch size of 64, achieving a validation accuracy of approximately 78.69%.


Model Evaluation:

I evaluated the model's performance on the test data, resulting in a test accuracy of 78.95%.
Model Summary: The model summary revealed a total of 2,625 trainable parameters.


Predictions and Insights:

I made predictions on the test data and rounded them to binary values (0 or 1) for interpretation.
Examples: I showcased examples of customer records and their corresponding predictions.


Results and Insights:

The neural network classification model effectively predicts customer churn based on various customer attributes, achieving a test accuracy of 78.95%. This accuracy highlights its potential as a valuable tool for identifying customers at risk of churning.

The model's predictions can provide businesses with actionable insights. By identifying customers at risk of churning, businesses can proactively implement retention strategies, ultimately reducing customer churn and improving customer retention rates.

Future work may involve optimizing the model further, exploring additional data analytics techniques, and integrating external data sources to enhance prediction capabilities and provide even more valuable insights to businesses.
