# Life-Expectancy-Prediction

## Data
The dataset used for this project contains features such as GDP, healthcare expenditure, and literacy rate, which are relevant for predicting life expectancy.

### Data Preprocessing
- Handle missing values.
- Normalize numerical features.
- Encoding categorical features.

## Methodology

### Feature Selection
1. **Sequential Feature Selection (SFS):**
   - SFS is used to identify the most relevant features for the model by adding or removing features iteratively.

2. **Variance Inflation Factor (VIF):**
   - VIF is calculated to detect multicollinearity among features.
   - Features with high VIF values are excluded.

### Model Training
- A linear regression model is trained using the selected features.
- Hyperparameters are tuned as necessary.

### Evaluation Metrics
- **R-squared Score**

## Results
The model achieved the following results on the test dataset:
- R-squared: 91% Accuracy of the model.
