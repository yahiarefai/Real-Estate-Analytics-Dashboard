# Real Estate Analytics Dashboard (Power BI)

This project analyzes short-term rental listings in Saudi Arabia using **Power BI** to generate actionable insights for pricing and investment decisions. The dashboard highlights activity by city, customer preferences by property type, the relationship between customer ratings and nightly price, and neighborhoods with the highest average returns.

## Project Objectives
- Identify the most active cities by number of listings.
- Discover the most common property types (e.g., apartment, resort, villa).
- Analyze pricing based on customer satisfaction (rating vs. average nightly price).
- Evaluate top-performing neighborhoods by average nightly price.

## Key Insights (Dashboard Outputs)
- **Listings by City:** shows where most properties are concentrated.
- **Listings by Property Type:** reveals the most common property categories.
- **Rating vs. Average Nightly Price:** explores how customer ratings relate to pricing.
- **Average Nightly Price by Neighborhood:** highlights high-return areas.

## Data Preparation (Power Query)
To improve accuracy and readability of the visuals, the following steps were applied:
- Filtered invalid ratings (e.g., rating = 0 where applicable).
- Used **Average** for nightly price instead of Sum to avoid misleading totals.
- Rounded rating values and converted them to **Whole Number** to reduce granularity and improve chart clarity.
- Applied sorting and consistent formatting for better dashboard usability.

## Dashboard Preview
Add a screenshot of the final dashboard here:

`/assets/dashboard.png`

## Tools Used
- Power BI (Visualization)
- Power Query (Data Cleaning & Transformation)

## How to Use
1. Download the `.pbix` file from this repository.
2. Open it in **Power BI Desktop**.
3. If prompted, update the data source path to your local dataset.
4. Refresh to load data and interact with the dashboard.

## Repository Structure
- `dashboard.pbix` — Power BI report file  

## Author
Yahya Alrefae
