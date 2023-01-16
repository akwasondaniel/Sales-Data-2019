# Sales-Data-2019


Cleaning Process

Because I used power query to merge the 12 different .xls files I had some blanks and inconsitent cell formats. I went 
ahead to remove empty roles inbetween my data set
- Removed 545 blanks spaces
- Removed 355 invalid records created by power query
- Used a text split function to split the address colunm to extra only the city and state
- formatted the 'price each' to dollars for better understanding and visualizion
- Created a column to calculate the total amount of product purchased per order id
- Create a column to convert the amount from dollar to naira using an exchange rate of 746/$ (as at Jan. 15, 2023)
- I dropped 34 rows from my dataset as they were sales carried out in 2020 and not 2019
