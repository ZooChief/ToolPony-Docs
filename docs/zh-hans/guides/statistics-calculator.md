# 统计计算器



计算均值、中位数、众数、四分位数，以及总体和样本的离散程度。





## 开始使用



1. 按示例填写数值，或输入你自己的测量值。
2. 计算后可复制结果或下载明细。







## 示例



### 输入



```
2, 4, 4, 6, 9
```



### 预期结果



```
均值 5，中位数 4
```







## 试一试



[打开完整工具](<https://toolpony.com/zh-hans/tools/statistics-calculator/>)







## 使用提示



计算在浏览器内完成。无单位标记的字段请使用一致单位。







## 计算方法



四分位数按 (n−1)p 线性插值。总体方差除以 n，样本方差除以 n−1。最多输入 1,000 个用逗号或空白分隔的数值。



$$
\bar x=\frac{1}{n}\sum_{i=1}^{n} x_i,\qquad s=\sqrt{\frac{\sum_i(x_i-\bar x)^2}{n-1}}
$$



$$
\operatorname{SE}(\bar x)=\frac{s}{\sqrt n},\qquad \bar x\pm z\operatorname{SE}(\bar x)
$$



从总体抽取的部分数据使用样本标准差，掌握全部数据时使用总体标准差。置信区间表列出均值在多个置信水平下的正态近似结果。







## 计算模式



**数据概览**

- 数据





**样本标准差**

- 数据





**总体标准差**

- 数据

[文档站](https://docs.toolpony.com/zh-hans/guides/statistics-calculator/)
