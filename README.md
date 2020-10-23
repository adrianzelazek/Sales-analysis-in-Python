# Analysis of sales in 2012-2014 in a certain company using Python
### Author: Adrian Żelazek

In this project was used dataset concerning sales data of a certain company between 2012 and Q3 2014. The dataset contains 88475 records as well as 13 columns. The main target of this project was to perform a sales analysis of a certain company and inferring based on the results obtained. This project was developed for the purpose of practicing data analysis and visualization using Python.

##### It is preferred to run/view the project via Jupyter Notebook (.ipynb) than via a browser (HTML). To see the HTML version you first need to download the HTML file and then run it in your browser.

### Programming language and platform
* Python - version : 3.7.4
* Jupyter Notebook

### Libraries
* Pandas version is 0.25.1
* NumPy version is 1.16.5
* Matplotlib version is 3.1.2
* Seaborn version is 0.9.0

### Actions performed
* Analysis of number of transactions in countries
* Analysis of number of order method types per country
* Analysis of popularity of order method types in specified countries
* Profitability and fequency of order method types
* Profit assesment
* Analysis of profitability of selected years (2012-2014)
* Analysis of profitability of products including units sold and unit price

### Short summary of results
1. Between 2012 and Q3 2014, 88475 transactions were carried out:
* 34128 in 2012,
* 33023 in 2013
* 21324 in 2014 (up to Q3)
2. There are:
21 countries,
7 order method types,
8 retailer types,
5 product lines,
21 item types,
144 different products
3. Year by year there is increase of profits in each country.
3. Year by year there in almost every country mean price is falling or rising minimally.
4. In 2013, compared to 2013, in each contry there was an increase in sales of products, except France, where was a minimal drop in sales. No complete data for 2014 (only up to Q3).
5. Most of the most expensive products (price above 351.62 money units, 10% of the most expensive products) were sold in: USA, France, Canada, Japan, Germany.
6. Most of the least expensive products (price below 6.65 money units, 10% of the least expensive products) were sold in: USA, Japan, France, Germany, Canada.
7. By far the most products were sold through the website. The website also generates the biggest profit, the biggest profit per order. However, the website does not generate the greatest profit per unit sold. It means that the most expensive products are not sold with this method of making an order.
8. The hugest profit per unit sold generate sales visit, and fax, so the most expensive products are sold by these order method types. Low indicator of profit per unit sold have: Mail and Special.
