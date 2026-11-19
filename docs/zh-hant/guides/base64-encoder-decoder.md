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

[打開完整工具 · Base64 編碼與解碼](<https://toolpony.com/zh-hant/tools/base64-encoder-decoder/>)





## 計算方法



文本以 UTF-8 轉換。URL 安全模式採用 “-” 和 “\_”，輸出省略填充。輸入上限爲 50 萬字符。





**方法來源** [IETF · RFC 4648 (Base64)](<https://www.rfc-editor.org/rfc/rfc4648>)



[ZooChief](<https://docs.toolpony.com/zh-hant/about/>) · [反饋結果問題](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fzh-hant%2Fguides%2Fbase64-encoder-decoder%2F>)

[文檔站](https://docs.toolpony.com/zh-hant/guides/base64-encoder-decoder/)
