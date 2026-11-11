# 置信区间计算器



估算均值的正态置信区间，或用 Wilson 方法计算比例区间。





## 开始使用



1. 按示例填写数值，或输入你自己的测量值。
2. 计算后可复制结果或下载明细。







## 示例



### 输入



```
样本 36，均值 56，标准差 8，置信水平 99%
```



### 预期结果



```
56 ± 3.434
```







## 试一试



[打开完整工具](<https://toolpony.com/zh-hans/tools/confidence-interval-calculator/>)







## 使用提示



计算在浏览器内完成。无单位标记的字段请使用一致单位。







## 计算方法



正态误差幅度为 z 乘以标准误 s/√n。Wilson 区间对比例的中心与宽度进行调整，并保持在 \[0,1\] 内。



$$
\bar{x}\pm z_{1-\alpha/2}\frac{s}{\sqrt n}
$$



$$
\frac{\widehat{p}+z^2/(2n)\pm z\sqrt{\widehat{p}(1-\widehat{p})/n+z^2/(4n^2)}}{1+z^2/n}
$$







## 计算模式



**正态均值区间**

- 样本量
- 均值
- 标准差
- 置信水平 · %





**Wilson 比例区间**

- 样本量
- 成功次数
- 置信水平 · %

[文档站](https://docs.toolpony.com/zh-hans/guides/confidence-interval-calculator/)
