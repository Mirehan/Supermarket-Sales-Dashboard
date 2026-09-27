# Supermarket Sales Dashboard

A Power BI dashboard analyzing supermarket sales performance across three 
branches (A, B, C) in three cities (Mandalay, Yangon, Naypyitaw), tracking 
revenue, gross income, customer demographics, payment method mix, and 
product line performance.

## Tools Used
- Power BI (data modeling, DAX measures, interactive visuals)
- Excel / CSV for source data

## Dataset
1,000 invoices covering sales, quantity, gross income, COGS, customer type 
(Member/Normal), gender, payment method, branch, city, product line, and 
customer rating.

## Key Insights

- **Scale:** 1,000 invoices generated 322.97K in total sales against 307.59K 
  in COGS, for a gross income of 15.38K — a gross margin of roughly 4.5%.
- **Revenue dipped sharply in February before recovering:** the trend line 
  shows a V-shape, dropping from ~120K in January to ~100K in February, then 
  climbing back to ~112K by March — worth investigating what drove the 
  February slump (seasonality, promotions, inventory).
- **Naypyitaw is pulling city performance up:** Mandalay and Yangon sit flat 
  around 106K, while Naypyitaw spikes to over 110K, making it the standout 
  location and a candidate for deeper analysis on what's driving the gap.
- **Branch performance is close but not equal:** Branch C leads at ~100K, 
  slightly ahead of A and B — a small enough gap that it may not be 
  statistically meaningful without more data.
- **Payment methods are nearly evenly split:** Ewallet (34.7%), Cash (34.1%), 
  and Credit card (31.2%) are all within 3.5 points of each other — no single 
  payment method dominates, suggesting customers have no strong preference.
- **Product lines are evenly distributed:** Food and beverages leads revenue, 
  but all six product lines (Food & beverages, Sports & travel, Electronic 
  accessories, Fashion accessories, Home & lifestyle, Health & beauty) sit in 
  a fairly tight band — no single category drives a disproportionate share.
- **Customer base skews Member and Female:** Female Members are the largest 
  segment on the customer type vs. gender breakdown, ahead of Male Members, 
  Female Normal, and Male Normal customers.
- **Average customer rating is 6.97/10** — solid but with clear room to 
  improve, especially if paired with a follow-up analysis on which branch 
  or product line drives lower scores.

## Dashboard Pages
1. **Home** — full KPI overview: sales, invoices, quantity, gross income, 
   avg rating, and COGS, alongside revenue trend, customer demographics, 
   payment mix, branch/city performance, and product line revenue

## How to Use
1. Download the `.pbix` file from this repo
2. Open in Power BI Desktop
3. Use the filter panel (left sidebar) to slice by branch, city, or product line
