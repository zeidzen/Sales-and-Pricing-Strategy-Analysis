# **UK Grocery Retailer Sales and Pricing Analysis 🛒🛍️**

This repository contains code and resources for forecasting weekly sales, analyzing the impact of pricing on sales, and providing pricing strategy recommendations for a UK grocery retailer.

<img src="https://assets.epicurious.com/photos/57eebe2eb382c3c017d3fff0/16:9/w_2560%2Cc_limit/supermarket-shelves.jpg">


**This comprehensive dataset comprises three distinct datasets: Items, PriceAdjustments, and SampleSales, collectively providing vital information for conducting a detailed analysis of a leading UK grocery retailer's sales and pricing strategies. Each dataset is stored in a separate file, streamlining access and analysis.**

> **SampleSales File (Weekly Sales Data):**
This file contains detailed weekly sales data covering the years 2018 and 2019. It contains the following fields:

- ItemID: Unique identifier for each item.
- Year: The year of the recorded data.
- WeekIdentifier: Unique identifier for each week.
- SalesChannel: Channel of sales (E-commerce, Stores).
- Territory: Geographical sales region.
- NewBasePrice: Updated item base price.
- TotalInventory: Available item stock.
- StoreInventory: Item stock in stores.
- WarehouseInventory: Item stock in warehouses.
- StockedStorePercentage: Percentage of item stock in stores.
- ProjectedInventory: Estimated future inventory.
- SellingStoresRatio: Ratio of stores selling the item.
- InboundInventory: Expected incoming stock.
- SalesQuantity: Quantity of items sold.

<br>

> **PriceAdjustment File (Historic Price Change Data):**
This file offers insights into the historic price changes for each product, aiding in understanding pricing strategies over time. It includes the following fields:

- ItemID: Unique identifier for each item.
- Year: The year of the recorded data.
- WeekIdentifier: Unique identifier for each week.
- SalesChannel: Channel of sales (E-commerce, Stores).
- Territory: Geographical sales region.
- BasePrice: The original price of the item.
- PrevBasePrice: The previous base price before any adjustments.
- NewBasePrice: Updated item base price.

<br>

> **Items File (Item Hierarchy Information):**
This file provides essential information about the product hierarchy, grouping products into logical categories for easier analysis and categorization. It contains the following fields:

- ItemID: Unique identifier for each item.
- Period: Indicates the sales season.
- Category: Broad item classification.
- SubCategory: Specific item subCategory.
- Type: Item type classification.
- SubType: Sub-classification within item type.


----
**These datasets collectively empower analysts to delve deep into the historical transactional data, allowing for accurate sales volume forecasts, pricing impact assessments, and strategic pricing recommendations. This comprehensive dataset serves as a valuable resource for understanding and optimizing sales performance in the UK grocery retail sector.**
