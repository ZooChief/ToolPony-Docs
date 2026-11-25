# 复利计算器使用指南



估算含定期投入和通胀的复利余额，或在不同计息频率间换算。





## 示例



### 输入



```
10,000 按 5% 年复利，10 年
```



### 预期结果



```
16,288.95
```





<a id="case-study"></a>



## 比较 30 个月的定期投入



1. 起始本金 10,000，每月投入 100，持续两年六个月。按名义年利率 6%、每月计息，月末投入的期末余额为 14,842.00，其中累计投入 13,000。改为月初投入可得 14,858.14。若年通胀率为 3%，前一种余额折合今天的购买力为 13,784.77。





## 试一试

[打开完整工具 · 复利计算器](<https://toolpony.com/zh-hans/tools/compound-interest-calculator/#example-30-months>)





## 计算方法



实际年增长率为 (1+r/m)^m−1，连续复利为 exp(r)−1。定期投入按选定的期初或期末开始计息。



$$
A=P(1+r/m)^{mt},\qquad \mathrm{APY}=(1+r/m)^m-1
$$







## 计算模式





### 未来余额



- 本金
- 年利率 · %
- 年
- 月
- 计息频率
- 每期投入
- 投入频率 · 每年 / 每半年 / 每季度 / 每月 / 每月两次 / 每两周 / 每周 / 每日
- 期初投入
- 年通胀率 · %







### 等效利率



- 年利率 · %
- 原计息频率
- 目标计息频率







**方法来源** [Investor.gov · Compound Interest](<https://www.investor.gov/financial-tools-calculators/calculators/compound-interest-calculator>)



[ZooChief](<https://docs.toolpony.com/zh-hans/about/>) · [反馈结果问题](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fzh-hans%2Fguides%2Fcompound-interest-calculator%2F>)

[文档站](https://docs.toolpony.com/zh-hans/guides/compound-interest-calculator/)
