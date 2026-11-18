# 复利计算器



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







## 试一试



[打开完整工具](<https://toolpony.com/zh-hans/tools/compound-interest-calculator/>)







## 计算方法



实际年增长率为 (1+r/m)^m−1，连续复利为 exp(r)−1。定期投入按选定的期初或期末开始计息。



$$
A=P(1+r/m)^{mt},\qquad \mathrm{APY}=(1+r/m)^m-1
$$







## 计算模式



**未来余额**

- 本金
- 年利率 · %
- 年
- 计息频率
- 每期投入
- 投入频率 · 每年 / 每半年 / 每季度 / 每月 / 每月两次 / 每两周 / 每周 / 每日
- 期初投入
- 年通胀率 · %





**等效利率**

- 年利率 · %
- 原计息频率
- 目标计息频率

[文档站](https://docs.toolpony.com/zh-hans/guides/compound-interest-calculator/)
