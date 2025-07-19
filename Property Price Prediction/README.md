### Property Price Prediction – Summary

**Objective**:
Predict the median house value in California districts using regression models.

**Dataset Overview**:
Includes features like `median_income`, `total_rooms`, `households`, `latitude`, and `ocean_proximity`.

**EDA Highlights**:

- Strong correlation between `median_income` and house value.
- House prices are generally higher near the coast.
- Skewed target distribution with a cap at \$500,000.

**Preprocessing**:

- Filled missing values in `total_bedrooms`.
- Encoded `ocean_proximity` using one-hot encoding.
- Added engineered features: `rooms_per_household`, `bedrooms_per_room`.

**Models Used**:

- **Simple Linear Regression** (using `median_income`):
  R² ≈ 0.46, RMSE ≈ 84,000
- **Multiple Linear Regression** (all features):
  R² ≈ 0.61, RMSE ≈ 71,000

**Conclusion**:
Multiple Linear Regression performed better overall. Key predictors include `median_income`, `location`, and room-related features. Further improvement is possible with advanced models.
