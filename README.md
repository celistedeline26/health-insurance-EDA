# Health-Insurance-EDA
Exploratory data analysis of health insurance data using Python

## Project Overview
This project performs exploratory data analysis (EDA) on a health insurance dataset to identify key factors influencing medical insurance charges. The analysis demonstrates data cleaning, statistical exploration, correlation analysis, and data visualisation using Python.

## Business Context
Health insurance providers need to understand the main drivers of medical costs in order to price insurance plans accurately, manage risk, and design targeted health interventions.

## Business Questions
- Which demographic factors are associated with higher insurance charges?
- How does smoking status impact medical costs?
- Is there a relationship between BMI and insurance charges?
- Are there regional differences in insurance costs?

## Dataset Used
The dataset used in this project is the Medical Cost Personal Dataset obtained from Kaggle. It contains anonymised records of health insurance customers, including demographic information, lifestyle factors, and medical insurance charges.

Key variables include:
- Age
- Sex
- Body Mass Index (BMI)
- Number of children
- Smoking status
- Region
- Insurance charges

---

## Data Cleaning & Preparation
The dataset was inspected and cleaned prior to analysis. Key data preparation steps included:
- Checking for missing and null values
- Verifying and correcting data types
- Renaming columns for clarity and consistency
- Identifying potential outliers in numerical variables
- Ensuring categorical variables were correctly formatted for analysis

These steps ensured the dataset was suitable for exploratory and statistical analysis.

---

## Exploratory Data Analysis (EDA)
Exploratory analysis was conducted to understand the distribution of variables and identify patterns in insurance charges. This included:
- Summary statistics for numerical variables
- Distribution analysis using histograms and boxplots
- Grouped comparisons (e.g. smokers vs non-smokers)
- Analysis of insurance charges across age groups and regions

Visualisations were used to support interpretation and identify meaningful trends.

---

## Correlation Analysis
Correlation analysis was performed to examine relationships between numerical variables such as age, BMI, number of children, and insurance charges. A correlation matrix was used to identify variables with strong or moderate associations with insurance costs.

---

## Statistical Hypothesis Testing
An independent two-sample t-test was conducted to compare the mean insurance charges between smokers and non-smokers. The test results showed a statistically significant difference in average charges, indicating that smoking status has a substantial impact on insurance costs.

---

## Key Findings & Insights
These findings are based on exploratory data analysis and descriptive statistics and indicate associations rather than causal relationships.
- Smoking status is the strongest driver of higher insurance charges.
- Insurance costs generally increase with age.
- BMI shows a moderate relationship with insurance charges, particularly among smokers.
- Regional differences exist but are less significant than lifestyle factors.

---

## Business Implications & Recommendations
Based on the analysis, the following insights may support business decision-making:
- Insurance providers may consider smoking status as a key risk factor in pricing strategies.
- Preventative health initiatives targeting high-BMI individuals could help reduce long-term costs.
- Age-based pricing models may be refined using additional health indicators.

---

## Limitations
- The analysis is exploratory and does not establish causal relationships.
- The dataset represents a limited population and may not generalise to all insurance customers.
- Some potentially important health factors (e.g. medical history, exercise habits) are not included.
- Outliers may influence summary statistics and visual interpretations.

---

## Tools & Technologies
- Python (pandas, numpy, matplotlib, seaborn)
- Jupyter Notebook
- GitHub
- Tableau Public (for dashboard visualisation)

---

## Tableau Dashboard
A Tableau dashboard was created to visualise key insights from the analysis.  
🔗 Tableau Public link will be added.

---

## Project Files
- 📓 [EDA Notebook](notebooks/health_insurance_eda.ipynb) – Data cleaning and analysis
- 📁 [Dataset](data/insurance.csv) – Raw insurance data
