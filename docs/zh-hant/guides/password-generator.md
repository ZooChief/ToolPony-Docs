# 密碼生成器



在本地生成密碼，支持字符集、自定義排除與字符不重複。





## 示例



### 輸入



```
20 位，啓用四個字符組
```



### 預期結果



```
生成一條隨機密碼
```







## 試一試

[打開完整工具 · 密碼生成器](<https://toolpony.com/zh-hant/tools/password-generator/>)





## 計算方法



使用 Web Crypto 隨機取樣。要求包含每個啓用的字符組時，先分別抽取，再隨機打亂位置。密碼僅顯示在當前頁面。

[文檔站](https://docs.toolpony.com/zh-hant/guides/password-generator/)
