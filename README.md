# Sales-and-Pricing-Strategy-Analysis
This repository contains code and resources for forecasting weekly sales, analyzing the impact of pricing on sales, and providing pricing strategy recommendations for a UK grocery retailer.

<img src="https://assets.epicurious.com/photos/57eebe2eb382c3c017d3fff0/16:9/w_2560%2Cc_limit/supermarket-shelves.jpg">

# About Dataset 

**This comprehensive dataset comprises three distinct sets of information vital for a detailed analysis of a leading UK grocery retailer's sales and pricing strategies. The dataset is provided in three distinct files:**
> 1- **Sales_Small File (Weekly Sales Data)**
This file encompasses weekly sales data spanning the years 2015 and 2016. It contains the following fields:

- Product ID
- Channel (Online/Stores)
- Country ID
- Week key (Year and week number)
- Original selling price (OSP)
- Current selling price (CSP)
- Sales volume
- Total stock volume – representing the volume of stock in store, depot, future commitments, and intake stock at the end of the target week
- Store stock volume – indicating the volume of stock in the store at the end of the target week
- Depot stock volume – showing the volume of stock in the depot at the end of the target week
- Future commitment volume – denoting stock quantities that have been ordered but not yet received in store or depot
- Intake volume – representing stock quantities received from the supplier to the depot in the target week
- % of stores with a stock count – indicating the proportion of total stores with a positive store stock count of the product in the associated week
- % of stores with a sales count – representing the proportion of total stores with positive sales of the product in the associated week

> 2- **Price_Changes File (Historic Price Change Data)**
This dataset provides information on historic price changes for each product. It includes the following fields:

- Product ID
- Week key (Year and week number)
- Channel (Online/Stores)
- Country ID
- Original selling price (OSP)
- Price point before the most recent change
- Current selling price (CSP)


> 3- **Products File (Product Hierarchy Information)**
This file offers crucial insights into the product hierarchy, categorizing products into logical groups. It contains the following fields:

- Product ID
- 0Season – representing one of two sales seasons: Autumn/Winter or Spring/Summer
- Group
- Subgroup
- Class
- Subclass

**For instance, a product like a pair of trousers could be classified in the following hierarchy: Menswear (Group) &gt; Bottoms (Subgroup) &gt; Trousers (Class) &gt; Casual (Subclass).**

These datasets collectively empower analysts to delve deep into the historical transactional data, allowing for accurate sales volume forecasts, pricing impact assessments, and strategic pricing recommendations. This comprehensive dataset serves as a valuable resource for understanding and optimizing sales performance in the UK grocery retail sector.
