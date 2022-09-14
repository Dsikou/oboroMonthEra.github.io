# mysqlCRUD

- **增加**
  - insert into 表名 (字段1,字段2 ...) values (值1,值2 ...)；
- **删除**
  - delete from 表名 where 筛选条件；
- **修改**
  - update 表名 set 字段=值 where 筛选条件；
- **查询**
  - select 字段名 from 表名 where 筛选条件；
***
- **sql执行顺序**
1. from表1别名
2. 连接类型join表2
3. on连接条件
4. where筛选
5. groupby分组列表
6. having筛选
7. select查询列表
8. orderby排序列表
9. limit起始条目索引,条目数
