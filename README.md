# BCG Data Science Virtual Internship (Forage)

## Project Overview

This project was completed as part of the BCG Data Science Virtual Internship on Forage. The objective was to analyze customer churn behavior for PowerCo, a European utility company, and identify the key factors influencing customer retention.

The project involved exploratory data analysis, feature engineering, predictive modeling, and business recommendations to support customer retention strategies.

---

## Problem Statement

PowerCo was experiencing customer churn and believed that price sensitivity was the primary reason customers were leaving.

The goal of this project was to:

- Analyze customer and pricing data
- Identify major churn drivers
- Build a machine learning model to predict churn
- Provide actionable business recommendations

---

## Project Structure

```bash
├── csv/                
├── docx/           
├── notebooks/         
├── tasks/
├── certificate_bcg.pdf          
├── README.md
├── summary.png
```

---

## Key Steps Performed

### 1. Exploratory Data Analysis (EDA)

- Analyzed customer and pricing datasets
- Studied missing values, distributions, and churn patterns
- Explored relationships between pricing and customer churn
- Identified that price sensitivity alone was not the strongest churn driver

#### Key Findings

- Churn rate was approximately 10%
- Customer behavior and account activity had stronger influence on churn
- Certain sales channels showed higher churn patterns

---

### 2. Feature Engineering

Created new features to improve predictive performance.

### Features Created

- 6-month and yearly price sensitivity
- Price volatility metrics
- Consumption behavior features
- Customer tenure metrics
- Contract duration features
- Gas subscription indicator

### Data Preparation

- One-hot encoded categorical variables
- Applied log transformation to skewed numerical features
- Prepared dataset for machine learning modeling

---

### 3. Model Building

Built predictive machine learning models to identify customers likely to churn.

### Models Used

- Logistic Regression
- Random Forest Classifier

### Techniques Applied

- Train-test split
- Feature importance analysis
- Addressed class imbalance using:

```python
class_weight='balanced'
```

---

## Model Insights

### Key Findings-1

- Price is not the primary driver of churn
- Net margin and electricity consumption were stronger predictors
- Customer acquisition channel (`origin`) had significant influence
- Customers with multiple services showed higher retention
- New customers had higher churn probability

### Top Predictive Factors

- Net margin
- Electricity consumption
- Customer tenure
- Product subscription type
- Account activity duration

---

## Business Recommendations

- Focus retention efforts on high-risk customer segments
- Improve onboarding experience for new customers
- Use predictive models for proactive churn prevention
- Promote bundled services to increase customer loyalty
- Apply targeted pricing strategies instead of blanket discounts

---

## Business Impact

This project helps businesses:

- Identify churn-risk customers early
- Improve customer retention strategies
- Increase customer lifetime value
- Reduce revenue loss from customer churn
- Optimize marketing and discount spending

---

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

---

## Learning Outcomes

Through this project, I gained practical experience in:

- Exploratory Data Analysis
- Feature Engineering
- Machine Learning Modeling
- Predictive Analytics
- Business Problem Solving
- Data-Driven Decision Making

---

## Conclusion

This project demonstrates how machine learning and business analytics can be used to solve real-world customer retention problems. It highlights the importance of combining technical analysis with business understanding to generate actionable insights.

---

## Acknowledgment

This project was completed as part of the BCG Data Science Virtual Experience Program offered by Forage.
