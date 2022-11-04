# redis
## redis 命令
### String 类型的常见命令
- SET：添加或者修改已经存在的一个 String 类型的键值对
- GET：根据 key 获取 String 类型的 value
- MSET：批量添加多个 String 类型键值对
- INCR：根据多个 key 获取多个 String 类型的 value
- INCRBY：让一个整形的 key 自增并指定步长，例如：incrby num 2 让 num 值自增2
- INCRBYFLOAT：让一个浮点类型的数字自增并指定步长
- SETNX：添加一个 String 类型的键值对，前提是这个 key 不存在，否则不执行
- SETEX：添加一个 String 类型的键值对，并指定有效期
