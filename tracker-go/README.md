



### **🔌 埋点接口结构**





- POST /track 请求示例、字段说明、标准响应格式
- 自动获取 IP、UA、Referer 等信息







### **🚦 性能与限流策略**





- 基于 Redis 的 IP 限流（如每分钟最多 60 次）
- 字段长度与格式验证，支持 CORS







### **📦 Redis 异步写入方案**





- 埋点数据入 Redis List（按 site_id 区分）
- 后台 goroutine 消费并批量写入 MySQL
- 批次大小控制 + 写入间隔优化性能





------

 