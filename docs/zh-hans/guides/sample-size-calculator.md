# 样本量计算器



求调查所需最小样本量，或计算经过有限总体修正的误差幅度。





## 示例



### 输入



```
置信水平 95%，误差 4%，比例 35%，总体 1,000
```



### 预期结果



```
354 个样本
```







## 试一试



[打开完整工具](<https://toolpony.com/zh-hans/tools/sample-size-calculator/>)







## 计算方法



初始样本量为 z²p(1−p)/e²。有限总体时，再除以 1 +（初始样本量−1）/N 并向上取整。误差幅度采用相同的比例与有限总体模型。



$$
n_0=\frac{z^2p(1-p)}{e^2},\qquad n=\left\lceil\frac{n_0}{1+(n_0-1)/N}\right\rceil
$$







## 计算模式



**求样本量**

- 置信水平 · %
- 误差幅度 · %
- 总体比例 · %
- 总体数量（0 表示不限）





**求误差幅度**

- 置信水平 · %
- 样本量
- 总体比例 · %
- 总体数量（0 表示不限）

[文档站](https://docs.toolpony.com/zh-hans/guides/sample-size-calculator/)
