# 置信區間計算器



估算均值的正態置信區間，或用 Wilson 方法計算比例區間。





## 開始使用



1. 按示例填寫數值，或輸入你自己的測量值。
2. 計算後可複製結果或下載明細。







## 示例



### 輸入



```
樣本 36，均值 56，標準差 8，置信水平 99%
```



### 預期結果



```
56 ± 3.434
```







## 試一試



[打開完整工具](<https://toolpony.com/zh-hant/tools/confidence-interval-calculator/>)







## 使用提示



計算在瀏覽器內完成。無單位標記的字段請使用一致單位。







## 計算方法



正態誤差幅度爲 z 乘以標準誤 s/√n。Wilson 區間對比例的中心與寬度進行調整，並保持在 \[0,1\] 內。



$$
\bar{x}\pm z_{1-\alpha/2}\frac{s}{\sqrt n}
$$



$$
\frac{\widehat{p}+z^2/(2n)\pm z\sqrt{\widehat{p}(1-\widehat{p})/n+z^2/(4n^2)}}{1+z^2/n}
$$







## 計算模式



**正態均值區間**

- 樣本量
- 均值
- 標準差
- 置信水平 · %





**Wilson 比例區間**

- 樣本量
- 成功次數
- 置信水平 · %

[文檔站](https://docs.toolpony.com/zh-hant/guides/confidence-interval-calculator/)
