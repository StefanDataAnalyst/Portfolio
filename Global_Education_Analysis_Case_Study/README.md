# 🌍 Global Education Analysis: Secondary School Age by Region (2015) - Case Study

This mini case study uses SQL to explore how many people were of official secondary school age in each global region, using World Bank data from 2015.

## 📊 Tools Used
- Google BigQuery
- World Bank Public Dataset (Google Cloud)

## ❓ Research Question
In 2015, how many people around the world were of official age for secondary education, broken down by region?

## 🔍 Methodology
- Used the `international_education` table for education indicator values.
- Joined with `country_summary` to assign countries to regions.
- Filtered for 2015 and the relevant education indicator.
- Aggregated by region using `GROUP BY`, and sorted results with `ORDER BY`.

## 💡 Key Learnings
- Practiced multi-table joins in SQL.
- Learned how to clean and filter large public datasets.
- Gained insight into using demographic data for real-world planning.

## 📄 View Full Case Study
👉 [📥 View Full PDF](./Global%20Education%20Analysis%20Secondary%20School%20Age%20by%20Region.pdf)
