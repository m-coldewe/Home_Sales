# Homes Sales Key Metrics

## Overview
This project uses knowledge of SparkSQL to determine key metrics about home sales data; specifically, to create temporary views, partition the data, cache and uncache a temporary table, and finally verify that the table has been uncached. 

## Results
Using SparkSQL on home sales data, I answered the following questions:
- What is the average price for a four-bedroom house sold for each each year?

![four_bedroom](https://github.com/m-coldewe/Home_Sales/assets/152045367/de34f509-7b9a-4cdf-8af1-b6b29692cacd)


- What is the average price of a home for each year the home was built, that has three bedrooms and three bathrooms?

![three_bed_three_bath](https://github.com/m-coldewe/Home_Sales/assets/152045367/ad62b055-3429-4876-a39d-1b8e5ef00e71)


- What is the average price of a home for each year the home was built, that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet?

![three_bed_two_floors](https://github.com/m-coldewe/Home_Sales/assets/152045367/050a3037-48b1-4333-90e6-497d9d1bf4ae)


- What is the average price of a home per "view" rating having an average home price greater than or equal to $350,000?
![avg_price_350k](https://github.com/m-coldewe/Home_Sales/assets/152045367/31354c10-fe2f-4d1a-8618-a34c1c530b2a)



Uncached runtime: 1.09
Cached runtime: 1.75
Partitioned runtime: 0.04
