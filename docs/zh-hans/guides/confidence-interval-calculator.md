# 置信区间计算器使用指南



由样本数据或汇总统计量计算均值的 z 或 t 置信区间，也可用 Wilson 方法估计比例区间。





## 示例



### 输入



```
样本 36，均值 56，标准差 8，置信水平 99%
```



### 预期结果



```
56 ± 3.434
```





<a id="case-study"></a>



## 用五次测量估计均值



1. 五次测量为 48、49、50、51、52，平均值为 50。采用样本标准差，自由度为 4，均值的 95% t 置信区间约为 48.04 至 51.96。这里假定观测相互独立，且总体近似正态。



[运行示例](<https://toolpony.com/zh-hans/tools/confidence-interval-calculator/#example-five-measurements>)





## 抽检 30 件，发现 0 件不合格



独立抽检 30 件，发现 0 件不合格。按 Wilson 方法估计总体不合格率，95% 区间为 0% 至约 11.35%。如果扩大抽样且仍未发现不合格，区间会变窄。



[运行示例](<https://toolpony.com/zh-hans/tools/confidence-interval-calculator/#example-no-failures>)







## 试一试

[打开完整工具 · 置信区间计算器](<https://toolpony.com/zh-hans/tools/confidence-interval-calculator/>)





## 计算方法



均值区间的误差幅度等于临界值 × 标准差 / √n。已知总体标准差时取 z，使用样本标准差时取自由度为 n − 1 的 t。Wilson 区间由二项试验中的成功次数和总次数估计比例。



$$
\bar{x}\pm z_{1-\alpha/2}\frac{s}{\sqrt n}
$$



$$
\frac{\widehat{p}+z^2/(2n)\pm z\sqrt{\widehat{p}(1-\widehat{p})/n+z^2/(4n^2)}}{1+z^2/n}
$$







## 计算模式





### 均值区间



- 数据来源 · 已知总体 σ / 样本 s / 样本数据
- 样本量
- 均值
- 标准差
- 样本数值
- 置信水平 · %







### Wilson 比例区间



- 样本量
- 成功次数
- 置信水平 · %







**方法来源** [NIST · Confidence limits for the mean](<https://www.itl.nist.gov/div898/handbook/eda/section3/eda352.htm>) · [NIST · Confidence limits for a proportion](<https://www.itl.nist.gov/div898/handbook/prc/section2/prc241.htm>)



[ZooChief](<https://docs.toolpony.com/zh-hans/about/>) · [反馈结果问题](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fzh-hans%2Fguides%2Fconfidence-interval-calculator%2F>)

[文档站](https://docs.toolpony.com/zh-hans/guides/confidence-interval-calculator/)
