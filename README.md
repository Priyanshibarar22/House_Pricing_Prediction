#  House Price Prediction using Machine Learning
Predict house prices using regression models with full data preprocessing, evaluation, and visualization.


##  Project Overview
This project predicts house prices using machine learning regression models. It demonstrates the complete end-to-end data science workflow including data exploration, preprocessing, visualization, model training, evaluation, and comparison.



##  Objective
To build regression models that can estimate house prices based on property features.



##  Dataset Features
- Area  
- Bedrooms  
- Bathrooms  
- Stories  
- Parking  
- Main Road Access  
- Guest Room  
- Basement  
- Hot Water Heating  
- Air Conditioning  
- Preferred Area  
- Furnishing Status  

Target Variable: **Price**



##  Workflow

1. Data Loading  
2. Exploratory Data Analysis  
3. Missing Value Check  
4. Data Visualization  
5. Categorical Encoding  
6. Train-Test Split  
7. Feature Scaling  
8. Model Training  
9. Model Evaluation  
10. Prediction Visualization  



##  Models Used

| Model | Purpose |
|------|---------|
| Linear Regression | Baseline linear model |
| Decision Tree | Non-linear decision model |
| Random Forest | Ensemble learning method |



## Evaluation Metrics

| Metric | Meaning |
|-------|--------|
| R² Score | Model explanatory power |
| MSE | Penalizes large errors |
| MAE | Average absolute prediction error |



##  Results

| Model | R² Score |
|------|---------|
| Linear Regression | **0.65** |
| Random Forest | 0.63 |
| Decision Tree | 0.47 |



##  Key Insights
- The dataset shows mostly linear relationships.
- Linear Regression outperformed complex models.
- Decision Tree overfitted due to small dataset size.



##  Visualizations
Project includes:
- Histograms  
- Feature vs Price scatter plots  
- Actual vs Predicted plots 
Images of Histograms and Scatter plots are attached in the files section.
 
  



##  Skills Demonstrated
✔ Data Preprocessing  
✔ Feature Engineering  
✔ Model Comparison  
✔ Evaluation Metrics  
✔ Visualization  
✔ Machine Learning Workflow  


## Conclusion

The Linear Regression model successfully captures the relationship between area and price, achieving **65% variance explanation**, making it a strong predictive system.

Linear Regression performed best due to the mostly linear relationships in the dataset.  
Decision Tree showed overfitting, while Random Forest improved stability but did not outperform Linear Regression.

This project demonstrates model comparison, evaluation, and proper preprocessing.


