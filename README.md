# Big-Data-I535-Project

# Author
- Ajinkya Pawale (ajpawale@iu.edu)


In this project I will be analyzing the stock data. There is a lot of data that is generated on a daily basis in the stock market. Stock market data may be fascinating to study, and excellent prediction models can result in significant financial gains. The amount of financial data available on the internet appears to be limitless. It might be difficult to find a substantial, well-structured dataset on a wide range of organizations. This dataset contains historical stock prices (for the previous five years) for all firms currently listed on the S&P 500 index. S&P 500 is an acronym for Standard and Poor's 500, a stock market index that measures 500 publicly listed domestic firms in the United States. Many investors believe it is the most accurate overall indicator of the success of the American stock market.  

The data consists of the following fields:  
 - Date - in format: yy-mm-dd
- Open - price of the stock at market open (this is NYSE data so all in USD)
- High - Highest price reached in the day
- Low - Lowest price reached in the day
- Close - price of the stock at market close
- Volume - Number of shares traded
- Name - the stock's ticker name

The steps included in project are: 
1) Get the stock data from Kaggle datasets. Store the data in Mongo DB in the form of collections using python connector pymongo. 
2) Make changes to the schema, insert/update/delete records using pymongo. 
3) Create a data lake and run queries on it using pymongo. 
4) Create visualizations on the data. 
5) Use PySpark to extract the data from Mongo DB. 
6) Perform preprocessing and data cleaning. 
7) Use PySpark to create a ML model to predict the stock prices. 
