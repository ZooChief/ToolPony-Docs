# 內部收益率計算器使用指南



根據不規則年度現金流，或到期金額和定期存取，計算年有效內部收益率。





## 示例



### 輸入



```
初始投入 55,000，之後流入 14,000、18,000、22,000、26,000
```



### 預期結果



```
內部收益率約 15.093%
```







## 試一試

[打開完整工具 · 內部收益率計算器](<https://toolpony.com/zh-hant/tools/irr-calculator/>)





## 計算方法



IRR 是使淨現值爲零的收益率。固定模式按選定的頻率與期初或期末計入現金流。可選擇期初模式是否在終點邊界再計入一筆存取。搜索收益率範圍爲 −99.9999% 至 10,000%。



$$
0=\sum_{i=0}^n\frac{F_i}{(1+r)^{t_i}}
$$







## 計算模式





### 不規則年度現金流



- 初始投入
- 以後各年現金流







### 固定存取與期末餘額



- 初始投入
- 完整年數
- 額外月數
- 期末餘額
- 單次存取金額
- 存取方向 · 取出 / 存入
- 每年次數 · 1 / 2 / 4 / 12 / 24 / 26 / 52
- 存取時點 · 期末 / 期初
- 期初模式包含終點存取







[ZooChief](<https://docs.toolpony.com/zh-hant/about/>) · [反饋結果問題](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fzh-hant%2Fguides%2Firr-calculator%2F>)

[文檔站](https://docs.toolpony.com/zh-hant/guides/irr-calculator/)
