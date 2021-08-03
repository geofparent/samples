This file has been created as a sample linear regression. Below is a summary of the process:

#### 1. Pandas Profiling:
- NULLS
- Frequency Distribution
- Outliers
- Identify Potential Variable Aggregates
- Identify Potential Joint Variables

#### 2. Analysis/Creation of Summary Tables:

- Daily Aggregated
    - Aggregated Monthly, Daily, Weekly, Quarterly
    - Moving Averages
    - Seasonality
    - Correlation Matrix
    - Time Series outliers
    - Identify Potential time related dummies
- Customer/User Aggregate
    - Return vs New
    - Grouping based on monetary value
    - Correlation Matrix##### Category Aggregates
    - Min/Max of category
    - Correlation Matrix
- Category Aggregates
    - Outliers
    - Identify Potential Dummy Variables
    - Identify aggregates with a numerical variables
 
#### 3. Transformation & Feature Selection

- Transformations
    - General Transformations:
        - Log Transformation
        - Clipping
            - Quantile
            - Both upper and lower?
        - Scaling
            - Min Max Normalization
            - Standard Scaler
            - Robust Scaler
    - Time Variables
        - Varaibles created from differences in two dates
        - Choose date granularity
        - Timezone
    - Monetary Variables
        - Remove signs, comma
        - Round
- Feature Selection
    - 

#### 4. Model
- Train, Test Split
- Run in stats model
- Check Summary Table
    - P-values
    - r2
    - f stat
    - 
- Check for OLS Assumptions
    - No Multicollinearity
    - Normality & Homoskadasiticty
    - No Autocorrelation
    - No Endogeneity
    - 
- Check against test
- Plot pred v acutal
- Check RSME, MAE

#### 5. Model Iteration:
   - Add/Remove Variable?
   - Combine Variable?
   - Run Model on Different Granularity?
   - Transform Variable?
     - Log
     - Normalize
     - Standardize
     - Square Root
     - Absolute