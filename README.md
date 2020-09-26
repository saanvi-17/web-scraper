# Web Scraper
<p> Web scraping is the process of using bots to extract content and data from a website.
Web scraping is not illegal but it is important to be ethical and respect the rules of thes site.
</p>
<p> In this project we have done webscraping for 'quotes.toscrape.com'.
10 pages of this site have been scraped and saved into a .csv file.
The data can be saved in a .csv/.json/.xml file and further exploratory data analysis can be done on the scraped data.
</p>
<p> This is the site from where data is being scraped.</p>


![image](https://user-images.githubusercontent.com/62648110/94331473-4ac3d680-ffea-11ea-8dfb-fff3ac433b2c.png)

# Steps involved 
1. Install the given python libraries.
- pip install Scrapy
2. open the terminal and write the following lines of code
- scrapy startproject quote
- cd quote
3. after you're done with the code, use the crawler
- scrapy crawl quotes
4. to save the scraped data in a .csv/.json/.xml
- scrapy crawl quotes -o items.csv

# Screenshots

### Terminal

![image](https://user-images.githubusercontent.com/62648110/94331615-91fe9700-ffeb-11ea-8b53-673c3a236cd0.png)

### .csv file
