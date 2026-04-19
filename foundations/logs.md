# Learning Log

## April 2026

### Day 1 — Exploratory Data Analysis (Online Retail Dataset)

#### Work Completed
- Loaded and explored a real-world retail transaction dataset
- Identified and handled missing values in `CustomerID`
- Removed invalid records such as negative quantities and non-positive prices
- Created a `Revenue` feature for business-focused analysis
- Performed structured exploratory data analysis across:
  - Revenue distribution
  - Customer-level revenue contribution
  - Product-level quantity and revenue
  - Country-level revenue patterns
  - Monthly revenue trends

#### Key Insights
- Revenue is highly right-skewed, with a small number of transactions contributing disproportionately to total value
- A small group of customers contributes a significant share of total revenue
- Revenue is heavily concentrated in the United Kingdom, indicating geographic dependency
- High-volume products are not always the highest-revenue products, showing the effect of pricing on business value

#### Technical Skills Applied
- Data cleaning and preprocessing with Pandas
- Feature engineering through revenue calculation
- Aggregation and grouping analysis
- Visualization using Matplotlib and Seaborn
- Handling skewed data through log transformation

#### Reflection
Today’s work helped strengthen my understanding of how exploratory data analysis goes beyond plotting charts.  
I focused on connecting technical analysis to business meaning, especially in identifying revenue concentration, customer dependency, and market patterns.
