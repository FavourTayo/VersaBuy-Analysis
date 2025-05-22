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
##### Below is an overview page of the sales dashboard and more examples are included throughout the report. The Entire Sales Dashboard can be downloaded <a href="https://github.com/FavourTayo/VersaBuy-Analysis/blob/main/Screenshot/Revenue%20dashboard.jpg">here</a>
![Screenshot](https://github.com/FavourTayo/VersaBuy-Analysis/blob/main/Screenshot/Revenue%20Dashboard2.jpg)

#### Sales Trend:
-  In 2021, November saw the highest order volume (62) and revenue ($79K). However, the highest average order value occurred in February $1.8k suggesting that while year-end drove volume, purchases were mostly made during off-peak times.
- In 2022, revenue outpaced order volume growth. December had the highest orders (64) and $73k revenue, while August led in revenue ($79k) and AOV ($1.6k), reflecting effective promotions and post-COVID spending shifts beyond holiday peaks.
- In 2023, sales peaked in June with $106K from 79 orders, showcasing strong mid-year performance, while December saw $60K despite a record of 71 orders with its average order value of +$1.1k, showing reliance on volume during peak seasons. February’s $1.6K AOV suggests more targeted, high-value campaigns in off-peak months.
-	In 2024, December had 112 orders and $112K revenue, however average order value peak occurred in august($1.5k) again highlighting that the highest volume transaction was made outside traditional peak periods. This recurring pattern suggests that while holiday season drove mass volume, VersaBuy opportunities lie in off peak months possibly tied to seasonal product launches. 
##### Below is a chart showing the sales trend year-over-year while pointing at the average order value, the order volume, and revenue.
 ![Screenshot](https://github.com/FavourTayo/VersaBuy-Analysis/blob/main/Screenshot/Sales%20Trend%20YoY.jpg)

 ### Product Performance Analysis 
 - As discount increases, the average profit margin decreases steadily and then sharply. Initially between 0% and 20% discount, the profit margin stays relatively close to 0%, slightly positive or neutral. Beyond the 20–40% discount range, the profit margin starts to dip below 0%—indicating losses begin here.From 40% onwards, the decline becomes steep, with many values droppings to -50% to -200%, suggesting that at high discounts, the company is losing money heavily.
##### Below is a chart showing impact of Discount on the profit margin. The Entire Product Performance Dashboard can be downloaded <a href="https://github.com/FavourTayo/VersaBuy-Analysis/blob/main/Screenshot/Product%20Performance%20Dashboard.jpg">here</a>
![Screenshot](https://github.com/FavourTayo/VersaBuy-Analysis/blob/main/Screenshot/Impact%20of%20Profit%20on%20Discount%205.jpg)
-	Nearly half of total company revenue comes from just three sub categories— Phones, Bookcases, and Copiers. These three subcategories accounted for $1.19M out of the total revenue of $2.54M. Phones and Bookcases, while high in sales volume, yield low profit margins, likely due to discounting or high input costs.
Copiers stand out with both healthy sales and strong profit margins, serving as a model for scalable, profitable growth. It is important to note that just like copiers, although not part of the top three, chairs also have a balanced sales volume and profit margins.
##### Below is a chart showing the highest order volume in each cayegory and sub-category
![Screenshot](https://github.com/FavourTayo/VersaBuy-Analysis/blob/main/Screenshot/Order%20Volume%20by%20Category%20and%20Sub-Category.jpg)
-	Over four years, Office Supplies made up 42% of orders—the highest volume—but had lower revenue impact due to smaller average order values. Technology (31%) and Furniture (27%) had fewer orders but generated more revenue per sale, making them more profitable categories.
-	Bookcases led Furniture with 117% order growth, followed by Chairs (40%) and Tables (41%), showing strong demand. In Office Supplies, Appliances (92%) and Binders (84%) saw the most growth, though Binders lacked profitability. Copiers (222%) and Phones (78%) drove strong order growth in Technology.
### Regional Comparison
-	The top three regions based on revenue, profit, average order value and order volume are Western Europe, Oceania, and Eastern Asia. 
##### Below is a chart the revenue patterns by region. The entire regional dashboard can be downloaded <a href="https://github.com/FavourTayo/VersaBuy-Analysis/blob/main/Screenshot/Revenue%20dashboard.jpg">here</a>
![Screenshot](https://github.com/FavourTayo/VersaBuy-Analysis/blob/main/Screenshot/Historical%20revenue%20by%20region.jpg)
-	Western Europe led in revenue and profit, driven by strong phone sales, with a 55.6% revenue increase and 44.9% profit growth despite a slight AOV drop. Oceania followed, showing high AOV ($1,692) and solid profit with fewer orders. Eastern Asia had strong margins and a 20.5% revenue and 29.1% profit rise, despite a decline in AOV efficiency.
-	In terms of sales trends, Oceania and Western Europe showed the most consistent year-over-year growth across revenue and profit, with both showing over 100% revenue increase and 150%+ profit growth from 2021 to 2024. Southern Asia, despite flat AOV, had the highest profit growth (229.6).
-	Sales distribution by subcategory varies by region, with Western Europe having the highest technology sales share at 7.77%, while Oceania leads in furniture sales at 5.73%. Southern Asia has the lowest office supplies share at 1.5%. Profit trends highlight Eastern Asia’s early dominance in 2021, but Southern Asia and Oceania take the lead in subsequent years, with Western Europe showing steady profit growth.
##### Below is a chart revenue of sub-category in each region
![Screenshot](https://github.com/FavourTayo/VersaBuy-Analysis/blob/main/Screenshot/Revenue%20by%20subcategories.jpg)
- AOV trends show Eastern Asia leading in 2021 with 182.28% growth, but Southern Asia takes over in 2022 and 2023, while Oceania peaks in 2024 at 165.88%. Central America consistently lags in AOV growth but had a leading order volume in 2021 and 2022 until western Europe surpassed it 2023 and 2024.
- The bottom regions, Southern US, Canada, and Central Asia, have significantly lower revenue and profit, with Central Asia even reporting a negative profit.
### Recommendations
-	February and August bring in bigger purchases even though they're not busy shopping months, so it's a great time to promote premium products. While November and December see more sales, people tend to spend less per order—bundles or loyalty deals could help improve profits. June and August sales show that mid-year promos work well, so we should keep doing those and make them even better.
- Limitation of discounting beyond 20%, as profit margins turn negative and sharply decline—particularly past 40%, where heavy losses occur.
- Focus pricing strategies on preserving margin, especially for high-volume but low-profit categories like Phones and Bookcases. Instead, prioritize and replicate the pricing and sales approach used for Copiers and Chairs, which show strong profitability and balanced volume.
-	Focus efforts on boosting sales of best-performing products like Astra 67531 and 3M, while evaluating lower-performing items such as Xerox 217 for possible discontinuation.
-	Although Office Supplies have the highest order volume, they contribute less to revenue—therefore, prioritize inventory management and marketing strategies on high-margin, fast-growing categories like Technology and Furniture to achieve sustainable revenue growth.
-	To drive sustained growth, prioritize increased investment in Western Europe and Oceania—focusing on technology and furniture—while enhancing sales strategies in Eastern Asia and Southern Asia to boost average order value and profitability, and simultaneously reassess and optimize operations in Southern US, Canada, and Central Asia to address their low or negative profit performance.

#### Challenges faced during analysis
While cleaning the dataset, I encountered inconsistencies in the date fields. Specifically, some date entries were stored as text strings and wrong date formats, causing parsing errors. Additionally, several date records were incomplete, missing key components such as day or month values, which required data imputation and exclusion to maintain data integrity during analysis.



 
