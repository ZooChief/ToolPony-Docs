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





<a id="case-study"></a>



## 两份库存表的列顺序变了，怎样核对数量



1. 载入库存示例，选择 ID 作键。旧表的列顺序是 ID、Name、Qty，新表则把 Qty 放在第一列。比较这两份导出数据。
2. 商品 001（Oak）的数量从 2 变为 4，002 被移除，003 是新增，004 保持原样。即使列顺序不同，结果仍应为变更 1 条、移除 1 条、新增 1 条。
3. 在新表里只把 001 改成 1，再次比较。这次应为新增 2 条、移除 2 条、变更 0 条。重新导出时保留前导零，就能再按同一商品核对数量。





## 试一试

[打开完整工具 · CSV 对账](<https://toolpony.com/zh-hans/tools/csv-compare/>)





## 适用范围



每张表最多 1 MiB UTF-8 文本、5,000 行数据和 80 列。按原文匹配并保留前导零，重复键与空键单列。记录编号从表头开始。



比对库存时可以用稳定的 SKU 作键。如果旧表写作 0012、新表写作 12，会得到一条删除和一条新增。要把数量差异识别为同一商品的变更，请在两次导出时都保留前导零。





**方法来源** [IETF · RFC 4180 (CSV)](<https://www.rfc-editor.org/rfc/rfc4180>)



[ZooChief](<https://docs.toolpony.com/zh-hans/about/>) · [反馈结果问题](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fzh-hans%2Fguides%2Fcsv-compare%2F>)

[文档站](https://docs.toolpony.com/zh-hans/guides/csv-compare/)
