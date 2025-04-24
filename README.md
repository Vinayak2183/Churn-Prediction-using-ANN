# Customer Churn Prediction using ANN

This repository contains a Jupyter Notebook that implements an Artificial Neural Network (ANN) for predicting customer churn using a dataset of customer information. Churn prediction helps companies identify which customers are likely to stop using their services, enabling better customer retention strategies.

##  Project Overview

This project builds and trains a feed-forward ANN using TensorFlow and Keras to classify whether a customer will churn or not based on features such as credit score, geography, gender, age, balance, etc.

##  Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib / Seaborn
- Scikit-learn
- TensorFlow / Keras

##  Dataset

The dataset used for training and testing the model includes the following columns:
- CustomerID
- CreditScore
- Geography
- Gender
- Age
- Tenure
- Balance
- NumOfProducts
- HasCrCard
- IsActiveMember
- EstimatedSalary
- Exited (target variable)

##  Steps Performed

1. **Data Preprocessing**
   - Encoding categorical variables (Label Encoding, One-Hot Encoding)
   - Splitting the dataset into training and testing sets
   - Feature scaling

2. **Model Building**
   - Constructing a sequential ANN model with input, hidden, and output layers
   - Using ReLU activation in hidden layers and sigmoid in the output layer
   - Compiling the model with binary crossentropy loss and Adam optimizer

3. **Model Training**
   - Training the ANN on the training data
   - Validating using the test set

4. **Evaluation**
   - Predicting churn on test data
   - Generating a confusion matrix and calculating accuracy

##  Results

The model achieved strong performance in classifying churned customers.

##  How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
