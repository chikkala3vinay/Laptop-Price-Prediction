# Laptop Price Prediction
## Problem Statement
The price of laptops varies significantly based on features such as processor, RAM, storage, brand, and display specifications. Customers often find it difficult to determine whether a laptop is fairly priced. The goal of this project is to develop a machine learning model that can predict the price of a laptop based on its specifications, helping users make informed purchasing decisions and assisting sellers in pricing strategies.
## Objective
To build a predictive model that estimates laptop prices using various hardware and brand features To analyze how different factors like RAM, processor type, and storage impact laptop pricing To perform data preprocessing, feature engineering, and model training To evaluate model performance using regression metrics such as MAE, MSE, and R² score
## Dataset Information

The dataset contains laptop specifications and corresponding prices.  
Features used in this project include:

- Company
- TypeName
- RAM
- Weight
- CPU
- GPU
- Operating System
- Storage
- Screen Resolution
- Inches
- Price

The target variable is:
- Price

## Machine Learning Workflow

1. Data Collection
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. Label Encoding
6. Train-Test Split
7. Model Training
8. Model Evaluation
9. Model Saving using Pickle
10. Deploying The Model using Streamlit


## Models Used

The following regression algorithms were tested:

- Linear Regression
- Random Forest Regressor
- Decision Tree Regressor
- XG Boosting Regressor

Random Forest Regressor provided the best performance. 

## Future Improvements

- Improve prediction accuracy
- Add advanced feature engineering
- Use deep learning models
- Create interactive visualizations

## Conclusion

This project successfully predicts laptop prices based on hardware specifications using machine learning techniques. The model helps users estimate laptop prices efficiently and supports better purchasing decisions.  
