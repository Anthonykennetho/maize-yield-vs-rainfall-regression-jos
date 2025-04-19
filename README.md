# Maize Yield Prediction

This project uses **simple linear regression** to predict **maize yield** (bags per hectare) based on **rainfall** (mm). The goal is to understand the relationship between these two variables and make predictions.

## Dataset

The dataset includes the following columns:
- **Year**: The year of observation.
- **Month**: The month of observation.
- **Rainfall_mm**: Amount of rainfall (mm).
- **Maize_Yield_bags_per_ha**: Maize yield (bags per hectare).

## Model

A **simple linear regression** model is used to predict **maize yield** based on **rainfall**.

### Key Metrics:
- **Pearson Correlation Coefficient**: **0.808**  
  Indicates a strong positive linear relationship between **rainfall** and **maize yield**.
  
- **R-squared (R²)**: **0.658**  
  About **65.8%** of the variance in **maize yield** is explained by **rainfall**.

- **Mean Absolute Error (MAE)**: **2.01 bags/ha**  
  On average, the model's predictions are off by about **2 bags per hectare**.

- **Mean Squared Error (MSE)**: **6.29**  
  This indicates moderate error, penalizing larger errors more heavily.

## Conclusion

The model provides a solid baseline for predicting **maize yield** based on **rainfall**. While the R² value suggests a moderate relationship, approximately **34.2%** of the variance in maize yield is unexplained. This indicates that other factors (e.g., **seasonality**, **soil type**, **temperature**) could further improve the model.

## Future Improvements
- **Feature Engineering**: Add seasonal features like **month**, **year**, **soil types** and **temperature** to capture temporal trends.
- **Advanced Models**: Explore **polynomial regression** or machine learning models (e.g., **random forests**, **gradient boosting**) to capture non-linear relationships.
- **Validation**: Test the model on a validation or test set to ensure it generalizes well.

## Getting Started

### Requirements
- Python 3.x
- Required libraries:
  - pandas
  - numpy
  - scikit-learn
  - matplotlib


