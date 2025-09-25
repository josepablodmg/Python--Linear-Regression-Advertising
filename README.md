# Linear Regression - Advertising

## Description
This project explores the relationship between advertising budgets and sales. Using a linear regression model, the goal is to predict sales based on spending in TV, radio, and newspaper advertising channels. The project also analyzes residuals and visualizes regression coefficients to understand the model's behavior.

## Dataset
**Number of Instances:** 200  
**Number of Attributes:** 4  

**Features:**
- `TV` – Advertising budget for TV
- `radio` – Advertising budget for radio
- `newspaper` – Advertising budget for newspaper  

**Target Variable:**
- `sales` – Sales in units (or currency)

Dataset source: [Advertising dataset](https://www.statlearning.com/)

## Libraries
- `pandas`, `numpy`
- `matplotlib`, `seaborn`
- `scikit-learn`

## Key Steps
1. **Data Exploration:** Checking shape, descriptive statistics, and correlations.
2. **Data Visualization:** Boxplots, pairplots, and heatmaps to visualize feature relationships.
3. **Linear Regression:**  
   - Simple regression: Sales vs TV advertising  
   - Ordinary Least Squares (OLS) regression  
4. **Model Evaluation:**  
   - Mean Squared Error (MSE)  
   - R² score  
   - Visualization of predicted vs actual values  
5. **Residual Analysis:**  
   - Distribution of residuals to assess model fit  
6. **Coefficient Visualization:**  
   - Grid search and 3D plots to visualize RSS against regression coefficients

## Results
- TV advertising is strongly correlated with sales (`r ≈ 0.78`)  
- Model slope (TV vs Sales): `0.0443`  
- Model intercept: `7.4983`  
- Test MSE: `3.51`  
- Test R²: `0.682`  
- Minimized RSS: `2.10`  
- Residuals analysis shows a roughly normal distribution, indicating a reasonable model fit.

## Insights
TV advertising has the strongest influence on sales compared to radio and newspaper. The simple linear regression model captures most of the trend but leaves some variance unexplained.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
