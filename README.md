# redis
## redis 命令
### String 类型的常见命令
- `SET`：添加或者修改已经存在的一个 String 类型的键值对
- `GET`：根据 key 获取 String 类型的 value
- `MSET`：批量添加多个 String 类型键值对
- `INCR`：根据多个 key 获取多个 String 类型的 value
- `INCRBY`：让一个整形的 key 自增并指定步长，例如：incrby num 2 让 num 值自增2
- `INCRBYFLOAT`：让一个浮点类型的数字自增并指定步长
- `SETNX`：添加一个 String 类型的键值对，前提是这个 key 不存在，否则不执行
- `SETEX`：添加一个 String 类型的键值对，并指定有效期

> 小提示：Redis的key允许有多个单词形成层级结构，多个单词用:隔开格式如：
      项目名:业务名:类型:ID

### Hash 类型的常见命令
- `HSET` key field value：添加或修改 hash 类型的 key 的 field 值
- `HGET` key field：获取一个 hash 类型的 key 的 field 的值
- `HMSET`：批量添加多个 hash 类型的 key 的 field 的值
- `HMGET`：批量获取多个 hash 类型的 key 的 field 的值
- `HGETALL`：获取一个 hash 类型的 key 中的所有 field 
- `HKEYS`：获取一个 hash 类型的 key 中的所有 field
- `HVALS`：获取一个 hash 类型的 key 中的所有 value
- `HINCRBY`：让一个 hash 类型 key 的字段自增并指定步长
- `HSETNX`：添加一个 hash 类型的 key 的 field 值，前提是这个 field 不存在，否则不执行
### List 类型的常见命令
- `LPUSH key element ...`：向列表左侧插入一个或多个元素
- `LPOP key`：移除并返回列表
- ``：1
- ``：向
- ``：向
- ``：向
