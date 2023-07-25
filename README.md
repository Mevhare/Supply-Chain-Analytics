# Supply-Chain-Analysis-Challenge
This is my entry for Datacamp Supply Chain Analytics competition.

## Background
Test your BI skills on a real-world dataset focusing on supply chain analytics. As the main data analyst for Just In Time, you will help solve key shipment and inventory management challenges, analyze supply chain inefficiencies, and create insightful dashboards to inform business stakeholders about potential problems and propose structural business improvements.

## Data Cleaning and Transformation
After carefully investigating the data available; fulfilment, orders and shipment and inventory, some data issues were discovered and this is how they were addressed;

1. **Negative Shipment Time**: Removed records of these transactions.
2. **Orders taking too long to ship**: Given the shipment modes and reorder fulfilment times, it is highly unlikely that orders took more than 14 days to ship. Orders that took more than 14 days to ship were filtered.
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
- Number of Customers

#### Inventory
- Units Available
- Inventory Cost
- Inventory Turnover Rate
- Backorder
- Reorder Level
- Inventory in Progress

#### Shipment
- Average Delivery Time
- Late Delivery Rate

### ABC & XYZ Analysis
ABC/XYZ analysis is a tool for classifying items in a product catalogue. It can help improve inventory management, production planning, and customer satisfaction.

ABC analysis classifies products into three categories; High, Medium and Low based on revenue generated and XYZ classifies products into Stable, Flunctuant and Unstable based on their demand volatility.

Out of 118 products, 5 were classified as High-Value products, 3 were classified as Medium value products and 110 were classified as low-value products. On the other hand, 35 products were classified as Stable demand, 22 as Flunctuant demand and 66 as Unstable demand.


## Insights
### Sales
- Decline in Revenue in Q4 of 2017 due to the unavailability of highest-selling products resulted in a 70% drop in revenue compared to Q3 2017. This also translated into an 85% drop in quantity sold in Q4 2017 compared to Q3 2017.
- From October to December 2017, for the first time recorded, some markets did not make any orders; Africa (3 months), Latin America and North America (2 months) and Pacific Asia (1 month).
- Field and Stream Sportsman 16 Gun Fire Safe generated the most revenue and profit with a profit margin of 55%.
- Golf, Fanshop and Apparel were the most sold product departments with 15460, 15265 and 13277 quantity sold respectively.
- Perfect Fitness Perfect Rip Deck, Nike Men’s Dri-Fit Victory Golf Polo and O’Brien Men’s Neoprene Life Vest were the best-performing Products with 9804,9190,7709 quantities sold respectively.
- Most of our customers stay in Latin America (2667), closely followed by Europe (2645), then North America (2170), then Pacific Asia (1369) and Africa (611). 


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


