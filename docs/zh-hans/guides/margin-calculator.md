# 利润率与加价率使用指南



比较毛利率和加价率，算出最低售价或最高采购成本，用相邻一分的报价核对目标。





## 示例



### 输入



```
成本 60，售价 100
```



### 预期结果



```
毛利率 40%，加价率约 66.67%
```





<a id="case-study"></a>



## 给出能达到 34% 毛利率的报价



1. 成本为 10.00 时，理论售价是 10 ÷ 0.66，约 15.1515。定价 15.15 会低于 34% 的目标；精确到分的最低售价为 15.16。用此售价核算，可得毛利 5.16，实际毛利率约 34.04%。





## 按分报价达到 12% 加价率



成本 17.20，按成本加价 12%，未取整售价是 19.264。报价 19.26 时实际加价率约 11.98%，报价 19.27 才达到约 12.03%。若目标是占售价 12% 的毛利率，最低售价则是 19.55。



[运行示例](<https://toolpony.com/zh-hans/tools/margin-calculator/#example-markup-quote>)







## 倒推采购成本上限



售价 20.01，目标毛利率 30%，精确成本上限是 14.007。按分结算，付 14.00 能达到目标，付 14.01 时毛利率就低于 30%。



[运行示例](<https://toolpony.com/zh-hans/tools/margin-calculator/#example-cost-ceiling>)







## 试一试

[打开完整工具 · 利润率与加价率](<https://toolpony.com/zh-hans/tools/margin-calculator/#example-cent-price>)





## 计算方法



毛利 = 售价 − 成本。毛利率的分母是售价，加价率的分母是成本。按分报价时，最低售价向上取整，最高采购成本向下取整。







## 计算模式





### 成本与售价



- 成本
- 售价







### 按目标毛利率定价



- 成本
- 目标毛利率 · %







### 按加价率定价



- 成本
- 目标加价率 · %







### 由售价和毛利率求成本



- 售价
- 目标毛利率 · %







**方法来源** [BDC · Gross margin](<https://www.bdc.ca/en/articles-tools/entrepreneur-toolkit/templates-business-guides/glossary/gross-margin>)



[ZooChief](<https://docs.toolpony.com/zh-hans/about/>) · [反馈结果问题](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fzh-hans%2Fguides%2Fmargin-calculator%2F>)

[文档站](https://docs.toolpony.com/zh-hans/guides/margin-calculator/)
