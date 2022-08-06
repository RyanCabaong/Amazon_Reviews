# Amazon_Reviews
The purpose of this project is to determine any rating bias on paid reviews in comparison to unpaid reviews on video game products from 2006 to 2015.
In summary, the dataset needed a PySpark ETL process to be extracted, connected to an AWS RDS Instance, and loaded as transformed data into pgAdmin for presentation.
However, this project did not come without difficulties as I was unfamiliar with making a AWS Databases. I was lucky to consult a professional and become more experienced.


All columns


![All Columns](https://user-images.githubusercontent.com/79386482/183269189-d13fcfed-29f2-43d6-8503-c4fea43121fa.PNG)


Products


![Product column](https://user-images.githubusercontent.com/79386482/183269212-f3bd679c-4572-490b-ae58-35b703bc93fa.PNG)


IDs and Dates (2006 to 2015)


![Ids and date](https://user-images.githubusercontent.com/79386482/183269218-2b257b65-f66c-44e6-9325-a043e20530af.PNG)


Vine and Verified


![vine and verified purchase column](https://user-images.githubusercontent.com/79386482/183269230-ebd62555-be85-4ca3-a901-716b8e73a038.PNG)


Helpful Product Reviews 


![helpful rating column](https://user-images.githubusercontent.com/79386482/183269428-0960d32d-c92a-4105-a66a-80484bb4c09f.PNG)


does paying for positive reviews make a difference here?

34% of 5 star reviews are unpaid

40% of 5 star reviews are paid

Paying for Reviews are 6% higher than unpaid

Total_paid_count:
830

Paid_five_star_count:
336

Percentage_five_star:
0.40481927710843374

Total_Unpaid_count:
855

Unpaid_five_star_count:
295

Percentage_five_star_Unpaid:
0.34502923976608185
