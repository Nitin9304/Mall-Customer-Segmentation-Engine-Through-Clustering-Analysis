
# Mall Customer Segmentation Engine Through Clustering Analysis
Description:Conducted a comprehensive clustering analysis on customer data from a shopping mall to gain insights into consumer behavior and preferences. Leveraged unsupervised machine learning techniques, including k-means clustering and hierarchical clustering, to categorize customers based on their shopping patterns.

Skills Utilized: Machine Learning, Clustering Analysis, Python, Data Exploration, Data Visualization, Customer Segmentation, Unsupervised Learning.

Impact: Uncovered distinct customer segments with similar preferences, enabling the mall management to tailor marketing strategies and optimize store layouts. The project facilitates a more personalized shopping experience for customers, contributing to increased customer satisfaction and improved business outcomes.

![alt_image](https://github.com/Nitin9304/Mall-Customer-Segmentation-Engine-Through-Clustering-Analysis/blob/c57bd2288199e4037aed7e633dbac13da89db4d5/mall_c.jpg)

# What is Customer Segmentation
Customer Segmentation is the process of division of customer base into several groups of individuals that share a similarity in different ways that are relevant to marketing such as gender, age, interests, and miscellaneous spending habits.

Companies that deploy customer segmentation are under the notion that every customer has different requirements and require a specific marketing effort to address them appropriately. Companies aim to gain a deeper approach of the customer they are targeting. Therefore, their aim has to be specific and should be tailored to address the requirements of each and every individual customer. Furthermore, through the data collected, companies can gain a deeper understanding of customer preferences as well as the requirements for discovering valuable segments that would reap them maximum profit. This way, they can strategize their marketing techniques more efficiently and minimize the possibility of risk to their investment.

The technique of customer segmentation is dependent on several key differentiators that divide customers into groups to be targeted. Data related to demographics, geography, economic status as well as behavioral patterns play a crucial role in determining the company direction towards addressing the various segments

# What is K-Means Algorithm
While using the k-means clustering algorithm, the first step is to indicate the number of clusters (k) that we wish to produce in the final output. The algorithm starts by selecting k objects from dataset randomly that will serve as the initial centers for our clusters. These selected objects are the cluster means, also known as centroids. Then, the remaining objects have an assignment of the closest centroid. This centroid is defined by the Euclidean Distance present between the object and the cluster mean. We refer to this step as “cluster assignment”. When the assignment is complete, the algorithm proceeds to calculate new mean value of each cluster present in the data. After the recalculation of the centers, the observations are checked if they are closer to a different cluster. Using the updated cluster mean, the objects undergo reassignment. This goes on repeatedly through several iterations until the cluster assignments stop altering. The clusters that are present in the current iteration are the same as the ones obtained in the previous iteration.

![image alt](https://github.com/Nitin9304/Mall-Customer-Segmentation-Engine-Through-Clustering-Analysis/blob/e7cccc74348365dca06f35c52d426b5e02a5d513/Screenshot%202025-04-02%20233021.png)
![image alt](https://github.com/Nitin9304/Mall-Customer-Segmentation-Engine-Through-Clustering-Analysis/blob/8efa6f5852abd3aff379f2620a941d5c13a8514a/Screenshot%202025-04-02%20235616.png)



K-means clustering groups similar data points by iteratively adjusting cluster centers until they stabilize. It's useful for 
pattern recognition but requires selecting the number of clusters in advance and may struggle with complex shapes or outliers


![image alt](https://github.com/Nitin9304/Mall-Customer-Segmentation-Engine-Through-Clustering-Analysis/blob/fe34fe1309cec3961c596ee83a773c4315f1e54e/Screenshot%202025-04-03%20000246.png)

# K-means Algorithm
We specify the number of clusters that we need to create.
The algorithm selects k objects at random from the dataset. This object is the initial cluster or mean.
The closest centroid obtains the assignment of a new observation. We base this assignment on the Euclidean Distance between object and the centroid.
k clusters in the data points update the centroid through calculation of the new mean values present in all the data points of the cluster. The kth cluster’s centroid has a - - Length of p that contains means of all variables for observations in the k-th cluster. We denote the number of variables with p.
Iterative minimization of the total within the sum of squares. Then through the iterative minimization of the total sum of the square, the assignment stop wavering when we - - Achieve maximum iteration. The default value is 10 that the R software uses for the maximum iterations.

![image alt](https://github.com/Nitin9304/Mall-Customer-Segmentation-Engine-Through-Clustering-Analysis/blob/c2dfb119ec1b6b1f9ed7c33bff91be56ee664edd/Screenshot%202025-04-03%20000906.png)
