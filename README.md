# go-mysql-elasticsearch_mine
forked from go-mysql-elasticsearch and   repaired  some problems

# 主要修改了以下内容:
1. 修复binlog 解析到trigger 相关内容时 同步 断开问题
2. 修复了同步decimal字段 且字段长度大于20 时出现截断问题
3. 修复了es 的http 响应415等响应码时，格式化错误问题
4. 添加了dryrun选项用户debug 输出 es 请求body 和binlog解析内容
