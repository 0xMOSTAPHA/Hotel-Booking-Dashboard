🏨 Hotel Summer Booking Power BI Dashboard
An interactive Power BI dashboard analyzing hotel booking performance across 2015–2017 — focusing on revenue, cancellations, daily rates, and booking lead time behavior.
📌 Dashboard Highlights
Revenue vs. Revenue Lost by Month
Stacked bar chart comparing total revenue earned against revenue lost to cancellations — peaking in August ($2.2M) and showing clear summer seasonality from May through October.
Average Daily Rate & Cancellation % by Month
Combo chart overlaying monthly ADR (ranging $70–$140) with cancellation rate trends — August has the highest ADR ($140) while cancellation rates fluctuate between 60–70% year-round.
Cancellations by Day of Week
Monday leads with 12K cancellations, gradually declining through the week to Tuesday at 9.4K — useful for staffing and overbooking strategy.
Lead Time Analysis (LTT)
Two donut charts breaking bookings into >30 days and 0–30 days lead time: bookings made more than 30 days out have a slightly lower ADR ($99 vs $103) but account for 58% of all cancellations (44K) — highlighting the risk of early bookings.
✨ Features

Customer Type dropdown filter
Year toggle buttons (2015, 2016, 2017)
Combo charts for dual-axis revenue and rate analysis
Lead Time Transformed (LTT) segmentation for cancellation risk modeling
Consistent dark teal theme throughout

🛠️ Tools & Tech

Power BI Desktop
DAX (revenue loss calculations, lead time segmentation, cancellation rates)
Date intelligence for monthly and weekday-level aggregations

📁 Dataset
Based on the publicly available Hotel Booking Demand dataset — containing reservation records with fields for customer type, booking dates, lead time, ADR, cancellation status, and revenue.
