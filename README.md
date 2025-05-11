# Entri-Final-Project
Healthcare Billing Amount Prediction 

# Entri-Final-Project
hospital length of stay prediction using linear regression
This machine learning project aims to predict the hospital length of stay (LOS) for patients based on a variety of features such as patient demographics, medical conditions, admission type, insurance provider, and other relevant data. The model helps healthcare providers forecast patient stays for better resource allocation and planning.  

## Best Algorithm Selection
In this project, I compared several machine learning algorithms including Linear Regression, Ridge, Lasso, Decision Trees, Random Forest, KNN, SVR, and Gradient Boosting. The performance of each model was evaluated using **Root Mean Squared Error (RMSE)** and **R² (Coefficient of Determination)** as the primary metrics.

### Best Model Based on RMSE and R²:
- Linear Regression was found to be the best model based on both RMSE (0.0000) and R² (1.0000).
- The R² score of 1.0000 indicates that the model perfectly explains the variance in the target variable, which is a highly desirable property in regression tasks.
- The RMSE of 0.0000 further confirms that the model's predictions are extremely accurate, with negligible error.
 ## Why Linear Regression is the Best:
Linear Regression is a simple yet effective model when the relationship between the features and target variable is linear. In this case, the data seems to fit well with a linear model, as evidenced by the high R² and low RMSE values. While more complex models like Random Forest and Gradient Boosting often perform well in capturing non-linear relationships, Linear Regression performed equally well and is more interpretable and easier to deploy.

Other models like Random Forest and Gradient Boosting showed comparable performance but had slightly higher RMSE values. The simpler Linear Regression model, in this case, provides the best trade-off between performance and simplicity.

## Conclusion:
Although more complex models can sometimes outperform simpler models, Linear Regression provided the most accurate and interpretable results for this dataset. Therefore, it is considered the best algorithm for this particular task.

   Project Structure:
ML-LengthOfStay-Prediction/
├── Entri Final Project.ipynb        
├── README.md                        
├── requirements.txt                 
├── data/
│   └── updated_healthcare_dataset.xlsx  
├── models/
│   └── final_linear_regression_model.pkl    

   ML Pipeline:
1.Data Collection,
2.Data Cleaning & Preprocessing,
3.Exploratory Data Analysis (EDA),
4.Feature Engineering,
5.Model Building,
6.Model Evaluation,
7.Model Saving.

  Tech Stack / Tools Used:
Python,
Jupyter Notebook, 
Pandas, NumPy,
Matplotlib, Seaborn,
Scikit-learn,
Joblib.

  Results:
Evaluation metrics used for this regression task:
-Mean Squared Error (MSE),
-R² Score (Coefficient of Determination).

  How to Run the Project:
1.Clone the Repository,
2.Install Dependencies,
3.Launch Jupyter Notebook,
4.Run All Cells.

  Authors:
[Theresa Dominic](https://github.com/theresa2004)
