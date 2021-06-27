# Amazon Vine Analysis



## Overview of the Analysis and Purpose

This project will analyse Amazon reviews written by members of the paid Amazon Vine Program and compare them to unpaid reviews. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies pay Amazon a fee to provide products to Amazon Vine members in return for their review.

The analysis will look at a dataset on video game reviews using PySpark to perform ETL, connect to AWS RDS instance and then load the transformed data to pgAdmin. The purpose of the analysis is to determine whether a bias exists for favourable reviews from Vine members (using pySpark) vs unpaid reviews.

## 

## Results

#### Summary of Paid and Unpaid reviews:

![summary](https://github.com/YanLuong/Amazon_Vine_Analysis/blob/master/screenshots/summary.png)

* There are a total of 94 paid vine reviews and 40,471 unpaid reviews.
* 48 out of 94 paid vine reviews gave a 5 star rating.
* 15663 out of 40471 unpaid reviews gave a 5 star rating.
* 5 Star rating reviews accounted for 51% of paid vine reviews while in unpaid reviews it accounted for 38.7%.

## Summary





|Paid Review   | Unpaid Reviews  |
|---|---|
|  ![bar1](https://github.com/YanLuong/Amazon_Vine_Analysis/blob/master/screenshots/paid_reviews.png) | ![bar2](https://github.com/YanLuong/Amazon_Vine_Analysis/blob/master/screenshots/unpaid_reviews.png)  |
