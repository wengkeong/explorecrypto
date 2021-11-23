# explorecrypto
This is a submission for my course assignment where we can choose a topic to work on and I thought it makes a lot of sense to take this opportunity to learn more about crypto assets

## 1.	PROJECT SUMMARY
### 1.1	BUSINESS BACKGROUND
Bitcoin has been around for a while and following it, many similar cryptocurrencies have come on to the market. As at this point of writing, there are 7,557 cryptocurrencies (https://www.statista.com/statistics/863917/number-crypto-coins-tokens/) and this is a huge number. Built on the blockchain technology, there are many use cases on the commercial side of things, quality crypto assets will be a key element of it. Hence it is important to understand more about the landscape as well as the whole eco-system on it.

### 1.2	OBJECTIVES (LONG-TERM AND SHORT-TERM)
Short-Term goal: 
Understand crypto assets, making sense of the data gathered from api like what is out there in the market, its eco-system, key trends and technology

Long-Term goal: 
Validating these data from other sources, get more in depth into crypto assets of interest and making use of API to get updated market intelligence if possible and using this information to select quality crypto assets for investment


## 2.	DATA SOURCE
### 2.1	API Platform
https://min-api.cryptocompare.com/ is the api platform of choice 

### 2.2	APIs
The apis are available under Documentation page at https://min-api.cryptocompare.com/documentation. There is a need to make sense of the apis and to choose suitable apis to build a story upon and to perform EDAs on.

### 2.3	List of APIs chosen
General Info
-	All the Coins
o	Returns all the coins that CryptoCompare has added to the website. This is not the full list of coins we have in the system, it is just the list of coins we have done some research on.

Top Lists
-	Toplist by 24H Volume Full Data:
o	Get a number of top coins by their total volume across all markets in the last 24 hours. Default value is first page (0) and the top 10 coins.
-	Toplist by 24H Top Tier Volume Full Data
o	Get a number of top coins by their total top tier volume based on the top 20 markets in the last 24 hours. Default value is first page (0) and the top 10 coins.

Trading Signals
-	Trading Signals Latest
o	Powered by IntoTheBlock, an intelligence company that leverages machine learning and advanced statistics to extract intelligent signals for crypto-assets.

Social Data
-	Historical Day Social Stats Data
o	You can only use this endpoint with a valid api_key. Returns daily social stats data for the coin requested

News
-	Latest News Articles
o	Returns news articles from the providers that CryptoCompare has integrated with.
-	List News Feeds and Categories
o	Returns all the news feeds (providers) that CryptoCompare has integrated with and the full list of categories

