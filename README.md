# DolphinScheduler-Process-Clean
海豚调度平台历史工作流实例清除工具

例如，清除2024-01-01之前的所有历史实例，示例如下：

`python dolphin_clean_process.py 2024-01-01`

注：只能删除完成状态的工作流实例，否则接口会报错，非完成状态的工作流不可删除。token从海豚调度 → 安全中心 → 令牌管理获取
