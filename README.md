# **Customer Mall Segmentation Analysis using K-Means Clustering**

**Introduction**
![]()

In today's fiercely competitive retail landscape, businesses recognize the critical importance of understanding customer behavior and preferences. By segmenting customers into distinct groups based on their demographics and shopping habits, retailers can effectively tailor their marketing strategies, product offerings, and services to better meet the needs and preferences of each segment. The project aims to conduct customer segmentation analysis using K-Means clustering to identify distinct customer groups and derive actionable insights for optimizing the operations of a customer mall.

**Dataset**

The dataset employed for this analysis comprises comprehensive information about customers of a mall, including demographic attributes such as age and gender, as well as their annual income and spending score. The overarching goal of this project is to segment customers based on their annual income and spending score to gain insights into their shopping behavior and preferences.

**Problem Statement**

The primary objective of this project is to segment customers into distinct groups based on their annual income and spending score using K-Means clustering. By identifying meaningful customer segments, the mall management can develop targeted marketing strategies, optimize tenant mix and merchandise offerings, and enhance customer experiences to drive sales and increase customer satisfaction.

**Data Collection and Analysis**

The project commences with the importation of necessary libraries before loading the dataset from a CSV file into a Pandas DataFrame. Subsequently, preliminary data analysis is conducted to gain insights into the structure and characteristics of the data. This includes univariate analysis to visualize the distributions of key variables such as age, annual income, and spending score, and checking for missing values to ensure data integrity.

![](data_collection_and_analysis.JPG)
![](shape_infoa_missing_values.JPG)

**Selecting Criteria for Customer Segmentation**

For customer segmentation, the annual income and spending score columns are chosen as criteria, given their significance in reflecting customers' purchasing power and shopping behavior.


**Choosing the Number of Clusters**

To determine the optimal number of clusters for segmentation, the Within Clusters Sum Of Squares (WCSS) metric is utilized, and the Elbow Point Graph is plotted. Analysis of the graph aids in identifying the point at which the rate of decrease in WCSS slows down, signifying the optimal number of clusters, which, in this instance, is indicated to be 5.
![](choosing_wcss.JPG)
![](plotting_elbow_graph.JPG)

**Training the K-Means Clustering Model**

A K-Means clustering model with 5 clusters is trained using the selected features. The model assigns each data point to one of the clusters based on their proximity to the cluster centroids.
![](training_kmeans_model.JPG)

**Visualizing all the Clusters**

The clusters and their centroids are visualized on a scatter plot to gain insights into the distribution of customers based on their annual income and spending score. This visualization helps in understanding the characteristics and behaviors of customers within each segment.
![](cluster_visual_code.JPG)
![](customer_group.JPG)

**Analytical Insights and Recommendations for the Customer Mall**

### Insights:
Our K-Means clustering analysis reveals the presence of distinct customer segments characterized by varying levels of annual income and spending behavior. Through visualizations and cluster profiling, we identify the following customer segments:
1. **High-Spending Affluents:** Customers with high annual incomes and high spending scores, representing a lucrative target for premium offerings and personalized services.
2. **Budget-Conscious Shoppers:** Customers with moderate to low annual incomes but high spending scores, seeking value-oriented products and promotions.
3. **Young and Aspirational:** Younger customers with moderate to high annual incomes and spending scores, exhibiting potential for future growth and brand loyalty.
4. **Sensible Savers:** Customers with moderate to low annual incomes and low spending scores, prioritizing savings and practical purchases.
5. **Occasional Splurgers:** Customers with high annual incomes but low spending scores, requiring targeted incentives to increase engagement and conversion.
### Recommendation:
1. Tailor Services for Each Customer Category:
Customize services and experiences to meet the needs of each customer category. For example, offer budget-friendly promotions and discounts for customers with low annual income and low spending scores to encourage their patronage. Conversely, provide premium services and exclusive benefits for high-spending customers with high annual incomes to enhance their shopping experience and foster loyalty.
2. Optimize Tenant Mix Based on Customer Segmentation:
Adjust the mall's tenant mix and merchandise offerings to cater to the preferences of each customer category. For instance, stock affordable yet trendy products for customers with low annual incomes but high spending scores, while also offering luxury brands and upscale amenities for high-income shoppers with discerning tastes. By aligning the mall's offerings with the preferences of each customer category, you can maximize sales and satisfaction across the board.
3. Develop Targeted Marketing Campaigns:
Create targeted marketing campaigns tailored to the unique characteristics and behaviors of each customer category. Utilize personalized messaging and promotions to appeal to the specific needs and preferences of low-income, budget-conscious shoppers, as well as high-income, luxury-seeking clientele. By delivering relevant and compelling marketing messages to each customer category, you can increase engagement and drive conversion rates effectively.
4. Enhance Loyalty Programs for High-Value Segments:
Enhance loyalty programs to reward and incentivize high-value customer segments, such as those with high annual incomes and high spending scores. Offer exclusive perks, VIP events, and personalized rewards to encourage repeat visits and purchases from these valuable customers. By nurturing loyalty among high-value segments, you can increase customer retention and lifetime value, driving sustained revenue growth.
5. Stay Agile and Responsive to Changing Preferences:
Continuously monitor and adapt to changing customer preferences and market trends across all customer categories. Regularly analyze sales data, customer feedback, and demographic insights to identify emerging opportunities and areas for improvement. Use this information to refine strategies, adjust offerings, and innovate services to meet the evolving needs of each customer category effectively. By staying agile and responsive, you can maintain relevance and competitiveness in the dynamic retail landscape.
Conclusion
In conclusion, customer segmentation analysis using K-Means clustering provides valuable insights for optimizing the operations of a customer mall and enhancing customer satisfaction. By understanding the distinct characteristics and behaviors of different customer segments, businesses can develop targeted strategies and initiatives to drive sales, increase customer loyalty, and stay ahead in today's competitive retail market.
