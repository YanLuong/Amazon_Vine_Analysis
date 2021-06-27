# Amazon_Vine_Analysis


Overview of the analysis: Explain the purpose of this analysis.

Results: Using bulleted lists and images of DataFrames as support, address the following questions:

How many Vine reviews and non-Vine reviews were there?
How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
Summary: In your summary, state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. Then, provide one additional analysis that you could do with the dataset to support your statement.




## Overview of the Analysis and Purpose

This project will analyse Amazon reviews written by members of the paid Amazon Vine Program and compare them to unpaid reviews. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies pay Amazon a fee to provide products to Amazon Vine members in return for their review.

The analysis will look at a dataset on video game reviews using PySpark to perform ETL, connect to AWS RDS instance and then load the transformed data to pgAdmin. The purpose of the analysis is to determine whether a bias exists for favourable reviews from Vine members (using pySpark) vs unpaid reviews.

## Results

#### Summary of Paid and Unpaid reviews:

![summary](https://github.com/YanLuong/Amazon_Vine_Analysis/blob/master/screenshots/summary.png)

* There are a total of 94 paid vine reviews and 40,471 unpaid reviews.
* 48 out of 94 paid vine reviews gave a 5 star rating.
* 15663 out of 40471 unpaid reviews gave a 5 star rating.
* 5 Star rating reviews accounted for 51% of paid vine reviews while in unpaid reviews it accounted for 38.7%.
