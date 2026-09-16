🚕 Smart Mobility & Ride Analytics

📌 Project Overview

Smart Mobility & Ride Analytics is a Data Science portfolio project focused on analyzing a real-world ride-hailing dataset using Python, Mathematics for Data Science, Probability, Statistics, and Hypothesis Testing.

The project investigates ride distance, fare amount, ride category, surge pricing, customer ratings, and peak/non-peak ride periods to identify relationships, patterns, anomalies, and statistically supported business insights.

The project is based on a Trip Analysis dataset containing 200 ride records and 6 variables.

Project Type: Data Science / Statistical Analysis / Business Analytics
Level: Beginner to Intermediate, with inferential statistics components
Primary Tool: Python & Jupyter Notebook

🎯 Business Problem

Ride-hailing companies generate large amounts of trip-level data. Understanding this data can help analyze:

How trip distance is related to fare

Whether premium rides have significantly higher fares

Whether surge pricing is associated with customer ratings

Whether peak-hour rides generate different revenue

Whether unusual fare values indicate possible anomalies

How ride demand probabilities differ across ride categories

Which operational factors are most strongly associated with fare/business performance

Whether statistical evidence can support pricing or service improvements

The objective of this project is to use quantitative methods rather than assumptions to investigate these questions.

📊 Dataset

Dataset: Trip_Analysis.xlsx

Dataset Dimensions

Rows: 200

Columns: 6

Features

Feature

Description

Trip_Distance

Distance travelled during the trip

Fare_Amount

Fare charged for the trip

Ride_Category

Category of ride such as Economy, Premium, or Shared

Surge_Multiplier

Surge pricing multiplier applied to the ride

Customer_Rating

Customer rating associated with the ride

Ride_Time

Peak or Non-Peak ride period

🧠 Analysis Performed

1. Data Preparation

The dataset is loaded and prepared using NumPy and Pandas.

Steps include:

Loading the Excel dataset

Checking dataset shape and structure

Removing duplicate records

Identifying numerical and categorical columns

Handling missing numerical values using the median

Handling missing categorical values using the mode

2. Mathematical Modeling – Linear Algebra

Linear algebra concepts are applied to the ride data:

Feature vectors

Vector magnitude

Correlation matrices

Matrix dimensions

Matrix determinant

Eigenvalues

Eigenvectors

Dot product

These techniques are used to understand the mathematical structure and relationships within the numerical features.

3. Probability Analysis

The project applies:

Basic probability

Conditional probability

Bayes' theorem

Probability distributions

Examples include:

Probability of each ride category

Probability of Premium rides given Peak time

Probability of Peak rides given Premium category

Probability of ride categories when surge pricing is greater than 1

Bayesian estimation of ride-category probabilities

4. Descriptive Statistics

The following statistical measures are calculated for key numerical variables:

Mean

Median

Mode

Variance

Standard deviation

Skewness

Kurtosis

The analysis focuses on:

Trip Distance

Fare Amount

Surge Multiplier

Customer Rating

5. Outlier & Anomaly Detection

Fare values are analyzed for unusual observations using:

Percentiles

Quartiles

Interquartile Range (IQR)

Z-score

The analysis calculates:

Q1

Median

Q3

IQR

Lower and upper IQR bounds

IQR-based outliers

Z-score-based outliers

This can help identify unusual fares that may require further investigation.

6. Relationship Analysis

Relationships between variables are examined using:

Pearson correlation

Spearman correlation

Covariance

Examples:

Trip Distance ↔ Fare Amount

Surge Multiplier ↔ Customer Rating

Operational variables ↔ Fare Amount

7. Inferential Statistics

The project applies inferential statistical techniques including:

Point estimation

95% confidence intervals

Central Limit Theorem (CLT)

Bootstrapping

Bootstrap confidence intervals

Bootstrapping is performed using repeated resampling to estimate the sampling distribution of the mean fare.

8. Hypothesis Testing

The notebook demonstrates several statistical tests:

Z-test

Independent t-test

Chi-square test

F-test

One-way ANOVA

A/B-style comparison of Peak vs Non-Peak rides

A significance level of:

α = 0.05

is used for hypothesis-testing decisions.

🔍 Key Business Questions

The project investigates eight major questions:

Q1. Does trip distance significantly affect fare amount?

