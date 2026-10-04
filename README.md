# Understanding Customer Value Drivers & Behavioral Impact: Instacart Segmentation and Regression Analysis

## Project Overview
This capstone project answers the question: *"Which retail levers should be prioritized to maximize customer value?"* It analyzes 3.4 million Instacart orders from 206,209 customers, using K-Means clustering on RFM (Recency, Frequency, Monetary) features to segment customers and cluster-specific Ridge regressions to identify the behaviors associated with reorder rate. Findings support revenue growth, customer retention and engagement, and more targeted marketing.

Capstone project for DATA 480, Nevada State University.

The dataset used for this project can be accessed [here](https://www.kaggle.com/c/instacart-market-basket-analysis).

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

![Dashboard preview](dashboard/dashboard_preview.png)

The interactive workbook is available at [`dashboard/Instacart_Dashboard.twbx`](dashboard/Instacart_Dashboard.twbx). Download it and open it with Tableau Desktop or the free [Tableau Public Desktop](https://www.tableau.com/products/public/download).

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
