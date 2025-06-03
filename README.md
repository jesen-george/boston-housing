# boston-housing

Predicting House Prices in 1970s Boston, USA
# Predicting Boston Housing Prices with Linear Regression

This project explores the Boston Housing dataset using regression analysis to predict median home values based on various features such as crime rate, number of rooms, and property tax rate. The goal is to demonstrate how linear regression can model real-world economic data.

## Project Files

- `Boston_Housing_Regression_Final.ipynb`  
  The main Jupyter notebook containing data exploration, preprocessing, model training, evaluation, and visualizations.

- `boston.csv`  
  The dataset containing housing data for suburbs of Boston, including features like crime rate, number of rooms, and access to highways.

## Techniques Used

- Data cleaning and preprocessing with **pandas**
- Exploratory data analysis (EDA) with **matplotlib** and **seaborn**
- Feature selection and correlation analysis
- **Linear regression** modeling with **scikit-learn**
- Model performance evaluation (R², MSE)

## Key Results

- Identified strongest predictors of housing prices (e.g., average number of rooms and % lower status population).
- Built and evaluated a linear regression model with reasonable accuracy.
- Visualized predictions vs actual values to assess model fit.

## Conclusion

The linear regression model provides a good baseline for predicting housing prices in Boston. The project illustrates how simple models can uncover meaningful patterns in housing and socioeconomic data.

## How to Run

1. Clone or download this repository.
2. Open `Boston_Housing_Regression_Final.ipynb` in Google Colab or Jupyter Notebook.
3. Ensure `boston.csv` is in the same directory, or update the path to match its location.
4. Run all cells to reproduce the analysis.

---

> This project is a classic example of using machine learning for real estate price prediction. It's suitable for beginners looking to apply regression techniques to structured datasets.
