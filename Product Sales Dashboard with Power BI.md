# Product Sales Dashboard

### Dashboard Link : https://drive.google.com/file/d/1qR3-Fu6KWao1A4CiholoMNHGOCimarXb/view?usp=sharing

## Problem Statement

This dashboard provides insights into product sales trends and performance. It helps businesses understand key metrics such as total sales, average sales per item, number of items sold, and customer satisfaction ratings. By analyzing performance by gender, category, and seasonal trends, businesses can optimize their sales strategies and improve overall performance.
Since a significant portion of sales occurs without discounts (57.35%), businesses may have strong brand value. However, only 26.88% of sales come from subscribed customers, indicating a need to enhance loyalty programs.

### Steps followed 

- Step 1 : Load data into Power BI Desktop; dataset is a CSV file.
- Step 2 : Open Power Query Editor and check the column distribution, column quality, and column profile under the "View" tab.
- Step 3 : Since by default, profiling is done only for 1,000 rows, select "Column Profiling Based on Entire Dataset" to analyze all 3,900 rows.
- Step 4 : It was observed that no errors or missing values were present except in the “Review Rating” column.
- Step 5 : When calculating average ratings, null values were ignored, as less than 1% of values were missing. 
- Step 6 : Card visuals were added to display key metrics such as total sales, average sales per item, total items sold, and average customer rating.
![Image](https://github.com/user-attachments/assets/5de1dddd-236d-420a-a134-c38ac47ad800)
- Step 7 : Created a bar chart to display the top 10 selling products, a pie chart to show performance by gender, and another pie chart for category by gender.
![Image](https://github.com/user-attachments/assets/7293ea14-743b-4ec4-84f1-76a670f18cb8)

- Step 8 : Added a slicer to filter total sales, average sales, number of items, and average ratings.
![Image](https://github.com/user-attachments/assets/9fb11f2c-c19a-4294-a92d-80f6d2dfe0f0)

- Step 9 : Created a tree visual to display the top 10 locations based on total sales.
![Image](https://github.com/user-attachments/assets/5f0affd5-d1fe-41a4-91aa-732d9ac8dbb5)

- Step 10 : Created a pie chart to display discount usage and subscription status.
![Image](https://github.com/user-attachments/assets/2308db6c-e785-4ebd-b8cb-30ff49256821) 

- Step 11 : Created a matrix visual to show total sales, number of items, average sales, and average rating based on season.
![Image](https://github.com/user-attachments/assets/03ed4c36-82be-4e6c-862a-99caed4b87ca)

- Step 12 : Added a slicer to filter category, item, shipping type, color, size, and payment method. Also, included additional filters to reset the dashboard to its default state.
![Image](https://github.com/user-attachments/assets/f01bcc8a-8e73-4db5-9712-af606b617d8f)

- Step 13 : Finalized the layout by arranging all created visuals for better readability and presentation.




### [1] Total Number of Customers

Total Customers = 3,900

Subscribed Customers = 26.88%

Non-Subscribed Customers = 73.12%

    Thus, businesses need to focus on increasing the number of subscribed customers.
           
### [2] Average Ratings

Overall Average Rating = 3.8/5

Fall Season = 3.8

Spring Season = 3.9

Winter Season = 3.8

Summer Season = 3.8
  
    While calculating the average rating, null values were ignored as they were not relevant for some customers. These ratings may change when different filters are applied.   
  
  ### [3] Revenue Insights 
  
Total Revenue: $233.08K

Average Sales per Item: $60

Total Items Sold: 3,900

 ### [4] Some other insights
 
 ### Purchase Frequency by Season
 
 1.1) Fall: $60.02K sales, 975 items, $62 avg sales, 3.8 avg rating.
 
 1.2) Spring: $58.68K sales, 999 items, $59 avg sales, 3.9 avg rating.
 
 1.3) Winter: $58.61K sales, 971 items, $60 avg sales, 3.8 avg rating.
 
 1.4) Summer: $55.78K sales, 955 items, $58 avg sales, 3.8 avg rating
 
     Thus, maximum customers travelled by Business class.
         
### Top-Selling Items

2.1) Shirt ($10.3K), Sunglasses ($9.6K), and Scarf ($9.6K) generate the highest revenue.

2.2) Clothing items like shirts, dresses, and pants dominate the list of top-selling products.
       
       The best-selling products should be prioritized for promotions and stock management.

### Top-Selling Locations

4.1) West Virginia, Vermont, and Virginia are the top three locations in terms of sales'.

        The business should focus marketing efforts on high-sales locations to maximize revenue'. Promotions can also be targeted at low-sales locations to increase customer engagement in those areas.


