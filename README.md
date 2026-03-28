# Urban Safety and Law Enforcement Resource Optimization in India (2020–2024)

## Project Overview
This project analyzes urban crime patterns and law enforcement efficiency across Indian cities from 2020 to 2024. The goal is to identify gaps in crime resolution, understand urban safety trends, and propose data-driven interventions.

## Dataset
- Source: [Indian Crimes Dataset - Kaggle](https://www.kaggle.com/datasets/sudhanvahg/indian-crimes-dataset)
- Records: 40,160 | Attributes: 14
- Key missing data handled during analysis:
  - `Weapons Used`: 5,790 missing entries (filled with "Unspecified")  
  - `Date Case Closed`: 20,098 missing entries (analyzed as unresolved cases)  
- Detailed handling and data preparation steps are included in the PDF report.

## Methodology
- **Data Cleaning:** Retained missing values to preserve analytical depth; standardized date fields.  
- **Exploratory Data Analysis (EDA):** Conducted using Python libraries (**Matplotlib**, **Seaborn**) to identify crime patterns, weapon usage, and urban concentration.  
- **Visualizations:** Created interactive dashboards in **Tableau** to highlight relationships between crime rates, police deployment, and victim demographics.

## Key Insights
- ~50% of reported cases remain unresolved despite proportional police deployment, indicating systemic inefficiencies.  
- Metropolitan areas show higher crime rates; female victims account for more than 50% of reported cases, highlighting the need for targeted, gender-sensitive interventions.  
- `Other Crime` category dominates, and weapons usage is fairly uniform across types.  
- Citizens demonstrate prompt reporting behavior: median reporting lag across cities is 1–2 days.

## Full Report
For detailed analysis, charts, and visualizations, see [EDA analysis.pdf](./EDA%20analysis.pdf).
