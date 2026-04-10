# E-Commerce Customer Churn Analysis

## Project Overview
This project analyzes customer churn behavior for an e-commerce company using Microsoft Excel.
The goal is to identify key factors driving customer churn and provide actionable business recommendations to improve customer retention.

## Dataset
- **Source:** [Kaggle - E-Commerce Customer Churn Dataset](https://www.kaggle.com/datasets/ankitverma2010/ecommerce-customer-churn-analysis-and-prediction)
- **Size:** 5,630 customers, 20 features
- **Churn Rate:** 16.8%

## Tools Used
- Microsoft Excel (Pivot Tables, AVERAGEIF, COUNTIF, XLOOKUP, Dashboard)

## Project Structure
| Sheet | Description |
|---|---|
| Raw Data | Original dataset (protected) |
| Cleaned Data | Missing values handled, helper columns added |
| Summary Stats | Churn vs Retained comparison |
| Pivot Analysis | Churn analysis across 6 dimensions |
| Dashboard | Visual summary with KPI cards and charts |
| Insights | Key findings and business recommendations |

## Data Cleaning
- 7 columns had missing values (total ~1,856 missing entries)
- Missing values filled using **median imputation**
- Added helper columns: `Tenure_Group` and `Cashback_Segment`

## Key Findings

| # | Finding | Data |
|---|---|---|
| 1 | New customers are at high churn risk | 0-6 month customers: 32% churn vs 24+ months: 0% |
| 2 | Complaining customers churn 3x more | Complain: 32% vs No Complain: 11% |
| 3 | Low cashback customers are at high risk | Low: 26% vs High: 5% |
| 4 | Single customers churn 2x more than married | Single: 27% vs Married: 12% |
| 5 | Mobile app users are more loyal | Mobile Phone: 13% vs Phone: 22% |
| 6 | Mobile product category has highest churn | ~28% churn rate |

## Business Recommendations
1. Launch a special onboarding program for customers in their first 6 months
2. Guarantee 24-hour complaint resolution to reduce churn risk
3. Expand cashback program targeting the Low segment
4. Design loyalty campaigns specifically for single customers
5. Encourage customers to use the mobile app with app-exclusive offers
6. Conduct competitive price analysis for the mobile product category

## Data Quality Note
The `PreferedOrderCat` column contains two separate entries — "Mobile" and "Mobile Phone" — which likely represent the same product group. This inconsistency was flagged and noted in the analysis.

## Contact
Feel free to connect with me on [LinkedIn] (www.linkedin.com/in/melike-n-a97480390) if you have any feedback or questions!
