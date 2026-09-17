# LumiWell Beauty Holdings Sales Analysis (2022-2024)

## Background and Overview

LumiWell Beauty Holdings is a Seoul-headquartered skincare group that owns five brands sold across 12 markets in Asia-Pacific and two international outposts (Australia, United States).				
							
The company has a significant a significant amount of data on its sales, marketing effort, operational efficiency, product offerings, target markets and loyalty programs.This project thoroughly analyzes this data to review the current standing of the business based on the financial year 2022-2024 data.

Insights and recommendations are provided on the following key areas:

- **Growth and Market Investment:** An analysis of company growth across markets and sales channels, and how marketing investment is performing against that growth.

- **Customer and Product Value:** An assessment of customer segments and spending behavior, and which products deliver the most value versus volume.

- **Profitability and Loss Analysis:** An evaluation of where and why the company is losing money, and which campaigns or channels are underperforming.

## Data Structure and Overview

Lumiwell Excel structure is shown below. 

Data Source: ClaudeAI | The raw dataset used for this analysis is found [here](LumiWell_Sales_Transactions_RAW.csv). 

Rows: 23,461

Columns: 47 

<img width="628" height="602" alt="Screenshot 2026-09-17 174735" src="https://github.com/user-attachments/assets/d8efb8fd-35fe-4e41-b7aa-8f435e9230e2" />



Prior to the beginning of the actual analysis, checks and cleaning were conducted for quality control and familiarization with the dataset. A cleaning log was used to track each column and row that needed to be checked and cleaned. Exploratory analysis was done through the creation of pivot tables to understand the company's sales data.

## Executive Summary

On one hand, there is significant revenue growth from 2022 to 2024, despite a dip in the 2nd quarter of 2024 that recovered by the following quarter. Total revenue grew to $8.33M, with $5.28M in net profit and a 65.6% profit margin. On the other hand, the return rate stands at 7.6% and the cancellation rate at 5.0%, largely attributable to operational issues and logistics, with an additional $1.36M (14.5% of gross sales) lost to returns, cancellations, and discounts combined.

#### Invest (Growing Figures)
- Markets: Philippines (118.1%), Indonesia (98.3%) , and Vietnam (79.0%)
- Product Category: Anti-Aging (80.5%), Acne Care (47.6%), and Moisturizer (44.1%) 
- Sales Channel: Online Market Place (50.6%)

#### Flag/Investigate (Losing and Declining Figures)
- Markets: Thailand (-39.8%), Taiwan (-27.3%), and Japan (-22.7%)
- Product Category: Face Mask (-36.9%), Toner (-22.7%), and Serum (-13.4%)
- Sales Channel: Distributor (3.4%) and Social Commerce (3.4%)

#### Leakage (Profit Loss)
- Market: South Korea (-$122,932), Japan (-$86,028) and Malaysia (-$71,892)
- Channel: Distributor (-$378,706) and Online Marketpage (-$118,111)

Below is the executive summary from the Excel dashboard; more detailed views are included throughout the report.

<img width="2183" height="1011" alt="Screenshot 2026-09-17 184129" src="https://github.com/user-attachments/assets/05360617-96dd-4459-a5ee-ad618ea2a062" />


The dashboard can be found here.

## Insights Deepdive

### Growth and Market Investment Analysis

<img width="2133" height="923" alt="image" src="https://github.com/user-attachments/assets/559b4475-2fb2-469e-9fd7-0232eaf8c2d3" />



**Philippines (+118.1%), Indonesia (+98.3%), and Vietnam (+79.0%)** are our three fastest-growing markets, and all three hold a strong ~66% profit margin, so this is rare, high-quality growth, not just volume for its own sake.

**Japan, Thailand, and Taiwan**, by contrast, all declined despite spending a relatively huge amount of campaign budget, likely reflecting strong homegrown skincare brands that already dominate local demand in those markets. South Korea is the outlier to flag: despite being a beauty-industry home turf with an established, quality-conscious customer base, it shows flat growth, which warrants deeper investigation into what's holding it back.


**Distributor** is our largest sales channel at 54.6% of revenue, but it's also the slowest-growing (+3.4%), that combination is a structural risk: over half the business depends on a channel that isn't expanding.

**Online Marketplace**, by contrast, is our fastest-growing channel (+51%), making it the strongest candidate for further investment.


**YouTube** gets the highest marketing budget but delivers only 0.20x ROI — our biggest misallocation. **Marketplace Ads and TikTok Affiliate/collaborations** deliver far higher ROI on much smaller budgets.


**Anti-Aging** leads on both size ($1.05M) and growth (+80%), the business's main engine. **Eye Care** is the key concern: second-largest by revenue ($900K) but shrinking (-13%). Acne Care, Moisturizer, Cleanser, and Sunscreen form a solid smaller tier, all growing 30-48%. Serum, Toner, and Face Mask are declining too, but at much smaller scale, lower priority than Eye Care.


### Customer & Product Value

<img width="2166" height="908" alt="image" src="https://github.com/user-attachments/assets/59e9f7a3-8819-4714-aa92-a2bdb6eb20c9" />

**VIP customers** generate the highest revenue per customer ($2,062) despite Mass driving the most total net sales. **Premium** sits oddly between them, closer to Mass than VIP in per-customer terms.

**Platinum members** are worth the most per customer ($2,117), proving the program works, but 1,910 customers generating real revenue aren't enrolled at all ("None" tier has the highest total net sales of any tier). Silver underperforms Bronze per customer, suggesting its benefits need reworking or members should be moved up.

Returning customer revenue has grown steadily and now outpaces new customer revenue. The business is increasingly retention-driven, with 72% of 2024 revenue coming from returning customers.

The **Aqua Lift Eye Patch** alone drives $769K in net profit, more than 3x the next-highest product. Meaning a disproportionate share of profit rests on one SKU. Eye Care products dominate the top-profit list (4 of the top 5), reinforcing category importance despite its declining growth.

**Eye Care** combines high net sales with the highest refund rate (~8%+), making it the category leaking the most value in absolute terms. **Anti-Aging,** by contrast, pairs high sales with a comparatively low refund rate, a healthier profile. Moisturizer and Sunscreen have the highest refund rates overall but at much lower sales exposure, so the dollar impact is smaller.
