# 折舊計算器



生成直線法、餘額遞減法或年數總和法的年度折舊表。





## 示例



### 輸入



```
原值 17,500，殘值 2,500，6 年，直線法
```



### 預期結果



```
每年折舊 2,500
```







## 試一試

[打開完整工具 · 折舊計算器](<https://toolpony.com/zh-hant/tools/depreciation-calculator/>)





## 計算方法



直線法將可折舊金額按使用年限均分。餘額遞減法按係數除以年限乘以期初賬面價值，達到殘值即停止。年數總和法按剩餘年限權重分配，每年進行金額舍入。



$$
D_{\mathrm{SL}}=\frac{C-S}{n},\quad D_{k,\mathrm{SYD}}=(C-S)\frac{n-k+1}{n(n+1)/2}
$$







## 計算模式



**直線法**

- 資產原值
- 殘值
- 使用年限
- 舍入精度 · 兩位小數 / 取整數





**餘額遞減法**

- 資產原值
- 殘值
- 使用年限
- 折舊係數
- 舍入精度 · 兩位小數 / 取整數





**年數總和法**

- 資產原值
- 殘值
- 使用年限
- 舍入精度 · 兩位小數 / 取整數







[ZooChief](<https://docs.toolpony.com/zh-hant/about/>) · [反饋結果問題](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fzh-hant%2Fguides%2Fdepreciation-calculator%2F>)

[文檔站](https://docs.toolpony.com/zh-hant/guides/depreciation-calculator/)
