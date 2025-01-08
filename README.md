# Sales-Analysis-Excel

### Project Overview
This project aims to review and analyse the sales data from multiple branches of a supermarket franchise in the United States. Using four years of business data, we seek to analyse the performance of sales and profit over the years. We also aim to analyse business performance by examining product sales, store performance and profitability of discount products. Finally, we will perform a profit forecast for the first quarter of the coming year.

### Table of content
- [Data Source](#data-source)
- [Business Questions](#business-questions)
- [Tools](#tools)
- [Data Cleaning/Validation](#data-cleaningvalidation)
- [Profit and Sales Analysis](#profit-and-sales-analysis)
- [Profit and Sales by State](#profit-and-sales-by-state)
- [Sales by Sub-Categories (Products)](#sales-by-sub-categories-products)
- [Sales and Profit by Discounted and Non-Discounted Products](sales-and-profit-by-discounted-and-non-discounted-products)
- [Next Year Profit Forecast (First Quater)](#next-year-profit-forecast-first-quater)
- [Insights](#insights)
- [Recommendation](#recommendation)

### Data Source
The dataset used in this project was obtained from [Kaggle](https://www.kaggle.com/datasets/ishanshrivastava28/superstore-sales) and titled the "Superstore sales" Dataset.

### Business Questions
- How have profit and sales performed over the years?
- What are our best-performing locations(states)?
- Which items(sub-category) have the worst and best sales
- What was the performance of discounted products compared to non-discounted products
- What is the profit forecast for the next year

### Tools
- Excel (Data Cleaning/Validation, Data Analysis, Dashboarding)

### Data Cleaning/Validation
Checking for duplicate rows

![Screenshot (133)](https://github.com/user-attachments/assets/735dac2c-9e87-4c36-af0e-29e8391ae7bf)

![Screenshot (134)](https://github.com/user-attachments/assets/62b67632-9d0f-4c05-b488-d830765580b8)


Checking column datatypes, checking for blank cells and checking for spelling errors in Power Query

![Screenshot (135)](https://github.com/user-attachments/assets/846149f0-bc89-46e1-a4b6-79b5d3571103)

### Profit and Sales Analysis
Creating a calculated Field to find out what % of the sales figure is the profit (profit as % of sales)

![Screenshot (137)](https://github.com/user-attachments/assets/cd57950f-3723-4147-8699-77a9c6dd39de)

Sales, Profit and Profit as % of Sales Over Time (Clustered Column Chart)

![Screenshot (152)](https://github.com/user-attachments/assets/4ac7992d-827d-4d6c-b77b-c77ce7d57963)

### Profit and Sales by State
We highlight the top 5 best-performing locations(states) by Profit and Sales(Clustered column chart).

![Screenshot (156)](https://github.com/user-attachments/assets/82b6f315-90e9-4374-9067-a4357e324fef)


### Sales by Sub-Categories (Products)
We show the best product sub-categories to the least Product sub-categories (column chart)

![Screenshot (157)](https://github.com/user-attachments/assets/92898d21-889a-46fb-8274-0f3a76cb2fc9)

### Sales and Profit by Discounted and Non-Discounted Products
We compare the sales and profits of discounted products against non-discounted products (stacked column chart)

![Screenshot (159)](https://github.com/user-attachments/assets/02d91327-59bf-417c-9278-f1a3c7cda501)


### Next Year Profit Forecast (First Quater)
Profit Forcast for "Quater 1 2015" With upper and lower confidence Bounds (Line chart)

![Screenshot (154)](https://github.com/user-attachments/assets/eb84a489-0bca-4ffb-8b23-a0bac50e7d14)

Profit Forcast for "Quater 1 2015" simplified to just forecast (Line chart)

![Screenshot (155)](https://github.com/user-attachments/assets/6bc90364-6ae6-4bce-b107-0fa24295dfb9)

### Insights
- There has been consistent growth in sales since 2013 but the profit margins have stagnated at 13% since 2012.
- California is the best-performing state in terms of profit and sales.
- Profits are set to increase in the first quarter of the following year
- Phones are the most sold items in the sub-category while Fasteners have the least amount of sales across all branches
- Discounted products make no profit and make less sales than non-discounted products. Not only do non-discounted products make more sales, they are also profitable.
- Profits are projected to increase by 98.86% in the first quarter of the coming year.

### Recommendation
- Limit the discounted product to the poorly performing locations and offer fewer discounts in states with better sales
  this aims to increase the performance of other branches as well as increase profit margins.
  


