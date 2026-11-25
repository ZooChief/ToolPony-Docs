# Unicode 編碼轉換使用指南



轉換 Unicode 碼點、UTF-8 字節與 JavaScript 轉義，逐字符檢查並比較規範化形式。





## 示例



### 輸入



```
🐴
```



### 預期結果



```
U+1F434 或 F0 9F 90 B4
```





<a id="case-study"></a>



## 檢查兩種看起來相同的 é



1. 檢查由 e、組合重音 U+0301、空格和 🐴 組成的文本。原文有 3 個字素簇、4 個碼點、5 個 UTF-16 碼元和 8 個 UTF-8 字節。選擇 NFC 後，重音合成爲 U+00E9，UTF-8 長度減爲 7 字節。🐴 始終是 1 個碼點、2 個 UTF-16 碼元。



[運行示例](<https://toolpony.com/zh-hant/tools/unicode-converter/#example-combining-accent>)





## 試一試

[打開完整工具 · Unicode 編碼轉換](<https://toolpony.com/zh-hant/tools/unicode-converter/>)





## 計算方法



碼點模式將輔助平面字符視爲一個標量。UTF-16 對該字符使用兩個編碼單元。無效代理項序列和 UTF-8 字節會被拒絕。







## 計算模式





### 編碼文本



- 輸入
- 編碼 · Unicode 碼點 / UTF-8 十六進制字節 / JavaScript UTF-16 轉義 / JavaScript 碼點轉義







### 解碼文本



- 輸入
- 編碼 · Unicode 碼點 / UTF-8 十六進制字節 / JavaScript UTF-16 轉義 / JavaScript 碼點轉義







### 檢查字符



- 輸入
- 規範化形式 · 原文 / NFC / NFD / NFKC / NFKD







**方法來源** [IETF · RFC 3629](<https://www.rfc-editor.org/rfc/rfc3629>) · [Unicode · UAX \#15](<https://www.unicode.org/reports/tr15/>)



[ZooChief](<https://docs.toolpony.com/zh-hant/about/>) · [反饋結果問題](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fzh-hant%2Fguides%2Funicode-converter%2F>)

[文檔站](https://docs.toolpony.com/zh-hant/guides/unicode-converter/)
