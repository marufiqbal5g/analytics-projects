# Data Analytics Projects

## Project - 01
File name: **_EDA-REGRESSION.ipynb_**

#### Project Title: Dataset Analysis and Regression Modeling

### Objective
1. Identify and resolve dataset issues (missing values, outliers).
2. Perform Exploratory Data Analysis (EDA).
3. Conduct ANOVA analysis.
4. Build and evaluate a Linear Regression model using statsmodels.

### Dataset Details
The dataset contains 3000 rows and 6 columns, described as follows:
• Revenue: Revenue generated by the food industry (numeric, with 150 missing values).

• Expense: Expenses incurred (numeric, no missing values).

• Profit: Profit calculated as Revenue - Expense (numeric, with 150 missing values).

• Region: Geographical region of operation (categorical, no missing values).

• Employees: Number of employees involved (numeric, with 150 missing values).

• Industry Type: Type of industry segment (categorical, no missing values; examples: Snacks,
Beverages).

### Full dataset download link
https://drive.google.com/file/d/1eg4yf3LmYdeCUbwpkyj_awoX-ojnUCZp/view

!gdown --id 1eg4yf3LmYdeCUbwpkyj_awoX-ojnUCZp

### Project Guidelines
1. Dataset Quality Check
• Step 1.1: Load the dataset.
– Use Python libraries such as pandas to inspect the dataset.
– Display basic information (e.g., df.info() and df.describe()).
• Step 1.2: Check for missing values.
– Visualize missing data using libraries such as seaborn or missingno.
– Apply appropriate imputation techniques (mean, median, mode, etc.).
• Step 1.3: Check for outliers.
– Use boxplots to detect outliers in numerical columns.
– Apply statistical methods (e.g., Z-score or IQR method) to identify outliers.
– Address outliers through capping, flooring, or removal.
2. Exploratory Data Analysis (EDA)
• Step 2.1: Univariate Analysis.
– Plot histograms, count plots, or boxplots for each variable.
• Step 2.2: Bivariate and Multivariate Analysis.
– Use scatter plots, pair plots, or heatmaps to understand relationships between variables.
• Step 2.3: Derive insights from EDA.
– Summarize key findings in 4-5 points.
3. ANOVA Analysis
• Step 3.1: Define the groups.
– Select a categorical independent variable and a numerical dependent variable.
• Step 3.2: Perform ANOVA.
– Use Python’s scipy.stats library to perform a one-way ANOVA test.
– Interpret the F-statistic and p-value.
• Step 3.3: Document the results.
– Clearly state whether the null hypothesis is accepted or rejected.
4. Linear Regression and Hypothesis Testing
• Step 4.1: Define target (Y) and feature (X) variables.
– Ensure the variables are correctly scaled and encoded if necessary.
• Step 4.2: Build the regression model.
– Use the statsmodels library to create an Ordinary Least Squares (OLS) regression model.
– Evaluate the model summary (e.g., R-squared, coefficients, p-values).
• Step 4.3: Perform hypothesis testing.
– Check the significance of coefficients.
– Verify model assumptions such as normality, homoscedasticity, and absence of multicollinearity.
• Step 4.4: Interpret the results.
– Explain the relationship between the independent and dependent variables.

## Project - 02
File name: **_hypothesis-analysis.ipynb_**

The retail marketing department wants to identify the potential customers who have a higher
probability of purchasing the loan. The dataset contains data on 5000 customers with several
variables.

1. Test the normality (Graphically and Numerically) of the variables Income and comment.
2. Is the average income of customers in the dataset significantly different from $75 thousand?
3. Is the proportion of customers who accepted the personal loan in the last campaign greater
than 40%?
4. Is there a significant difference in the average spending on credit cards (CCAvg) between
customers who accepted the personal loan and those who did not?
5. Is there a significant difference in the average annual income between customers who
accepted the personal loan and those who did not?
6. Is there a significant difference in the proportion of customers who have a credit card versus
those who do not. 

