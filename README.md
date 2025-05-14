# Top 1000 IMDb Movies 

### Project Link : top 1000 movies pbix file.pbix

## Problem Statement

This project focuses on analyzing the Top 1000 IMDb movies to understand trends in genres, certifications, ratings, metascores, and revenue. The goal is to derive meaningful insights that explain what attributes top-rated movies share, how genres and certifications influence performance, and how audience engagement (votes) aligns with critical reception. By doing so, this project aims to showcase the power of data-driven storytelling in the entertainment industry.

### Steps followed 

Stage 1 : Data Cleaning in Excel.

- Step 1 : Imported the raw IMDb Top 1000 movies dataset (CSV format).

- Step 2 : Removed duplicates and irrelevant columns.

- Step 3 : Cleaned inconsistent values (e.g. standardized genres, removed special characters from revenue, runtime).

- Step 4 : Converted data types (e.g. numbers, dates, currency).

- Step 5 : Created new helper columns: Decade from year (e.g. 1990s, 2000s)

- Step 6 : Primary Genre from multi-genre field.

- Step 7 : Handled missing data (replaced “-” or blanks with NA where necessary).

- Step 8 : Saved the cleaned dataset as a .xlsx file for import into Power BI.
 
Stage 2 : Data Visualization in Power BI

- Step 9 : Imported the cleaned Excel file into Power BI.

- Step 10 : Built a multi-page dashboard:

- Step 11 : Page 1 – Overview:

Pie chart : Number of Movies by Genre

Bar chart : Meta Score by Genre

Stacked Area chart : Revenue by Genre

Donut chart : Movies by Certificate Type

- Step 12 : Page 2 – KPIs & Interactivity

KPI cards: Average Rating, Total Votes, Total Revenue,Total Movies,
Scatter Chart: Rating vs Revenue.

Slicers for Genre, Certificate, and Year.

# Screenshot of Dashboard 

![Image](https://github.com/user-attachments/assets/9f7b6310-3f87-405f-bb13-43127b48798f)

 
 # Screenshot KPIs

![Image](https://github.com/user-attachments/assets/78e43928-5861-466f-9f1d-e1dc8c93a919)

# Insights

- Drama is the most common genre among the Top 1000 movies, indicating a strong preference for emotionally rich storytelling.

- R-rated movies dominate the top list, suggesting mature themes often resonate with critics and audiences alike.

- Meta Score and IMDb Rating generally align, but a few movies with high public ratings have modest critical scores, highlighting the difference in public vs critic perception.

- The 2000s and 2010s contributed the most to the Top 1000 list, showing a rise in high-quality, high-budget cinema in recent decades.

- Movies with higher runtime (above 150 mins) tend to have better ratings, suggesting that more time allows for better character and story development.

- Revenue and Rating are not strongly correlated  some of the highest grossing films do not necessarily have the best ratings, and vice versa.

- Some movies have high IMDb ratings but relatively low vote counts, suggesting they may be underappreciated or lesser known classics.








