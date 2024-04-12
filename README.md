# Financial Conditions Index Replication in Python
Repo for Financial Conditions index replicatio

Data Series Used:

1. Dow Jones Industrial Average
2. High Yield Credit Rates
3. US Dollar Relative Strength Index
4. Zillow Housing Index
5. 10 Year Treasury Rate
6. Fed Funds Rate
7. Mortgage Rate

These series are adjusted based on the technical index in the analysis 
"For rates and yields, ΔXjt−i

is calculated as the difference between the average levels of end-of-day values recorded over two subsequent three-month periods. For example, the change in the federal funds rate measured at the end of May 2023 is the difference between the average daily rates in the three-month period between March 1, 2023, and May 31, 2023, and the average daily rates in the three-month period between December 1, 2022, and February 28, 2023. The difference is in levels and therefore expressed in percentage points.

For stock and house price indexes, changes are computed as 100 times three-month differences in log levels and, as such, are expressed in percent rates. For example, the change in the Dow Jones total stock market index measured at the end of May 2023 is 100 times the log difference between the levels of the index on May 31, 2023, and February 28, 2023.

For the dollar index, changes are computed as 100 times three-month differences in log average levels. As such, changes are expressed in percent rates. Average levels are calculated on daily data over three-month periods. For example, the change in the nominal dollar measured at the end of May 2023 is 100 times the log difference between the average daily dollar index in the three-month period between March 1, 2023, and May 31, 2023, and the average daily rate in the three-month period between December 1, 2022, and February 28, 2023

Percent changes in the financial variables of interest are weighted using parameters that reflect the estimated response of GDP to unanticipated permanent changes in those same variables. We sign the weights so that changes in financial variables that tighten financial conditions within the models contribute positively to the index."


After that the FCI is calculated by using the weights outlined in the paper to adjust the values for the appropriate lookback window. 
![image](https://github.com/C00ldudeNoonan/financial-conditions-index/assets/48368867/d38ba623-9151-4a20-b404-ec6f3d984073)


# Charts

![Untitled](https://github.com/C00ldudeNoonan/financial-conditions-index/assets/48368867/e80a3220-7580-4eeb-883d-9292c1baec7c)

![Untitled-1](https://github.com/C00ldudeNoonan/financial-conditions-index/assets/48368867/5c14ec45-1a38-4997-b601-6fe911245bed)


Links:

Original Paper Link: https://www.federalreserve.gov/econres/notes/feds-notes/a-new-index-to-measure-us-financial-conditions-20230630.html
Sample Google Sheet: https://docs.google.com/spreadsheets/d/1k8qnFgKx3xk4CCp55m1zPrZaiulSBHRpE9_BlfeCy2M/edit#gid=0
