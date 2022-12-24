# Amazon_Vine_Analysis

## Overview of the analysis:

In the following analysis Amazon reviews written by members of the paid Amazon Vine program get analyzed. In the first section we pick a dataset and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. In the second section of the analysis the dataset gets analyzed whether there is any bias towards reviews that were written as the part of the vine program.

- Deliverable 1: Perform ETL on Amazon Product Reviews
- Deliverable 2: Determine Bias of Vine Reviews
- Deliverable 3: A Written Report on the Analysis (README.md)

## Results:

- How many Vine reviews and non-Vine reviews were there?
	- The total number of helpful reviews was 40,565.
	- The total number of helpful reviews by Vine members was 94.
	- The total number of helpful reviews by non-Vine members was 40,471. 
	
<img width="1088" alt="Question1" src="https://user-images.githubusercontent.com/69826498/209451405-eebf5146-2c6b-4db5-81f6-b01f18b1ed6a.png">

- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
	- In total there have been 48 member 5 star reviews.
	- And 15663 non member 5 star reviews. 
	
<img width="990" alt="Question2" src="https://user-images.githubusercontent.com/69826498/209451409-7c7dcdc4-3ceb-4f31-a214-a2dc0aad4b5e.png">

- What percentage of Vine reviews were 5 stars? What percentage of non_Vine reviews were 5 stars?
	- In total 51% of Vine member reviews have been 5 stars.
	- In total 38% of non-Vine member reviews have been 5 stars. 
	
<img width="1033" alt="Question3" src="https://user-images.githubusercontent.com/69826498/209451412-c56497d4-f355-41af-852b-099ce05cc3fa.png">

## Summary:

Based on our analysis we can see that Vine members are likely to give better reviews than non-Vine members. In total 51% of positive reviews in comparison to 38% of non-Vine members. However doing the analysis of only one category gives us not yet enough insights to decide whether there is a bias in the reviews. Additional analysis over several categories are necessary. In addition statistical analysis can help to understand the differences better. 

