# Online-sales-platform-analysis
This Capstone project combines SQL, Google Sheets, and Tableau to analyze the e-commerce platform sales data.

# Project Overview
In this project, I used SQL, Google Sheets, and Tableau to analyze Unicorn E-commerce platform sales data, find interesting insights and identify weak areas and opportunities for Unicorn to boost business growth.

# The Datasets
I used datasets that includes 4 tables with the following structure:





# Outcomes
I've written SQL queries to provide the following information:
1. GLOBAL SITUATION
- What was the total forest area (in sq km) of the world in 1990? Please keep in mind that you can use the country record denoted as “World" in the region table.
- What was the total forest area (in sq km) of the world in 2016? Please keep in mind that you can use the country record in the table is denoted as “World.”
- What was the change (in sq km) in the forest area of the world from 1990 to 2016?
- What was the percent change in forest area of the world between 1990 and 2016?
- If you compare the amount of forest area lost between 1990 and 2016, to which country's total area in 2016 is it closest to?
2. REGIONAL OUTLOOK
- What was the percent forest of the entire world in 2016? Which region had the HIGHEST percent forest in 2016, and which had the LOWEST, to 2 decimal places?
- What was the percent forest of the entire world in 1990? Which region had the HIGHEST percent forest in 1990, and which had the LOWEST, to 2 decimal places?
- Based on the table you created, which regions of the world DECREASED in forest area from 1990 to 2016?
3. COUNTRY-LEVEL DETAIL
- Which 5 countries saw the largest amount decrease in forest area from 1990 to 2016? What was the difference in forest area for each?
- Which 5 countries saw the largest percent decrease in forest area from 1990 to 2016? What was the percent change to 2 decimal places for each?
- If countries were grouped by percent forestation in quartiles, which group had the most countries in it in 2016?
- List all of the countries that were in the 4th quartile (percent forest > 75%) in 2016.
- How many countries had a percent forestation higher than the United States in 2016?

As a result of the above, I have prepared a report to help understand the global deforestation overview between 1990 and 2016.

# Requirements

* Language: SQL

# Get started with the project
- Download and install [DB Viewer](https://sqlitebrowser.org/dl/) for SQLite or use another tool of your choice that can load SQLite db file and run the queries.
- The first step is to download the DB and the DB.sqbpro files. The second step is to open the DB.sqbpro as a project in SQLite. Scripts for running the queries are also attached to the report.

# Author

 * [Manuk Mikayelyan](https://github.com/mmikayelyan) - Sole author for this program.
 
 # Acknowledgements

* [Udacity](https://udacity.com) - Udacity's Data Analyst Nanodegree program and [Masterschool](https://www.masterschool.com/) instructors were extremely helpful while I was pursuing this project.
* [devart](https://www.devart.com/dbforge/sql/sqlcomplete/self-join-in-sql-server.html) - Understanding SQL Server SELF JOIN By Practical Examples
* [w3schools](https://www.w3schools.com/sql/sql_join_self.asp) - SQL Self Join
* [dpriver](https://www.dpriver.com/pp/sqlformat.htm) - Instant SQL Formatter


# Explore-NYSE-financial-data
MS Excel is being used to analyze real life financial data from the New York Stock Exchange.

# Project Overview
I analyzed historical financial data from S&P 500 companies for this project. As part of my work, I developed a financial forecasting model, a report, and dynamic dashboards within a spreadsheet program. 

# The Dataset
In this project I used a subset of a large dataset provided by [Kaggle](https://www.kaggle.com/datasets/dgawlik/nyse). The following information is included in the projectdata-nyse.csv file:
- Ticker symbol: Stock symbol
- Years: Number of years for which data is provided
- Period ending
- Total revenue
- Cost of goods sold
- Sales, General, and Administrative expenses
- Research and Development expenses
- Other Operating expense items
- Global Industry Classification Standard (GICS) Sector: The industry sector the company is categorized under (e.g., American Airlines with the ticker symbol AAL is categorized under Industrials.)
- GICS Sub Industry: Sub-industry sector the company is categorized under (e.g., AAL is further categorized under the sub-category of the "Airlines" industry.)

# The Outcomes
- An analysis of the data was conducted and a presentation was prepared to share the results
- Created a dashboard for a profit and loss statement
- Developed a financial forecasting model based on three scenarios

The resultes are presented in the folloeing files:
 -nyse_project.pdf - the presentation with the visuals and summary
 -nyse_project.xlsx - spreadsheet workbook used to do the analysis for the report containing the following tabs:
   - Data file
   - Summary statistics
   - P&L Statement Dashboard
   - Forecast scenarios

# The Interactive Experience
A dashboard created for a Profit and Loss Statement that calculates the Gross Profit, Operating Profit, or EBIT for a company selected from a drop-down list. The drop-down list pulls historical fundamentals data to create the P&L Statement. The P&L statement includes the Gross Profit, Operating Profit, and EBIT values for all the years there is historical data available for that company in the dataset.
A financial model created for a company of user choice that forecasts out the Gross Profit, Operating Profit, and EBIT for two more years using three scenarios (Best case, Weak case, and Base case). The forecasting model is dynamic for the selection of the case (Weak, Base, Strong) and for the chosen company sticker symbol.

# Requirements

* You may use any spreadsheet application you like. This includes Google Sheets, Microsoft Excel, etc.

# Author

 * [Manuk Mikayelyan](https://github.com/mmikayelyan) - Sole author for this program.
 
 # Acknowledgements

* [Udacity](https://udacity.com) - Udacity's Data Analyst Nanodegree program and [Masterschool](https://www.masterschool.com/) instructors were extremely helpful while I was pursuing this project.
