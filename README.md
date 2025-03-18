This Python script scrapes product data from an e-commerce website, specifically the product titles and their corresponding prices, using BeautifulSoup. After scraping the data, it applies a Linear Regression model to predict the price of a product based on the length of its title. The script follows these steps:

Web Scraping:
Scrapes product titles and prices from a given URL.
Extracts the product title and price, storing them in a Pandas DataFrame.

Data Analysis:
Adds a new column to the DataFrame that contains the length of each product's title.
Splits the data into training and testing sets.

Predictive Modeling:
Trains a Linear Regression model using the length of the product title to predict its price.
The model's performance is evaluated using the Mean Squared Error metric.

Prediction:
Uses the trained model to predict the price of a new product based on its title length.

The script demonstrates a simple yet effective use of web scraping for data collection, followed by predictive analytics to model product pricing.







