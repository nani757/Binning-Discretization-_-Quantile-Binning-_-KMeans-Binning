# Binning-Discretization-_-Quantile-Binning-_-KMeans-Binning
## credits: bit.ly/38qpuDB
## binning:Discretization  is the process  of transforming continuous variables into discrete variables by creating a set of contiguous intervals that span the range of the variable's values .discretization is also called  binningwe use binning to
i) To handle outliers
ii)To improve the value spread
![discretization](https://user-images.githubusercontent.com/68773015/165554364-8798b8c4-ad18-4273-9daf-5d6f74e03d16.png)
![types of discretization](https://user-images.githubusercontent.com/68773015/165554369-5ebf41d0-70ea-4024-b2d3-10e5267fe6ab.png)
## Quantile-Binning: Quantile binning aims to assign the same number of observations to each bin, if the number of observations is evenly divisible by the number of bins. As a result, each bin should have the same number of observations, provided that there are no tied values at the boundaries of the bins.
![equal fraequency     quantileBinning](https://user-images.githubusercontent.com/68773015/165554378-d6b1e76f-1aa6-43fb-b63d-e7a01091bdef.png)

## KMeans-Binning: Ckmeans allows to cluster numeric data (on one dimension) into groups with the least within-group sum-of-squared-deviations. We'll use simple-statistics' very fast implementation of this algorithm in Plot.binX's transform: # of thresholds.

