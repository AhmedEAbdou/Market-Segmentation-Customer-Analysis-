# Maximizing-Direct-Mail-Marketing-Profitability-Using-Machine-Learning

Project Summary: Segmenting Consumers of Bath Soap

​

Objective

This project aims to segment the bath soap market based on purchase behavior and the basis of purchase variables. The project uses k-means clustering to gain insights into different consumer groups, which will help a firm called IMRB design cost-effective promotions and increase brand loyalty.

​

Data

The dataset consists of 600 records, profiling each household with variables such as demographics, possession of durable goods, and purchase data of product categories and brands. The variables in this dataset can be grouped into two main categories: purchase behavior (including brand loyalty) and the basis of purchase.

​

Approach

First, the data was cleaned and prepared, removing the Member id variable and scaling numeric columns. Then, k-means clustering was performed on three sets of variables: purchase behavior, the basis of purchase, and the combination of both.

The k-means clustering algorithm was applied for each group of variables, resulting in three separate cluster assignments for each household. In this case, the best segmentation combined both purchase behavior and the basis of purchase variables, as it would provide the most comprehensive insights for advertising and promotional campaigns.

​

The k-means_combined segmentation revealed three distinct clusters:

​

Cluster 1: Balanced purchase behavior, moderately price-sensitive. Target with general advertising campaigns.

Cluster 2: Higher transactions, effective for promotional category 4. Focus on loyalty and targeted promotions.

Cluster 3: Larger volumes, lower price point, and high responsiveness to promotional category 3. Target with volume discounts and category-specific promotions.

​​

Following this, a classification tree model and logistic regression model were trained to predict the segments. The logistic regression model showed better accuracy, making it the preferred choice for segment prediction.

​

Conclusion

Using k-means clustering, the market for bath soap was segmented based on purchase behavior and basis of purchase variables. These segments provide valuable insights that can be leveraged by IMRB to design cost-effective promotions and increase brand loyalty. The logistic regression model can be used for segment prediction in targeted direct-mail promotions.
