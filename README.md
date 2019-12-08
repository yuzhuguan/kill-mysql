# kill-mysql

## 数据表的编码格式

'''
show create table <表名>;
修改数据库的编码格式

mysql>alter database <数据库名> character set utf8mb4;
修改数据表格编码格式

alter table <表名> character set utf8mb4;
修改字段编码格式

alter table <表名> change <字段名> <字段名> <类型> character set utf8mb4;

'''
