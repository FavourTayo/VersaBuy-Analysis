# VersaBuy-Analysis
## Project Background
VersaBuy, established in 2019 is an e-commerce wholesaler and retail distributor that caters to both modern business and niche markets.The goal was to analyze VersaBuy’s sales data, product performance, impact of discount on profit margin and also regional comparison to uncover actionable insights. It involved stages such as data processing, data cleaning and data visualization. 

#### Key insights and recommendations are provided on the following key areas:
-	Sales Performance Analysis: Evaluation of historical sales pattern, focusing on revenue, order volume and average order value.
-	Product Level Performance: Evaluation of how different product lines influence sales.
-	Regional Comparison
## Dataset Overview
VersaBuy’s dataset comprises of 17,416 rows of detailed transactional data. It provides a comprehensive view of sales transactions, customer behavior, product performance, capturing key business metrics across multiple dimensions. It includes order-level details (e.g., dates, shipping modes, costs), customer demographics (segment, location), product hierarchies (category, sub-category), and regional market segmentation.
## Executive Summary
#### Overview of Findings
- VersaBuy demonstrated a strong growth between 2021 and 2023 with order volume rising by 43.8% and revenue increasing by 48.4%, supported by steady annual average order value of +1.8%/year. 
- The first drop happened in 2024 revenue growth (28.17%) slowed slightly lower than 2023(+34.90%), order volume surging 31.9% as average order value declined by -2.6% indicates that growth relied entirely on volume not customer spend.
- The average order value highlights that while Q4 holiday month consistently drove order volume, high single month transactions occurred outside traditional peak hours.
##### Below is an overview page of the sales dashboard and more examples are included throughout the report. The entire Sales Dashboard can be downloaded <a href="https://github.com/FavourTayo/VersaBuy-Analysis/blob/main/Screenshot/Revenue%20dashboard.jpg">Here</a>
![Screenshot](https://github.com/FavourTayo/VersaBuy-Analysis/blob/main/Screenshot/Revenue%20Dashboard2.jpg)

#### Sales Trend:
- In 2021, November saw the highest order volume (62) and revenue ($79K), likely tied to holiday demand and post-COVID recovery spending. However, the highest average order value occurred in February $1.8k suggesting that while year-end drove volume, purchases were concentrated in non-peak periods.
- In 2022, revenue growth exceeded order volume growth, with December recording revenue ($73k) and the highest order volume (64), and august leading in revenue ($79k) suggests effective promotions or product mix adjustments. Highest average order value in August ($1.6k) points to post-COVID spending dispersion beyond traditional holiday peaks.
- In 2023, Sales peaked in June with 79 orders generating $106K revenue, showcasing strong mid-year performance, while December revenue dropped to $60k despite a record of 71 orders with its average order value of +$1.1k This divergence reveals over-reliance on volume-driven tactics in peak seasons versus value-focused approaches. Meanwhile, February had an average order value of $1.6k reinforcing that non holiday months continued to attract higher targeted campaigns.
-	In 2024, December had 112 orders and $112K revenue, however average order value peak occurred in august($1.5k) again highlighting that the highest volume transaction was concentrated outside traditional peak periods. This recurring pattern suggests that while holiday season drove mass volume, VersaBuy opportunities lie in off peak months possibly tied to seasonal product launches.
##### Below is a chart showing the sales trend year-over-year while pointing at the average order value, the order volume, and revenue.
 ![Screenshot](https://github.com/FavourTayo/VersaBuy-Analysis/blob/main/Screenshot/Sales%20Trend%20YoY.jpg)

 ### Product Performance Analysis 
 - As discount increases, the average profit margin decreases steadily and then sharply. Initially between 0% and 20% discount, the profit margin stays relatively close to 0%, slightly positive or neutral. Beyond the 20–40% discount range, the profit margin starts to dip below 0%—indicating losses begin here.From 40% onwards, the decline becomes steep, with many values droppings to -50% to -200%, suggesting that at high discounts, the company is losing money heavily.
##### Below is a chart showing impact of Discount on the profit margin. The entire product performance dashboard can be downloaded <a href="https://github.com/FavourTayo/VersaBuy-Analysis/blob/main/Screenshot/Product%20Performance%20Dashboard.jpg">Here</a>
![Screenshot](https://github.com/FavourTayo/VersaBuy-Analysis/blob/main/Screenshot/Impact%20of%20Profit%20on%20Discount%205.jpg)
-	Nearly half of total company revenue comes from just three sub categories— Phones, Bookcases, and Copiers. These three subcategories accounted for $1.19M out of the total revenue of $2.54M. Phones and Bookcases, while high in sales volume, yield low profit margins, likely due to discounting or high input costs.
Copiers stand out with both healthy sales and strong profit margins, serving as a model for scalable, profitable growth. It is important to note that just like copiers, although not part of the top three, chairs also have a balanced sales volume and profit margins.
##### Below is a chart showing the highest order volume in each cayegory and sub-category
![Screenshot](https://github.com/FavourTayo/VersaBuy-Analysis/blob/main/Screenshot/Order%20Volume%20by%20Category%20and%20Sub-Category.jpg)
-	Office Supplies contributed 947 out of 2,274 orders (42%) over four years, making it the largest category by transaction count. Technology followed with 708 orders (31%), mainly driven by Phones and Copiers, while Furniture had 619 (27%). This suggests Office Supplies drive operational volume, but may not proportionally reflect in revenue due to lower average order values. Furniture and Technology categories, while smaller in order count, offer better revenue-per-order ratios.
-	In Furniture, Bookcases saw 117% order growth, followed by Chairs (40%) and Tables (41%), indicating strong category interest. In Office Supplies, Appliances (92%) and Binders (84%) led in order counts, though Binders have poor profitability despite volume. For Technology, Copiers grew 222% in orders, Phones 78%, confirming high user demand for these sub-categories.
### Regional Comparison
-	The top three regions based on revenue, profit, average order value and order volume are Western Europe, Oceania, and Eastern Asia. 
##### Below is a chart the revenue patterns by region. The entire regional dashboard can be downloaded <a href="https://github.com/FavourTayo/VersaBuy-Analysis/blob/main/Screenshot/Revenue%20dashboard.jpg">here</a>
![Screenshot](https://github.com/FavourTayo/VersaBuy-Analysis/blob/main/Screenshot/Revenue%20by%20subcategories.jpg)
-	Western Europe ranks highest in both revenue and profit, driven largely by phone sales within the technology sub-category. Despite modest AOV growth decline (143.85% to 125.9%), and the highest order volume of 257 revenue rose to 55.6% (2021-2024) with steady profitability (+44.9%). Oceania ranks second in revenue and profit, with a higher AOV of $1,692 but fewer orders at 190. Eastern Asia stands out for strong profit margins, supported by an AOV of $1,669 and 167 orders. Its AOV rose from 182.28% in 2021 to 155.88% in 2024, indicating a slight decline in pricing efficiency over time. Nevertheless, revenue climbed from $83,977 in 2021 to $101,250 in 2024 (20.5% growth), and profit jumped from $17,475 to $22,560 (29.1%) reflecting high efficiency in both sales and margins
-	In terms of sales trends, Oceania and Western Europe showed the most consistent year-over-year growth across revenue and profit, with both showing over 100% revenue increase and 150%+ profit growth from 2021 to 2024. Southern Asia, despite flat AOV, had the highest profit growth (229.6).
-	Sales distribution by subcategory varies by region, with Western Europe having the highest technology sales share at 7.77%, while Oceania leads in furniture sales at 5.73%. Southern Asia has the lowest office supplies share at 1.5%. Profit trends highlight Eastern Asia’s early dominance in 2021, but Southern Asia and Oceania take the lead in subsequent years, with Western Europe showing steady profit growth.
##### Below is a chart showing the highest order volume in each cayegory and sub-category
![Screenshot](https://github.com/FavourTayo/VersaBuy-Analysis/blob/main/Screenshot/Revenue%20by%20subcategories.jpg)
-AOV trends show Eastern Asia leading in 2021 with 182.28% growth, but Southern Asia takes over in 2022 and 2023, while Oceania peaks in 2024 at 165.88%. Central America consistently lags in AOV growth but had a leading order volume in 2021 and 2022 until western Europe surpassed it 2023 and 2024.
-The bottom regions, Southern US, Canada, and Central Asia, have significantly lower revenue and profit, with Central Asia even reporting a negative profit.
### Recommendations
-	February and August bring in bigger purchases even though they're not busy shopping months, so it's a great time to promote premium products. While November and December see more sales, people tend to spend less per order—bundles or loyalty deals could help improve profits. June and August sales show that mid-year promos work well, so we should keep doing those and make them even better.
- Limitation of discounting beyond 20%, as profit margins turn negative and sharply decline—particularly past 40%, where heavy losses occur.
- Focus pricing strategies on preserving margin, especially for high-volume but low-profit categories like Phones and Bookcases. Instead, prioritize and replicate the pricing and sales approach used for Copiers and Chairs, which show strong profitability and balanced volume.
-	Focus efforts on boosting sales of best-performing products like Astra 67531 and 3M, while evaluating lower-performing items such as Xerox 217 for possible discontinuation.
-	Although Office Supplies have the highest order volume, they contribute less to revenue—therefore, prioritize inventory management and marketing strategies on high-margin, fast-growing categories like Technology and Furniture to achieve sustainable revenue growth.
-	To drive sustained growth, prioritize increased investment in Western Europe and Oceania—focusing on technology and furniture—while enhancing sales strategies in Eastern Asia and Southern Asia to boost average order value and profitability, and simultaneously reassess and optimize operations in Southern US, Canada, and Central Asia to address their low or negative profit performance.

#### Challenges faced during analysis
While cleaning the dataset, I encountered inconsistencies in the date fields. Specifically, some date entries were stored as text strings and wrong date formats, causing parsing errors. Additionally, several date records were incomplete, missing key components such as day or month values, which required data imputation and exclusion to maintain data integrity during analysis.



 
