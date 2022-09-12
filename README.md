# IMF Project - Exploring Relationship Between CPI and Global Commodity Prices (PCPS)
Analyzing public data available at https://data.imf.org/ to  explore relationship between Consumer Price Index (CPI) and Global Commodity Prices (PCPS)

## Consumer Price Index (CPI):
Consumer Price Indexes (CPIs) are index numbers that are index numbers that measure the changes in the prices of goods and services purchased or otherwise acquired by households for direct use or consumption [link](https://drive.google.com/file/d/1tOwkrb57DNLYH3dAs1j8yZwEns43h1sI/view?usp=sharing). 

__Source of data:__ The data has been collected from external data source.
Owner/collector/trustworthiness of data: The data has been collected by IMF (International Monetary Fund) and . Organization for Economic Cooperation and Development (OECD). The dataset is open source and available at: https://data.imf.org/. Therefore, the data is trustworthy. 

__Data collection method:__ The data has been collected manually through surveys conducted by the government of each country and then reported to IMF and OECD. IMF also verifies the data to ensure reliability.

__Contents of data:__ The dataset includes country wise monthly Consumer Price Index (CPI) data from 1990 to 2022, for overall and 12 subgroups of consumption expenditure. It also includes actual weights, weight percentage and percentage change from previous period for each subgroup. 
Limitations of data: A lot of data is missing from this data set. As IMF depends of independent countries to report their data, the data might be vulnerable to misrepresentation by the reporting countries.

__Relevance of data:__ The data in the data set is relevant for this project as it has country wise monthly consumer expenditure data for different goods and services from 1990-2022.

## Primary Commodity Pricing System (PCPS): 
Average monthly global price indexes and actual prices for fuel and non-fuel commodities [link](https://drive.google.com/file/d/14xtJ7CKZvujt8TCFOJE0yginG_N1BPsb/view?usp=sharing).

__Source of data:__ The data has been collected from external data source.

__Owner/collector/trustworthiness of data:__ The data has been collected by IMF (International Monetary Fund). The dataset is open source and available at: https://data.imf.org/. Therefore, the data is trustworthy. 

__Data collection method:__ The benchmark prices for commodities are determined by the largest markets of a given commodity.
Contents of data: Average monthly global price indexes and actual prices for fuel and non-fuel commodities from 1992-2022.

__Limitations of data:__ The price indexes are estimates determined based on the largest markets of a given commodity. Hence, the actual market prices might differ from country to country

__Relevance of data:__ The data is relevant to the project as it will help me determine correlation between global commodity prices and Consumer Price Indexes.

### Reason for choosing these datasets:
I chose these datasets for the following reasons:
i)	Reliable source: the source of the data is IMF which is one of the most reliable sources of data
ii)	Timeliness: This dataset contains recent data up to second quarter of 2022.
iii)	Detailed data: We have monthly data for more than 100 countries since late 1990s

## Tools/Skills/Procedures
Python and Tableau
Data wrangling and data merging
Deriving new variables
Grouping data and aggregating data
Correlation matrix
Supervised Machine learning: Linear Regression
Unsupervised machine learning: K-means clustering

## Analysis Flow:
1) Sourcing the datasets then cleaning and merging relevant variables
2) Exploring relationships with correlation matrix, pairplots and scatterplots
3) Identifying outliers and exploring relationships excluding them
4) Testing hypothesis with supervised machine learning
5) Finding clusters in the data using k-means clustering and re-running linear regression model cluster wise

## Findings: 
Despite having negative correlation during the years: 2010-2013, Overall CPI and Price of Agricultural Raw Materials have had a positive correlation during the recent years (2014-2021).
Although there is a positive correlation between the Overall CPI and Price of Agricultural Raw materials, the relationship is very weak. Therefore, the Price of Agricultural Raw Materials cannot be used to predict the future changes in Overall CPI variable.

## [Final tableau story board](https://public.tableau.com/views/IMFProject-ExploringrelationshipsbetweenCPIandGlobalCommodityPrices/Story?:language=en-US&:display_count=n&:origin=viz_share_link)
