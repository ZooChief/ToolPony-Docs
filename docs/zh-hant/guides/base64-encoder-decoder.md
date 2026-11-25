# Base64 編碼與解碼使用指南



將 UTF-8 文本或十六進制字節轉換爲 Base64、Base64url，可查看解碼字節並保存二進制文件。





## 示例



### 輸入



```
編碼 hello
```



### 預期結果



```
aGVsbG8=
```





<a id="case-study"></a>



## 從 Base64url 還原二進制字節



1. 選擇解碼、URL 安全和十六進制字節，粘貼 \_wCA7w。結果 FF 00 80 EF 含一個零字節，也有無法組成 UTF-8 文本的值。點擊“下載原始字節”可保存這四個字節。



[運行示例](<https://toolpony.com/zh-hant/tools/base64-encoder-decoder/#example-binary-bytes>)





## 試一試

[打開完整工具 · Base64 編碼與解碼](<https://toolpony.com/zh-hant/tools/base64-encoder-decoder/>)





## 計算方法



標準 Base64 使用 + 和 /，Base64url 使用 - 和 \_，輸出省略填充。文本模式校驗 UTF-8 並保留開頭的 U+FEFF。文本輸入上限爲 500,000 個 UTF-16 碼元，二進制輸入上限爲 500,000 字節。





**方法來源** [IETF · RFC 4648 (Base64)](<https://www.rfc-editor.org/rfc/rfc4648>) · [IETF · RFC 3629](<https://www.rfc-editor.org/rfc/rfc3629>)



[ZooChief](<https://docs.toolpony.com/zh-hant/about/>) · [反饋結果問題](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fzh-hant%2Fguides%2Fbase64-encoder-decoder%2F>)

[文檔站](https://docs.toolpony.com/zh-hant/guides/base64-encoder-decoder/)
