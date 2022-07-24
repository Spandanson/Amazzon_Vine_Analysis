# Amazzon_Vine_Analysis
# Overview of the analysis:
* The SellBy project that me and worked was so successful.
* So we got anotherlarger project: analyzing Amazon reviews written by members of the paid Amazon Vine program. 
* The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products.
* Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.
* In this project, we have access to approximately 50 datasets.
* Each one contains reviews of a specific product, from clothing apparel to wireless products. 
* We need to pick one of these datasets and use PySpark to perform the ETL process to extract the dataset, transform the data, 
  connect to an AWS RDS instance, and load the transformed data into pgAdmin. 
* Next, you’ll use PySpark, Pandas, or SQL to determine if there is any bias toward favorable reviews from Vine members in your dataset.
* Then, we write a summary of the analysis for Jennifer to submit to the SellBy stakeholders.
# Results:
### The results of the analysis are shown below:
![](https://github.com/Spandanson/Amazzon_Vine_Analysis/blob/master/Amazon_Vine_Analysis/Resources/vine%20Table.png)
![](https://github.com/Spandanson/Amazzon_Vine_Analysis/blob/master/Amazon_Vine_Analysis/Resources/Total_vote%20more%20or%20equal%20to%2020.png)
![](https://github.com/Spandanson/Amazzon_Vine_Analysis/blob/master/Amazon_Vine_Analysis/Resources/Per%20helpvote%3D50%20percent.png)
![](https://github.com/Spandanson/Amazzon_Vine_Analysis/blob/master/Amazon_Vine_Analysis/Resources/Vine%20review.png)
![](https://github.com/Spandanson/Amazzon_Vine_Analysis/blob/master/Amazon_Vine_Analysis/Resources/No%20vine%20review.png)
* Total_review:9002021
* Total_fivestar_review: 4824725
* paid_fivestar_review: 6522
* unpaid_fivestar_review:4818203
* pecentage_paid_fivestar:0.00135
* percentage_unpaid_fivestar:0.998
# Summary:
* The sum of unpaid review and paid review are not equal to the total reviews(Bias)
* All the datas are not utilzed properly, need further analysis including more parameters.
