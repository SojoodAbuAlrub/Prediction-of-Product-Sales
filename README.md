# Sale Prediction for food items sold at various stores Project. 
The dataset was focused on Sale Prediction for food items sold at various stores. There were 8523 Rows  and  12 Volumns.
# Data Dictionary: 
 <img width="495" alt="Screen Shot 2024-10-17 at 5 06 07 PM" src="https://github.com/user-attachments/assets/48ecdbcb-fa89-4fac-a5ca-fac3f2bec304">

# Prediction-of-Product-Sales

This repository contains a machine learning project focused on predicting future sales based on historical data. The project involves data collection, exploratory analysis, feature engineering, and model development using various algorithms. The goal is to create an accurate sales forecasting model to help businesses optimize inventory management and improve decision-making.

#Features:
Data preprocessing and cleaning
Exploratory Data Analysis (EDA)
Model training with algorithms like Linear Regression, Random Forest, and Gradient Boosting
Model evaluation and tuning

- Python
- Libraries: pandas, NumPy, scikit-learn, seaborn, matplotlib
- Visualization tools: Matplotlib, Seaborn
Explore the code, contribute to the development, and use the insights to enhance sales strategies.

Team: This project was developed by three dedicated data science students:
Sojood AbuAlrub, Mohemmed Qwasmi, Oday Qtit. 

![download](https://github.com/user-attachments/assets/41f914c4-6c8b-4888-afed-0474be5b444f)


# Maching Learning Using the Following Models:
- Linear Regression Model
- Random Forest Regressor Model
- Tuned Random Forest Regressor Model

# Models Evaluated & Results
## Linear Regression Model (Testing Set):
- Results for training data:
  - R^2 = 0.675
  - MAE = 730.773
  - MSE = 961298.775
  - RMSE = 980.458
- Results for testing data:
  - R^2 = -2.2137526981458333e+20
  - MAE = 2388885071705.636
  - MSE = 6.200706978685387e+26
  - RMSE = 24901218802872.656

 ## Random Forest Regressor Model
 - Results for training data:
  - R^2 = 0.936
  - MAE = 301.239
  - MSE = 188081.314
  - RMSE = 433.683
- Results for testing data:
  - R^2 = 0.546
  - MAE = 782.768
  - MSE = 1272843.53
  - RMSE = 1128.204

 - The Final Model Chosen was a Random Forest Regressor Model with the n_estimators tuned to 100, although its testing R2 is lower at 0.546. 
 - The Mean Squared Error was  1272843.5303$
 - 
