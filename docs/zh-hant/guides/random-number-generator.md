# 隨機數生成器



在閉區間內生成隨機整數，支持去重和排序。





## 示例



### 輸入



```
最小 1，最大 10，生成 5 個
```



### 預期結果



```
5 個 1 至 10 的隨機整數
```







## 試一試



[打開完整工具](<https://toolpony.com/zh-hant/tools/random-number-generator/>)







## 計算方法



隨機值來自 Web Crypto，採用拒絕採樣避免取模偏差。最多生成 1,000 個數，區間範圍爲 −10 億至 10 億。

[文檔站](https://docs.toolpony.com/zh-hant/guides/random-number-generator/)
