# Supermarket-Sales-Analys-Power-BI-
An analysis of a supermarket sales dataset using Power BI.

## Tony Supermarket Sales Analysis

### Data Importation

The data was imported from Kaggle and loaded into Power BI. The dataset is a sales record for a supermarket, which I’ve dubbed “Tony Supermarket” for the purpose of this analysis.

### Observation:

The dataset has 17 columns and 1000 rows. Also, two columns “Tax 5%” and “gross income” appears to be a duplicate of one another. I ran a quick check with other sales columns and realized that the “Tax 5%” was mistakenly duplicated to form the “gross income” income.

![PB1-1](https://user-images.githubusercontent.com/101093568/186973762-763ecba7-61d7-4529-b2cc-b39d65959b12.png)


### Data Wrangling:

i) Rename table: I renamed the table to “supermarket_sales”.


ii) Remove columns: I started cleaning the data by deleting the “gross income” column. The “Time” and “gross margin percentage” columns won’t also be important in my analysis so I removed them.


iii) Data Types: I made sure that the data types of every column are the appropriate data type.


iv) Remove errors: I selected the “Invoice ID” column and filtered out the empty and duplicate rows. Since there must be only one ID valid for every sales, the Invoice ID column is the primary key in this table.


v) Rename columns: The “Tax 5%” column was renamed to “Tax Imposed (5%)” and the “Total” column also renamed to “Total COGS”. This is to ensure clarity.


vi) Table Creation: I created a new date table called “date” that corresponds to the “Date” column of the supermarket_sales table.


Dashboard:

After cleaning the data I proceeded to making various charts and bringing them together to form a dashboard.

![PB1-2](https://user-images.githubusercontent.com/101093568/186973828-3b223244-7063-4a21-a9d4-43c1702a132d.png)
