# Project Tasks

## Task 1: Inspect Data and Limit Output

**Instructions:**
- Connect to the `international_debt` database.
- Select all columns from the `international_debt` table.
- Limit the output to the first 10 rows.

## Task 2: Count Distinct Countries

**Instructions:**
- Use the DISTINCT clause and COUNT() function on the `country_name` column.
- Alias the resulting column as `total_distinct_countries`.

## Task 3: Extract Unique Debt Indicators

**Instructions:**
- Use the DISTINCT clause on the `indicator_code` column.
- Alias the resulting column as `distinct_debt_indicators`.
- Order the results by `distinct_debt_indicators`.

## Task 4: Calculate Total Debt

**Instructions:**
- Use the SUM function on the `debt` column and divide it by 1000000.
- Round the result to 2 decimal places.
- Alias the resulting column as `total_debt`.

## Task 5: Country with Highest Debt

**Instructions:**
- Select `country_name` and apply the SUM function on the `debt` column.
- Alias the result as `total_debt`.
- GROUP the results BY `country_name` and ORDER BY `total_debt` in descending order.
- LIMIT the results to one row.

## Task 6: Average Debt Across Categories

**Instructions:**
- Select `indicator_code` aliased as `debt_indicator`.
- Select `indicator_name` and `debt`.
- Apply an aggregate function to calculate the average debt and alias it as `average_debt`.
- GROUP the results BY `debt_indicator` and `indicator_name`.
- ORDER the results by `average_debt` in descending order.
- LIMIT the results to ten rows.

## Task 7: Country with Highest Principal Repayments

**Instructions:**
- Select `country_name` and `indicator_name` columns.
- Use a WHERE clause to filter the maximum debt in `DT.AMT.DLXF.CD` category.

## Task 8: Most Frequent Debt Indicator

**Instructions:**
- Select the `indicator_code` column.
- Apply an aggregate function to count its values and alias it as `indicator_count`.
- GROUP the results BY `indicator_code`.
- ORDER the results by `indicator_count` and `indicator_code` in descending order.
- LIMIT the results to 20 rows.

## Task 9: Maximum Debt by Country

**Instructions:**
- Select `country_name`.
- Apply an aggregate function to find the maximum debt and alias it as `maximum_debt`.
- GROUP the results BY `country_name`.
- ORDER the results by `maximum_debt` in descending order.
- LIMIT the results to 10 rows.

