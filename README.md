# Home Purchasing Forecast 
**Overview:** Studying the effects of including household income, student loan debt, mortgage rates and price of homes on homebuying rates in the U.S. between late 1900's and early/mid 2000's. By analyzing the effect of these key factors on the housing market we will be able to forecast a homebuying trend for a future decade based key factors that is most correlated with historic home purchases. 

**Table of Contents (maybe)**
1. Dependecies
2. Installation Instructions
3. Features
4. Acknowledgements

**Dependencies:**
1. Pandas
2. Matplotlib.pyplot
3. Sklearn.linear_model
    LinearRegression 
5. Numpy
6. Datetime
7. Scipy.stats
   Linregress 

**Installation Instructrions:**
* Clone repository locally
* Activate dev enviornment via Anoconda
* Open project with Jupyter Notebook 

**Features**
Correlations between Homebuying and
      1. Household Income
      2. Mortage Rates
      3. Student Loan Debt
      4. Price of Homes 
**Acknowledgements**
Datasets were sourced from: 
* `MEHOINUSA672N.csv` : https://fred.stlouisfed.org/series/MEHOINUSA672N
* `average_number_of_house_sold_by_year_output.csv`
* `average_student_loan_debt.csv`
 


#Isfund Akram Task : Housing Market Analysis with Student Loan Debt

My task was to analyze the relationship between student loan debt and the number of homes sold over the years. The data includes average student loan debt and average number of homes sold by year.

I used two datasets:
1. `average_number_of_house_sold_by_year_output.csv`: Contains the average number of homes sold per year (in thousands) from 1963 to 2023.
2. `average_student_loan_debt.csv`: Contains the average student loan debt for graduating classes from 1993 to 2023.

My analysis includes the following steps:
1. Gathering data and create CSV files 
2. Loading the data from CSV files into pandas DataFrames.
3. Descriptive Statistics: Calculating the mean, median, standard deviation, and other descriptive statistics for both datasets.
4. Correlation Analysis: Performing a correlation analysis between the average student loan debt and the average number of homes sold per year.
5. Regression Analysis: Performing simple linear regression analysis between average student loan debt and the average number of homes sold per year.
6. Visualization: Creating various plots to visualize the data, including:
      - Line graph showing the number of homes sold over the years with student loan debt and a regression line.

 I merged the datasets on the year columns to align the data for analysis. Converted the Average Student Loan Debt to a numeric type for analysis.

