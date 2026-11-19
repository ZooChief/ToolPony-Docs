# 顏色對比度檢查



比較兩個不透明顏色，並檢查是否達到 WCAG 2.2 對比度閾值。





## 示例



### 輸入



```
#000000 放在 #FFFFFF 上
```



### 預期結果



```
21:1
```







## 試一試

[打開完整工具 · 顏色對比度檢查](<https://toolpony.com/zh-hant/tools/contrast-checker/>)





## 計算方法



對比度爲（較亮顏色相對亮度 + 0.05）除以（較暗顏色相對亮度 + 0.05）。達標判斷使用未舍入數值。普通文本 AA 爲 4.5:1，AAA 爲 7:1，大號文本分別爲 3:1 和 4.5:1。

[文檔站](https://docs.toolpony.com/zh-hant/guides/contrast-checker/)
