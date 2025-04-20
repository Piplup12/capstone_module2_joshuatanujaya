# capstone_module2_joshuatanujaya
This project aims to identify and resolve inefficiencies in the discounting strategy of a SaaS (Software as a Service) company by conducting a deep data analysis on sales transactions. Using historical sales data, I discovered that a significant number of transactions were generating negative profit, often as a result of inconsistent or excessive discounts. These findings highlighted a serious flaw in the company's current discounting system, which lacked structure and profitability safeguards.
To address this, I designed and implemented a data-driven discount optimization framework. The core approach involved:

1. Analyzing all relevant variables (e.g., discount, profit, product, country, industry, segment, and date) to understand where and why losses were occurring.

2. Grouping transactions logically based on discount size and profit impact — such as “High Discount - High Loss,” “Medium Discount - Moderate Loss,” etc.

3. Assigning discount caps to each group based on their performance, ensuring that loss-prone groups were either given strict limits or no discount at all.

4. Recalculating sales and profit using the new capped discount values to simulate a revised pricing model.

5. Comparing profitability before and after the new strategy was applied, showing improvements in total profit and a reduction in loss-making transactions.

6. Visualizing results by category (country, product, industry, etc.) to validate the effectiveness of the new system and support business decision-making.

The project demonstrates how data science can be used not only to diagnose problems but also to implement strategic, financially-sound solutions that are scalable and actionable.