Methods:

Pearson correlation

Covariance

Dot product

Linear algebra interpretation

Q2. Are Premium rides statistically more expensive than Economy rides?

Methods:

Descriptive statistics

Independent t-test

ANOVA

Q3. Is there a relationship between surge pricing and customer ratings?

Methods:

Spearman correlation

Statistical significance testing

Q4. Do Peak-hour rides differ in revenue compared with Non-Peak rides?

Methods:

Mean comparison

Independent t-test

Q5. Are there unusual fare values that may indicate anomalies or pricing errors?

Methods:

Percentiles

Quartiles

IQR

Z-score

Q6. Can ride demand probabilities be estimated for different ride categories?

Methods:

Basic probability

Conditional probability

Bayes' theorem

Q7. Which operational factors are most strongly related to business performance?

Methods:

Pearson correlation

Spearman correlation

Covariance

Eigenvalue/eigenvector analysis

Q8. Can statistical evidence support pricing or service improvements?

Methods:

Confidence intervals

Bootstrapping

Hypothesis testing

🛠️ Technologies & Libraries

Programming Language

Python

Libraries

NumPy – numerical computing and linear algebra

Pandas – data loading, cleaning, transformation, and analysis

Matplotlib – data visualization

Seaborn – statistical visualization

SciPy – statistical tests and statistical calculations

Jupyter Notebook – interactive analysis and documentation

📁 Project Structure

Smart-Mobility-Ride-Analytics/
│
├── Smart_Mobility_&_Ride_Analytics.ipynb
├── Trip_Analysis.xlsx
├── README.md
└── requirements.txt

⚙️ Installation & Setup

1. Clone the repository

git clone <your-github-repository-url>
cd Smart-Mobility-Ride-Analytics

2. Create a virtual environment

python -m venv venv

3. Activate the environment

Windows:

venv\Scripts\activate

Linux/macOS:

source venv/bin/activate

4. Install dependencies

pip install numpy pandas matplotlib seaborn scipy openpyxl jupyter

5. Launch Jupyter Notebook

jupyter notebook

Open:

Smart_Mobility_&_Ride_Analytics.ipynb

and run the cells sequentially.

📈 Portfolio Skills Demonstrated

This project demonstrates practical skills in:

Data cleaning

Exploratory data analysis

NumPy

Pandas

Data visualization

Linear algebra

Probability

Bayes' theorem

Descriptive statistics

Outlier detection

Correlation analysis

Covariance analysis

Inferential statistics

Confidence intervals

Bootstrapping

Central Limit Theorem

Hypothesis testing

Business interpretation

Evidence-based decision making

💡 Project Outcome

The final notebook is designed to connect statistical calculations with real business questions.

Instead of only calculating statistical values, the analysis interprets whether the observed relationships or differences provide statistical evidence relevant to:

Pricing analysis

Ride-category strategy

Peak-hour operations

Surge pricing

Customer experience

Fare anomaly detection

Service improvement

⚠️ Notes & Limitations

The dataset contains 200 records, so findings should be interpreted within the scope of this sample.

Statistical significance does not automatically establish causation.

Correlation should not be interpreted as proof that one variable causes another.

Detected fare outliers are indicators for investigation, not automatically confirmed pricing errors.

The notebook uses random resampling for CLT and bootstrap demonstrations, so exact bootstrap outputs can vary between runs unless a random seed is fixed.

Business recommendations should be validated with additional operational and customer-level data before production use.

🚀 Future Improvements

Possible extensions for this project include:

Add an interactive Power BI / Tableau dashboard

Perform deeper Exploratory Data Analysis (EDA)

Build a fare prediction model using Machine Learning

Compare multiple regression models

Add feature engineering

Analyze ride demand by time/category

Build a classification model for ride categories

Perform cross-validation

Add statistical effect sizes

Automate the analysis pipeline

Deploy the project as a Streamlit application

👨‍💻 About the Project

This project was developed as part of a Data Science learning portfolio to demonstrate the practical application of mathematical and statistical concepts to a real-world business analytics problem.

Focus: Data Science | Statistics | Probability | Business Analytics | Python

⭐ If You Find This Project Useful

If this project helped you understand statistical analysis in Python, feel free to star ⭐ the repository and explore the notebook.
