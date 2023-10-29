# Data Analysis Projects Repository
Welcome to my Data Analysis Projects Repository! This repository is a collection of my data analysis projects presented in a professional manner. Whether you're a fellow data enthusiast, a potential employer, or just curious, you'll find a diverse range of projects here, showcasing my skills and expertise in data analysis. You can 

Project Structure
The repository is organized into subdirectories, each representing a specific data analysis project. You can explore these projects to see how I've tackled various real-world data challenges, from data cleaning and preprocessing to visualization and modeling.

Project List
Here are a few of the projects you can find in this repository:

Project 1: # Unsupervised Learning Trading Strategy

* Download/Load SP500 stocks prices data.
* Calculate different features and indicators on each stock.
* Aggregate on monthly level and filter top 150 most liquid stocks.
* Calculate Monthly Returns for different time-horizons.
* Download Fama-French Factors and Calculate Rolling Factor Betas.
* For each month fit a K-Means Clustering Algorithm to group similar assets based on their features.
* For each month select assets based on the cluster and form a portfolio based on Efficient Frontier max sharpe ratio optimization.
* Visualize Portfolio returns and compare to SP500 returns.

Project 2: # Twitter Sentiment Investing Strategy

* Collecting data from Twitter(X), data on stocks and comparing it with other stocks based on thier likes and comments.
* Aggregate on a monthly level and calculate average monthly metric, for the one we choose.
* Select top 5 stocks by rank for each month and fix the date to start at beginning of next month.
* Create a dictionary containing start of month and corresponded selected stocks.
* Download fresh stock prices for only selected/shortlisted stocks.
* Calculate Portfolio Returns with monthly rebalancing.
* Download NASDAQ/QQQ prices and calculate returns to compare to our strategy

Project 3: # Intraday Strategy Using GARCH Model

* Using simulated daily data and intraday 5-min data.
* Load Daily and 5-minute data.
* Define function to fit GARCH model on the daily data and predict 1-day ahead volatility in a rolling window.
* Calculate prediction premium and form a daily signal from it.
* Merge with intraday data and calculate intraday indicators to form the intraday signal.
* Generate the position entry and hold until the end of the day.
* Calculate final strategy returns.
* 
Feel free to explore the individual project directories to access detailed project descriptions, code, and documentation. If you have any questions or would like to get in touch, don't hesitate to contact me.

I hope you find these projects insightful and informative. Thank you for visiting!

## Acknowledgment

This project is based on the fantastic work of @lachone_ , whose Algorithmic Trading – Machine Learning & Quant Strategies Course with Python([link-to-original-source](https://youtu.be/9Y3yaoi9rUQ?feature=shared)) served as the foundation for this work.


Jagjeet Singh Chauhan
