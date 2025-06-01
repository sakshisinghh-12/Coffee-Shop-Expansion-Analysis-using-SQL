# Coffee-Shop-Expansion-Analysis-using-SQL

# Project Objective

To analyze sales, customer, and city data to uncover key patterns and business opportunities, and to support strategic decision-making through SQL-based reporting and analysis.

# Tools & Technologies

- **Language**: SQL
- **Techniques**: Joins, CTEs, Aggregations, Window Functions, Date Functions

# Dataset Overview

The database includes the following tables:
- `city`: City-level demographic and economic data
- `products`: Coffee products offered
- `customers`: Customer details with city associations
- `sales`: Transaction records with revenue and date

# Key Analyses Performed

1. **Coffee Consumer Estimation**  
   Estimated the number of coffee consumers per city using population data and market assumptions.

2. **Revenue Analysis**  
   Calculated total and city-wise revenue for Q4 2023 to assess financial performance.

3. **Product Performance**  
   Identified top-selling products in each city using sales count and ranking logic.

4. **Customer Segmentation**  
   Counted unique customers by city and analyzed average sales per customer.

5. **Market Potential Evaluation**  
   Merged sales, rent, and population data to evaluate ROI and identify high-potential cities.

6. **Monthly Sales Growth**  
   Measured month-over-month growth trends using window functions and time-series grouping.

# Key Insights

- Pune generated the highest revenue with low average rent per customer, indicating high ROI.

- Delhi had the largest estimated coffee-consuming population and customer base.

- Jaipur showed strong customer engagement with low rent and solid sales per customer.
