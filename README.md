# Supply-Chain-Analysis-Challenge
This is my entry for Data Camp Supply Chain Analytics competition.

## Background
Test your BI skills on a real-world dataset focusing on supply chain analytics. As the main data analyst for Just In Time, you will help solve key shipment and inventory management challenges, analyze supply chain inefficiencies, and create insightful dashboards to inform business stakeholders about potential problems and propose structural business improvements.

## Data Cleaning and Transformation
After carefully investigating the data available; fulfilment, orders and shipment and inventory, some data issues were discovered and this is how they were addressed;

1. **Negative Shipment Days**: Removed records of these transactions.
2. **Orders taking too long to ship**: Assumed these orders weren't recorded properly therefore filtered orders that took more than two weeks to ship.
3. **Correction of Country Names**: Some country's names had special characters and these were corrected to ensure correct names.

### Measures Created
#### Sales
- Net Sales
- Profit from Sales
- Profit after Inventory Costs
- Profit Margin
- Number of Orders
- Quantity Sold
- Average Order Value (AOV)

#### Inventory
- Stock Available
- Inventory Cost
- Inventory Turnover Rate
- Backorder
- Reorder Level
- Stock Indicator
- Inventory in Progress

#### Shipment
- Average Delivery Time
- Late Delivery

### XYZ & ABC Analysis
ABC/XYZ analysis is a tool for classifying items in a product catalogue. It can help improve inventory management, production planning, and customer satisfaction.

ABC analysis classifies products into three categories; High, Medium and Low based on revenue generated and XYZ classifies products into Stable, Flunctuant and Unstable based on their demand volatility.

Out of 118 products, 5 were classified as High-Value products, 3 were classified as Medium value products and 110 were classified as low-value products. On the other hand, 35 products were classified as Stable demand, 22 as Flunctuant demand and 66 as Unstable demand.


## Insights
### Sales
- Decline in Revenue in the last 3 months of 2017 due to the unavailability of highest-selling products resulting in an 85% drop in quantity ordered from September 2017. This ultimately resulted in a 16.34% drop in revenue generated in 2017 compared to 2016.
- From October to December 2017, for the first time recorded, some markets did not make any orders; Africa (3 months), Latin America and North America (2 months) and Pacific Asia (1 month).
- Field and Stream Sportsman 16 Gun Fire Safe generated the most revenue and profit despite not being the most ordered product because it is among the most expensive products with a profit margin of 55%.
- Golf, Fanshop and Apparel were the most sold product departments with 15460, 15265 and 13277 quantity sold respectively.
- Perfect Fitness Perfect Rip Deck, Nike Men’s Dri-Fit Victory Golf Polo and O’Brien Men’s Neoprene Life Vest were the best-performing Products with 9804,9190,7709 quantities sold respectively.
- 


### Inventory
- Apparel, Fanshop and Golf were the most expensive product departments to keep in inventory.
- High Value goods have the highest turnover rate of 68.86 followed by medium-value (44.18) and low-value (28.99).
- Stable demand products have the highest turnover rate of 57.1 followed by Flunctaunt demand (20.45) and Unstable demand (31.43). Unstable demand goods have a higher turnover rate than fluctuant demand products because a number of high-value products have unstable demand.
- Pelican Sunstream 100 Kayak had the highest number of backorders (253) while the remaining products all had less than 51 backorders each.

### Shipping 
- On-time Shipping is very poor due to the fact that only about 40% of orders are delivered on time.
- Most shipments were made from the USA warehouse (15904) compared to the Puerto Rico Warehouse (9688).
- 130 countries received deliveries from USA while 120 countries received deliveries from Puerto Rico.
- No significant difference in the shipment quality in terms of shipping times between Second class and Standard Class Shipping.



## Recommendations
Backordered goods: These are goods that are currently out of stock and will be shipped to you as soon as they become available.Pending shipment:** These are goods that have been ordered but have not yet been packed and shipped.
Unfulfilled order: This is an order that has not yet been shipped for any reason, such as a delay in processing or a lack of stock.
On hold:** This is an order that has been placed but is not being processed at this time. This may be due to a problem with the order, such as a missing item or an incorrect shipping address.

