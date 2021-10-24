# Amazon Vine Analysis
## Purpose
Jennifer needs our help with a new project. Our goal is to analyze Amazon reviews that were written by paid members of the Amazon Vine program. First, we pick a specific type of product to do our review on. The type of product I chose was video games. We will utilize PySpark to extract the data set, transform the data, connect with a AWS RDS instance, then load the newly transformed data into pgAdmin by performing the ETL process. Next, I used Pandas to analyze the data in order to see if there is any bias regarding complimentary reviews from paid members of the Amazon Vine program in the dataset.
## Results
![Paid Review Count](Images/paid_review_count.PNG)
- There are 94 total Vine reviews.\
![Unpaid Review Count](Images/unpaid_review_count.PNG)
- There are 40,471 total non-Vine reviews.\
![Five Star Paid Review Count](Images/five_star_paid_review_count.PNG)
- There are 48 5-star Vine reviews.\
![Five Star Unpaid Review Count](Images/five_star_unpaid_review_count.PNG)
- There are 15,663 5-star non-Vine reviews.\
![Five Star Paid Review Percentage](Images/five_star_paid_review_percentage.PNG)
- 51.06% of the Vine reviews are 5-star reviews.\
![Five Star Unpaid Review Percentage](Images/five_star_unpaid_review_percentage.PNG)
- 30.70% of the non-Vine reviews are 5-star reviews.
## Summary
