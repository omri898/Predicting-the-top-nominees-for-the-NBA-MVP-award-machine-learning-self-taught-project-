# Predicting the top nominees for the NBA MVP award 
#### A self taught machine learning project

## Part 1 - Web Scraping

Web scraping from "Basketball Reference" website.
Here are the key things I'm doing:

* I'm getting data on past MVP winners, player stats per season, and team record per season.
* To get data on past MVP winners, I downloaded the HTML pages for each year using requests and extracted the tables using pandas.
* To get data on player stats per season, I used ChromeDriver and the Selenium library to render the webpage and load the complete HTML.
* To get data on team record per season, I downloaded the division standings of each division and extracted the tables using pandas.
* Tools used: Pandas, Requests, BeautifulSoup and Selenium

Overall, I'm working with data from 1990/1991 season to 2021/2022 season (a total of 32 seasons).

## Part 2 - Data Cleaning & Visualization

The three datasets used are:
* Past MVP winners dataset
* Players' stats dataset
* Teams' stats dataset

Key elements:
* Selecting relevant columns, and deleting unnecessary columns.
* Dealing with missing values.
* Dealing with NaN values.
* Fixing abbreviations mismatch.
* Changing datatypes of columns.
* And more...

Finally, I merged the three datasets into one and created visualizations that highlight interesting insights.
