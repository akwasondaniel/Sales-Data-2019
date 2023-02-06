# Sales-Data-2019

Introduction

An Electronics shop in Nigeria decided to expand their reach in the US. Here is their data for the year 2019 only. 


Busineess Problem

My task here is to look at the business data and study it enough to help between their renenue and increase sales for the coming year in 2020.


Data wrangling Process

Because I used power query to merge the 12 different .xlsx files into one sheet, I had some blanks and inconsitent cell formats. I went 
ahead to remove empty roles in between my data set. During my cleaning process I did the following
- Removed 900 rows of blanks spaces and unrelated texts
- Dropped 34 rows from my dataset as they were sales carried out in 2020 leaving only sales for 2019
- Used a text split function to split the address colunm to extract only the city, state, and Zip code.
- Used a text split function to split the date colunm to extract only the month, day and time
- Formatted the 'price each' column to dollars for better understanding and visualizion
- Created a column to calculate the total amount of product purchased per order id ('Quantity purchased' * 'Price each')
- Create a column to convert the amount from dollar to naira using an exchange rate of 746/$ (as at Jan. 15, 2023)
- Using the Find and Replace function I converted my month column from number format to text.

Exploratory questions
1. What was the month with the most revenue
2. What city generated the most sales
3. What product were purchased most often than others
4. Are there products that sell along side it
5. What can be done to improve the business
6. What can the business channel more efforts to increase sales

Analysis and Viz
