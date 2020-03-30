# sf-crime-data

1. How did changing values on the SparkSession property parameters affect the throughput and latency of the data?
The processedRowsPerSecond were affected by different property parameters.

2. What were the 2-3 most efficient SparkSession property key/value pairs? Through testing multiple variations on values, how can you tell these were the most optimal?

The processedRowsPerSecond were affected by changing maxRatePerPartition and maxOffsetsPerTrigger,