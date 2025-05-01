# Customer-Segmentation-for-an-E-Commerce-Platform-Using-K-Means-Clustering
```Python
Fact_['UnitPrice']=Fact_['UnitPrice'].replace('Unknown', 0)
Fact_['UnitPrice']=Fact_['UnitPrice'].astype(float).round(0)
Fact_['TotalAmount']=Fact_['UnitPrice']*Fact_['Quantity']
Fact_['TransactionDate']= Fact_['TransactionDate'].replace("InvalidDate",np.nan)
Fact_.dropna(subset='TransactionDate',inplace=True)
Fact_['TransactionDate']=pd.to_datetime(Fact_['TransactionDate'])
Fact_['TransactionDate']=Fact_['TransactionDate'].dt.date

Fact_.head(5)```
