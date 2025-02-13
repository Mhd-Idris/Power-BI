# IMDb Performance Dashboard

### Dashboard Link : https://drive.google.com/file/d/1xBRhlhXDIgQqGuV15ROGO_g6EsMoeIG5/view?usp=sharing

## Problem Statement

This dashboard provides insights into the performance of movies based on their budget, worldwide gross, ratings, and distribution by country and language. It helps stakeholders understand key metrics such as total titles, average ratings, and average Metascores. By analyzing trends in budget allocation, audience preferences by language, and top-performing movies, the entertainment industry can make data-driven decisions to optimize production and marketing strategies.

### Steps followed 

- Step 1 : Load movie dataset into Power BI Desktop; dataset contains information on movies, a CSV file.
- Step 2 : Open Power Query Editor and check the column distribution, column quality, and column profile under the "View" tab.
- Step 3 : Since by default, profiling is done only for 1,000 rows, select "Column Profiling Based on Entire Dataset" to analyze all rows.
- Step 4 : Perform data cleaning by removing unnecessary data, such as empty columns, especially in the budget and worldwide gross sections, and separating the release year from the country of origin.
- Step 5 : Since there were differences in currency formats for the budget and worldwide gross, I converted all values to USD for consistency. 
- Step 6 : As some movies had identical titles but were released in different years, I added a new column combining the movie title and release year to ensure accurate visualization.
- Step 7 : After finalizing the data processing in Power Query, I created card visuals displaying key metrics such as total titles, average rating, average Metascore, and release year.

![Image](https://github.com/user-attachments/assets/a0749c93-7796-4a4a-bfef-9864f4c74265)
- Step 8 : Added a bar chart displaying budget and worldwide gross, as well as another bar chart showing languages used in movies.

![Image](https://github.com/user-attachments/assets/36bc0e4e-12d3-4f7e-8d78-51debd856945)
- Step 9 : Created a line chart to visualize movie production trends over the years.

![Image](https://github.com/user-attachments/assets/1fa34c82-bc50-4673-82b2-6274fb2f0c78)
- Step 10 : Developed a treemap displaying the top 10 countries with the highest movie production.

![Image](https://github.com/user-attachments/assets/9d4bf919-9fb5-438d-9844-d5f7227873dc)
- Step 11 :Added slicers to allow users to filter specific searches easily.

![Image](https://github.com/user-attachments/assets/e5b14efc-67a1-409d-affd-0ded907b95be)
- Step 12 : Finally, I arranged all visuals on the dashboard to ensure a clear and visually appealing layout.



### [1] IMDb Overview

Total Number of Titles: 1,855

Total Countries Represented: 53

Time Period Covered: 1927 - 2024

    The dataset spans nearly a century of film production, providing insights into long-term industry trends.
           
### [2] Average Ratings & Metascore

Overall Average Rating: 7.61/10

Average Metascore: 74.06/100
  
    While calculating the average rating, null values were ignored as they were not relevant for some customers. These ratings may change when different filters are applied.   
  
  ### [3] Revenue Insights 
  
Avatar: $2.9B

Avengers: Endgame: $2.8B

Avatar the Way of Water: $2.3B

Titanic: $2.3B

Star Wars: The Force Awakens: $2.1B

	Many top-grossing movies had budgets between $200M - $400M, but revenue varies significantly.

 ### [4] Country & Language Insights
 
 ### Top 3 Countries by Number of Titles:
 
  United States – 1,106 titles
 
 United Kingdom – 246 titles
 
 France – 93 titles
          
### Top 3 Languages Used in Movies:

English (1,496 movies)

French (74 movies)

Japanese (42 movies)
       
       The best-selling products should be prioritized for promotions and stock management.

 ### [5] Movie Trends by Year

The graph shows a significant increase in movie production each year. However, there was a sharp decline in 2020 and 2022, coinciding with the COVID-19 pandemic that severely impacted the film industry, causing delays, cancellations, and reduced production. Despite the setback, movie production started recovering in the following years, indicating a gradual rebound in the industry


