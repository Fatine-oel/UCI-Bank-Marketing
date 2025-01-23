# UCI-Bank-Marketing
UCI Bank Marketing Project: A machine learning project leveraging the UCI Bank Marketing dataset to predict the likelihood of customers subscribing to a term deposit. The project includes data preprocessing, feature engineering, exploratory data analysis (EDA), model building, and evaluation

## Dataset

The dataset used in this project contains multiple attributes regarding individuals' personal information, past interactions with the bank, and their financial status. Below is a brief description of the dataset:

| Column        | Description |
|---------------|-------------|
| **age**       | Age of the individual. |
| **job**       | Type of job (e.g., management, technician, entrepreneur, etc.). |
| **marital**   | Marital status (e.g., married, single, divorced). |
| **education** | Level of education (e.g., tertiary, secondary, primary, unknown). |
| **default**   | Whether the individual has credit in default (yes/no). |
| **balance**   | Account balance (numeric). |
| **housing**   | Whether the individual has a housing loan (yes/no). |
| **loan**      | Whether the individual has a personal loan (yes/no). |
| **contact**   | Type of communication used to contact the individual (e.g., cellular, telephone, unknown). |
| **day**       | Last day of the week the individual was contacted (numeric). |
| **month**     | Last month of the year the individual was contacted (e.g., jan, feb, ...). |
| **duration**  | Duration of the last contact in seconds. |
| **campaign**  | Number of contacts performed during this campaign. |
| **pdays**     | Number of days since the last contact (if -1, means no previous contact). |
| **previous**  | Number of contacts performed before this campaign. |
| **poutcome**  | Outcome of the previous marketing campaign (e.g., success, failure, unknown). |
| **y**         | Whether the individual subscribed to a term deposit (yes/no). (Target variable) |


## Installation

To run this project locally, you need to clone the repository and install the necessary dependencies.

## 1. Clone the repository:
    git clone https://github.com/Fatine-oel/UCI-Bank-Marketing.git

## 2. Navigate into the project directory:
  cd UCI-Bank-Marketing
## Install the required Python packages:
  pip install -r requirements.txt

# Model
The model used in this project is a Classification Model, which aims to predict whether a customer subscribes to a term deposit. Various machine learning algorithms, such as logistic regression, decision trees , KNN , Random Forest , and support vector machines (SVM), are used in this project to build a predictive model.

# Key Steps:
## Data Preprocessing:
  Cleaning the data by handling missing values, encoding categorical variables, and scaling numerical values.

## Model Training:
  Training the model on the training set and validating it using the testing set.

## Model Evaluation:
  Evaluating the model's performance using metrics like accuracy, precision, recall, and F1-score.

## Prediction:
  Making predictions on data.

## Authors
 **Fatine El Ouahdani** - Lead Developer.
