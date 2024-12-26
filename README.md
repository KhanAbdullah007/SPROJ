Project: Impact of Digital Literacy on Financial Outcomes – A Cross-Country Analysis

Dataset Overview: This study utilized aggregated data from 82 countries, focusing on 2021, to investigate the relationship between digital literacy and financial outcomes. Key data sources included:
  World Bank: Provided metrics on digital literacy, financial inclusion, and perceived financial well-being.
  Meta's Data for Good: Supplied control variables for cross-country comparisons.
  ITU Internet Inclusivity Index: Offered insights into digital skills and infrastructural variables.
  
Data Preparation:
  Timeframe: Data from 2010–2023 was cleaned and filtered to focus on 2021 for consistency.
  Missing Data: Addressed using imputation techniques, including K-Nearest Neighbors (KNN).
  Variable Selection: Key variables were grouped into digital literacy metrics, financial inclusion indicators, and financial outcomes (e.g., "worried index").
  Dimensionality Reduction: Principal Component Analysis (PCA) was applied to condense financial outcome variables into meaningful indices.

Exploratory Data Analysis:
  Patterns were examined across income levels and regions, highlighting disparities in internet access, education, and digital literacy.
  Variables such as internet banking skills showed strong correlations with financial confidence and well-being.
  
Modeling Approaches:
  Ordinary Least Squares (OLS): Explored linear relationships between digital literacy and financial outcomes, controlling for socioeconomic variables.
  Random Forest: Identified non-linear relationships and feature importance in predicting financial outcomes.

