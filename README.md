**1.	Introduction**

This analysis evaluates 2500 sales records for furniture sales and profitability performance across key business dimensions, including product category, brand, color, material, season, location, and store type. Using 62,310 sales transactions, the analysis examines the net revenue, gross profit, discounts, and profit margins to identify key profitability drivers and underperforming segments. The findings provide data-driven insights to support pricing, inventory management, product strategy, seasonal planning, and overall profitability improvement within the furniture retail business.

 <img width="975" height="466" alt="image" src="https://github.com/user-attachments/assets/89a57ade-2ade-4475-97c8-ee6e7eaf36d7" />

Furniture sales and profitability dashboard

**2. Story of Data**

**Data Source:** The dataset used for this analysis was sourced from Kaggle.com, a widely used platform for data science and analytics datasets. 

**Dataset Structure:** The raw dataset is structured in rows and columns, comprising 2,500 furniture sales records. Each row represents an individual sales record, while the columns contain relevant product, sales, and operational attributes, including Category, Material, Color, Location, Season, Store Type, Brand, Unit Price, Cost Price, Sales Volume, Profit Margin Percentage, Inventory, Discount Percentage, Delivery Days, and Revenue. This structure provides a comprehensive basis for analyzing sales performance, profitability, product characteristics, and operational efficiency within the furniture retail business.

**Story Data is Telling:** The dataset tells the story of a furniture retail business generating strong sales across diverse products, brands, materials, locations, seasons, and sales channels. With 2,500 sales records the analysis can tell a full story of furniture sales profitability across products, brands, locations, seasons, materials, and store types which can help to identify the strongest and weakest profit contributors, revealing where the business makes the most money, which products and brands drive profitability, and how performance varies across markets and seasons. This will provide a basis for optimizing product mix, inventory, pricing, store strategy, and resource allocation to improve overall profitability.

**3. Data Splitting and Preprocessing**

**Data Cleaning:** To ensure data quality and establish a reliable foundation for analysis, the dataset was reviewed for empty rows, missing values, and duplicate records. The validation confirmed that the dataset contained no empty rows, missing values, or duplicate records, indicating a complete and consistent data structure. For improved readability and navigation, the dataset was formatted to enhance the visibility and organization of column headers and cell contents. The top row was frozen to keep the column headers visible while scrolling through the records. The dataset was also converted into a standard Excel Table, providing a structured format that supports efficient data organization, filtering, accessibility, and subsequent transformation and analysis.

**Data Transformation:** Data transformation was performed in Microsoft Excel by creating calculated columns using formulas derived from the existing Unit Price, Cost Price, Sales Volume, and Discount Percentage fields. These transformations generated key financial metrics including Gross Revenue, Gross Profit, Gross Discount, Net Revenue, COGS, Actual Unit Price, Profit Per Unit Sold, Profit After Discount, and Net Profit Margin. The calculated fields provided a consistent basis for evaluating revenue generation, discount impact, cost structure, and profitability across the furniture sales dataset.

<img width="797" height="697" alt="image" src="https://github.com/user-attachments/assets/5b8fc0df-ffac-4b4a-a922-d412d4753728" />

**Data Splitting:** The dataset was divided into two main categories to enable a more focused analysis and provide clearer insights into distinct aspects of the furniture sales data.

**A. Category One** — Independent value

Category 

Material 

Color 

Location 

Season

Store_Type 

Brand 

**B. Category Two** — Dependent value

Unit Price 

Cost Price 

Sales Volume 

Profit_Margin_Percentage 

Profit Per Unit Sold 

Gross Profit 

Discount Per Unit Price 

Actual Unit Price 

Profit After Discount 

Inventory 

Discount_percentage 

Gross Revenue 

Gross Discount 

Net Revenue

Net Profit Margin 

COGS 

**Industry Context:** The dataset is relevant to the Retail Industry, with a specific focus on Furniture and Home Furnishings, covering sales performance, product characteristics, profitability, discounts, inventory, and store-channel performance.

**Stakeholders:** The stakeholders of this project may include the Furniture Retailers & Business Owners, Store Managers, Sales Managers, Merchandising/Product Managers, Inventory & Supply Chain Managers, Marketing Managers, Regional Managers, Financial Analysts, Procurement Managers, Executive Management, Data Team.

