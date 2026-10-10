# ALPHA-MARKETING
Multi-page Power BI dashboard analyzing marketing performance: revenue, ROI, ROAS, CAC, campaigns, customers, and channels.
<img width="1153" height="554" alt="الصفحه الاولي " src="https://github.com/user-attachments/assets/76a45181-441a-40b4-a064-cbaa6efd15b6" />
<img width="1156" height="556" alt="2" src="https://github.com/user-attachments/assets/0fa75b41-0d9a-44d0-91b3-bb32bafbfdba" />
<img width="1145" height="543" alt="3" src="https://github.com/user-attachments/assets/692fdb64-b5c0-441b-9e8a-4f036bd5b86b" />
<img width="1146" height="550" alt="4" src="https://github.com/user-attachments/assets/94059a4d-3a3d-432b-a917-f73b3a50830f" />
<img width="1145" height="551" alt="5" src="https://github.com/user-attachments/assets/ef3eb0a7-a824-4925-bcc1-0f3dbf96d4dc" />
<img width="1376" height="768" alt="قرار شركة التسويق" src="https://github.com/user-attachments/assets/2166b5e1-a36f-4bff-a29e-9ff99fa16216" />
<img width="673" height="530" alt="diagram" src="https://github.com/user-attachments/assets/6800c2e7-d04c-48bf-84e9-f031a03d7b41" />

# 📈 Marketing Analytics Dashboard (Power BI)

A multi-page, interactive Power BI dashboard that analyzes marketing performance end to end: revenue, profitability, campaign efficiency, customer behavior, and channel results.

## Pages
- **Home**: landing page with navigation to all sections
- **Marketing**: overall revenue, cost, profit, profit margin, and ROI by funnel stage, campaign type, and channel
- **Campaign Performance**: CAC, ROAS, total orders, marketing spend, and budget vs. revenue by target audience and objective
- **Customer**: revenue by customer segment and gender, average order price, average revenue per customer, CTR, and customers by region
- **Channel Performance**: revenue by channel category, platform, and paid vs. organic, plus conversion rate
- **Decision**: summary page for final insights and recommendations

## Key Metrics
Total Revenue · Total Cost · Total Profit · Profit Margin · ROI · ROAS · CAC · CTR · Conversion Rate · Total Orders · Average Order Price · Average Revenue per Customer

## Filters (Slicers)
Year · Product Status and Sub-Category · Market · Region · Country · City · Campaign Status · Email Opt-in

## Data Model
Star-schema style model with a `Marketing` fact table linked to the dimension tables: `Campaign`, `Customer`, `Channel`, `Product`, `Geography`, and `Date`, plus a dedicated `Measure` table for DAX calculations.

## Tools
- Power BI Desktop
- DAX / Power Query

## How to Open
Download `Marketing_project_depi_Alpha.pbix` and open it with Power BI Desktop.
