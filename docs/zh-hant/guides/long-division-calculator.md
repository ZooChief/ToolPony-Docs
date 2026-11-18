# 長除法計算器



支持整數與小數除法，查看商、餘數、小數結果以及長除法步驟。





## 示例



### 輸入



```
12,345 ÷ 67
```



### 預期結果



```
商 184，餘數 17
```







## 試一試



[打開完整工具](<https://toolpony.com/zh-hant/tools/long-division-calculator/>)







## 計算方法



被除數和除數按同一 10 的冪放大。整數商向零取整，帶符號餘數滿足被除數 = 商 × 除數 + 餘數。步驟表使用絕對值。



$$
a=bq+r,\quad q=\operatorname{trunc}(a/b),\quad |r|<|b|
$$

[文檔站](https://docs.toolpony.com/zh-hant/guides/long-division-calculator/)
