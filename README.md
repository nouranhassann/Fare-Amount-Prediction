# Fare-Amount-Prediction
his project predicts taxi fare amounts based on trip and passenger data. The goal is to build a **regression model** that accurately estimates fare prices using historical trip information.
## Workflow
The analysis follows a **complete regression modeling pipeline**:

1. **Data Wrangling**
   - Handled missing values, outliers, and inconsistent formats.
   - Converted timestamps and categorical data to usable formats.

2. **Exploratory Data Analysis (EDA)**
   - Analyzed patterns in fare amounts relative to distance, time, and passenger count.
   - Visualized trends using scatter plots, histograms, and correlation matrices.

3. **Feature Engineering & Selection**
   - Created features such as trip distance, time of day, and day of week.
   - Applied feature selection techniques to improve model performance.

4. **Regression Modeling**
   - Tested multiple regression models: Linear Regression, Decision Trees, Random Forest, and Gradient Boosting.
   - Evaluated models using RMSE, MAE, and R² metrics.

5. **Insights & Recommendations**
   - Identified key factors influencing fare amounts.
   - Suggested improvements for fare prediction accuracy.

## Tools & Technologies
- Python, Pandas, NumPy  
- Scikit-learn (Linear Regression, Random Forest, Gradient Boosting)  
- Matplotlib, Seaborn  
- Regression Evaluation Metrics (RMSE, MAE, R²)
- ## Regression Model Performance

| Model                  | MAE   | RMSE  | R² Score |
|------------------------|-------|-------|----------|
| Model 1 (e.g., Linear Regression)   | 0.20  | 0.27  | 0.6579   |
| Model 2 (e.g., Random Forest)       | 0.18  | 0.25  | 0.7024   |

- **MAE (Mean Absolute Error):** Measures average absolute difference between predicted and actual fare amounts.  
- **RMSE (Root Mean Squared Error):** Penalizes larger errors more heavily than MAE.  
- **R² Score:** Indicates proportion of variance in fare explained by the model (closer to 1 is better).  

**Insight:** Random Forest outperformed Linear Regression, achieving higher accuracy and better variance explanation.


## Key Achievements
- Built a predictive model with high accuracy for fare estimation.  
- Identified trip distance, passenger count, and time of day as major fare drivers.  
- Delivered actionable insights for optimizing pricing strategies.
