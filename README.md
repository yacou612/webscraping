The goal of this project is to create database containg the pricing per location, type of estate, year for the housing market in Ivory Coast. 

ideally the variables to include in the final database should be: 

1. year (of the entry)
2. month (of the entry)
3. day(optional)
4. vente (binary) --else location
5. type (villa, apartment,etc.. )
6. price
7. price_per_month (if vente == 0)
8. location
9. piscine (binary)
10. nb_baths
11. nb_beds
12. size
13. source (website (website+page) from wich the data was scrapped) -- can reference company_list.csv

The website that will be scrapped are obtained from 'websites_to_scrappe.ipynb' and are contained in company_list.csv
--------------------------------------------------------------
step 1: 
add a new col 'scrape' to company_list.csv to indicate if the site is scrapable
a.
b.
c.
step 2: create individual scrappers to collect the data we need from each website
a. 
b.
c. 
step 3: create database and bulk upload the files