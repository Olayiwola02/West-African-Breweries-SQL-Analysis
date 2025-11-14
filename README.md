# West-African-Breweries-SQL-Analysis
SQL analysis of brewery sales & profits across Anglophone (Nigeria, Ghana) vs Francophone countries (2017–2019). Includes territory/brand categorization & top insights.

**Project Overview**
This project analyzes **sales, profit, and consumption patterns** of breweries across **Nigeria, Ghana, Benin, Togo, and Senegal** using **SQL**. It categorizes countries into **Anglophone** and **Francophone** territories and brands into **Beer** and **Malt**, enabling deep comparative insights.

**Dataset**: `Breweries` table with columns: `BRANDS`, `COUNTRIES`, `YEARS`, `MONTHS`, `QUANTITY`, `COST`, `PROFIT`

 **Key Objectives**
- Compute total and territorial profits
- Identify top-performing countries, years, and brands
- Compare **Anglophone** vs **Francophone** markets
- Analyze **beer vs malt** consumption trends
- Highlight regional consumer preferences


**Key Findings (Sample Insights)**
**Highest profit in 2019?** 
`Nigeria` 
**Top beer-consuming country?** `Nigeria` 
**Favorite malt in Anglophone region?** `Beta Malt` 
**Top 2 brands in Ghana?** 
`Eagle Lager`, `Castle Milk Stout` **Francophone favorite (2018–19)?** `Trophy`, `Hero`, `Budweiser`

**SQL Features Used**
`ALTER TABLE` + `UPDATE` + `CASE` for **data categorization**
`GROUP BY`, `SUM()`, `TOP`, `ORDER BY` for **aggregation & ranking**
`WHERE` with `IN` for **multi-condition filtering**
- Subqueries & conditional logic for **advanced insights**
