
## [ 1. OVERVIEW ]()
[ **1.1 About the data**: ]() 

**- Sale dataset:** There is a big mall in a small city where most people go to and buy anything in the mall whatever they need. And the mall gathered some informations of to hundreds of their customers which are customers that normally subscribe the the membership card.

The mall computes spending score for each of their customer. Spending score takes values between 1 and 100.

Now the problem is that the mall would like to segment their customers into different groups but the mall has actually no idea of what this groups might be.

---
## [ 2. THE APPROACH ]()
**For this problem, I will try out many different technique in dealing with unsupervised learning. Details as below.**

**The explaination below is collected in many different sources in order to make clear of the technique that I used.**

[ **2.1 Hierachical Clustering**: ]() 

- **Explained:** It is an algorithm that groups similar objects into groups called clusters. The endpoint is a set of clusters, where each cluster is distinct from each other cluster, and the objects within each cluster are broadly similar to each other.

- **How it works:** Hierarchical clustering starts by treating each observation as a separate cluster. Then, it repeatedly executes the following two steps: (1) identify the two clusters that are closest together, and (2) merge the two most similar clusters. This continues until all the clusters are merged together. 
![](https://i.imgur.com/FwYvPuW.png)

[ **2.2 K-Means Clustering**: ]() 
- **Explained:** KMeans is a top down approach, while hierachical is a bottom-up approach.

- **How it works:** The way kmeans algorithm works is as follows:
1. Specify number of clusters K.
2. Initialize centroids by first shuffling the dataset and then randomly selecting K data points for the centroids without replacement.
3. Keep iterating until there is no change to the centroids. i.e assignment of data points to clusters isn’t changing.
![](https://i.imgur.com/hJUWCmw.png)

[ **2.2 Principal Component Analysis**: ]() 
**This defines the goal of PCA:**
1. Find linearly independent dimensions (or basis of views) which can losslessly represent the data points.
2. Those newly found dimensions should allow us to predict/reconstruct the original dimensions. The reconstruction/projection error should be minimized.
---
