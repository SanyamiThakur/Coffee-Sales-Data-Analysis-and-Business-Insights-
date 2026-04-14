# Coffee-Sales-Data-Analysis-and-Business-Insights-
Coffee sales analysis using Python. Cleaned and processed data with Pandas and NumPy, performed exploratory data analysis, and built visualizations using Matplotlib and Seaborn. Identified sales trends, top-performing products, and customer purchasing patterns to generate actionable insights for improving revenue and business strategy.

☕ Coffee Shop Sales Data Analytics

📌 Project Overview
An end-to-end exploratory data analysis project on a coffee shop's transaction records, covering the full pipeline from raw CSV data to a suite of charts and summaries built in Python. The project uncovers insights around product revenue, customer payment behaviour, and temporal sales patterns to support smarter menu, staffing, and operational decisions.

🛠️ Tools & Technologies

Python (pandas, matplotlib, seaborn, numpy) — Data loading, cleaning, feature engineering, and visualisation
Jupyter Notebook — Interactive development environment for step-by-step analysis


🔍 Analysis Highlights
All analytical outputs are structured across 15 clearly labelled sections in coffee_sales_analysis.py:

Data Quality Checks — Identified 89 missing card values (cash transactions) and confirmed zero duplicate records across 1,133 rows
Payment Behaviour — Breakdown of card vs. cash usage across the full transaction history
Product Mix Analysis — Percentage share of each drink by order volume
Feature Engineering — Extracted month, ISO weekday, and hour from raw datetime fields to enable time-series analysis
Revenue Aggregation — Total revenue ranked by coffee type with labelled bar charts
Temporal Trends — Monthly pivot tables and line charts tracking each drink's sales trajectory from March to July 2024
Peak Hour Profiling — Hourly transaction counts and per-drink hourly breakdowns across a 2×4 subplot grid


📊 Visualisations
The script produces 7 charts across the following dimensions:
Revenue & Product

Horizontal bar chart — Total revenue by coffee type (all 8 drinks ranked)
Histogram — Payment method distribution (card vs. cash)

Time-Based Patterns

Multi-line trend chart — Monthly sales volume per drink (March–July 2024)
Bar chart — Transaction count by day of week (Sun–Sat)
Bar chart — Transaction count by hour of day (07:00–22:00)
2×4 subplot grid — Hourly sales broken down by individual coffee type

Distribution

Percentage table — Order share per drink, sorted descending


💡 Key Business Insights

92.1% of payments were made by card, with only 7.8% in cash — the shop is effectively card-first and could consider going cashless without meaningful customer impact.
Americano with Milk dominated order volume at 23.65%, followed by Latte (21.45%) and Cappuccino (17.30%). Espresso and Cocoa together account for under 8% of orders, and may warrant menu rationalisation or promotional focus.
Peak trading falls between 10–11 AM, with over 130 transactions in that single hour — nearly double most other hours. Staffing and stock preparation should be concentrated around this window.
A secondary afternoon peak appears around 6–7 PM, consistent with an after-work customer segment that represents a meaningful second wave of daily demand.
Wednesday recorded the highest transaction count of any weekday; Sunday was the quietest day, suggesting reduced weekend staffing may be appropriate.
Sales dipped noticeably in June across most drink categories before recovering in July — this could reflect seasonal behaviour, a local event, or a data gap worth investigating.
Average transaction value was £33.11, with the full range sitting between £18.12 and £40.00, indicating a relatively consistent price band with limited outlier risk.
