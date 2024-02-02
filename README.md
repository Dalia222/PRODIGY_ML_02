# PRODIGY_ML_02 - K-means clustering for customers of a retail store.
## Data acquiring
```python
CustomerID	Gender	Age	Annual Income (k$)	Spending Score (1-100)
0	1	Male	19	15	39
1	2	Male	21	15	81
2	3	Female	20	16	6
3	4	Female	23	16	77
4	5	Female	31	17	40
```
## Data Analysis
```python
CustomerID	Age	Annual Income (k$)	Spending Score (1-100)
count	200.000000	200.000000	200.000000	200.000000
mean	100.500000	38.850000	60.560000	50.200000
std	57.879185	13.969007	26.264721	25.823522
min	1.000000	18.000000	15.000000	1.000000
25%	50.750000	28.750000	41.500000	34.750000
50%	100.500000	36.000000	61.500000	50.000000
75%	150.250000	49.000000	78.000000	73.000000
max	200.000000	70.000000	137.000000	99.000000
```
## Mapping and data Re-processing
```python
CustomerID	Gender	Age	Annual Income (k$)	Spending Score (1-100)
0	1	1	19	15	39
1	2	1	21	15	81
2	3	0	20	16	6
3	4	0	23	16	77
4	5	0	31	17	40
```
## finding wcss value (Within Clusters Sum of Squares) Using the elbow method
![Elbow method](https://i.postimg.cc/x86VXDkq/Elbow-Methodpng.png)

## Plotting the clustered data
![Clustered data](https://i.postimg.cc/fyzhWTR6/Clusters.png)
