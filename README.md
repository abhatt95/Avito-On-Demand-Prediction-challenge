# Avito-On-Demand-Prediction-challenge

The online advertisement industry is filled with a variety of advertisements that suffer from lack of proper optimization. 
The project aims at predicting the probability of online ads sale going through based on a variety of categorical and numerical features like category, geographical location and price or date respectively along with historical demand for such ads.
Kaggle Competition https://www.kaggle.com/c/avito-demand-prediction

1. Exploratory Data Analysis
2. Data Preprocessing
 - Handling Missing Data
 - Handling Categorical Features
3. Applying following Algorithms <br>
 i. Bayes Ridge Regression  <br>
 ii. Lasso <br>
 iii. XG Boost Regression <br> 
 iv. Light Gradient Boosting Regression <br>

 ### Comparison of Scores <br>
 
 ![Screenshot](images/Untitled.png)

4. Stacking the output of indivisual algorithm as input  

 ### Comparison of Scores after stacking <br>
 
![Screenshot](images/u2.png)

<br>
Content of files:<br>
preprocessing.ipynb - conatins script to preprocess data.<br>

EDA.ipynb - Visualizing and better understanding the data. <br>

4models.ipynb - Applying 4 algorithms on clean data. <br>

LGBoostCV.ipynb - Parameter tuning and CV for LGBoost. <br>

XGBoostCV.ipynb - Parameter tuning and CV for XGBoost. <br>

Stacking.ipynb - Visual comparision of results and stacking ouput as input to OLS, LASSO and LGBoost. <br>

INF552_Project_Avito_final.pdf - Detailed report on project. 
