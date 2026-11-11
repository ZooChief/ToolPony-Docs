# CSV 對賬



粘貼或導入新舊兩張表。首行保留表頭，再選擇分隔符和主鍵列。 執行對賬並篩選變更。CSV 可用表格軟件打開，JSON 保留原始文本和完整報告。





## 開始使用



1. 粘貼或導入新舊兩張表。首行保留表頭，再選擇分隔符和主鍵列。
2. 執行對賬並篩選變更。CSV 可用表格軟件打開，JSON 保留原始文本和完整報告。







## 示例



### 輸入



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



### 預期結果



```
新增 1 · 缺失 1 · 變更 1
```







## 試一試



[打開完整工具](<https://toolpony.com/zh-hant/tools/csv-compare/>)







## 適用範圍



每張表最多 1 MiB UTF-8 文本、5,000 行數據和 80 列。按原文匹配並保留前導零，重複鍵與空鍵單列。記錄編號從表頭開始。

[文檔站](https://docs.toolpony.com/zh-hant/guides/csv-compare/)