**Success to the Industry:** Success in the Retail Industry means maximizing profitable furniture sales by optimizing product assortment, pricing, inventory, brand selection, store performance, and geographical and seasonal strategies while minimizing operational costs.

**4. Potential-Analysis**

Areas identified for potential profitability analysis during the pre-analysis phase are outlined below.

•	Net Profit by Color

•	Net Profit by Category

•	Net Profit by Brand

•	Net Profit by Season

•	Net Profit by Location

•	Net Profit by Material

•	Net Profit by Store Type

**Initial Insights**

•	Identify the colors generating the highest and lowest net profit. High-profit colors may indicate stronger customer preference or better margins, while low-profit colors may require pricing or inventory review.

•	Determine which product categories contribute the largest share of net profit. High-performing categories should receive greater inventory and marketing attention, while weak categories may need repositioning or cost optimization.

•	Compare profitability across brands to identify the most and least profitable brands. A brand generating high sales but low profit could indicate discounting or high acquisition costs, while highly profitable brands may deserve stronger promotion.

•	Examine how profitability changes across seasons. Strong seasonal periods can guide inventory planning, promotions and staffing, while weak periods may require targeted campaigns or cost control.

•	Identify locations contributing the highest and lowest net profit. High-profit locations may represent priority markets, while low-profit locations require investigation into demand, operating costs, pricing or product mix.

•	Determine which materials are associated with the highest profitability. This may reveal customer preferences and help optimize product sourcing, production and inventory allocation.

•	Compare profitability across store formats/types. This helps determine which retail formats generate stronger returns and where expansion or operational improvements may be justified.

**5. In-Analysis**

**1. Analysis - Net Profit by Color**  

**Observations**

Blue generated the highest net profit at $467,597.04, followed by Red $452,252.65 and White $439,528.27. Black contributed $434,931.89, while Brown generated $411,194.79. Green recorded the lowest net profit at $378,212.15.

**Insights**

•	Blue is the most profitable color, generating $467,597.04, making it the strongest contributor to net profit. 

•	Red and White also performed strongly, generating $452,252.65 and $439,528.27, respectively. 

•	Green recorded the lowest net profit at $378,212.15, indicating weaker profitability compared with the other colors. 

•	The gap between the highest and lowest performers is approximately $89,385, suggesting a meaningful difference in profitability by color.

**2. Analysis - Net Profit by Category**

**Observations**

Table generated the highest net profit at $545,160.66, followed by Chair $530,696.88 and Sofa $529,719.02. Desk contributed $519,990.33, while Bed recorded the lowest net profit at $458,149.90.

**Insights**

•	Tables are the most profitable category, generating $545,160.66. Chairs and sofas also show strong profitability, with both exceeding $529,000. 

•	Desks remain a strong contributor at $519,990.33, although slightly below the top three categories. 

•	Beds recorded the lowest net profit at $458,149.90, indicating weaker profitability relative to the other categories. 

•	The difference between the highest and lowest categories is approximately $87,011, showing a notable profitability gap. 

•	Tables, chairs, and sofas are the strongest profit contributors and could be prioritized in inventory, marketing, and sales strategies.

**3. Analysis - Net Profit by Brand**

**Observations**

BrandC generated the highest net profit at $661,020.97, followed by BrandD $652,623.53 and BrandA $650,882.51. BrandB recorded the lowest net profit at $619,189.77.

**Insights**

•	BrandC is the most profitable brand, generating $661,020.97. BrandD and BrandA performed strongly, with profits above $650,000. 

•	BrandB recorded the lowest net profit at $619,189.77, trailing BrandC by approximately $41,831. 

**4. Analysis - Net Profit by Season**

**Observations**

Fall generated the highest net profit at $712,784.23, followed by Winter $674,119.72 and Spring $611,810.99. Summer recorded the lowest net profit at $585,001.85.

**Insights**

•	Fall is the strongest season, generating $712,784.23 in net profit. 

•	Winter also performed strongly, with $674,119.72, making it the second-most profitable season. 

•	Spring generated $611,810.99, placing it in the middle of the seasonal performance ranking. 

•	Summer recorded the lowest profit at $585,001.85, approximately $127,782 below Fall. 

