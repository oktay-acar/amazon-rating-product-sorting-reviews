# Rating Product & Sorting Reviews in Amazon

**Business Problem**

One of the most important problems in e-commerce is the correct calculation of the points given to the products after sales. 

The solution to this problem means providing greater customer satisfaction for the e-commerce site, prominence of the product for the sellers and a seamless shopping experience for the buyers.

Another problem is the correct ordering of the comments given to the products. Since misleading comments will directly affect the sale of the product, it will cause both financial loss and loss of customers.

In the solution of these 2 basic problems, e-commerce site and sellers will increase their sales, while customers will complete their purchasing journey without any problems.

**Dataset Story**

This dataset, which includes **Amazon** product data, includes product categories and various metadata.

The product with the most reviews in the electronics category has user ratings and reviews.

**Variables**
- **reviewerID:** User ID
- **asin:** Product Id
- **reviewerName:** User Name
- **helpful:** Useful rating degree
- **reviewText:** Useful review rating
- **overall:** Product rating
- **summary:** Review summary
- **unixReviewTime:** Review time
- **reviewTime:** Review Time
- **day_diff:** Number of days since review
- **helpful_yes:** Number of times the review was found useful
- **total_vote:** Number of votes for review

---

## Requirements
~~~python
pandas==1.5.1
scipy==1.11.4
~~~

---

## Author
[Oktay Acar](https://github.com/oktay-acar)