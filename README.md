# Kanchan Bansode - Data Analyst Portfolio
## About
Hi, I'm Kanchan Bansode! I have a background in mechanical engineering, with both a diploma and bachelor's degree in the field. Currently, I am pursuing my master’s in Data Analytics in Berlin, Germany, where I’m developing strong skills in data science and analytics.

My journey has allowed me to bridge the gap between technical engineering knowledge and data analysis, which I find both challenging and rewarding. I’m excited to leverage my technical foundation along with my analytical abilities in data analytics. I am particularly interested in applying my skills to extract actionable insights and contribute to data-driven decision-making.

In my free time, I enjoy exploring new analytical tools and deepening my understanding of machine learning and data visualization techniques. I am eager to make an impact in the field of data analytics and bring my unique perspective to solving complex problems through data.

My CV in [pdf](https://github.com/Kanchan-Bansode/Data-Analyst-Portfolio/blob/main/Base%20CV.pdf)

This is a repository to showcase skills, share projects and track my progress in Data Analytics / Data Science related topics.

## Table of Contents

- [About](https://github.com/Kanchan-Bansode/Data-Analyst-Portfolio/blob/main/README.md#about)
- [Portfolio Projects](https://github.com/Kanchan-Bansode/Data-Analyst-Portfolio/blob/main/README.md#portfolio-projects)
  - Python
    - [Adidas Store Sales Analysis](https://github.com/Kanchan-Bansode/Data-Analyst-Portfolio/blob/main/README.md#adidas-store-sales-analysis)
    - [HSBC Bank Fraud Analysis](https://github.com/Kanchan-Bansode/Data-Analyst-Portfolio/blob/main/README.md#hsbc-bank-fraud-analysis)
  - SQL
    - [Housing Data Cleaning](https://github.com/Kanchan-Bansode/Data-Analyst-Portfolio/blob/main/README.md#housing-data-cleaning)
    - [Covid 19 Data Exploration](https://github.com/Kanchan-Bansode/Data-Analyst-Portfolio/blob/main/README.md#covid-19-data-exploration)
  - Excel / Google Sheets
  - Tableau ---> [go to Tableau..](https://public.tableau.com/app/profile/kanchan.bansode6882/vizzes)
  - Power BI ---> [go to Power BI..](https://github.com/Kanchan-Bansode/Portfolio_Projects/tree/main/Power%20BI)
  


- [Education](https://github.com/Kanchan-Bansode/Data-Analyst-Portfolio/blob/main/README.md#education)  
- [Certificates](https://github.com/Kanchan-Bansode/Data-Analyst-Portfolio/blob/main/README.md#certificates)
- [Contact](https://github.com/Kanchan-Bansode/Data-Analyst-Portfolio/blob/main/README.md#contacts)
## Portfolio Projects
In this section I will list data analytics projects briefly describing the technology stack used to solve cases.

### Adidas Store Sales Analysis
**Code:** [`Adidas Store Sales Analysis.ipynb`](https://github.com/Kanchan-Bansode/Portfolio_Projects/blob/main/Adidas_Retail_Sales_Analysis.ipynb)

**Goal:** To perform exploratory data analysis (EDA) on the Adidas US retail dataset to evaluate sales performance, identify trends, and provide actionable insights for business decisions.

**Description:** This project utilizes the Adidas US sales dataset, which includes columns such as retailer information, sales data, product details, and regional distribution. The analysis encompasses data cleaning, preprocessing, and answering business-specific questions to uncover trends and opportunities. Key operations include exploring relationships between variables, calculating metrics like average operating margins, and visualizing trends across regions, retailers, and products.

**Skills:** Data cleaning, exploratory data analysis (EDA), data visualization, statistical analysis, and deriving business insights.

**Technology:** Python, Pandas, Numpy, Matplotlib, Seaborn.

**Results:** 

 - Identified total sales and operating profit trends across regions, highlighting the West region as a top performer.
 - Analyzed the impact of sales methods, with in-store sales outperforming online channels.
 - Determined the most popular products sold by each retailer, with "Men's Street Footwear" being the highest-selling category.
 - Visualized average operating margins across all product categories, pinpointing the most profitable items.
 - Explored the correlation between price per unit and total sales, revealing a positive relationship.
 - Evaluated average price per unit across cities to identify price-sensitive markets.
 - Ranked the top 10 retailers by total sales, offering insights into key partnerships and advertising strategies.

**Business Questions Addressed:**

 - How sales methods impact total sales.
 - The trend of sales and operating profit across regions.
 - The most popular products for each retailer.
 - Average operating margins for products sold across retailers.

### HSBC Bank Fraud Analysis

**Goal:** To build a machine learning pipeline for detecting fraudulent banking transactions at HSBC using Random Forest, SVM, and Decision Tree models.

**Code:** [`HSBC Bank Fraud Analysis.ipynb`](https://github.com/Kanchan-Bansode/Portfolio_Projects/blob/main/HSBC_Bank_Fraud_Detection.ipynb)

**Description:** The project aimed to develop predictive models that can identify fraudulent transactions in real-time by analyzing historical banking data. The goal was to create accurate and efficient models to help HSBC prevent fraud and secure customer data.

**Skills:** Data cleaning, data analysis, data visualization, supervised machine learning, model evaluation, feature engineering, performance metrics analysis.

**Technology:** Python, Pandas, Numpy, Seaborn, Matplotlib, Scikit-learn (Random Forest, SVM, Decision Tree).

**Results:** The Random Forest model achieved 99.52% accuracy, proving to be the most effective for detecting fraud, while SVM and Decision Tree models showed promising but less optimal results. The pipeline helps HSBC by identifying fraudulent transactions early, minimizing financial losses, and improving security measures for customer data.



### Housing Data Cleaning
**Code:** [`Housing Data Cleaning.sql`](https://github.com/Kanchan-Bansode/Portfolio_Projects/blob/main/Housing%20Data%20Cleaning.sql)

**Description:** This project analyzes a dataset of houses sold in Nashville from 2013 to 2019. It involves critical steps such as data loading, cleaning, and preprocessing to ensure data readiness for analysis.


**Skills:** Data Manipulation Language (DML), Data Query Language (DQL), Data Definition Language (DDL).

**Technology:** SQL Server

**Summary of Findings:**

 - Property and owner addresses were split into separate components (Address, City, State) for improved granularity.
 - Missing property addresses were populated using related records.
 - Data Integrity Improvements: Standardized date formats, converted binary "Y/N" values to more intuitive "Yes/No" labels.
 - Identified and removed duplicate records based on key attributes such as Parcel ID and Sale Price.
 - Dropped unused columns (e.g., TaxDistrict, OwnerAddress) to streamline the dataset for analysis.

**Limitations:**

 - Some records had missing addresses or inconsistent formats, requiring assumptions during imputation.
 - Data preprocessing relied on parsing patterns, which might not account for edge cases.
 - Dropped columns could limit further analysis if those fields are later deemed useful.


### Covid 19 Data Exploration
**Code:** [`Covid 19 Data Exploration.sql`](https://github.com/Kanchan-Bansode/Portfolio_Projects/blob/main/Covid19_DataExploration.sql)

**Description:** The dataset contains records of Covid-19 cases, deaths, and vaccine records by country in 2020-2021. This project includes the following steps: data loading, data cleaning and preprocessing, and exploratory data analysis (EDA).

**Skills:** Joins, CTEs, Temp Tables, Windows Functions, Aggregate Functions, Creating Views, Converting Data Types.

**Technology:** SQL Server

**Summary of Findings:**

 - Identified regions with the highest death counts per population, providing insights into pandemic severity.
 - Analyzed countries with the highest infection rates and death counts.
 - Explored vaccination rates by country, highlighting the global progress in vaccination campaigns.
 - Calculated infection percentages for each country, giving a comparative view of infection rates globally.

**Limitations:**

 - Some records included null or invalid values, which were excluded during analysis.
 - Variations in reporting standards and testing rates among countries could introduce biases in the results.






## Education
Berlin School of Buisness and Innovation, Berlin, Germany: 
Master of Science - MSc, Data Analytics,
Oct 2023 - Jul 2025 

Rajiv Gandhi Institute of Technology, Mumbai, India:
Bachelor's degree, Mechanical Engineering,
Oct 2020 - May 2023

Diploma:
Level 4 Diploma Course, Mechanical Engineering,
Aug 2017 - Jan 2020

## Certificates
The best way to showcase skills is by doing and sharing your job done but sometimes certificates appear to be as an indirect result. Here's a list of the ones I have (in reverse-chronological order, with the date of completion in brackets):
- [Data Analysis & Visualization with Power BI ]() (Coursera - Microsoft)
- [Data Analysis with Python Certificate]() (Coursera - IBM)
- [Microsoft Office Specialist: Excel Associate (Office 2019)]() (Jan 2024)

## Contacts
- LinkedIn: [@KanchanBansode](https://www.linkedin.com/in/kanchan-bansode)
- Email: kanchanbansode30@gmail.com
