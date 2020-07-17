# sharding-jdbc-demo
支持实时改变分表规则动态分表

redis存储分表信息，根据分表规则实时获取刷新，推送至actual-data-nodes

tips：
后续考虑增加分页查询结果归并逻辑  如es缓存分库分表策略选取的id
