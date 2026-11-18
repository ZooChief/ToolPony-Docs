# 大數計算器



使用精確大整數和十進制係數計算，支持爲除法與平方根設置舍入位數。





## 示例



### 輸入



```
9,007,199,254,740,993 + 7
```



### 預期結果



```
9007199254741000
```







## 試一試



[打開完整工具](<https://toolpony.com/zh-hant/tools/big-number-calculator/>)







## 計算方法



加減乘、整數冪和整數運算使用 BigInt 係數。除法舍入到所選小數位數。平方根可截斷或就近舍入。結果範圍內支持正負整數指數。



$$
x=m\cdot 10^e,\quad x_1x_2=(m_1m_2)\cdot 10^{e_1+e_2}
$$

[文檔站](https://docs.toolpony.com/zh-hant/guides/big-number-calculator/)
