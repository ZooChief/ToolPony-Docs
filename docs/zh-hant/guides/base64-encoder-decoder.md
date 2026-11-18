# Base64 編碼與解碼



將 UTF-8 文本編碼爲標準或 URL 安全 Base64，並校驗解碼文本。





## 示例



### 輸入



```
編碼 hello
```



### 預期結果



```
aGVsbG8=
```







## 試一試



[打開完整工具](<https://toolpony.com/zh-hant/tools/base64-encoder-decoder/>)







## 計算方法



文本以 UTF-8 轉換。URL 安全模式採用 “-” 和 “\_”，輸出省略填充。輸入上限爲 50 萬字符。

[文檔站](https://docs.toolpony.com/zh-hant/guides/base64-encoder-decoder/)
