# 樣本量計算器



求調查所需最小樣本量，或計算經過有限總體修正的誤差幅度。





## 示例



### 輸入



```
置信水平 95%，誤差 4%，比例 35%，總體 1,000
```



### 預期結果



```
354 個樣本
```







## 試一試



[打開完整工具](<https://toolpony.com/zh-hant/tools/sample-size-calculator/>)







## 計算方法



初始樣本量爲 z²p(1−p)/e²。有限總體時，再除以 1 +（初始樣本量−1）/N 並向上取整。誤差幅度採用相同的比例與有限總體模型。



$$
n_0=\frac{z^2p(1-p)}{e^2},\qquad n=\left\lceil\frac{n_0}{1+(n_0-1)/N}\right\rceil
$$







## 計算模式



**求樣本量**

- 置信水平 · %
- 誤差幅度 · %
- 總體比例 · %
- 總體數量（0 表示不限）





**求誤差幅度**

- 置信水平 · %
- 樣本量
- 總體比例 · %
- 總體數量（0 表示不限）

[文檔站](https://docs.toolpony.com/zh-hant/guides/sample-size-calculator/)
