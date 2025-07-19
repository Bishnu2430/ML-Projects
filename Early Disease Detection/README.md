### Early Disease Detection – Summary

**Objective**:  
Build a classification model to predict the presence of heart disease using patient health and lifestyle data.

**Workflow Summary**:

- **Data Exploration**: Analyzed key variables such as age, blood pressure, cholesterol, and glucose. Boxplots and countplots revealed differences in these features between diseased and healthy individuals.
- **Preprocessing**: Handled missing values, encoded categorical features (like gender), and scaled numerical inputs.
- **Modeling**: Trained and evaluated four classifiers:
  - Logistic Regression
  - Random Forest
  - Gradient Boosting
  - XGBoost

**Best Model**:

- **Gradient Boosting** achieved the highest F1 Score (0.7236), with good balance between precision and recall.

**Key Insights**:

- Higher systolic blood pressure (`ap_hi`) and cholesterol levels were more common among patients with heart disease.
- Lifestyle factors like alcohol use and physical inactivity were also associated with higher disease risk.
- Age was a strong continuous predictor, as expected in cardiovascular risk profiling.

**Conclusion**:  
Machine learning can effectively support early detection of heart disease. The trained model can be used by healthcare providers for early screening, allowing for timely interventions and lifestyle modifications.
