1. “Which product categories drive the most revenue, and how does that vary by region?”
 - Technology is the Revenue Driver in The East and West Region, around 11% each. Then follow by furniture and office supplies, for each region.
 On Central Region, theres a balanced distribution between the 3 categories around 7% each.
 and the lowest region is the south, with a balance distrubtion as well around 5-6% each category.
-
-time-trend category sales over the year - quarter
  ![image](https://github.com/user-attachments/assets/e374d45e-bb10-489e-b614-328d49db51a1)


sub-category 
- Salah satu barang yang paling sering di beli secara bersamaan yaitu binders. Binders + Paper, adalah the most bought pair items. follow by Binders + Storages, and Phones.
- But the pair items that contribut to the most sales is Chairs + Papers, conrtributing 5% of total sales
- where accros the 3 segment, binders + papers is the most bought paired items. 

2. Top Customer Segments and Their Buying Behavior

Consumer Segment is the most contributor around 51% of total sales and 52% of the  customer base. They tend to purchase technologies category, but with pretty balanced sales distribution on the other 2 categories, with peak in Q4 and dip on Q1 each year. 
the pattern also same for all other segments where the sales dip at q1 and peak at q4, with tehnology being the most bought categories acrros all segments.  

3. Shipping Performance and Delays

Average shipping for each ship_mode, days_to_ship (Ship_Date - Order_Date) > avg_ship then 'Delayed', Else 'On-Time':
 - Same Day       = 0 Days
 - First Class    = 2 Days
 - Second Class   = 3 Days
 - Standard Class = 5 Days

The majority, or 67% of the order, is on time, where Standard Class is the most used ship mode with 60% of the total order, but also contributes to the most delayed order, with 30% of its orders being delayed. 
where same day has the least orders, only 5% of total orders, but also has the least delayed percentage, below 1%.In  where first and second classes, the delayed order is below 10%.

Standard Class is the most used ship mode acrros 4 region, but also the most delayed ship mode acrros those region.  where the most delayed order is from New York and Los Angeles, both combine as 4% of delayed total orders.
the most delayed category is Office Supplies by standard_class, follow by Furniture Standard Class and office supplies second class. 
top 3 most delayed sub-category is binders, papers, and furnishings. need to mark on this, because binders+papers, is the most bought paired item. 

4. “Which states or cities generate the most revenue, and are we over-relying on certain regions?”
west region is the top region, contributing  32% of total sales and customer base. follow by the east, and central region. the least is South region, 17% total sales and 16% of customer base.

the top 5 city is New York, LA, seattle, san fransisco, and philadelphia. where New York is the highest contribute with 11% and LA the second with 8%. the other 3 is 5% and below that is under 5%. so pretty relying on new york and LA.

The top 5 states by market share are California with 20%, New York with 14%, then Texas with 7%, Washington with 6%, and Pennsylvania with 5% The other are below 5%.

5. “Are there any seasonal trends in sales performance?”

- By Quarter
![image](https://github.com/user-attachments/assets/2ffe8c7a-f4fe-4970-a7f6-f9710411dc6a)
theres always a pattern or seasonality spike at Q4 and dip at Q1.
- By Month
  ![image](https://github.com/user-attachments/assets/06056f9e-70bf-429e-a47b-73d9d1faf2e1)
# FIX
# Analysis
# 1. Which product categories drive the most revenue, and how does that vary by region?
## Key Insight Summary:
**Technology** is the **top revenue contributor** in both the East and West regions (~11% each).

In the **Central** region, sales are **evenly split** between Technology, Furniture, and Office Supplies (~7% each).

The **South** region shows the **lowest sales volume**, with all three categories contributing about 5–6% each, suggesting an underperforming market.

## Visual: Quarterly Sales by Category, Split by Region

![image](https://github.com/user-attachments/assets/f4a83166-db21-4aa0-a7ce-c7da3b2a95aa)

### East & West Regions:
- **Technology**  consistently leads sales and shows **strong seasonal spikes in Q4**, especially in East, where Q4 2018 saw a major peak.

### Central Region:
- All three categories are relatively balanced, with **Technology slightly increasing** toward the end of the period.

### South Region:
- Sales volume is significantly lower across all categories.
- **A sudden spike in Q1 2015 for the Technology Category**  may indicate a **large one-off purchase or a data anomaly**, and should be investigated further.

## Business Implications:
### East & West:
- **Prioritize Technology** inventory, marketing, and promotions.
- Align Q4 campaigns with historic revenue spikes.

### Central:
- Maintain a **balanced product strategy** while tracking trends for any dominant shift over time.

### South:
- Consider targeted marketing or channel reviews to identify growth opportunities.
- Investigate the Q1 2015 spike for validity.

## Frequently Bought Together (Sub-Category Pairs)

- **Binders + Paper** are **the most frequently bought pair**, consistent **across all customer segments**.
- **The highest-revenue pair is Chairs + Paper**, contributing roughly 5% of total sales.

### Business Implications for Cross-Selling:

- Promote **binders + paper bundles** to increase average basket size.
- Consider **premium Chairs + Paper** packages to maximize transaction value in campaigns.
- Pay attention to stock and delivery of these paired products, especially since **Binders** also show up as one of the **most delayed items in shipping.**
- 
# 2. Who are our top customer segments, and what do they buy?
## Key Insight Summary
## Quarterly Sales by Segment
This chart shows total sales over time by each customer segment, revealing seasonality patterns and segment growth.
![image](https://github.com/user-attachments/assets/4ae7b128-182b-4d79-a372-ccebab9671c7)

- The **Consumer** segment is the **largest revenue driver**, contributing **51% of total sales** and **52% of the customer base**.
- Followed by **Corporate**, and **Home Office** with **19% share**.
- All segments show a **clear Q4 sales peak** and **Q1 dip**, indicating seasonality.

## Quarterly Sales by Category per Segment
![image](https://github.com/user-attachments/assets/61b3577b-4b2a-478f-b8ab-f0877b948ac9)
### Consumer Segment:
- Highest revenue and customer base.
- **Strong Q4 peaks** — especially in **Technology** and **Furniture**.
- Office Supplies performs consistently but rarely spikes to the highest.

### Corporate Segment:
- Several **Q4 spikes** across all three categories (2015–2016).
- A **sharp** Technology **surge** in **Q4 2017**.
- Since 2018, all categories show an **upward trend**, indicating increasing corporate engagement.

### Home Office Segment:
- **Lowest** **overall sales** volume.
- One major **Technology spike in Q1 2015**, possibly a special order or data anomaly (**needs verification**).
- Noticeable **upward growth across all categories from early 2018**.

## Business Implications:
### Consumer:
- Remains the core revenue segment → focus marketing, loyalty programs, and Q4 promotions here.
- Prioritize Furniture and Technology bundles, especially for seasonal pushes.

### Corporate:
- Increasing activity — consider enterprise packages and B2B loyalty plans.
- Monitor post-2018 trends for strategic expansion.

### Home Office:
- Small but growing — test remote work bundles, especially in Technology.
- Investigate the 2015 Technology spike for potential learnings or corrections.

### All Segments:
- Technology is a consistent leader → ensure inventory readiness, especially before Q4.
- Leverage Q1 dips with off-season promotions or subscription programs to smooth demand.




# END



## 1. What product categories drive the most revenue by region?
### Key Insight:

**Technology** is the **leading revenue** driver in both the **East** and **West regions**, contributing **~11%** each. 
**Furniture** and **Office Supplies** follow closely in both areas.

In the **Central region**, sales are **evenly distributed across the three categories** (~7% each).
**The South region** has the **lowest** contribution (**~5–6%** per category), showing balanced but lower sales volume.

### 1.1 Time-series line chart of quarterly sales by category


- **East & West**: **Technology** spikes significantly each year in Q4, especially in East with a sharp surge in late 2018.
- **Central**: All categories have a balanced pattern, though Technology shows slightly higher peaks in later years.
- **South**: Overall revenue is lower, with no dominant category overall even tho theres a huge spike in early 2015 at Q1 on Home Office category need to clarify this if this because special contracts, or data issues?, and Technology even dips below Furniture in several quarters.

### Business Value:
- **East & West**: Double down on Technology stock, marketing, and Q4 campaign
- **South**: Watch performance - possible area for growth or cost-saving.
- **Central**: Focus on maintaining balance and responding to quarterly surges.

### 1.2 Sub-Category Pairing:

- **Binders + Paper** are the **most frequently bought together**, especially by all three customer segments.
- However, the **highest revenue-generating** product pair is **Chairs + Paper**, accounting for **~5%** of total sales.

### Business Value:

- **Cross-sell campaigns for Binders + Paper** could increase basket size.

2. Who are our top customer segments and what do they buy?
Key Insight:
The Consumer segment contributes over 50% of both sales and customer base, making it the most critical segment.
All segments (Consumer, Corporate, Home Office) show a similar purchasing pattern:

Tech is the most purchased category

Sales peak in Q4 and dip in Q1 consistently every year

Visual:
📊 Bar chart: Sales by Segment
📈 Line chart: Category sales by quarter per segment

Business Value:

Consumers drive the most value — consider loyalty programs or segment-based marketing

Technology campaigns should be planned for Q4

Prepare for demand slowdowns in Q1

3. Are there shipping delays and which ship modes cause them?
Key Insight:
On-time delivery rate is 67%.
Standard Class is the most used ship mode (60% of orders), but also has the highest delay rate (30% delayed).
Same Day is the most reliable, with almost 0% delay but only used for 5% of orders.

Delayed Order Patterns:

New York & Los Angeles are the cities with the most delayed orders (~4% combined).

Delays are most common in Office Supplies, especially in the Standard Class.

Top delayed sub-categories: Binders, Paper, Furnishings.

Business Value:

Standard Class needs review — is it cost-efficient or hurting customer experience?

Target supply chain fixes in NY & LA.

High-volume items like Binders + Paper must be prioritized in fulfillment, since they’re frequently bought together and also highly delayed.

4. Are we over-relying on certain states or cities for revenue?
Key Insight:
Yes. Sales are heavily concentrated in a few regions:

West region leads with 32% of total sales, followed by East and Central.

South lags behind with only 17%.

City-Level:

Top 5 cities: New York (11%), LA (8%), Seattle, San Francisco, Philadelphia (~5% or below)

NY + LA together = nearly 20% of total sales

State-Level:

California (20%), New York (14%), Texas (7%), Washington (6%), Pennsylvania (5%)

All other states <5%

Business Value:

There’s a potential risk in over-reliance on a few states.

Diversify campaigns or promotions to drive growth in underperforming regions.

West performs well — reinforce success with deeper segmentation.

5. Are there seasonal trends in sales performance?
Key Insight:
Clear and consistent seasonal patterns across 4 years:

Sales spike in Q4 (especially November)

Lowest in Q1, especially February

Secondary spike observed in September

Visual:
📈 Monthly and quarterly trend line charts

Business Value:

Plan major campaigns in Q4 (Black Friday, holiday season)

Avoid major promotions in Q1 unless needed to recover sales

Align inventory and staffing with seasonal demand

theres consistent spike at september and November in those 4 years and noticable dip at February.



