# 統計計算器



計算均值、中位數、衆數、四分位數，以及總體和樣本的離散程度。





## 開始使用



1. 按示例填寫數值，或輸入你自己的測量值。
2. 計算後可複製結果或下載明細。







## 示例



### 輸入



```
2, 4, 4, 6, 9
```



### 預期結果



```
均值 5，中位數 4
```







## 試一試



[打開完整工具](<https://toolpony.com/zh-hant/tools/statistics-calculator/>)







## 使用提示



計算在瀏覽器內完成。無單位標記的字段請使用一致單位。







## 計算方法



四分位數按 (n−1)p 線性插值。總體方差除以 n，樣本方差除以 n−1。最多輸入 1,000 個用逗號或空白分隔的數值。



$$
\bar x=\frac{1}{n}\sum_{i=1}^{n} x_i,\qquad s=\sqrt{\frac{\sum_i(x_i-\bar x)^2}{n-1}}
$$



$$
\operatorname{SE}(\bar x)=\frac{s}{\sqrt n},\qquad \bar x\pm z\operatorname{SE}(\bar x)
$$



從總體抽取的部分數據使用樣本標準差，掌握全部數據時使用總體標準差。置信區間表列出均值在多個置信水平下的正態近似結果。







## 計算模式



**數據概覽**

- 數據





**樣本標準差**

- 數據





**總體標準差**

- 數據

[文檔站](https://docs.toolpony.com/zh-hant/guides/statistics-calculator/)
