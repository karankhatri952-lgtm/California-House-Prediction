# 🏠 California House Price Prediction

 Project Overview

This project predicts **house prices in California** using Machine Learning.

The project uses the **California Housing dataset** and applies data preprocessing, feature engineering, and a Machine Learning regression model to predict the median house value based on different housing and demographic features.

 Objective

The main objective of this project is to build a Machine Learning model that can predict California house prices using features such as:

* Longitude
* Latitude
* Housing Median Age
* Total Rooms
* Total Bedrooms
* Population
* Households
* Median Income
* Ocean Proximity

Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

Project Workflow

The project follows these steps:

1. Import the dataset
2. Explore the data
3. Check missing values
4. Analyze numerical and categorical features
5. Visualize the data
6. Split the data into training and testing sets
7. Create preprocessing pipelines
8. Handle missing values
9. Scale numerical features
10. Encode categorical features using One-Hot Encoding
11. Train the Machine Learning model
12. Make predictions
13. Evaluate model performance

Data Preprocessing

### Numerical Features

For numerical features:

* Missing values are handled using **Median Imputation**
* Features are standardized using **StandardScaler**

### Categorical Features

For categorical features:

* Missing values are handled using the **Most Frequent** strategy
* Categorical values are converted into numerical values using **OneHotEncoder**

A `Pipeline` and `ColumnTransformer` are used to organize the preprocessing steps.
 🤖 Machine Learning

This is a **supervised learning regression problem** because the target variable is a continuous house-value amount.

The model learns relationships between the housing features and the target house value and then uses those relationships to predict prices for unseen data.

 Model Evaluation

The model can be evaluated using regression metrics such as:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score

These metrics help measure how accurately the model predicts house prices.

 Project Structure

```text
California-House-Prediction/
│
├── california_house_prediction.ipynb
├── README.md
└── dataset/
    └── housing.csv
```

 Example

The project takes housing information such as:

```text
Median Income
House Age
Total Rooms
Population
Households
Location
Ocean Proximity
```

and uses these features to predict:

```text
Median House Value
```

 What I Learned

Through this project, I practiced:

* Data cleaning
* Exploratory Data Analysis (EDA)
* Data visualization
* Handling missing values
* Feature preprocessing
* One-Hot Encoding
* Feature scaling
* Machine Learning pipelines
* Train/test splitting
* Regression
* Model evaluation

 Future Improvements

Possible improvements include:

* Trying different regression algorithms
* Hyperparameter tuning
* Feature engineering
* Comparing multiple models
* Improving prediction accuracy
* Deploying the model as a web application

## 👨‍💻 Author

**Karan**
