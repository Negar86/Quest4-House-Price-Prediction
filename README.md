# Quest4 | Iron_regression
---
![types-of-real-estate-investments](https://github.com/Negar86/Quest4-Iron_regression/assets/160590005/91b5e7bb-ad57-48e2-a0f5-6287db07b307)

# Project Overview
In this project, we aim to analyze and predict house sale prices in King County using a dataset that includes various attributes of the houses sold in this region. By performing Exploratory Data Analysis (EDA) and data processing, we will gain insights into the dataset and prepare it for machine learning. Our ultimate goal is to determine which machine learning model best predicts house prices based on the available features.  

---
# Data Source:
The dataset used in this project contains house sale prices and various attributes related to the houses sold in **King County**. Key features in the dataset include:  
- **id:** A unique identifier for a house.  
- **date:** The date on which the house was sold.  
- **price:** The sale price of the house (prediction target).  
- **bedrooms:** Number of bedrooms in the house.  
- **bathrooms:** Number of bathrooms in the house, per bedroom.  
- **sqft_living:** Square footage of the interior living space.  
- **sqft_lot:** Square footage of the land space.  
- **floors:** Number of floors (levels) in the house.  
- **waterfront:** Whether the house has a waterfront view.  
- **view:** Number of times the house has been viewed.  
- **condition:** The overall condition of the house.  
- **grade:** The overall grade given to the house, based on the King County grading system.  
- **sqft_above:** Square footage of the house apart from the basement.  
- **sqft_basement:** Square footage of the basement.  
- **yr_built:** The year the house was built.  
- **yr_renovated:** The year the house was renovated.  
- **zipcode:** ZIP code area.  
- **lat:** Latitude coordinate.  
- **long:** Longitude coordinate.  
- **sqft_living15:** The interior living space for the nearest 15 neighbors in 2015.  
- **sqft_lot15:** The land spaces for the nearest 15 neighbors in 2015.
---
# Conslusion:  
Features most influce the house price:  
![image](https://github.com/Negar86/Quest4-Iron_regression/assets/160590005/8936f3b7-3979-41b0-9b59-371481628844)

By analyzing different supervised models including:   
- Linear Regression,   
- Ridge,   
- Lasso,   
- Decision Tree,   
- K-Nearest Neighbors (KNN), and   
- XGBoost,  
  
The results showed that the XGBoost model is the most accurate for predicting house prices. The XGBoost model achieved an R² score of 0.67775,RMSE of 215,690.53 and MEA 130,857.90 indicating its superior performance compared to the other models evaluated.  

To enhance the model's performance, we applied standardization, which significantly improved the accuracy of our predictions. Additionally, we excluded outliers towards the end of our analysis to compare the improvement in the model's performance. This step helped in refining the predictions by reducing the impact of extreme values on the model.  
![comparison](https://github.com/Negar86/Quest4-Iron_regression/assets/160590005/a1db9efc-0bdc-4ee6-8489-b4850b4e9fca)

