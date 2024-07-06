# Walmart Customer Purchase Analysis

## Introduction

Walmart, an American multinational retail corporation, operates a chain of supercenters, discount departmental stores, and grocery stores. With a customer base exceeding 100 million worldwide, Walmart's management team seeks to understand customer purchase behavior, specifically examining if spending habits differ between male and female customers during Black Friday sales. The study aims to provide actionable insights to enhance business decisions.

## Business Problem

The primary objective is to analyze whether there is a significant difference in the purchase amounts between male and female customers. The secondary goals include understanding spending patterns across different demographic groups, such as marital status and age categories.

## Dataset

The dataset consists of transactional data from customers who purchased products during Black Friday sales at Walmart. The key features include:

- **User_ID**: Unique identifier for each customer
- **Product_ID**: Unique identifier for each product
- **Gender**: Customer's gender
- **Age**: Customer's age group
- **Occupation**: Customer's occupation (masked)
- **City_Category**: Category of the city (A, B, C)
- **StayInCurrentCityYears**: Number of years the customer has stayed in the current city
- **Marital_Status**: Customer's marital status
- **ProductCategory**: Product category (masked)
- **Purchase**: Purchase amount

## Steps and Methodology

### 1. Data Import and Initial Analysis
- Import the dataset and perform an initial examination to understand its structure and characteristics.
- Check for null values and outliers using techniques like box plots and descriptive statistics.

### 2. Data Exploration
- Analyze the amount spent per transaction by all 50 million female customers and all 50 million male customers.
- Calculate the average spending and infer the results.

### 3. Confidence Interval and Central Limit Theorem
- Use sample averages to find an interval within which the population average will lie.
- Apply the Central Limit Theorem (CLT) to compute this interval, altering the sample size to observe distribution changes.
- Calculate the confidence interval for the average spending of male and female customers at different confidence levels (90%, 95%, 99%).

### 4. Comparative Analysis
- Examine if the confidence intervals of average male and female spending overlap.
- Perform similar analysis for different demographics: married vs. unmarried customers, and various age groups (0-17, 18-25, 26-35, 36-50, 51+ years).

### 5. Visual and Statistical Analysis
- Utilize visual tools such as histograms, count plots, box plots, and heatmaps for univariate and bivariate analysis.
- Conduct non-graphical analysis like value counts and unique attribute identification.

### 6. Insights and Recommendations
- Derive insights based on the exploration and application of the CLT.
- Provide actionable recommendations for Walmart to leverage these insights for business improvements.

## Results and Insights

### Gender-Based Spending
- Determine if women spend more per transaction than men and explore possible reasons.
- Analyze the overlap of confidence intervals for male and female spending and interpret the implications.

### Marital Status and Age Group Analysis
- Investigate spending patterns for married vs. unmarried customers and across different age groups.
- Offer insights into how these demographic factors influence spending behavior.

## Recommendations

Based on the analysis, provide simple, actionable recommendations for Walmart to enhance customer engagement and optimize sales strategies. Ensure that the suggestions are devoid of technical jargon, making them easily understandable and implementable by the business team.

## Conclusion

Summarize the findings and their potential impact on Walmart's business decisions. Highlight key insights and recommended actions to improve customer satisfaction and drive sales growth during Black Friday and other sales events.

