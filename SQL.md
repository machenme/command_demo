| 操作对象 | 创建          | 删除          | 修改         |
|----------|---------------|---------------|--------------|
| 模式     | CREATE SCHEMA | DROP SCHEMA   |              |
| 表       | CREATE TABLE  | DROP TABLE    | ALTER TABLE  |
| 视图     | CREATE VIEW   | DROP VIEW     |              |
| 索引     | CREATE INDEX  | DROP INDEX    | ALTER INDEX  |

`DISTINCT` 独一无二
```sql
SELECT DISTINCT <col> FROM <table>;
```
`WHERE` 条件语句 `> < = != >= <=`
```sql
SELECT <col> FROM <table> WHERE <condition>
```


`LIKE` `A%` 以A开头， `%z`以z结尾
```sql
SELECT * FROM shows
WHERE genre LIKE '%com%'；
```

Between 在什么之间，和`python`一样左闭右开，如下所示，选择所有ABD的

```sql
SELECT *
FROM shows
WHERE name
BETWEEN 'A' AND 'D';
```

ORDER BY 以什么进行排序 默认从小到大 如果结尾加上DESC代表从大到小


```sql
```
```sql
```
```sql
```
```sql
```
```sql
```
```sql
```
```sql
```
```sql
```
```sql
```
```sql
```
```sql
```
```sql
```
```sql
```
```sql
```
```sql
```
```sql
```
```sql
```
```sql
```
```sql
```
```sql
```
```sql
```
```sql
```
