Countries X and Y Risk Analysis and Data Compilation
This project involves analyzing corporate and retail data for MBM Countries X and Y, including risk assessment tasks and VBA-based data compilation for Country X's Dealer portfolio. The project is divided into two parts: Analysis of Corporate & Retail Data and VBA Code for Dealer Portfolio.
Part I: Analysis of Corporate & Retail Data
Objective
Perform a risk assessment of the portfolio for MBM Countries X and Y, each with two funding entities having distinct business profiles, over a 12-month period. The analysis uses data from the RetailFleet_Data.xlsx file, which includes risk parameters, number of contracts, total volume, and reserves level.
Tasks

Aggregation of Probability of Default (PD):
Calculate volume-weighted PD on the total portfolio level per country for June 2020.

Aggregation of Future Expectations (FE):
Calculate volume-weighted FE on the total portfolio level per country for June 2020.

Provisioning Ratio:
Compute reserves divided by volume on the total portfolio level per country for June 2020.

Power BI Dashboard:
Create a dashboard to visualize reserves and parameter development over the past year.
Highlight major changes in the portfolio and justify deviations (e.g., identify risk parameters contributing to higher or lower reserves).
Include filtering capabilities at the country level.

Data Source

File: RetailFleet_Data.xlsx
Content: Risk parameters, number of contracts, total volume, and reserves level for the last 12 months, per country and funding entity.

Part II: VBA Code for Country X Dealer Portfolio
Objective
Compile and analyze data for Country X’s Dealer portfolio, which is associated with a single funding entity. The raw data is provided in Dealer_Data.xlsx, split across separate worksheets for the last 6 months.
Tasks

Overview Worksheet:
Create a new worksheet named Overview.
Aggregate portfolio-level values for volume and reserves on a monthly basis.
Calculate the provisioning ratio (reserves divided by volume) for each month.


Top3 Worksheet:
Create a new worksheet named Top3.
List the top 3 customer groups by reserves for each month, sorted in descending order.
Display total volume and reserves level for each customer group.



Data Source

File: Dealer_Data.xlsx
Content: Monthly data for the last 6 months, stored in separate worksheets.

Requirements

Software:
Microsoft Excel (for VBA code execution and data processing).
Power BI (for dashboard creation in Part I).


Inputs:
RetailFleet_Data.xlsx (Part I).
Dealer_Data.xlsx (Part II).

Outputs:
Aggregated metrics (PD, FE, provisioning ratio) for June 2020 (Part I).
Power BI dashboard with visualizations and country-level filters (Part I).
Excel workbook with Overview and Top3 worksheets for Country X’s Dealer portfolio (Part II).

Instructions

Part I:
Load RetailFleet_Data.xlsx into Power BI for analysis and dashboard creation.
Perform volume-weighted calculations for PD and FE, and compute provisioning ratios for June 2020.
Develop the Power BI dashboard to visualize trends and highlight significant changes, ensuring country-level filtering.

Part II:
Open Dealer_Data.xlsx in Microsoft Excel.
Run the VBA script to create the Overview and Top3 worksheets with the specified aggregations and rankings.
Verify the accuracy of the provisioning ratio and top 3 customer group listings.

