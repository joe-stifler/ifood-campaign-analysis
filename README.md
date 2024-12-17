# iFood Marketing Campaign Optimization Project

[Link to Tableau Dashboard](https://public.tableau.com/views/iFoodCampaignAnalysis_17343986684990/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

## Project Overview

This project aimed to improve the effectiveness of iFood's marketing campaigns by using data analysis and machine learning to better understand our customers. I focused on segmenting customers into distinct groups, identifying key drivers of campaign response, and building a predictive model to optimize targeting and maximize campaign profit and ROI. This project provides a data-driven approach to move beyond 'one-size-fits-all' strategies.

## Main Accomplishments

*   Developed a customer segmentation using data-driven clustering based on purchasing behavior, engagement, and other customer attributes.
*   Built a predictive machine learning model to accurately identify customers most likely to respond to marketing campaigns.
*   Identified key factors influencing campaign response.

## Methodology

This project involved the following key steps:

1.  **Data Exploration and Preprocessing:** Initial analysis and cleaning of the provided customer dataset, dealing with missing values and preparing the data for further analysis.
2.  **Feature Engineering:** Creation of new relevant features, such as `TotalSpending`, `TotalPurchases`, `CustomerAge`, and calculating the purchase proportions by each channel. These new features enriched the dataset and supported better predictions.
3.  **Customer Segmentation:** Using KMeans clustering, identified three distinct customer segments: "Value-Conscious Shoppers", "Established Spenders", and "High-Value Customers." Each segment exhibits unique characteristics regarding spending habits, purchase channels, income, and propensity to accept campaigns.
4.  **Predictive Modeling:** Developed a Random Forest classification model to predict individual customer responses to marketing campaigns. The model was trained using historical data and oversampling techniques to mitigate class imbalance, and was carefully evaluated with high precision, recall and f1 score values.

## Key Findings

*   Customers with higher income, total spending are significantly more likely to respond to marketing campaigns.
*   Customer purchase behavior is not uniform: Most spending is done on wines, with store purchases as the preferred channel.
*   Customer segmentation revealed distinct segments with different responses to campaigns.
    *   **Value-Conscious Shoppers:** good acceptance of deals, shop in-store or web. Bigger amount of children, usually kids.
    *   **Established Spenders:** Tend to purchase in store or through web, prefer wines and meat, and are inclined to accept deals. Also have some children, usually teenagers.
    *    **High-Value Customers:** Have a preference for store and catalog channels, are very responsive to current campaign, and have a high spending on wines and meat. Almost no children.
*   The predictive model is effective, with key predictors being `Recency`, `Teenhome`, `Days with the company`,  `NumWebVisitsMonth`, and `MntGoldProds`. This highlight the need to generate actions that lead to recent purchases, increase engagement on web visits, and take into consideration customers with teenagers.

## Business Recommendations

*   **Personalized Targeting:** Implement tailored marketing strategies for each segment, focusing on their unique preferences and behavior.
*   **Resource Optimization:** Prioritize high-value customers and the potential of middle spenders to maximize marketing ROI.
*   **Channel Alignment:** Adjust communication channels to match the preferred purchase channels of each segment.
*   **Product Selection:** Focus offers on products based on each segment's most relevant purchases.

## Conclusion

This project provides a framework to enhance iFood's marketing campaigns. By leveraging data analysis and machine learning, we can now target specific segments of customers with tailored messages, maximizing campaign efficiency and increasing revenue