#### Project 2: Loan Decision Tool
##### Anvitha Chaluvadi, Maria Notarianni, Owura Fosuhene Akosah

# **<ins>You Are Not A-Loan</ins>**

## Background
Both borrowers and lenders view loans as a financial commitment. Successful loans enable borrowers to fulfill lifelong aspirations, while unsuccessful ones pose challenges for everyone involved. Our aim is to develop a machine learning model that empowers lenders to make wiser business decisions while ensuring borrowers avoid enduring financial hardships down the road.

This repository contains the code and documentation for our project. The project focuses on predicting loan default risk using machine learning techniques.

## What We Are Creating
Our tool utilizes machine learning models to assist lenders in making informed decisions, ensuring borrowers achieve their goals without facing financial strain. By evaluating borrowing capacity, we mitigate risks and foster successful lending outcomes. To tackle the challenge of predicting loan default likelihood, we leverage historical loan data and employ classification algorithms such as Logistic Regression and Decision Trees to construct a predictive model.

If you would like to look at our in-depth analysis, please refer to our `test-loan defaulter.ipynb`

## Installation Instructions
To run the project locally, follow these steps:

1. Install Python 3.x.
2. Install Anaconda Navigator.
3. Clone this repository.
4. Install required Python libraries using `pip install -r requirements.txt`.

## Usage
* Data Preparation: Preprocess the loan datasets to handle missing values, outliers, and feature engineering tasks such as encoding categorical variables, scaling numerical features, and creating new features.

* Model Training: Train machine learning models using the preprocessed datasets, experimenting with different algorithms, and feature combinations. Evaluate model performance using appropriate metrics.

* Model Interpretation: Interpret model predictions, analyze feature importance, and assess model biases and limitations. Ensure transparency and accountability in model decision-making processes.

## Preview Visualizations
### Exploratory Data Analysis

<p align="center"> <img src = Images/EDA/EDA-Gender.png width =45% height 30%=/> </p>

<p align="center"> <img src = Images/EDA/EDA-Married.png width =45% height 30%=/> </p>

<p align="center"> <img src = Images/EDA/EDA-Dependents.png width =45% height 30%=/> </p>

<p align="center"> <img src = Images/EDA/EDA-Education.png width =45% height 30%=/> </p>

<p align="center"> <img src = Images/EDA/EDA-Self_Employed.png width =45% height 30%=/> </p>

<p align="center"> <img src = Images/EDA/EDA-Property_Area.png width =45% height 30%=/> </p>

<p align="center"> <img src = Images/EDA/EDA-Loan_Status.png width =45% height 30%=/> </p>

<p align="center"> <img src = Images/EDA/EDA-App_Loan_Amounts.png width =45% height 30%=/> </p>

### Creating a Logistic Regression Model with the Original Data
#### Making Predictions Using Training Data

<p align="center"> <img src = Images/Confusion-Matrix/Confusion-Matrix_Training.png width =45% height 30%=/> </p>

#### Making Predictions Using Testing Data 

<p align="center"> <img src = Images/Confusion-Matrix/Confusion-Matrix_Testing.png width =45% height 30%=/> </p>

#### Confusion Matrix
<p align="center"> <img src = Images/Confusion-Matrix/Confusion-Matrix_CM.png width =45% height 30%=/> </p>
<p align="center"> <img src = Images/Confusion-Matrix/Confusion-Matrix_CM-2.png width =45% height 30%=/> </p>

#### Decision Tree

<p align="center"> <img src = Images/Confusion-Matrix/Confusion-Matrix_DT.png width =45% height 30%=/> </p>

#### Random Forest

<p align="center"> <img src = Images/Confusion-Matrix/Confusion-Matrix_RF.png width =45% height 30%=/> </p>

#### Naive Bayes

<p align="center"> <img src = Images/Confusion-Matrix/Confusion-Matrix_NB.png width =45% height 30%=/> </p>

#### Gradient Boosting

<p align="center"> <img src = Images/Confusion-Matrix/Confusion-Matrix_GB.png width =45% height 30%=/> </p>

### Feature Importances

<p align="center"> <img src = Images/Confusion-Matrix/Feature_Importance.png width =45% height 30%=/> </p>

## Data Sources
The dataset used in this project can be found at [test-loan defaulter data.csv](https://github.com/Akosah304/loan_decsion_tool_Project-2/tree/main/Resources).

## Results
As a result, the logistic and decision tree models demonstrate balanced performance across all metrics, positioning them as strong contenders. The Random Forest model follows closely behind as a reliable choice. Although Naive Bayes remains competitive but slightly less consistent, Gradient Boosting shows lower overall effectiveness in this evaluation. Ultimately, selecting the best model depends on the specific priorities of the task, whether focusing on precision, recall, accuracy, or a combination of these metrics.

### <ins>Presentation</ins> 
[You Are Not A-Loan Presentation](https://docs.google.com/presentation/d/14dwuvp862QAsIPoE3zPzj3lQefg4naZ2HSFHFiIx_xQ/edit?usp=sharing)


