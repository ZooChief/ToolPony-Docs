# 字數統計



粘貼文本或導入文本、DOCX、ODT、PDF、SRT 或 WebVTT。導入字幕時統計對白。查看詞數和一至三個詞的短語頻率，可導出統計 CSV。





## 開始使用



1. 輸入文本，或導入純文本、DOCX、ODT 或含可選文字的 PDF。
2. 導入 SRT 或 WebVTT 時，自動去掉時間碼和常見標記，再統計對白。
3. 在高頻詞中選擇一至三個詞的短語，再下載統計和頻率 CSV。







## 示例



### 輸入



```
藍天 白雲 藍天 白雲
```



### 預期結果



```
4 個詞，2 個不同詞
```







## 試一試



[打開完整工具](<https://toolpony.com/zh-hant/tools/word-counter/>)







## 使用提示



按 UTF-8 編碼計最多 1 MiB。字符按 Unicode 碼點統計。短語不會跨標點和換行，佔比的分母爲同長度的全部短語。







## 適用範圍



文本按 UTF-8 計最多 1 MiB。分詞取決於瀏覽器語言規則，PDF 導入使用文本層，DOCX 和 ODT 只讀取正文。短語佔比爲出現次數除以同長度短語總數。

[文檔站](https://docs.toolpony.com/zh-hant/guides/word-counter/)
