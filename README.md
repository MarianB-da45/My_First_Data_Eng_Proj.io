# My_First_Data_Eng_Proj.io
Title: Juno Ecommerce Market Analysis

Overview: Juno Ecommerce, a leading vendor on Jumia, undertook a data-driven initiative to enhance competitiveness in the online retail space. The project centered on automating the collection of product and pricing data for real-time market insights.
Role: Data Engineer
Project Description: Designed and implemented web scraping pipelines to automate the extraction of product and pricing data from Jumia. Leveraged Python and relevant libraries for web scraping, data cleaning, and transformation. Built scalable systems to handle large data volumes and integrated results into dashboards for actionable insights.
Results:
Automated data collection reduced manual efforts by 90%.
Enabled real-time market analysis, optimizing pricing strategies and inventory management.
Improved decision-making agility, boosting competitiveness in a fast-paced market.


Title: Modular ClickHouse ETL Pipeline for Divy Trips

Overview: Divy Trips, a cab-hailing service in New York City, aimed to analyze historical trip data (2009–2016) stored in ClickHouse to derive actionable insights. The project required creating an automated pipeline for aggregating and loading monthly metrics into a data warehouse (DWH) to support business analytics.
Role: Data Engineer
Project Description:
Explored ClickHouse trip data to identify relevant metrics.
Developed an ETL pipeline to extract data from ClickHouse, stage it in an on-prem database, and load aggregated tables into a DWH.
Created procedures to calculate monthly metrics (average trip count, duration, and fare).
Leveraged Git for version control and collaboration:
Pushed the initial codebase to GitHub.
Refactored code for incremental data loading and created a pull request to merge changes.
Orchestrated the incremental load pipeline using Windows Task Scheduler for daily updates.
Results:
Streamlined data pipeline reduced manual intervention and ensured daily updates.
Enabled the business to perform accurate monthly trend analysis.
Facilitated collaboration and future development through modular code and Git-based version control.


Title: Orchestration and Version Control of Modular ClickHouse ETL v3

Overview: Divy Trips, a cab-hailing company in New York City, sought to process its large dataset (2009–2016) stored in ClickHouse. The goal was to generate monthly aggregated metrics and load them into a data warehouse (DWH) to support business analytics and decision-making.
Role: Data Engineer
Project Description:
Explored ClickHouse to understand the schema and identify relevant data for aggregation.
Designed and implemented a modular ETL pipeline to:
Extract trip data from ClickHouse.
Load data into a staging area in an on-prem database.
Transform and aggregate data to calculate monthly metrics, including average trip count, duration, and fare.
Utilized Git for version control:
Pushed the initial ETL code to a GitHub repository.
Created a branch, refactored the code for incremental loading, and initiated a pull request to merge changes to the main branch.
Orchestrated the pipeline for daily incremental data loads using Windows Task Scheduler, ensuring up-to-date metrics.
Results:
Developed an efficient ETL pipeline, reducing manual effort and data processing time.
Delivered actionable monthly insights to support strategic decision-making.
Established a modular and version-controlled codebase, enhancing maintainability and team collaboration.
Automated daily updates to ensure timely data availability for analytics.


Title: Data Retrieval and Storage Pipeline for GoalBet

Overview: GoalBet, a leader in sports data analytics, processes large volumes of semi-structured data (CSV, JSON, Excel) from public websites and commercial providers. The goal of the project was to automate data retrieval, enhance data quality and reliability, and store it in PostgreSQL for use by the data science team.
Role: Data Engineer
Project Description:
Designed an automated ETL pipeline to retrieve data from multiple sources, ensuring seamless integration of semi-structured formats (CSV, JSON, Excel).
Implemented data validation and transformation steps to maintain high data quality and reliability.
Configured a PostgreSQL database as the persistent store, optimizing it for efficient querying and integration with the data science team's workflows.
Used Python libraries such as Pandas, Requests, and SQLAlchemy to build the pipeline, ensuring scalability and maintainability.
Results:
Achieved end-to-end automation of data ingestion, reducing manual intervention by 95%.
Ensured high data reliability with stringent validation checks, increasing downstream analytics accuracy.
Enabled efficient storage and accessibility of data, improving the productivity of the data science team.
Delivered a robust solution that streamlined data operations and improved overall analytics workflows.
