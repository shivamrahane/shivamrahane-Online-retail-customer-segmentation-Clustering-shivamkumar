Online Retail Customer Segmentation (Clustering)

>Project Summary

This project focuses on Online Retail Customer Segmentation, a crucial aspect of modern business. By categorizing customers into distinct groups based on purchasing behavior, businesses can optimize marketing strategies and enhance customer satisfaction.

The dataset used in this project is a transnational dataset from an online retail company specializing in all-occasion gifts. The data spans from 01/12/2010 to 09/12/2011, including transactions from both individual customers and wholesalers.

To achieve customer segmentation, the Recency-Frequency-Monetary (RFM) model was used, which evaluates customers based on:

   Recency (R): How recently a customer made a purchase.

   Frequency (F): How often they purchased.

  Monetary (M): The total monetary value of their purchases.

The K-Means, Agglomerative Hierarchical Clustering, and DBSCAN algorithms were applied to cluster customers based on their RFM scores, helping to derive meaningful insights for targeted marketing strategies.

>Problem Statement

The objective of this project is to develop a customer segmentation model for an online retail business. By analyzing transactional data, the project aims to:

   Identify meaningful customer segments.

   Improve targeted marketing campaigns.

   Optimize inventory management.

   Enhance customer satisfaction and loyalty.
   
>Data Processing and Exploratory Data Analysis (EDA)

   Data Cleaning: Removed null values and duplicates to ensure data quality.

  Customer Insights:

   -Top 5 Customer IDs: 17841.0, 14911.0, 14096.0, 12748.0, 14606.0.

   -Top 5 Countries by Total Orders: United Kingdom (88.95%), Germany (2.33%), France (1.84%), Ireland (1.84%), Spain (0.62%).

   -Top 5 Most Purchased Products: White Hanging Heart T-Light Holder, Regency Cakestand 3 Tier, Jumbo Bag Red Retrospot, Party Bunting, Assorted Colour Bird 
    Ornament.

   -Top 5 Stock Codes by Count: 85123A, 22423, 85099B, 47566, 84879.

   -Peak Sales Months: November, October, December, September, May.

   -Most Active Purchasing Days: Thursday, Wednesday, Tuesday, Monday, Saturday, Friday.

   -Peak Shopping Hours: Between 10:00 AM and 2:00 PM.

New time-based features were created from the InvoiceDate column, such as Year, Month, Day, Hour, Month_Num, and Day_Num, to gain deeper insights into customer behavior.

?Clustering Techniques Applied

  1.RFM Segmentation: Customers were grouped based on their RFM scores.

  2.K-Means Clustering:

   -  Used Silhouette Score and Elbow Method to determine the optimal number of clusters.

  3.Hierarchical Clustering:

   -  Applied Agglomerative clustering to visualize customer segments in a dendrogram.

   4.DBSCAN:

   -   Used for identifying potential noise and outlier customers.

>Key Findings and Business Recommendations

To help the business optimize customer engagement and increase revenue, the following strategies are suggested:

  Optimize Pricing Strategy: Adjust prices based on customer segmentation insights, demand, and location.

  Enhance Availability: Encourage high-value customers to increase order frequency.

  Improve Customer Experience: Encourage hosts to focus on quality service to increase reviews and engagement.

  Target High-Value Customers: Focus marketing efforts on high-spending customers.

  Seasonal Promotions: Offer discounts during off-peak seasons to maintain sales consistency.

>Conclusion

This project successfully implemented customer segmentation using clustering algorithms, allowing for deeper insights into purchasing behavior. The analysis revealed key trends in:

  Customer purchase patterns

  Seasonal trends

  High-value customers

  Optimal marketing strategies

By leveraging these insights, businesses can improve marketing campaigns, optimize pricing strategies, and enhance customer engagement, ultimately driving business growth in a competitive retail environment.

>Technologies Used

  Python

  Pandas, NumPy

  PandasSQL

  Matplotlib, Seaborn

  Scikit-Learn (K-Means, Hierarchical Clustering, DBSCAN)

>How to Use This Project

  Install necessary libraries

  Load and preprocess the dataset.

  Perform EDA to explore customer behavior.

  Apply clustering models for segmentation.

  Visualize the insights and interpret the results for business recommendations.

>Future Enhancements

  Implementing Deep Learning for advanced segmentation.

  Integrating real-time customer data analysis.

  Exploring predictive modeling for future customer behavior trends.
