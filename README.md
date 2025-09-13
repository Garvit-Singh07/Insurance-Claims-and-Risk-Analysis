# Insurance-Claims-and-Risk-Analysis

Real-Time Insurance Analytics Dashboard (Power BI)

Project Overview

This project demonstrates a complete real-time dashboard built in Power BI for the insurance domain.
Goal: Provide stakeholders with up-to-date metrics and visibility into insurance operations — policies, premiums, claims, loss ratio, etc. — so that decision-making can be faster and more data-driven.


---

Tools & Technologies Used

Power BI Desktop & Service — for data modeling, visualization, real-time dashboards

DAX — to create measures & calculated columns (e.g. Loss Ratio, Claims per Policy)

Data Sources / Refresh Mechanism — simulated or live data refresh (depending on setup) to keep the dashboard updated

Filters / Slicers / Drilldowns for granular insights



---

Data & Domain

Insurance domain
• Policies: counts by type (e.g. life, auto, health)
• Premiums collected over time / by region / by product
• Claims filed: numbers, amount, status (paid / pending)
• Loss Ratio: claims amount ÷ premiums (or as defined)

Time series data — Month / Quarter / Year breakdowns

Geographic / Product segmentation



---

Dashboard Features

Real-Time Data Refresh or periodic updates (depending on data source)

KPIs / Cards showing key metrics: Total Premium, Total Claims, Loss Ratio, Claim Count, etc.

Trend Visuals: line charts or area charts showing premium / claim trends over time

Comparisons: region-wise, product-wise performance

Interactive Filters / Slicers: time period, region, product type, policy status etc.

Visuals: bar charts, line graphs, cards, maybe maps if geographic data included



---

Insights & Learnings

Discovered product lines with highest risk due to high claims vs low premium yield

Observed seasonal spikes / drops in claims or premium collection

Regional disparities in claims frequency or severity

Identified potential bottlenecks or leakage points (e.g., long pending claims)

Improved ability to make data-driven decisions in insurance operations



---

How to Run / Use It Locally

1. Clone this repository


2. Open the .pbix file in Power BI Desktop


3. If live data source is used, configure data credentials / connection


4. Explore the visuals; use slicers / filters


5. (Optional) Publish to Power BI Service / Embed if needed




---

Files Included

InsuranceDashboard.pbix — Power BI dashboard file

Data/ — folder containing sample data (raw + cleaned)

Documentation/ — screenshots, data dictionary, transformation steps

README.md — this description



---

Possible Future Enhancements

Integrate live streaming data for claims or policy creation

Extend predictive analytics (e.g. forecast claims, detect anomalies)

Add more product types or granular segmentation

Improve UI/UX with more dynamic visuals

Automate data ingestion pipeline

Interactive Dashboard link = https://shorturl.at/wuzAR
Image of Dashboard = 
