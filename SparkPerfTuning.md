1. 删除不必要的cache标记
2. 大rdd join 小rdd 转成  map  
   1. [vendor schedule]
3. HashPartitioner -> SKUPartitioner
4. Partition 数量 20(executors: 10) -> 64,128,256 -> 1024 (executors: 20)
5. 把实体对象加入到KryoRegistrator                                   
   1.   [Inventory, TipRoq, Openorder, ForecastSales, SkuLevelInfo]
6. 关键的可重复利用RDD: MEMORY_ONLY_2 
   1.  [Fresh DemandDataCalculator, demandRDD]
7. groupByKey -> reduceByKey
   1. RebateOpenOrderJoiner(L:28)
