# Data_Mining
## task1: Data Exploration

We will explore the review dataset and write a program to answer the following questions:

A. The total number of reviews 

B. The number of reviews in a given year, y 

C. The number of distinct users who have written the reviews 

D. Top m users who have the largest number of reviews and its count 

E. Top n frequent words in the review text. The words should be in lower cases. The following punctuations
“(”, “[”, “,”, “.”, “!”, “?”, “:”, “;”, “]”, “)” and the given stopwords are excluded 

## task2: Exploration on Multiple Datasets

In task2, we will explore the two datasets together (i.e., review and business) and write a program to
compute the average stars for each business category and output top n categories with the highest
average stars. The business categories should be extracted from the “categories” tag in the business file
and split by comma (also need to remove leading and trailing spaces for the extracted categories). We
need to implement a version without Spark  and a version with Spark.

## task3: Partition  

In this task, we will learn how partitions work in the RDD. we need to compute the businesses that have
more than n reviews in the review file. Other than the default way of partitioning the RDD, we should
also design a customized partition function to improve the computational efficiency. Our program will be
given the partition_type to decide which partition method to use. For eitherthe default or the customized
partition function, we need to show the number of partitions for the RDD, the number of items per
partition and the businesses that have more than n reviews(1ptsfor each partition type). Our customized
partition function should improve the computational efficiency, i.e., reducing the time duration of
execution.
