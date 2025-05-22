# VersaBuy-Analysis
## Project Background
VersaBuy, established in 2019 is an e-commerce wholesaler and retail distributor that caters to both modern business and niche markets.The goal was to analyze VersaBuy’s sales data, product performance, and also regional comparison to uncover actionable insights. It involved stages such as data processing, data cleaning and data visualization. 

#### Key insights and recommendations are provided on the following key areas:
-	Sales Performance Analysis: Evaluation of historical sales pattern, focusing on revenue, order volume and average order value.
-	Product Level Performance: Evaluation of how different product lines influence sales.
-	Regional Sales and Order Distribution
## Dataset Overview
VersaBuy’s dataset comprises 17,416 rows of detailed transactional data. It provides a comprehensive view of sales transactions, customer behavior, product performance, and logistics, capturing key business metrics across multiple dimensions. It includes order-level details (e.g., dates, shipping modes, costs), customer demographics (segment, location), product hierarchies (category, sub-category), and regional market segmentation.
## Executive Summary
#### Overview of Findings
- VersaBuy demonstrated a strong growth between 2021 and 2023 with order volume rising by 43.8% and revenue increasing by 48.4%, supported by steady annual average order value of +1.8%/year. 
- The first drop happened in 2024 revenue growth (28.17%) slowed slightly lower than 2023(+34.90%), order volume surging 31.9% as average order value declined by -2.6% indicates that growth relied entirely on volume not customer spend.
- The average order value highlights that while Q4 holiday month consistently drove order volume, high single month transactions occurred outside traditional peak hours.
##### Below is an overview page of the sales dashboard and more examples are included throughout the report. The entire Download can be downloaded <a href="https://github.com/FavourTayo/VersaBuy-Analysis/blob/main/Screenshot/Revenue%20dashboard.jpg">Here</a>
![Screenshot](https://github.com/FavourTayo/VersaBuy-Analysis/blob/main/Screenshot/Revenue%20Dashboard2.jpg)

#### Sales Trend:
- In 2021, November saw the highest order volume (62) and revenue ($79K), likely tied to holiday demand and post-COVID recovery spending. However, the highest average order value occurred in February $1.8k suggesting that while year-end drove volume, purchases were concentrated in non-peak periods.
- In 2022, revenue growth exceeded order volume growth, with December recording revenue ($73k) and the highest order volume (64), and august leading in revenue ($79k) suggests effective promotions or product mix adjustments. Highest average order value in August ($1.6k) points to post-COVID spending dispersion beyond traditional holiday peaks.
- In 2023, Sales peaked in June with 79 orders generating $106K revenue, showcasing strong mid-year performance, while December revenue dropped to $60k despite a record of 71 orders with its average order value of +$1.1k This divergence reveals over-reliance on volume-driven tactics in peak seasons versus value-focused approaches. Meanwhile, February had an average order value of $1.6k reinforcing that non holiday months continued to attract higher targeted campaigns.
-	In 2024, December had 112 orders and $112K revenue, however average order value peak occurred in august($1.5k) again highlighting that the highest volume transaction was concentrated outside traditional peak periods. This recurring pattern suggests that while holiday season drove mass volume, VersaBuy opportunities lie in off peak months possibly tied to seasonal product launches.
##### Below is an image showing the sales trend year over year while pointing at the average order value, the order volume, and revenue.
 ![Screenshot](https://github.com/FavourTayo/VersaBuy-Analysis/blob/main/Screenshot/Sales%20Trend%20YoY.jpg)

 ### Product Performance Analysis 
 - As discount increases, the average profit margin decreases steadily and then sharply. Initially between 0% and 20% discount, the profit margin stays relatively close to 0%, slightly positive or neutral. Beyond the 20–40% discount range, the profit margin starts to dip below 0%—indicating losses begin here.From 40% onwards, the decline becomes steep, with many values droppings to -50% to -200%, suggesting that at high discounts, the company is losing money heavily.
##### Below is an image showing the sales trend year over year while pointing at the average order value, the order volume, and revenue.
 ![Screenshot](https://github.com/FavourTayo/VersaBuy-Analysis/blob/main/Screenshot/Sales%20Trend%20YoY.jpg)

   
•	Nearly half of total company revenue comes from just three sub categories— Phones, Bookcases, and Copiers. These three subcategories accounted for $1.19M out of the total revenue of $2.54M. Phones and Bookcases, while high in sales volume, yield low profit margins, likely due to discounting or high input costs.
Copiers stand out with both healthy sales and strong profit margins, serving as a model for scalable, profitable growth. It is important to note that just like copiers, although not part of the top three, chairs also have a balanced sales volume and profit margins.
•	3M (Furniture), Astra 67531 (Phone), and Acco 7-Outlet are top-performing products by both sales and order volume. Their performance highlights them as high-value SKUs that contribute meaningfully to revenue and inventory movement. On the other hand, Xerox 217, Zipper Ring Bia, and Xero Comp are underperformers, making them candidates for review or discontinuation.
•	Office Supplies contributed 947 out of 2,274 orders (42%) over four years, making it the largest category by transaction count. Technology followed with 708 orders (31%), mainly driven by Phones and Copiers, while Furniture had 619 (27%). This suggests Office Supplies drive operational volume, but may not proportionally reflect in revenue due to lower average order values. Furniture and Technology categories, while smaller in order count, offer better revenue-per-order ratios.
•	In Furniture, Bookcases saw 117% order growth, followed by Chairs (40%) and Tables (41%), indicating strong category interest. In Office Supplies, Appliances (92%) and Binders (84%) led in order counts, though Binders have poor profitability despite volume. For Technology, Copiers grew 222% in orders, Phones 78%, confirming high user demand for these sub-categories.


 
