Machine Learning
==========

## K-Means clustering

K-means clustering is very faster, it can handle up to 1M records in a very short time. Benchmark of different clustering methods can be find [here](http://hdbscan.readthedocs.io/en/latest/performance_and_scalability.html).

	| Interactive|	Get Coffee|	Over Lunch|	Overnight|
|---|---|---|---|---|
AffinityPropagation|	2000|	10000|	25000|	100000|
Spectral|	2000|	5000|	25000|	75000|
Agglomerative|	2000|	10000|	25000|	100000|
DeBaCl|	5000	25000|	75000|	250000|
ScipySingleLinkage|	25000|	50000|	100000|	250000|
Fastcluster|	50000|	100000|	500000|	1000000|
HDBSCAN|	100000|	500000|	1000000|	5000000|
DBSCAN|	75000|	250000|	1000000|	2500000|
SKLearn KMeans|	1000000000|	1000000000|	1000000000|	1000000000|

Given simple, well-separated data, k-means finds suitable clustering results. 
