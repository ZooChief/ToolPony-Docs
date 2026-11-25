# 密碼生成器使用指南



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





<a id="case-study"></a>



## 試做一批便於抄錄的測試碼



1. 用大寫字母和數字生成六組 16 位測試碼。在排除框中填入 2Z5S8B，避開印刷時容易看錯的三組字符。
2. 每一行都含字母和數字，行內字符不重複。複製其中一行就能測試表單。再次打開示例會在設備上重新生成。



[運行示例](<https://toolpony.com/zh-hant/tools/password-generator/#example-readable-codes>)





## 試一試

[打開完整工具 · 密碼生成器](<https://toolpony.com/zh-hant/tools/password-generator/>)





## 計算方法



使用 Web Crypto 隨機取樣。要求包含每個啓用的字符組時，先分別抽取，再隨機打亂位置。密碼僅顯示在當前頁面。





**方法來源** [W3C · Web Cryptography](<https://www.w3.org/TR/WebCryptoAPI/#Crypto-method-getRandomValues>)



[ZooChief](<https://docs.toolpony.com/zh-hant/about/>) · [反饋結果問題](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fzh-hant%2Fguides%2Fpassword-generator%2F>)

[文檔站](https://docs.toolpony.com/zh-hant/guides/password-generator/)
