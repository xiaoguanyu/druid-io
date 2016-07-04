---
---

## 入门指南
  * [概念](../design/)
  * [快速入门](../tutorials/quickstart.html)
  * [加载数据](../tutorials/ingestion.html)
    * [加载文件数据](../tutorials/tutorial-batch.html)
    * [加载流数据](../tutorials/tutorial-streams.html)
    * [加载Kafka数据](../tutorials/tutorial-kafka.html)
  * [集群模式](../tutorials/cluster.html)

## 数据接入
  * [数据格式](../ingestion/data-formats.html)
  * [数据模式](../ingestion/index.html)
  * [设计数据模式](../ingestion/schema-design.html)
  * [修改数据模式](../ingestion/schema-changes.html)
  * [文件数据批量接入](../ingestion/batch-ingestion.html)
  * [流数据接入](../ingestion/stream-ingestion.html)
    * [推送流数据](../ingestion/stream-push.html)
    * [拉取流数据](../ingestion/stream-pull.html)
  * [更新已存在数据](../ingestion/update-existing-data.html)
  * [常见疑问](../ingestion/faq.html)

## 数据查询
  * [概览](../querying/querying.html)
  * [Timeseries](../querying/timeseriesquery.html)
  * [TopN](../querying/topnquery.html)
  * [GroupBy](../querying/groupbyquery.html)
  * [时间范围](../querying/timeboundaryquery.html)
  * [Segment元数据](../querying/segmentmetadataquery.html)
  * [DataSource元数据](../querying/datasourcemetadataquery.html)
  * [Search](../querying/searchquery.html)
  * [Select](../querying/select-query.html)
  * 结构
    * [Datasources](../querying/datasource.html)
    * [Filters](../querying/filters.html)
    * [Aggregations](../querying/aggregations.html)
    * [Post Aggregations](../querying/post-aggregations.html)
    * [Granularities](../querying/granularities.html)
    * [DimensionSpecs](../querying/dimensionspecs.html)
    * [Context](../querying/query-context.html)
  * [多值维度](../querying/multi-value-dimensions.html)
  * [SQL](../querying/sql.html)
  * [Joins](../querying/joins.html)
  * [多租户](../querying/multitenancy.html)
  * [缓存](../querying/caching.html)

## 设计
  * [概览](../design/design.html)
  * 存储
    * [Segments](../design/segments.html)
  * 节点类型
    * [Historical](../design/historical.html)
    * [Broker](../design/broker.html)
    * [Coordinator](../design/coordinator.html)
    * [Indexing Service](../design/indexing-service.html)
    * [Realtime](../design/realtime.html)
  * 依赖
    * [Deep Storage](../dependencies/deep-storage.html)
    * [元数据存储](../dependencies/metadata-storage.html)
    * [ZooKeeper](../dependencies/zookeeper.html)

## 使用
  * [推荐做法](../operations/recommendations.html)
  * [指定扩展](../operations/including-extensions.html)
  * [数据保留](../operations/rule-configuration.html)
  * [数据指标监控](../operations/metrics.html)
  * [告警](../operations/alerts.html)
  * [集群升级](../operations/rolling-updates.html)
  * [hadoop版本兼容](../operations/other-hadoop.html)
  * [性能常见疑问](../operations/performance-faq.html)

## 配置
  * [通用配置](../configuration/index.html)
  * [Indexing Service](../configuration/indexing-service.html)
  * [Coordinator](../configuration/coordinator.html)
  * [Historical](../configuration/historical.html)
  * [Broker](../configuration/broker.html)
  * [Realtime](../configuration/realtime.html)
  * [日志配置](../configuration/logging.html)
  * [生产环境集群配置](../configuration/production-cluster.html)
  * [生产环境hadoop配置](../configuration/hadoop.html)
  * [生产环境zookeeper配置](../configuration/zookeeper.html)

## 开发
  * [概览](../development/overview.html)
  * [工具库](../development/libraries.html)  
  * [Druid扩展](../development/modules.html)
  * [可用的扩展](../development/extensions.html)
  * [源码编译](../development/build.html)
  * [版本控制](../development/versioning.html)
  * [技术整合](../development/integrating-druid-with-other-technologies.html)
  * 实验特性
    * [概览](../development/experimental.html)
    * [Approximate Histograms和Quantiles](../development/extensions-core/approximate-histograms.html)
    * [Datasketches](../development/extensions-core/datasketches-aggregators.html)       
    * [Geographic Queries](../development/geo.html)
    * [Router](../development/router.html)    

## 其它
  * [论文和探讨](../misc/papers-and-talks.html)
  * [感谢](/thanks.html)
