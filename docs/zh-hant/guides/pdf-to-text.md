# PDF 轉文字



選擇頁面，複製文字或下載 TXT、帶原頁碼的 JSON。





## 開始使用



1. 打開包含可選文字的 PDF。
2. 選擇頁面並調整順序，再提取文字。
3. 複製結果或下載 TXT、JSON。JSON 保留原始頁碼。







## 示例



### 輸入



```
PDF 的前兩頁分別寫着 One 和 Two。選頁 2, 1，格式爲 JSON。
```



### 預期結果



```
[{"page":2,"text":"Two"},{"page":1,"text":"One"}]
```







## 試一試



[打開完整工具](<https://toolpony.com/zh-hant/tools/pdf-to-text/>)







## 使用提示



TXT 用換頁符分隔頁面。提取按 PDF 內部文字順序進行，多欄佈局的輸出順序可能與視覺閱讀順序不同。掃描件需要 OCR。







## 適用範圍



最大 30 MB、300 頁、200 萬字符及 20 萬段文字。輸出遵循 PDF 內部文字順序。掃描件需要 OCR，不支持加密文件。

[文檔站](https://docs.toolpony.com/zh-hant/guides/pdf-to-text/)
