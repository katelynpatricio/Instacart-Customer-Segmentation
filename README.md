# Understanding Customer Value Drivers & Behavioral Impact: Instacart Segmentation and Regression Analysis

## Project Overview
This capstone project answers the question: *"Which retail levers should be prioritized to maximize customer value?"* It analyzes 3.4 million Instacart orders from 206,209 customers, using K-Means clustering on RFM (Recency, Frequency, Monetary) features to segment customers and cluster-specific Ridge regressions to identify the behaviors associated with reorder rate. Findings support revenue growth, customer retention and engagement, and more targeted marketing.

Capstone project for DATA 480, Nevada State University.

The dataset used for this project can be accessed [here]([https://www.kaggle.com/c/instacart-market-basket-analysis](https://www.kaggle.com/datasets/yasserh/instacart-online-grocery-basket-analysis-dataset)).

---

## Features
- Data merging, exploration, and preparation in R
- Customer-level feature engineering (order volume, reorder rate, basket size, days between orders, cart position, aisle variety)
- Customer segmentation using K-Means clustering on RFM features, with the elbow method used to select k = 4
- Ridge regression by segment, with bootstrap resampling to calculate standard errors and confidence intervals
- Interactive Tableau dashboard for stakeholder use
- Segment-specific marketing and retention recommendations

---

## Tools Used
- **R:** Merge, explore, and prepare data
- **Python:** K-Means customer segmentation (RFM) and Ridge regression analysis
- **Tableau:** Interactive dashboard creation

---

## Tableau Dashboard

**Contents:**
- **Summary Metrics**: Average basket size, number of orders, days between orders, number of aisles, average cart position, and total customers (206,209)
- **Cluster Filter**: View all customers or a single segment (High Value Customers, Frequent Shoppers, Inactive Customers, or Loyal Shoppers)
- **Segment Drivers**: Regression coefficients for number of orders and average basket size by segment
- **Feature Importance**: Ranked regression coefficients for each behavior, color-coded as positive or negative relationships

The interactive workbook is available at [`Instacart_Capstone Dashboard.twbx`]([Instacart Capstone Dashboard.twbx])

---

## Presentation

[View the Presentation]([https://canva.link/mo9gppdgcfkhssm])

**Contents:**
- **Introduction**: Business question and expected impact
- **Data Overview**: Dataset size, unit of analysis, and key fields
- **Methodology**: Customer segmentation, driver analysis, and translating insights into strategy
- **Insights & Recommendations**: Primary value drivers and segment-level actions
- **Limitations & Next Steps**: Data constraints and future work
- **Conclusion**: Key takeaways and business impact

---

## Contact
For questions or feedback, please contact [k.atelynpatricio26@gmail.com].