•	The results show a clear seasonal profitability pattern, with Fall and Winter outperforming Spring and Summer.

**5. Analysis - Net Profit by Location**

**Observations**

The suburban area contributed the highest share of net profit at 35.70%, followed by rural area at 34.35%. The urban area accounted for 29.95%, making it the lowest contributor.

**Insights**

•	Suburban locations lead profitability, contributing 35.70% of total net profit. 

•	Rural locations are also strong performers at 34.35%, only 1.35 percentage points behind Suburban locations. 

•	Urban locations recorded the lowest contribution at 29.95%, suggesting comparatively lower profitability.

•	Investigate the factors driving strong performance in Suburban and Rural markets and identify opportunities to improve profitability in Urban locations.

**6. Analysis - Net Profit by Material**

**Observations**

Wood generated the highest net profit at $577,281.30, followed by Metal ($523,251.87) and Glass ($509,296.33). Plastic contributed $495,311.04, while Fabric recorded the lowest net profit at $478,576.24.

**Insights**

•	Wood is the most profitable material, generating $577,281.30 and outperforming all other materials.

•	Metal and Glass are also strong contributors, generating $523,251.87 and $509,296.33, respectively. 

•	Plastic recorded a moderate profit of $495,311.04. Fabric generated the lowest net profit at $478,576.24, approximately $98,705 below Wood. 

•	The results suggest that Wood-based furniture is a particularly strong profit driver, potentially reflecting higher demand, pricing, or margins.

**7. Analysis - Net Profit by Store Type**

**Observations**

Online stores generated the larger share of net profit at 52.30%, while Retail stores contributed 47.70%

**Insights**

•	Online sales lead profitability, contributing 52.30% of total net profit. 2. Retail stores also remain a strong contributor at 47.70%, showing that both channels play an important role.

•	Examine the factors driving strong performance in the online store and identify opportunities to improve profitability in retail store.

**6. Post-Analysis and Insights**

**•	Strong revenue and sales volume** - Net revenue stands at $14.55M from 62,310 units sold, indicating substantial sales activity. The business has a broad customer and product base rather than relying on a single product or channel.

**•	Discounts are the biggest profitability concern** - Gross discount reached $2.53M, which is almost 49.4% of gross profit $5.11M making profit after discount fall to $2.58M.  This suggests that aggressive discounting is having a significant impact on profitability.

**•	Profitability is relatively well distributed across brands** - BrandC leads with $661,020.97, while BrandB is lowest at $619,189.77. The relatively small gap of about $41,831 suggests that no single brand dominates profitability.

**•	Wood is the strongest material** - Wood generated $577,281.30, the highest profit among the materials while fabric generated the lowest profit at $478,576.24. This creates an opportunity to investigate whether wood products have stronger demand, pricing, or margins.

**•	Tables shows the strongest product category by profit** - Tables generated $545,160.66 profit, followed closely by Chairs and Sofas. Beds were the weakest category at $458,149.90 profit. The business could examine whether the lower profitability of beds is caused by pricing, production costs, demand, or discounting

**•	Highest profit in Fall season** - Fall generated the highest profit at $712,784.23, while Summer generated $585,001.85. This indicates a meaningful seasonal difference in profitability. Inventory and promotional strategies should therefore be aligned with seasonal demand.

**•	Relatively balanced profitability by location** - Suburban areas contributed 35.70% of the total profit, Rural 34.35%, and Urban 29.95%. The spread suggests that the business is not overly dependent on one location type.

**•	Online sales have a slight profitability advantage** - Online contributed 52.30% of profit compared with 47.70% from Retail. The relatively close split suggests that an omnichannel strategy is important rather than relying exclusively on either channel.

**•	Blue is the best-performing color by profit** - Blue generated $467,597.04, while Green generated $378,212.15. The approximately $89,385 gap suggests that product color may influence profitability, although sales volume and product mix should be examined before attributing the difference directly to customer preference.

**7. Charts and Visualizations**
 
<img width="762" height="269" alt="Screenshot 2026-08-19 174838" src="https://github.com/user-attachments/assets/8747f98a-8aaf-4c2e-8eba-e01b27005aec" />

