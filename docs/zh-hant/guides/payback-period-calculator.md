# 投資回收期計算器



用增長型或不規則年度現金流計算普通回收期和折現回收期。





## 示例



### 輸入



```
初始投入 17,500，首期流入 4,700，年增 8%，折現率 6%
```



### 預期結果



```
回收期約 3.379 年，折現回收期約 3.841 年
```







## 試一試

[打開完整工具 · 投資回收期計算器](<https://toolpony.com/zh-hant/tools/payback-period-calculator/>)





## 計算方法



從初始支出起累計現金流。在首次跨越零的年份線性插值。第 k 年現金流除以 (1+r)^k 得到折現值。固定現金流的折現回收期使用反向年金公式。



$$
C_k=\sum_{i=0}^{k}F_i,\qquad F_i^{\mathrm{PV}}=\frac{F_i}{(1+r)^i}
$$







## 計算模式



**固定或增長現金流**

- 初始投入
- 首年現金流
- 年增減率 · %
- 年數
- 年折現率 · %





**不規則年度現金流**

- 初始投入
- 以後各年現金流
- 年折現率 · %







[ZooChief](<https://docs.toolpony.com/zh-hant/about/>) · [反饋結果問題](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fzh-hant%2Fguides%2Fpayback-period-calculator%2F>)

[文檔站](https://docs.toolpony.com/zh-hant/guides/payback-period-calculator/)
