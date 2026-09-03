# Australian Supermarket Sales & Performance Dashboard

**Tool:** Tableau | **Team Project** | **Role:** Dashboard Design & Build

## Overview

This report was prepared for the top management of an Australian supermarket chain to evaluate commercial performance and provide strategic recommendations for improving sales and operational efficiency. Analyzing product dynamics, customer trends, geographic performance, and temporal sales patterns during Q3 and Q4 of 2025, the objective was to identify specific opportunities for sustainable growth.

Using Tableau, the dashboards examine revenue concentration across states, fluctuations in demand, and category contributions to total profit. They further explore purchasing behavior across fulfilment channels and key customer segments. By integrating these perspectives, the report supports data-driven decision-making in areas such as resource allocation, marketing focus, and customer engagement — aiming to strengthen the company's competitive position and long-term profitability.

*Note: this project uses simulated/mock data created for analytical training purposes and does not reflect a real company's financials.*

## My Role

This was a team project. Each member independently explored and identified patterns within their assigned section of the data, then we came together to evaluate our findings collectively and shape them into a cohesive business narrative. Building on that shared analysis, I designed and built all three dashboards in Tableau — translating our combined insights into the final visualizations, layout, and interactivity shown below.

## Dashboards

**1. Sales Summary — Dashboard Overview**
![Dashboard Overview](images/dashboard-overview.png)

Built as the executive landing view, this dashboard surfaces three headline KPIs (Total Sales $5.61M, Total Profit $373K, Total Quantity 135,110) alongside trend sparklines, so management can gauge overall health at a glance before drilling into detail. Below that, a **product assortment matrix** breaks sales down by category and sub-category over time, letting stakeholders spot which product lines are consistently strong versus seasonal. A **packed bubble chart** visualizes brand contribution and profitability side by side — sizing and color are used together so the highest-revenue *and* highest-margin brands are identifiable in a single glance, rather than needing two separate charts. Paired horizontal bar charts for **sales vs. profit by product** were deliberately placed side by side to expose products that sell well but underperform on margin — a common blind spot in raw sales reporting.

**2. Regional and Time — Superstore Sales Dashboard**
![Superstore Sales Dashboard](images/superstore-sales-dashboard.png)

This view answers "where and when" the business performs best. A **map of Australia** plots sales concentration by location, immediately surfacing the eastern-state revenue concentration referenced in the report's conclusion. A **sales heatmap by day and hour** (rows = days, columns = hourly bands) was built to identify peak trading windows — critical for staffing and promotional timing decisions rather than just descriptive reporting. A **scatter plot of store sales vs. profit margin** was added specifically to separate high-revenue stores from high-margin stores, which is what surfaced the metropolitan-store margin issue called out in the recommendations. Quarterly sales and average daily sales by time-of-day round out the view to support demand-planning conversations.

**3. Customers — Customer Behaviour Dashboard**
![Customers Dashboard](images/customers-dashboard.png)

Focused on segment-level behavior rather than aggregate totals. Total Customers (2,500) and Average Sales per Customer ($197.10) anchor the view, with a **customer distribution by sales histogram** used to show that spending is not evenly distributed across the customer base — a key input for the tiered loyalty strategy recommended in the report. A **profit-by-age-group pie chart** was built to identify the 25–34 segment as the core profit driver, directly informing the age-targeted loyalty recommendation. A **ranked top-customers table** with total sales and profit ratio columns supports account-level prioritization, letting the business identify and retain its highest-value customers specifically, not just its highest-spending ones.

## Key Findings & Recommendations

- **Lower profit margins in high-volume metropolitan stores** and **revenue concentration in the eastern states** were identified as the two main areas limiting overall profitability despite strong topline sales.
- **Cross-merchandising strategies** are recommended to lift average transaction value (ATV) by encouraging complementary purchases.
- **Inventory alignment for top-selling products** would reduce stockouts/overstock and improve fulfilment efficiency.
- **Tiered loyalty initiatives targeting the core 25–34 age demographic** — the highest-profit customer segment — are recommended to deepen engagement and repeat purchase rates.

Together, these data-driven adjustments are intended to help the business maximize ATV and strengthen its competitive position within the Australian retail industry.

## Tools & Skills

Tableau (dashboard design, geographic mapping, heatmaps, calculated fields), data visualization, business analysis, stakeholder-driven design (translating a teammate's data findings into visual storytelling).
