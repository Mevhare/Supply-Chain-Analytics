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
- Number of Customers

#### Inventory
- Units Available
- Inventory Cost
- Inventory Turnover Rate
- Overstock/Backorder
- Reorder Level
- Inventory in Progress

#### Shipment
- Average Delivery Time
- Late Delivery Rate

### ABC & XYZ Analysis
ABC/XYZ analysis is a tool for classifying items in a product catalogue. It can help improve inventory management, production planning, and customer satisfaction.

ABC analysis classifies products into three categories; High, Medium and Low based on revenue generated and XYZ classifies products into Stable, Flunctuant and Unstable based on their demand volatility.

Out of 118 products, 5 were classified as High-Value products, 3 were classified as Medium value products and 110 were classified as low-value products. On the other hand, 35 products were classified as Stable demand, 22 as Flunctuant demand and 66 as Unstable demand.

### Data flaws
Profit figures aren't logical because higher profits were generated on prices eg $150 profit on a $100 sale. The assumption is made that there are different suppliers, multiple wholesale discounts or Just In Time is being paid by brands to sell their products. 


## Insights
### Sales
- Decline in Revenue in Q4 of 2017 due to the unavailability of highest-selling products resulted in a 70% drop in revenue compared to Q3 2017. This also translated into an 85% drop in quantity sold in Q4 2017 compared to Q3 2017.
- More than 90% of sales were made to new customers in Q4 2017.
- From October to December 2017, for the first time recorded, some markets did not make any orders; Africa (3 months), Latin America and North America (2 months) and Pacific Asia (1 month).
- Field and Stream Sportsman 16 Gun Fire Safe generated the most revenue and profit with a profit margin of 55%.
- Golf, Fanshop and Apparel were the most sold product departments with 15460, 15265 and 13277 quantity sold respectively.
- Perfect Fitness Perfect Rip Deck, Nike Men’s Dri-Fit Victory Golf Polo and O’Brien Men’s Neoprene Life Vest were the best-performing Products with 9804,9190,7709 quantities sold respectively.
- Dell laptop, SOLE E25 and E35, Bushnell pro-X7 Rangefinder and Bowflex 1090 dumbbells didn't record a single sale for the three-year period of 2015-2017


### Inventory
- Apparel, Fanshop and Golf were the most expensive product departments to keep in inventory.
- High Value goods have the highest turnover rate of 68.86 followed by medium-value (44.18) and low-value (28.99).
- Stable demand products have the highest turnover rate of 57.1 followed by Flunctaunt demand (20.45) and Unstable demand (31.43). Unstable demand goods have a higher turnover rate than fluctuant demand products because a number of high-value products have unstable demand.
- Golf, Fan Shop and Apparel product departments struggled with backorders the most.

### Shipping 
- On-time Shipping is very poor due to the fact that only about 40% of orders are delivered on time.
- Most shipments were made from the USA warehouse (15904) compared to the Puerto Rico Warehouse (9688).
- 130 countries received deliveries from USA while 120 countries received deliveries from Puerto Rico.
- No significant difference in the shipment quality in terms of shipping times between Second class and Standard Class Shipping.



## Recommendations

### Sales
- Forecasting and Replenishment: Implement a more effective inventory forecasting and replenishment system. This can help ensure high-selling products are always in stock, preventing revenue losses like those experienced in Q4 2017.
- Targeted Marketing Initiatives: For markets that didn't make orders for certain periods, consider deploying targeted marketing strategies. It could be pop-up sales, discounts or bundles targeted specifically for those markets.
- Promote High-Margin Products: Double down on promotional strategies around your highest-margin products like the Fire Safe, to optimize profits. This might include product positioning, up-selling and cross-selling, or strategic pricing.
- Customer Retention: Given the high percentage of new customer sales in Q4 2017, fostering customer loyalty and repeat business with an effective customer retention strategy would be beneficial. This could include personalized follow-up communications, loyalty programs or exclusive discounts for returning customers.

  
### Inventory
- Demand-based Management: Consider refining inventory management strategies based on product demand. High-value goods tend to have higher turnover rates, so it's beneficial to maintain smaller, more frequent replenishment cycles for these products to continue this trend.
- Preventing backorders: Leverage historical sales data for product departments with high backorders, like Golf, Fan Shop and Apparel, to anticipate demand and prevent future backorders.


### Shipping
- Revamp the Delivery Process: To increase on-time shipping, evaluate the current delivery process, identify inefficiencies, and consider alternative logistics strategies. Perhaps consider outsourcing to a third-party logistics provider if in-house improvements aren't enough.
- Optimize Warehouse Operations: If far more shipments are coming from the USA warehouse than Puerto Rico, you may need to rebalance your inventory locations. Consider splitting products based on the geographical demand between your warehouses to optimize delivery times.
- Review Shipping Classes: It's important to distinguish between different shipping classes. If there's no perceived difference, customers won't see the value in paying for premium shipping options. Start by differentiating clearly and guaranteeing delivery periods for your Standard Class Shipping.

## Dashboard
Power BI Link: https://app.powerbi.com/view?r=eyJrIjoiZDhhZWQ2NjYtZDlmNS00ZTUwLWFmYTktZDUyNTc3NTlhOGUwIiwidCI6ImRmODY3OWNkLWE4MGUtNDVkOC05OWFjLWM4M2VkN2ZmOTVhMCJ9


![Afe_Mevhare_just_in_time](Afe_Mevhare_just_in_time.jpg)



