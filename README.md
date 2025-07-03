# Home-Credit-Default-Risk
Exploratory Data Analysis, Data Preprocessing &amp; Feature Engineering 

**Overview**
This project involves data exploration, preprocessing, and feature engineering for the Home Credit Default Risk dataset. The primary goal is to analyze client credit data to understand factors influencing loan default rates and prepare the data for modeling.

Contents
1. Data Exploration
- Load and inspect datasets
- Examine missing values
- Analyze distributions and anomalies

2. Feature Engineering
- Create new features based on domain knowledge
- Calculate financial ratios and metrics
- Explore relationships between features and the target variable

3. Visualizations
- Histograms and KDE plots for feature distributions
- Correlation heatmaps
- Pair plots for feature relationships

**Datasets**
application_train.csv: Training data containing client information and loan details
application_test.csv: Test data for prediction
bureau.csv: Bureau credit information
bureau_balance.csv: Bureau credit balance information
credit_card_balance.csv: Credit card balance information
installments_payments.csv: Installments payments history
previous_application.csv: Previous loan application details
POS_CASH_balance.csv: Point-of-sale cash balance information

**Key Features**
CREDIT_INCOME_PERCENT: Percentage of the credit amount relative to client income
ANNUITY_INCOME_PERCENT: Percentage of the loan annuity relative to client income
CREDIT_TERM: Length of the payment term in months
DAYS_EMPLOYED_PERCENT: Percentage of days employed relative to client age

**Dependencies**
- pandas
- numpy
- matplotlib
- seaborn
