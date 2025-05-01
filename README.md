# Customer-Segmentation-for-an-E-Commerce-Platform-Using-K-Means-Clustering
```Python
Fact_['UnitPrice']=Fact_['UnitPrice'].replace('Unknown', 0)
Fact_['UnitPrice']=Fact_['UnitPrice'].astype(float).round(0)
Fact_['TotalAmount']=Fact_['UnitPrice']*Fact_['Quantity']
Fact_['TransactionDate']= Fact_['TransactionDate'].replace("InvalidDate",np.nan)
Fact_.dropna(subset='TransactionDate',inplace=True)
Fact_['TransactionDate']=pd.to_datetime(Fact_['TransactionDate'])
Fact_['TransactionDate']=Fact_['TransactionDate'].dt.date

Fact_.head(5)
```Output
TransactionID	CustomerID	TransactionDate	ProductID	Quantity	UnitPrice	TotalAmount	Rating	PaymentMethod
0	1	1276	2023-01-10	200	3	310.0	930.0	4.0	12345
1	2	1471	2023-08-21	204	4	559.0	2236.0	4.0	PayPal
2	3	1376	2023-07-14	262	7	70.0	490.0	1.0	Credit Card
3	4	1377	2023-01-12	298	6	132.0	792.0	2.0	PayPal
4	5	1388	2023-06-26	235	11	0.0	0.0	NaN	12345
```
