# Project Overview

This report analyzes sales data from a retail store operating between **2015 and 2018**. 

The dataset includes **9,789 rows** and **17 columns** representing various dimensions of business operations, from customer transactions to product categories, shipping logistics, and geographic locations. The goal is to uncover actionable insights that can drive smarter business decisions across product, customer, operations, and marketing strategy.

# Dataset Structure

**Identifiers & Customer Info**: Row_ID, Order_ID, Customer_ID, Customer_Name

**Shipping Info**: Ship_Mode, Order_Date_Clean, Ship_Date_Clean

**Customer Segmentation**: Segment, Country, City, State, Postal_Code, Region

**Product Info**: Product_ID, Category, Sub_Category

**Sales Info**: Sales_Clean

The cleaned dataset enables a structured and meaningful analysis across the following key stakeholder questions.

# 🧑‍💼 Stakeholder Context & Business Questions

The following five questions were posed by different departments to support strategic decision-making:

### "Are there any seasonal trends in sales performance?"
- Asked by: Marketing Director
- Purpose: Align promotional planning and staffing with seasonal demand.
  
### "Which product categories drive the most revenue, and how does that vary by region?"
- Asked by: Head of Product & Merchandising
- Purpose: Optimize inventory planning and product strategy across regions.

### "Who are our top customer segments, and what do they buy?"
- Asked by: VP of Sales & Customer Strategy
- Purpose: Tailor marketing and retention efforts based on buyer behavior.

### "What is the shipping performance like – are there delays between order and ship date?"
- Asked by: Logistics & Fulfillment Manager
- Purpose: Identify areas for operational improvement in delivery timelines.

### "Which states or cities generate the most revenue, and are we over-relying on certain regions?"
- Asked by: Regional Sales Strategy Lead
- Purpose: Guide geographic expansion and de-risk revenue concentration.



# Executive Summary
- **Seasonality & Growth Trends**: **November** is the peak sales month every year with **February** the **lowest**.
  Overall **sales grew 31% in 2017 and 21% in 2018**, showing strong upward momentum. These trends are consistent across product and customer segments.
  
- **Product Category Performance**: **Technology** leads sales across all regions especially **East and West**.
  **Q4** consistently drives peak sales while **Q1** lags. In **underperforming** regions like the **South**, no category stands out, hinting at missed market potential.
  
- **Seasonality & Growth Trends**: **November** is the peak sales month every year with **February** the lowest
  Overall sales grew **31**% in 2017 and **21**% in 2018, showing strong upward momentum. These trends are consistent across product and customer segments.
  
- **Customer Segment Behavior**: **Consumer** segment dominates (**51**% of sales), but **Corporate** has grown significantly since 2017.
  **Technology** and **Furniture** are the top categories, and all segments show clear seasonal patterns (**Q4 peak, Q1 dip**).
  
- **Shipping Performance**: **67**% of orders are delivered on time, but **Standard Class**, though most use, accounts for **30**% of delays
  **New York and LA** contribute heavily to delayed shipments, with **Office Supplies and Binders being the most affected**.
  
- **Geographic Revenue Concentration**: **California and New York drive 34% of total sales**, while **NYC** and **LA** alone contribute **19**%. **The South** underperforms significantly, highlighting both concentration risk and growth opportunity.


# Insights and Findings
# 1. Are there any seasonal trends in sales performance?

## Key Insight Summary
- **2018** marked the highest total sales, with **21**% YoY growth from **2017**  strong upward trend in business performance.
- **February** is the **weakest** sales month across all years,  likely due to the  post-holiday dip and fewer working days.
- **Q4** is consistently the **peak** quarter, especially in **November**,  aligning with seasonal demand like Black Friday and holiday shopping.
- **Upward sales trend from Q1 to Q4 every year** — presents a reliable pattern for inventory planning and campaign launches.

