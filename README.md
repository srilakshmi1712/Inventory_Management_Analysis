#**Inventory Management Analysis**


##**Problem Statement**

Efficient inventory management is critical for organizations to:

1. Reduce operational costs
2. Evaluate inventory levels
3. Forecast demand
3. Achieve cost efficiency
4. Ensure customer satisfaction

This project addresses challenges related to demand variability, stockouts, and overstock situations. 
The primary objective was to classify inventory based on value and demand patterns using ABC and XYZ methodologies. 
Key metrics such as inventory turnover ratios, safety stock levels, and reorder points were also calculated to optimize inventory management. 
Demand forecasting through Power BI provided data-driven insights, enhancing decision-making and proactive inventory control.

##**Objectives**

1. Classify inventory based on value and demand patterns using ABC and XYZ analysis.
2. Calculate key inventory metrics such as Inventory Turnover Ratio, Safety Stock Levels, and Reorder Points
3. Identify Stock Status Categories to monitor critical items
4. Leverage Demand Forecasting to improve inventory planning and management
   
##**Data Sources**
1. Orders: (order date, SKU ID, order quantity)
2. Stock: (SKU ID, stock quantity, price)
3. Lead Time: Average duration between order placement and delivery (involves processing, manufacturing, packaging, shipping, and delivery)

##**Business Benefits**
1. Stock Planning: Helps determine reorder points to prevent stockouts
2. Supplier Evaluation: Measures supplier reliability and efficiency
3. Cost Efficiency: Reduces excessive safety stock by predicting accurate restocking times
4. Customer Satisfaction: Ensures timely fulfillment of customer orders

##****Methodology**

**1. ABC Analysis**

ABC Analysis categorizes inventory based on the revenue it generates. The steps involved include:
1. Gather data on inventory items (demand, cost, risk)
2. Rank the items from highest to lowest value
3. Calculate the percentage contribution of each item
4. Categorize items into A, B, or C groups based on their contribution to total revenue
Using Pareto's 80/20 rule, A items represent 20% of goods that generate 80% of the value, B items are moderately important, and C items are less critical.

##**2. XYZ Analysis**

XYZ Analysis classifies inventory by demand variability:
1. X items: Have consistent demand and are easy to forecast
2. Y items: Exhibit moderate demand variability (e.g., seasonality)
3. Z items: Have the highest demand variability, making them difficult to forecast
This analysis helps improve inventory accuracy, enhance forecasting, reduce waste, and increase turnover.

##**Key Metrics Calculated**

1. Inventory Turnover Ratio: Measures how often inventory is sold and replaced over a period
2. Safety Stock Calculation: Determines the optimal buffer stock to prevent stockouts
3. Reorder Points: Calculates the point at which inventory should be reordered to maintain stock levels
4. Stock Status Classification: Classifies inventory based on current stock levels (critical, low, excess)


##**Outcome**
This analysis helped optimize stock levels, reduce operational costs, and improve inventory control. By applying ABC and XYZ classification methods, businesses can focus resources on high-value and high-demand items, streamline operations, and enhance customer satisfaction through more accurate demand forecasting and stock replenishment.
