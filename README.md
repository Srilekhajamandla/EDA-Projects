# 🦄 Unicorn Data Analysis | Exploratory Data Analysis (EDA)

 This project performs an in-depth Exploratory Data Analysis (EDA) on a global dataset of unicorn startups (companies valued at over $1 billion).

The goal is to identify startup trends, valuation patterns, top industries, regional distribution, and insights that explain how unicorns evolve across the world.

All visualizations, insights, and detailed explanation are included in the project PPT. 

Unicorn Data Analysis PPT - Pha…

## 📊 Dataset Overview

According to the dataset summary in the PPT 

Unicorn Data Analysis PPT - Pha…

:

1070+ rows, 10 columns

Key attributes include:

Company Name

Industry

Country / Region

City

Date Joined

Year Founded

Valuation (in USD billions)

Investors

Employees

#### Objective

Analyze unicorn distribution across industries and countries

Study valuations, time-to-unicorn, investor presence

Understand global startup growth patterns

Identify emerging sectors and regions

##  Data Cleaning & Preprocessing

###🔸 Handling Missing Values  

- Unicorn Data Analysis PPT 

- Missing data mainly in City and Select Investors

- Since missing values were few, they were removed instead of imputed to avoid bias

### 🔸 Handling Duplicates

- Example: Company “Bolt” appeared twice

- Duplicates removed for clean, accurate analysis

### 🔸 Fixing Inconsistencies 

- Valuation column had inconsistent symbols ("$", "B")

- Cleaned using string formatting

- Date Joined converted to proper datetime

- Extracted Year, Month for time trend analysis

###🔸 Outlier Detection 

- Valuation distribution is right-skewed

- Majority startups have moderate valuations

- A few extreme outliers represent tech giants

## 🔍 Exploratory Data Analysis (EDA)

### ⭐ Univariate Analysis 

- Most unicorns are created within 6–10 years

- Huge spike in startups founded after 2010

- Early years (<2000) have very few unicorns

### ⭐ Bivariate Analysis

1. Numerical vs Numerical 

  - Companies founded recently reached unicorn status faster

  - Quarterly valuations for startups joining in 2020 vs 2021

2. Numerical vs Categorical 

  - Faster unicorn formation for companies joining in Oct–Dec

  - USA leads global valuation by a large margin

  - Fintech and Internet Software dominate the unicorn landscape

  - Germany has the highest unicorn valuation among non–Big Four countries

### ⭐ Multivariate Analysis

  - Strong negative correlation (–0.94) between:

  - Year Founded ↔ Years to Unicorn

  - Companies founded later → reach unicorn status faster

  - Valuation has weak correlation with most other variables

### ⭐ Geographical Insights 

  - Germany, Sweden, Australia, France → highest valuation among non–Big Four
  - South Korea, Israel, and Brazil emerging rapidly

  - Global unicorn growth is expanding beyond traditional tech hubs

## 💡 Key Insights 

- Unicorns founded after 2010 are growing exponentially

- New startups reach unicorn status much faster than older ones

- Europe is rising with strong startup ecosystems

- Fintech, E-commerce, AI dominate unicorn creation

- San Francisco, Beijing, London remain global unicorn hubs

## 🏁 Conclusion 

- Global startup ecosystem is evolving rapidly

- Fastest unicorn growth seen in modern tech-driven sectors

- Strong investor confidence driving high valuations

- Emerging markets are becoming significant players

- Innovation + Digital Adoption = Next wave of unicorns

## 🚀 Future Scope 

- Potential next steps:

  - Build an interactive Unicorn Insights Dashboard

  - Develop Unicorn Trend Predictor for sector forecasting

  - Create Funding Pattern Analyzer

  - Build Regional Ecosystem Tracker

  - Implement Sector Intelligence Model

  - Combine all analytics into a Global Startup Intelligence Platform

## 📁 Files Included

- Unicorn Data Analysis PPT - Phase2.pdf → Full EDA explanation with visuals

README.md → Project documentation

## 🛠️ Tools & Skills Used

- Python (EDA)

- Pandas, NumPy

- Matplotlib / Seaborn

- Data Cleaning & Preprocessing

- Statistical Analysis

- Correlation & Trend Analysis
