# DS471-project
machine learning project

## Dataset Description

This project uses the Obesity Level Estimation dataset from the UCI Machine Learning Repository.

The original dataset contains 2,111 records, 16 input features, and 7 obesity level categories.

The goal is to predict a person's obesity level based on eating habits, physical characteristics, and lifestyle information.

## Data Preprocessing

The dataset was checked for missing values and duplicate records. No missing values were found, and 24 duplicate records were removed, leaving 2,087 records.

Categorical features were converted into numerical features using one-hot encoding. Numerical features were standardized for Logistic Regression and the Neural Network.

The cleaned dataset was divided into three sets using stratified splitting:

•⁠  ⁠Training: 70%
•⁠  ⁠Validation: 15%
•⁠  ⁠Testing: 15%


## Machine Learning Models

This project uses three machine-learning models to predict seven obesity categories.

### 1. Logistic Regression
Logistic Regression was selected as a baseline model because it is simple, efficient, and suitable for multiclass classification.

### 2. Random Forest
Random Forest combines multiple decision trees to make predictions. It can identify complex relationships between the dataset features.

### 3. Neural Network
The Neural Network was developed using TensorFlow and Keras. It uses a hidden layer with ReLU activation, Dropout to reduce overfitting, and a Softmax output layer for the seven obesity categories.

The three models were trained and compared using the same training, validation, and test datasets.
