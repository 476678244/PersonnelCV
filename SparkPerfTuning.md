- 删除不必要的cache标记
- 大rdd join 小rdd 转成  map  
  
   > [vendor schedule]
- HashPartitioner -> SKUPartitioner
- Partition 数量 20(executors: 10) -> 64,128,256 -> 1024 (executors: 20)
- 把实体对象加入到KryoRegistrator                                   
   
   > [Inventory, TipRoq, Openorder, ForecastSales, SkuLevelInfo]
- 关键的可重复利用RDD: MEMORY_ONLY_2 
   
   >  [Fresh DemandDataCalculator, demandRDD L:465]
- groupByKey -> reduceByKey
   
   > RebateOpenOrderJoiner(L:28)
- Default(shuffle 0.2, storage 0.6) -> Customized(shuffle 0.3, storage 0.5)
   
   > DefaultSparkConfigurator (L:27)
