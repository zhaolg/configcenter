# configcenter
分布式配置中心服务

> 主要实现为：使用ZK作为注册中心，提供admin 配置管理、审核、版本记录、回滚功能，提供客户端一键接入到服务端
##### 模块列表
* configcenter：core  --提供核心服务modle
* configcenter: server --服务端+admin 
* configcenter: client  -- 提供客户端快速接入
