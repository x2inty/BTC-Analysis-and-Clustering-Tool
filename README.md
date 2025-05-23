BTC-Analysis-and-Clustering-Tool

Tabs of Version 6

RawData
Raw candlestick data (Open, High, Low, Close, Volume, DateTime, Cluster, etc.) for each 15-minute interval.

GlobalStats
Global statistics on price changes (Delta): mean, standard deviation, skewness, kurtosis, normality test, autocorrelation, Sharpe ratio,...

HourlyStats
Statistics grouped by hour of the day, including means, standard deviations, maxima/minima of Delta and volatility, as well as an average risk score.

ConditionalStats
Conditional counts on extreme movements: number of strong moves in delta, volatility, or combined (above the 90th percentile).

Clustering 
Summary of clusters identified by KMeans on Delta, volatility, and volume, with means and standard deviations per cluster.

TopOscillations
The top 100 strongest oscillations (by absolute delta) with their metrics, sorted by intensity.

TopOscByCluster
Statistical summary of top oscillations by cluster: mean, standard deviation, count, and risk score.

ClusterHourlyPct
Percentage distribution of clusters by hour of the day (the share each cluster represents at each hour).

TransitionMatrix
Matrix of transition probabilities between clusters from one candle to the next (study of cluster dynamics).

ClusterTimeline
3-day rolling average of the number of candles per cluster per day (visualization of cluster evolution over time).

DayClusterSummary
Daily statistics grouped by day: means and standard deviations of Delta, volatility, volume, and identification of the dominant cluster per day.
