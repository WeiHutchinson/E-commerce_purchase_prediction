# Customer Behaviour Analysis and Marketing Campaign Impact Assessment

## Business Problem

The marketing team at our startup faces a challenge in optimising customer engagement and increasing sales on our newly launched online shopping platform. With November and December being the busiest months, there is an urgent need to understand customer browsing behaviour to inform future marketing strategies. Specifically, the team requires insights into two key customer segments:

- **Low Purchase Rate Customers:** Customers who engage with the site but rarely make purchases.
- **Returning Customers:** Customers who have previously purchased and returned to the site.

The objective is to analyse these segments, understand their behaviours during the peak shopping months, and estimate the effectiveness of a proposed marketing campaign aimed at increasing their purchase rates.

## Analysis Overview

This project is conducted as part of a DataCamp exercise, focusing on applying data science techniques to solve real-world business problems. The analysis includes the following key components:

### 1. **Customer Segmentation and Behaviour Analysis**

- **Objective:** Identify and analyse the behaviour of low purchase rate customers and returning customers during November and December.
- **Key Metrics Analysed:**
  - **Purchase Rate:** The proportion of sessions that result in a purchase.
  - **Session Duration:** The amount of time customers spend on the site.
  - **Page Interaction:** The types of pages customers interact with (e.g., Administrative, Product-related).
- **Findings:** Returning customers have a lower purchase rate (19.6%) compared to new customers (27.3%), highlighting a need for targeted re-engagement strategies.

### 2. **Correlation Analysis**

- **Objective:** Understand the relationship between different types of page interactions (e.g., Administrative vs. Product-related) and how they relate to purchase behaviour.
- **Methodology:** Calculate correlation coefficients between time spent on different page types.
- **Key Findings:** A moderate correlation (0.39) exists between time spent on Administrative and Product-related pages, suggesting that customers who engage with account management are also more likely to browse products.

### 3. **Campaign Impact Estimation**

- **Objective:** Estimate the likelihood of achieving specific sales targets under a new marketing campaign aimed at returning customers.
- **Methodology:** 
  - **Baseline Analysis:** Use the current purchase rate of returning customers as a baseline.
  - **Scenario Simulation:** Apply a binomial distribution model to estimate the probability of reaching at least 100 sales out of 500 sessions with a projected 15% increase in purchase rate.
- **Results:**
  - **Increased Purchase Rate:** If the campaign increases the purchase rate to 22.5%, there is a 90.1% probability of achieving at least 100 sales out of 500 sessions.
  - **Business Insight:** The high probability suggests that the campaign has strong potential for success, providing a solid foundation for marketing strategy.

## Recommendations

1. **Targeted Campaign for Returning Customers:**
   - Implement loyalty programmes, personalised offers, and cart reminders to re-engage returning customers and boost conversion rates.

2. **Monitor and Adjust Campaign Strategy:**
   - Proceed with the campaign but set realistic goals and closely monitor performance to make necessary adjustments.

3. **Enhance Customer Experience:**
   - Improve the user experience on administrative pages by adding features like product recommendations based on past purchases to encourage further browsing and purchasing.

## Conclusion

This analysis addresses the key business problem by providing insights into customer behaviour and offering data-driven recommendations for a targeted marketing campaign. By focusing on re-engaging returning customers and optimising their interaction with the platform, we can drive significant sales growth and improve customer loyalty during peak shopping periods.

---

*This project is part of a DataCamp exercise designed to apply data science techniques to solve real-world business problems. For further details, data, and code, please refer to the project files in this repository. If you have any questions or need additional insights, feel free to reach out.*
