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
 
#### 3. Model
- Feature Selection
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

#### 4. Model Iteration:
   - Add/Remove Variable?
   - Combine Variable?
   - Run Model on Different Granularity?
   - Transform Variable?
     - Log
     - Normalize
     - Standardize
     - Square Root
     - Absolute