This column chart shows profit made by each color base furniture sold. It indicates that blue color made the highest profit while green made the least profit. 

 <img width="606" height="269" alt="Screenshot 2026-08-19 174904" src="https://github.com/user-attachments/assets/1efb85ce-249b-4b7a-a3b3-fc45e5d4593c" />

The bar-chart show the profit made by each furniture category. Table account for the highest profit of $545,160.66 while bed account for the lowest profit. 
 
 <img width="531" height="262" alt="Screenshot 2026-08-19 174926" src="https://github.com/user-attachments/assets/c550f3bc-cd01-4fe3-aac2-1120bf6e253a" />

This bar-chart shows brands by their profits where BrandC tops by $661,020.97 and BrandB had the lowest profit of $619,189.77. 

 <img width="299" height="266" alt="Screenshot 2026-08-19 174946" src="https://github.com/user-attachments/assets/1c5a4f74-5fc7-4854-97eb-66c10b513b0a" />

This pie-chart shows the percentages of profit made in each location. Suburban tops by 35.70% followed by Rural 34.35% and Urban 29.95%

<img width="527" height="267" alt="Screenshot 2026-08-19 175007" src="https://github.com/user-attachments/assets/abc33a54-e7ff-4392-857b-a8c372ac1d3b" />

This column chart indicates profit made in each season. It shows that Fall accounted for the highest while summer accounts for the lowest profit. 

**8. Post Analysis Recommendations**

**•	Reduce excessive discounting:**  The $2.53M gross discount is the biggest profitability concern. 
Cutdown or Introduce discount limits and target promotions rather than broad discounts. 
Monitor whether discounts actually generate enough additional sales to justify the lost margin.

**•	Prioritize high profit products:**  Increase focus on Tables, Chairs, and Sofas, which are among the strongest categories.  Ensure these products have adequate inventory and prominent placement across online and physical stores.

**•	Increase focus on high performing materials:** Wood generated the highest material level profit at $577,281.30. Consider expanding the range of profitable wood-based furniture while monitoring material costs and supply availability

**•	Optimize seasonal inventory:** Fall and Winter are the strongest profit-generating seasons. 
Increase inventory and marketing activities ahead of these periods while using targeted promotions to stimulate demand during weaker seasons such as Summer.

**•	Strengthen the online sales channel:** Online sales contribute 52.30% of profit, slightly ahead of retail at 47.70%. Invest in digital marketing, website usability, product presentation, delivery experience, and customer retention

**•	Improve weaker performing segments:** Investigate why Beds, Fabric products, Green products, BrandB, and Summer sales generate comparatively lower profits. Assess their pricing, demand, production costs, discount levels, and sales volumes before making decisions to reduce or discontinue them.

**•	Replicate successful location strategies:** Suburban and Rural locations outperform Urban locations. Investigate the factors driving their performance such as product mix, pricing, customer demand, and operating costs and apply relevant strategies to Urban markets

**•	Strengthen brand level profitability management:** Although BrandC leads profitability, the relatively narrow gap between the brands suggests a balanced portfolio. Rather than focusing exclusively on one brand, identify the specific products and pricing strategies responsible for higher margins within each brand.

**•	Monitor profit margin as a core KPI:** With an average profit margin of 17.09%, management should track margin alongside revenue and sales volume. A rise in sales should not be considered successful if it comes primarily from heavy discounting and produces little additional profit.

**9.   Conclusion**

The analysis provides a comprehensive view of the furniture retail business's sales and profitability performance across products, brands, materials, seasons, locations, and store types. The business generated $14.55 million in net revenue and $2.58 million net profit from 62,310 units sold, demonstrating strong sales activity and a diverse revenue base. The analysis also identified key profitability drivers, including Fall season, Wood materials, Tables, BrandC, Suburban locations, and Online sales. However, a $2.53 million in gross discounts which is almost 49.4% of gross profit $5.11M from total sales represents a significant opportunity to improve profit retention, contributing to a relatively modest 17.09% average profit margin. The findings suggest that the business can strengthen financial performance by improving discount management, prioritizing high-performing products and materials, optimizing seasonal inventory, and strengthening profitable sales channels. A more data-driven approach to pricing, product mix, and inventory allocation can help the business increase profitability while maintaining strong sales performance.

**10. 	References**

https://kaggle.com

https://flaticon.com

https://tristen.ca/hcl-picker
