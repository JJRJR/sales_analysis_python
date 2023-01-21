# sales_analysis_python
Working step by step through data sets to provide a full Business Analysis.

Task:
## How much was earned that Year?
### Total sales for 2019: $34,483,365.68
- First step was to merge all the month files into one using Python. 
- Cleaned up the data via excel by removing all NaN values and errors in data. 
- Multiplied quantity * price of each item to get totals of each transaction 
- AutoSum on the total column

## What was the best month for sales? How much was earned that month?
### December is the best month of sales. December sales: $4,589,254
- In the merged_file_2019 I added a filter for each column
- Filtered date column by each month
- Autosum each month's Total

## What City had the highest number of sales?
### San Francisco  44,720 transactions

- Highlighted Address column
- Used Text to Columns to seperate address into street address, City, State, and zip code
- changed format to '00000' under special
- created a new Dataframe in Python with the updated merged_file_2019
- Used unique() to get view how manay different cities the items were sold in
- since each transaction has an order I.D I used value_counts() to get a count of each cities total number of sales
- confirmed it with total from all locations

Q: What time should we display adverstisement to maximize likelihood of customer's buying product?
Q: What products are most often sold together?
Q: What product sold the most? Why do you think it sold the most?

How Much Probability?
How much probability for next people will ordered USB-C Charging Cable?
How much probability for next people will ordered iPhone?
How much probability for next people will ordered Google Phone?
How much probability other peoples will ordered Wired Headphones?