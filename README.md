# bizzbuysell_scraper
Scrapes for the following information format
[Name,location,block1,block2,block3,ad_id,phone_block, url]

name- posting name
location - county or state or both
block1- contains asking price,Cashflow,Inventory,EBITDA,FF&E, Inventory,Rent,Established date
block2 - description of the company
block3- contains detailed information about company
ad_id - ID of the company posting
phone_block-name of broker and contact
url- the postings url


# User Interface
Currently under construction 

# Scraping information. 
Given a state or city url from bizbuysell.com the scraper can return the listings and the contents within the listing.
After the program has access to the results page, it can use another Python package called BeautifulSoup, which accesses a copy of the page's HTML source. This package then sorts through all of the objects on the page by tag, and pulls out the relevant information by categories and compiles a list of results. This list is then converted into a csv file and concats the results. 
