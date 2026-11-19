# 投资回收期计算器



用增长型或不规则年度现金流计算普通回收期和折现回收期。





## 示例



### 输入



```
初始投入 17,500，首期流入 4,700，年增 8%，折现率 6%
```



### 预期结果



```
回收期约 3.379 年，折现回收期约 3.841 年
```







## 试一试

[打开完整工具 · 投资回收期计算器](<https://toolpony.com/zh-hans/tools/payback-period-calculator/>)





## 计算方法



从初始支出起累计现金流。在首次跨越零的年份线性插值。第 k 年现金流除以 (1+r)^k 得到折现值。固定现金流的折现回收期使用反向年金公式。



$$
C_k=\sum_{i=0}^{k}F_i,\qquad F_i^{\mathrm{PV}}=\frac{F_i}{(1+r)^i}
$$







## 计算模式



**固定或增长现金流**

- 初始投入
- 首年现金流
- 年增减率 · %
- 年数
- 年折现率 · %





**不规则年度现金流**

- 初始投入
- 以后各年现金流
- 年折现率 · %







[ZooChief](<https://docs.toolpony.com/zh-hans/about/>) · [反馈结果问题](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fzh-hans%2Fguides%2Fpayback-period-calculator%2F>)

[文档站](https://docs.toolpony.com/zh-hans/guides/payback-period-calculator/)
