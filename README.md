## CTC Prediction For New Joiners
 ### Problem Statement:
  The aim of this project is to build a robust machine learning model that accurately predicts the Cost to Company (CTC)
  for new joiners based on various attributes such as work experience, educations, skills and other relevant factors.

  This problem is important from a business perspective as it helps companies make data-driven compensation decisions,
  maintain salary consistency and optimize hiring budgets.

### Objective:
  •  Predict candidate CTC using historical data.
  
  •  Identify key factors influencing salary.
  
  •  Build a robust and generalized regression model.
  
  •  Minimize prediction error using appropriate evaluation metrics.

### Tools and Technologies:
  •  Programming Languages: Python
  
  •  Libraries: Pandas, Numpy, Seaborn, Matplotlib, Scikit-Learn
  
  •  Environment: Jupyter Notebook

### Data Workflow:
   ### 1.) Data Preprocessing
  •  Handled missing values.
      
  •  Removed outliers from the CTC using statistical techniques.
      
  •  Encoded categorical variables.
   ### 2.) Exploratory Data Analysis (EDA)
  •  Analyzed distribution of CTC using histograms.
   
  •  Identified relationships between features and target variable.
   
  •  Used correlation heatmap to understand feature importance.
   
  •  Visualized outliers and data spreads using box and scatter plots.
   ### 3.) Feature Engineering
  •  Transformed variables to handle skewness (log transformation of CTC).
  
  •  Improved data representation for better learning.
   ### 4.) Model Building
  •  Implemented multiple models: Linear Regression and Random Forest Regressor.
   ### 5.) Model Evaluation
  Used appropriate evaluation metrics:
  
•  Mean Absolute Error (MAE)
  
•  Root Mean Squared Error (RMSE)
  
•  R2 Score
   ### 6.) Model Optimization
  •  Applied hyperparameter tuning using GridSearchCV.
  
  •  Reduced overfitting and improved generalization.
   ### 7.) Residual Analysis
  •  Analyzed residual plots to validate model assumptions.
  
  •  Identified unequal variance and addressed it using log transformation.
  
  •  Ensured errors are randomly distributed around zero.
   ### 8.) Key Insights
  •  Experience and certain features significantly influence CTC.
  
  •  Log transformation improved model stability and reduced variance.
  
  •  Tree-based models performed better for capturing non-linear relationships.
  
