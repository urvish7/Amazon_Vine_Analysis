# Amazon_Vine_Analysis

# Purpose and Overview of the analysis of the Vine program:

Since our work with Jennifer on the SellBy project was so successful, we’ve been tasked with another, larger project: analyzing Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.

In this project, we’ll have access to approximately 50 datasets. Each one contains reviews of a specific product, from clothing apparel to wireless products. We’ll need to pick one of these datasets and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, we’ll use PySpark, Pandas, or SQL to determine if there is any bias toward favorable reviews from Vine members in your dataset. Then, we’ll write a summary of the analysis for Jennifer to submit to the SellBy stakeholders.\


## Deliverable 1: Perform ETL on Amazon Product Reviews:


Using your knowledge of the cloud ETL process, we’ll create an AWS RDS database with tables in pgAdmin.
Extracting the Amazon review data set into the data frames:

![](https://github.com/urvish7/Amazon_Vine_Analysis/blob/main/ScreenShots/Dev1/Amazonreviewdataframe.png)


The final customer table data frame:

![](https://github.com/urvish7/Amazon_Vine_Analysis/blob/main/ScreenShots/Dev1/customer_table.png)

The product data frame and dropping the duplicates.

![](https://github.com/urvish7/Amazon_Vine_Analysis/blob/main/ScreenShots/Dev1/Product_id_title.png)

The review id data frame :

![](https://github.com/urvish7/Amazon_Vine_Analysis/blob/main/ScreenShots/Dev1/review_id_table.png)

The Vine table data frame:

![](https://github.com/urvish7/Amazon_Vine_Analysis/blob/main/ScreenShots/Dev1/vine_table.png)

The four frames that are imported in the database:

The review_id table:

![](https://github.com/urvish7/Amazon_Vine_Analysis/blob/main/ScreenShots/Dev1/review_table_pgadmin.png)


The Product table in PGAdmin:

![](https://github.com/urvish7/Amazon_Vine_Analysis/blob/main/ScreenShots/Dev1/product_table_pgadmin.png)


The customer's table in PG admin:

![](https://github.com/urvish7/Amazon_Vine_Analysis/blob/main/ScreenShots/Dev1/customer_table_pgadmin.png)


The vine table in PG admin:

![](https://github.com/urvish7/Amazon_Vine_Analysis/blob/main/ScreenShots/Dev1/vine_table_pgadmin.png)


## Deliverable 2: Determine Bias of Vine Reviews:

The Vine data frame for the analysis: 

![](https://github.com/urvish7/Amazon_Vine_Analysis/blob/main/ScreenShots/Dev2/vine_dataframe.png)

creating the vine dataframe:

![](https://github.com/urvish7/Amazon_Vine_Analysis/blob/main/ScreenShots/Dev2/vine_show.png)

The total vote data frame :

![](https://github.com/urvish7/Amazon_Vine_Analysis/blob/main/ScreenShots/Dev2/votecount.png)

The data frame of the helpfulvotes equal or greater than 50%:

![](https://github.com/urvish7/Amazon_Vine_Analysis/blob/main/ScreenShots/Dev2/helpful_totalvotes.png)

The paid vine dataframe:

![](https://github.com/urvish7/Amazon_Vine_Analysis/blob/main/ScreenShots/Dev2/paid_vine_review.png)

The unpaid vine frame:

![](https://github.com/urvish7/Amazon_Vine_Analysis/blob/main/ScreenShots/Dev2/unpaid_vine_review.png)













