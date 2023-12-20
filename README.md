# Music Store Data Analysis Project

## Overview
This project aims to analyze music store data to derive meaningful insights that the company can use to improve its sales and business strategies. The analysis is conducted using Excel for data preparation, SQL for data processing, and Tableau for visualization.

## Business Objectives
The primary business objectives of this analysis are:
1. Optimize profits by identifying key regions and genres.
2. Identify emerging trends in customer spending.
3. Provide recommendations based on the analysis.

## Data Source
The music store dataset is freely available and can be downloaded [here](https://shorturl.at/DJMUX). It consists of 12 CSV files containing album details, invoice details, customer details, genre details, playlist details, as well as artist and track details.

## Steps of Data Analysis

### Step 1: Ask
Define business objectives and questions to address:
- How to optimize profits?
- What are emerging trends?
- How to build recommendations?

### Step 2: Prepare
Identify and assess features of the Music Store dataset:
- Dataset available in 12 CSV files.
- Customer data limited to 59 customers.
- Data cleaning and manipulation using Excel.

### Step 3: Process
Use Excel to observe, check for missing data, remove duplicates, and format columns for SQL analysis. Ensure data consistency and correctness.

### Step 4: Analyze
Use PostgreSQL 15 for SQL queries on the Album dataset. Answer key questions such as:
1. Most profitable region and top 5 genres.
2. Top 5 non-performing regions.
3. Location of top 10 customers.
4. Most sold genre and artist.
5. Top spending customers in each country.

### Step 5: Share
Share observations through Tableau dashboard. Key findings include:
- USA as the most profitable region.
- Top spending customers from unexpected regions.
- Popular genres and artists in different regions.



### Step 6: Act
Conclusions and Recommendations:
- Consider focusing on profitable regions (USA, Canada) and developing Brazil market.
- Use dynamic dashboard insights for targeted promotions.
- Evaluate non-performing regions for potential closure.

## Project Structure
- **/data**: Contains the raw dataset files.
- **/sql**: SQL scripts for data analysis.
- **/docs**: Project documentation, including this README file.

## Usage
1. Download the music store dataset from the provided link.
2. Use Excel for initial data observation and cleaning.
3. Execute SQL scripts in PostgreSQL 15 for detailed analysis.
4. Explore Tableau dashboard for visualizations and insights.

## Contributor
- Yogeshwar Kaulwar

## License
This project is licensed under the [MIT License](LICENSE).
