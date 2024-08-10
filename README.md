# **Will This Customer Purchase Your Product?**
## **Project Overview**
This project, based on a DataCamp exercise with further explorations, focuses on analysing online shopping behaviours of new and returning customers. The primary aim is to understand the differences in browsing habits and shopping patterns between these two customer groups. The insights generated from this analysis are intended to help the marketing team optimise strategies for customer engagement and predict future purchasing behaviour.

## **Data Description**
The analysis uses a dataset containing information about online shopping sessions over the past year. Each session corresponds to a unique user and includes various details such as the number of pages visited, time spent on different page types, and whether a purchase was made.

## Columns
#### <p>**SessionID** : Unique session ID.<p>
#### <p> **Administrative** : Number of pages visited related to the customer account.<p>
#### <p>**Administrative_Duration** : Total amount of time spent (in seconds) on administrative pages.<p>
#### <p>**Informational** : Number of pages visited related to the website and the company.<p>
#### <p>**Informational_Duration**: Total amount of time spent (in seconds) on informational pages.<p>
#### <p>**ProductRelated**: Number of pages visited related to available products.<p>
#### <p>**ProductRelated_Duration**: Total amount of time spent (in seconds) on product-related pages.<p>
#### <p>**BounceRates**: Average bounce rate of pages visited by the customer.<p>
#### <p>**ExitRates**: Average exit rate of pages visited by the customer.<p>
#### <p>**PageValues**: Average page value of pages visited by the customer.<p>
#### <p>**SpecialDay**: Closeness of the site visiting time to a specific special day.<p>
#### <p>**Weekend**: Indicator of whether the session is on a weekend.<p>
#### <p>**Month**: Month of the session date.<p>
#### <p>**CustomerType**: Type of customer (New_Customer or Returning_Customer).<p>
#### <p>**Purchase**: Whether the customer made a purchase (1 for yes, 0 for no).<p>

## Data Source Reference
The dataset was adapted from the Online Shoppers Purchasing Intention Dataset donated to the UC Irvine Machine Learning Repository on 8/30/2018 (DOI: 10.24432/C5F88Q). Some modifications include renaming and removing specific columns for clarity and relevance.

## Analysis and Insights
### **Purchase Rates**
The project starts by calculating the online purchase rates during November and December, the busiest months for shopping. It was observed that:
**Returning Customers**: Had a lower purchase rate compared to new customers.
**New Customers**: Showed a higher likelihood of making a purchase during these months.
### **Correlation Analysis**
The strongest correlations in total time spent between different types of pages visited were identified:
**Administrative and Product-Related Pages**: Showed the highest correlation, suggesting that time spent on administrative tasks might be linked to product interest.
### **Predicting Future Sales**
The likelihood of achieving a specific sales target was estimated using binomial probability:
**Sales Probability**: With an increased purchase rate, the probability of achieving at least 100 sales out of 500 sessions for returning customers was calculated.
### **Further Explorations**
The analysis extended beyond the original project scope by integrating additional statistical tests and visualisations to provide deeper insights into customer behaviour.

## **Conclusion**
This project provides actionable insights into customer behaviour patterns, enabling the marketing team to better understand and target different customer segments. The analysis highlights the importance of personalised strategies for new and returning customers to maximise conversions.

**Acknowledgements**
This project was initially based on a DataCamp exercise, with further analyses and insights added to extend its scope and depth.
