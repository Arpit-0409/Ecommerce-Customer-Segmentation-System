# Ecommerce-Customer-Segmentation-System

Build a Customer Segmentation mini project which sperate customers on the basis of related features like Income , TotalSpending , Family , WebsiteVisit, StorePurchases, WebPurchases etc. using  K-Means Clustering Unsupervised Machine Learning Algorthim which sperated customer into four seperate segments.

Dataset - contain around 2250 rows and 22 columns .

Pre-Processing - handle Missing Value in Income column with random imputation because very few values were missing.

Feature Engineering - 
handled date column - convert it to Tenure days so that it helps model to generalize better
handled year-birth column - convert it to Age
combined several other columns of children , different product spending into one.

Co-relation Heatmap:-
<img width="786" height="689" alt="Co-Relationheatmap" src="https://github.com/user-attachments/assets/0382f8a6-23a6-4314-a59b-d7cd9251744e" />

        






Income having positive co-relation with Total-Spending :-    0.79
Income having positive co-relation with NoofStorePurchases:-   0.63
Income having negative co-relation with NoofWebVisits:-    -0.64




Applied PCA - Principal Component Analysis to visualize the data in 3D
and 3 Principal COmponet were giving 52% variance of the original data.


Applied Twoc Clustering Algortims - KMeans and Agglormative Clustering

Kmeans was giving better speration
while Agglormative data points where in other cluster as welll


so for this project KMeans is the selected Model.

There are Total- 4 cluster 
I find  optimal cluster  value after plotting elbow method and Silhuate_score.


cluster summary - 

cluster 0 (DarkBLUE)-:                                          
>Low-Medium Income Customer
>Low-Medium Spending Customer
>More no. of childrens
>Most Web Visit
>Married

cluster 1 (Purple)-:
> High Income Customer
> High Spending Customer
> Few no. of children
> Age Higher
> High no. of Store Purchases
> Response is not good
>Married

cluster 2 (Pink)-:
> Low Income Customer
> Low Spending Customer
> More no. of children
> Most Web Visit - but rarely buying things
>Married

cluster 3 (Yellow)-:
> Medium - High Income Customer
> Medium - High Spending Customer
> Age Higher
> Best Response
> High Store Purchases
> few no. of children
> Alone


conclusion -  Customers in cluster 3 are giving best Rate of Interest .
              Customer in cluster 2 are more engaging with websites but rarely spending money.
              






 


