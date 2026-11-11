# CSV 对账



粘贴或导入新旧两张表。首行保留表头，再选择分隔符和主键列。 执行对账并筛选变更。CSV 可用表格软件打开，JSON 保留原始文本和完整报告。





## 开始使用



1. 粘贴或导入新旧两张表。首行保留表头，再选择分隔符和主键列。
2. 执行对账并筛选变更。CSV 可用表格软件打开，JSON 保留原始文本和完整报告。







## 示例



### 输入



```
ID,Name,Qty
001,Oak,2
002,Pine,1
004,Ash,3

Qty,ID,Name
4,001,Oak
1,003,Fir
3,004,Ash
```



### 预期结果



```
新增 1 · 缺失 1 · 变更 1
```







## 试一试



[打开完整工具](<https://toolpony.com/zh-hans/tools/csv-compare/>)







## 适用范围



每张表最多 1 MiB UTF-8 文本、5,000 行数据和 80 列。按原文匹配并保留前导零，重复键与空键单列。记录编号从表头开始。

[文档站](https://docs.toolpony.com/zh-hans/guides/csv-compare/)