### Yearly Sales Trend:
 ![image](https://github.com/user-attachments/assets/c408a712-b8fa-4249-8df9-34fbb64b155c)

- **2016** experienced a **-5% sales dip**.
- In **2017**, sales **rebounded sharply by +31%**  a significant recovery and growth.
- **2018** continued **upward momentum with +21% YoY growth**, reaching the **highest annual sales total.**

### Quarterly Seasonality:
 ![image](https://github.com/user-attachments/assets/3e24fdbc-dbf9-4c87-9b4c-cab1cd90a0f2)
- **Q1** is consistently the **lowest-performing quarter**, likely due to the consumer slowdown post-holiday.
- **Q4** is the **peak every year** , sales **climb gradually from Q1 → Q4.**
- Most significant **Q4 growth occurred in 2017 and 2018**, showing market acceleration in those years.


### Monthly Trend Confirmation:
![image](https://github.com/user-attachments/assets/9d573c91-ddab-40dd-b9be-9e5059cf2fc9)

Across all 4 years (2015–2018), there is a clear seasonal sales pattern:
- **February** has the **lowest sales in all 4 years** , likely due to shorter month & budget resets.
- **November** consistently shows the highest monthly sales, likely driven by Black Friday and holiday shopping.
- **2018** outperformed other years in nearly **every month,** confirming business growth.
- **Key months**: **September, November, December.**
- **November** is the **consistent peak** month.
- **February** **lags** in all 4 years.
- 2015–2018 trends align well, confirming pattern reliability.
  
## Business Implications:

 - Prioritize marketing budgets, stock levels, and staffing for **Q4**. Launch campaigns in late **Q3** to build momentum.
 - Introduce **off-season promos, bundled discounts, or subscription renewals** to reduce the **dip in Q1**.
 - Monthly Seasonality is **predictable**. Use these patterns in demand **forecasting models to align procurement, marketing, and logistics.**

# 2. Which product categories drive the most revenue, and how does that vary by region?
## Key Insight Summary:
- **Technology** is the **top revenue contributor** in both the East and West regions (~11% each).
- In the **Central** region, sales are **evenly split** between Technology, Furniture, and Office Supplies (~7% each).
- The **South** region shows the **lowest sales volume**, with all three categories contributing about 5–6% each, suggesting an underperforming market.
- 
### Total Sales by Category
![image](https://github.com/user-attachments/assets/304db43b-e0a8-4274-9b6f-c5f5f17b0f65)

- Sales across all three categories consistently exceeded the long-term average in **Q4**, especially for Technology in **2018**.
- Most dips below the average line occur in **Q1**, confirming a consistent post-holiday slowdown.

### Quarterly Sales by Category, Split by Region

![image](https://github.com/user-attachments/assets/56e58963-9f14-43e9-b063-4bf787bc7e19)
### East: 
- **Technology** is a consistent **outperformer**, especially in **Q4**, with a dramatic spike in late **2018**. 
- This indicates strong seasonal demand and a market highly responsive to tech promotions.

### West: 
- Performance is steady across categories, with **Technology** and **Furniture** showing repeated seasonal peaks.
- This suggests a mature market with opportunities to sustain revenue through dependable campaigns rather than aggressive growth pushes.

### Central: 
- Sales are **balanced across all three categories**, with no clear leader.
- Technology begins to trend upward toward the end of the period, pointing to a potential shift in customer preferences.

### South: 
- Lags significantly behind other regions.
- The one notable event is a spike in Technology sales in **Q1** 2015, possibly a large **one-time purchase or data anomaly**.
- Otherwise, sales remain flat, signaling either low demand or operational constraints.

## Business Implications:
### East & West:
- **Prioritize Technology** inventory, marketing, and promotions.
- Align **Q4** campaigns with historic revenue spikes.

### Central:
- Maintain a **balanced product strategy** while tracking trends for any dominant shift over time.

### South:
- Consider targeted marketing or channel reviews to identify growth opportunities.
- Investigate the **Q1** 2015 spike for **validity**.

## Frequently Bought Together (Sub-Category Pairs)

- **Binders + Paper** are **the most frequently bought pair**, consistent **across all customer segments**.
- **The highest total sales pair is Chairs + Paper**, contributing roughly 5% of total sales.

### Business Implications for Cross-Selling:

- Promote **binders + paper bundles** to increase average basket size.
- Consider **premium Chairs + Paper** packages to maximize transaction value in campaigns.
- Pay attention to stock and delivery of these paired products, especially since **Binders** also show up as one of the **most delayed items in shipping.**

# 3. Who are our top customer segments, and what do they buy?

**Segment Overview**:
The customer base is divided into three primary segments: Consumer, Corporate, and Home Office.

## Key Insight Summary
- The **Consumer** segment drives the **majority of sales**, contributing **51% of revenue** and **52% of the customer base**. It consistently performs above average, with notable **Q4** surges — especially in 2015, 2017, and 2018.
- The **Corporate** segment is gaining momentum, particularly from **2017 onward**. Its **Q4** growth and increasing share position it as a rising strategic opportunity.
- The **Home Office** segment, although the **smallest** (~**19**%), is **trending upward**. Growth is most visible from mid-**2017**, with all three categories gaining traction, especially Technology.
- All segments share the same seasonal rhythm — dipping in **Q1** and peaking in **Q4** — reinforcing the importance of aligning campaigns with buying cycles.
- Across segments, **Technology** and **Furniture** **dominate**, while Office Supplies provides consistent, if less volatile, performance.

### Quarterly Sales by Segment
![image](https://github.com/user-attachments/assets/06db3197-c64a-4a14-b46c-299b6eaa6291)

- **Consumer** is consistently **above average** and the largest contributor to revenue, particularly strong in late **2015, 2017, and 2018**.
- **Corporate** has a **steady upward trend**, showing increased engagement, especially from **2017** onward, nearly reaching Consumer's level in some quarters.
- **Home Office** is **below the average**, but has shown clear improvement starting in mid-2017, especially in late 2018.

### Quarterly Sales by Category per Segment
![image](https://github.com/user-attachments/assets/d60d81f3-6aa2-43e2-b775-ee177e107d24)

### Consumer Segment:
- Highest revenue and customer base.
- **Strong Q4 peaks** — especially in **Technology** and **Furniture**.
- Office Supplies performs consistently but rarely spikes to the highest.
- All 3 categories mostly stay above the average line, confirming high-value behavior.

### Corporate Segment:
- Several **Q4 spikes** across all three categories (2015–2016).
- A **sharp** Technology **surge** in **Q4 2017**.
- Since 2018, all categories show an **upward trend**, indicating increasing corporate engagement.
- All categories gradually rise above the average by 2018.

### Home Office Segment:
- **Lowest** **overall sales** volume.
- One major **Technology spike in Q1 2015**, possibly a special order or data anomaly (**needs verification**).
- Noticeable **upward growth across all categories from early 2018**.

## Business Implications:
### Consumer:
- Remains the **core revenue segment** → focus marketing, loyalty programs, and Q4 promotions here.
- Prioritize Furniture and Technology bundles, especially for seasonal pushes.

### Corporate:
- Increasing activity — consider enterprise packages and B2B loyalty plans.
- Monitor post-2018 trends for strategic expansion.

### Home Office:
- Small but growing — test remote work bundles, especially in Technology.
- Investigate the 2015 Technology spike for potential learnings or corrections.

### All Segments:
- **Technology** is a consistent leader → ensure **inventory readiness**, especially before **Q4**.
- Leverage Q1 dips with off-season promotions or subscription programs to smooth demand.

# 4. What is the shipping performance like – are there delays between order and ship date?
## Key Insight Summary:
- Overall, **67% of orders** were delivered **on time**.
- **Standard Class** is the **most used shipping method** (**60%** of orders) but also has the **highest delay rate** (**30%**).
- Follow by **Same-day** shipping has **<1% delays**, but it’s used in only **5% of orders**.
- **First Class and Second Class perform relatively well**, with **<10% delay rates**.
- Delays are concentrated in **Standard Class** shipments across **all four regions**.

## Method Used to Identify Delays:
For each shipping mode, we calculated its average shipping time:

 days_to_ship = DATEDIFF(Ship_Date, Order_Date)
 If days_to_ship > avg_days_for_that_ship_mode → Delayed
 Else → On-Time
 
| Ship Mode      | Average Shipping Time (days) |
| -------------- | ------------- |
| Same Day       | 0 days        |
| First Class    | 2 days        |
| Second Class   | 3 days        |
| Standard Class | 5 days        |

## Regional & Product-Level Delay Breakdown:
- **Standard Class** is the **most delayed ship method** in every region.
- **New York and Los Angeles** contribute the **most delayed orders**, together forming **6%** of total delays order.
   - Delays are most concentrated in these categories & shipping combos:
     
    **- Office Supplies – Standard Class** (**14%** of total orders)
     
    **- Furniture – Standard Class**
  
    **- Office Supplies – Second Class**

   - The top 3 delayed sub-categories are:
     
    **-** **Binders - Standard Class** 
  
    **-** **Papers - Standard Class**
  
    **-** **Furnishings - Standard Class**

**Important**: 
**Binders + Papers are also the most frequently bought pair sub-category.**

## Business Implications:
### Operational Fixes
- Improve **Standard Class** delivery performance, especially in **NY & LA**.
- Consider re-routing or optimizing warehouse distribution for high-demand cities.

### Product Handling
- Flag **Binders and Papers** for tighter shipping control.
- Monitor inventory + carrier SLAs for **Office Supplies** more closely.

### Strategic Levers
- Highlight **First Class** and **Same Day** options for **priority customers**.
- Use delay insights to negotiate better terms with carriers or offer free upgrades to improve the experience

# 5. Which states or cities generate the most revenue, and are we over-relying on certain regions?
## Key Insight Summary:
- The **West region** is the company’s strongest market, contributing **32%** of **total sales and customer base.**
- It is followed by the **East** region with **29**% of sales and **28**% of customers, then the **Central** region at **22**% of sales and **24**% of customers.
- The **South** region **underperforms**, with just **17**% of total sales and **16**% of customers.
- Across cities and states, a significant share of sales is concentrated in a few key areas, especially **New York** and **Los Angeles**.

## Region Sales Performance:
| Region      | % of Total Sales | % of Customers |
| ----------- | ---------------- | -------------- |
| **West**    | **32%**          | **32%**        |
| **East**    | **29%**          | **28%**        |
| **Central** | **22%**          | **24%**        |
| **South**   | **17%**          | **16%**        |
### Top 5 States by Sales:
| State          | % of Total Sales |
| -------------- | ---------------- |
| **California** | **20%**          |
| **New York**   | **14%**          |
| Texas          | 7%               |
| Washington     | 6%               |
| Pennsylvania   | 5%               |

All other states contribute **less than 5%** of sales, confirming concentration at the top.

### Top 5 Cities by Sales:

| State          | % of Total Sales |
| -------------- | ---------------- |
| **New York City** | **11**%          |
| **Los Angeles**   | **8**%          |
| Seattle          | 7%               |
| San Francisco     | 5%               |
| Philadelphia   | 5%               |


**Takeaway**: Over **19**% of total sales come from just **New York** and **LA**, indicating a high concentration risk.

## Business Implications:
### Over-Reliance Risk
- **NYC + LA** = **19**% of total revenue → high business risk if those cities decline.
- Begin diversifying sales toward 2nd-tier cities  to reduce risk.

### West & East Optimization
- These two regions generate **61**% of all sales.
- Prioritize inventory allocation, **Q4** seasonal offers, and premium shipping options to retain dominance



