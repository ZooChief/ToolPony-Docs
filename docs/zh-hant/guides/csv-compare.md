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





<a id="case-study"></a>



## 兩份庫存表的列順序變了，怎樣覈對數量



1. 載入庫存示例，選擇 ID 作鍵。舊錶的列順序是 ID、Name、Qty，新表則把 Qty 放在第一列。比較這兩份導出數據。
2. 商品 001（Oak）的數量從 2 變爲 4，002 被移除，003 是新增，004 保持原樣。即使列順序不同，結果仍應爲變更 1 條、移除 1 條、新增 1 條。
3. 在新表裏只把 001 改成 1，再次比較。這次應爲新增 2 條、移除 2 條、變更 0 條。重新導出時保留前導零，就能再按同一商品覈對數量。





## 試一試

[打開完整工具 · CSV 對賬](<https://toolpony.com/zh-hant/tools/csv-compare/>)





## 適用範圍



每張表最多 1 MiB UTF-8 文本、5,000 行數據和 80 列。按原文匹配並保留前導零，重複鍵與空鍵單列。記錄編號從表頭開始。



比對庫存時可以用穩定的 SKU 作鍵。如果舊錶寫作 0012、新表寫作 12，會得到一條刪除和一條新增。要把數量差異識別爲同一商品的變更，請在兩次導出時都保留前導零。





**方法來源** [IETF · RFC 4180 (CSV)](<https://www.rfc-editor.org/rfc/rfc4180>)



[ZooChief](<https://docs.toolpony.com/zh-hant/about/>) · [反饋結果問題](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fzh-hant%2Fguides%2Fcsv-compare%2F>)

[文檔站](https://docs.toolpony.com/zh-hant/guides/csv-compare/)
