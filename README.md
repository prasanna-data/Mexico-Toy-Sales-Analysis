#MEXICO TOY SALES – MAVEN TOYS
Maven Toys, a company currently operating in North and South America with around 50 stores, is looking to expand its reach to key markets in North America and Europe. To identify areas for improvement and propose strategies for successful expansion, this document analyzes sales data. Although the global toy market is expected to grow significantly, Maven Toys faces challenges such as seasonality, lack of online presence, and underperforming product categories.

## Data Preparation
For this project, I used Power BI Desktop. The dataset consists of 5 CSV files: Stores, Sales, Inventory, Products, and Date. After downloading and connecting the files, the first step I took was data profiling. This step is necessary to get familiarized with the data and to ensure its completeness while identifying any potential anomalies.

## Data Modeling
The data model includes one fact table and four dimension tables. Three dimension tables - Stores, Date, and Products tables - are connected to the fact table named Sales table. The Inventory table is connected to the Products table and Stores table. These are connected in a star schema with one-to-many relationships.

## Data Analysis
I added some calculated columns in the tables along with a new table named Key Measures to contain all the necessary measures for data analysis. Then, I created a report which includes toys sales analysis, location analysis, product analysis, and key influencers. This report helps in getting insights about the business.

## Insights and Recommendations
Here are the insights and recommendations based on the data analysis:
1. Prioritize expanding with new stores in Airports, Downtown, and Commercial locations.
2. Limit restocking the Sports & Outdoors product category. Implement targeted sales, discounts, and promotions to boost sales for the slow-moving items.
3. Implement loyalty programs, particularly for products like Lego Bricks, to encourage repeat purchases and foster customer loyalty.
4. Expand new stores from March to July, which have more sales than the other months of the year.
