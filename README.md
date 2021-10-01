# Bitcoin-Transaction-Confirmation-Time-Regression
## Abstract 
#### The goal of this project is to scrab historical bitcoin prices data and merge it with more features to predict the transaction confirmation time.

## Design 
### Background 
#### Bitcoin is an open source cryptocurreny that was invented in 2008. Transactions of bitcoins are verified by network nodes through cryptography and recorded in a public distributed ledger called a blockchain.
### Problem
#### The transaction confirmation time varies for each transaction, so predicting the confirmation time would be a great idea.
### Value
#### Being able to predict confirmation time is valuable for the traders. 

### Data
#### Feature scrapped from stocks website "https://coinmarketcap.com/currencies/bitcoin/historical-data/"

|  Feature  | Description    |
| :----------:  | :----------: | 
|  Date| Date of the Day  | 
|  Open_Price | Price at 12:00 AM of that day  | 
|  Highest_Price | Highest price during the day  | 
|  Lowest_Price | Lowest price during the day  | 
|  Close_Price | Price at 11:59 AM of that day  | 
|  Volume | Volume is counted as the total number of shares that are actually traded (bought and sold) during the trading day  | 
|  Market_Cap | the total value of all a company's shares of stock  | 


### Tools 
#### Python Libraries: Selenium, BeautifulSoup, skLearn.


<a href="https://github.com/RaghadAlkhudhair/Bitcoin-Transaction-Confirmation-Time-Regression/blob/main/Bitcoin_Regression.ipynb" > Jupyter Notebook </a>
