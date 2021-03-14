# Amazon_Vine_Analysis

## Purpose 
The purpose of the Amazon/Vine Analysis was to compare the reviews left on items in the 'Baby' department and determine whether or not the reviews that were left by customers involved in the 'Paid Vine Campaign' showed bias. 
To determine this, we extracted the review data from Amazon, then filtered out the reviews that would prove to be most helpful and authentic.

## Results
- The total number of reviews was 27,389
- The total number of 5-start reviews was 12,235

### Vine - Paid
- The total number of reviews ('Y') with paid Vine Campaign was 463
- The total number of 5-star reviews ('Y') with paid Vine Campaign was 202
This concludes that the percentage of 5-star reviews from paid reviews totaled to <b>43.63%</b>

### Vine - Unpaid
- The total number of reviews ('N') unpaid was 25,094
- The total number of 5-star reviews ('N') unpaid was 12,033
This concludes that the percentage of 5-star reviews from unpaid reviews totaled to <b>47.95%</b>

## Summary
The data concludes that there was actually a greater percentage of 5-star reviews given from unpaid reviews than those of the paid. Again, the percentage for unpaid 5-star reviews was 47.95%, whereas 5-star reviews stemming from the paid was 43.63%. This suggests that there was no bias from those that were paid to provide reviews for items in the 'Baby' department. 

-----------------------------------------------------------------------------------------

### SQL-Postgres 
- Customers Table

![Customers_Table](https://user-images.githubusercontent.com/73874291/111086432-5728e680-84d9-11eb-91a4-5dc1f3ecb42a.png)


- Products Table

![Products_Table](https://user-images.githubusercontent.com/73874291/111086435-598b4080-84d9-11eb-9408-1c75e6b6570e.png)


- Review ID Table

![Review_ID_Table](https://user-images.githubusercontent.com/73874291/111086438-5b550400-84d9-11eb-946c-963b82010615.png)


- Vine Table

![Vine_Table](https://user-images.githubusercontent.com/73874291/111086441-5d1ec780-84d9-11eb-8a74-692e7cfdcd6a.png)
