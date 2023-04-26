# Predicting the top nominees for the NBA MVP award 
### A self taught machine learning project

## Part 1 - Web Scraping

Web scraping from "Basketball Reference" website.
Here are the key things I'm doing:

#### Key elements:
* getting data on **past MVP winners** - downloading the HTML pages for each year using requests and extracted the tables using pandas.
* Getting data on **player stats per season** - I used ChromeDriver and the Selenium library to render the webpage and load the complete HTML.
* Getting data on **team record per season** - I downloaded the division standings of each division and extracted the tables using pandas.

Overall, I'm working with data from 1990/1991 season to 2021/2022 season (a total of 32 seasons).
 
## Part 2 - Data Cleaning & Visualization

#### The three datasets used are:
* Past MVP winners dataset
* Players' stats dataset
* Teams' stats dataset

#### Key elements:
* Selecting relevant columns, and deleting unnecessary columns.
* Dealing with missing values.
* Dealing with NaN values.
* Fixing abbreviations mismatch.
* Changing datatypes of columns.
* And more...

Finally, I merged the three datasets into one and created visualizations that highlight interesting insights.

## Part 3 - Using Machine Learning
I used regression to predict the 5 players with the highest share of votes.

#### Key elements:
* Defining relevant predictors.
* Spliting training and testing datasets.
* Training and fitting the model.
* Deciding on an error metric (Avarage Precision).
* Using backtesting to get a more robust error metric.
* Adding more predictors to get better results.
* Testing on different models such as: Ridge Regression, Elastic Net Regression, Gradient Boosting and Random Forest.


**The tools used for this project:** Pandas, Requests, BeautifulSoup, Selenium, Matplotlib and Seaborn
