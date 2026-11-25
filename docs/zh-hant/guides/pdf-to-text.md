# PDF 轉文字使用指南



選擇頁面，複製文字或下載 TXT、帶原頁碼的 JSON。





## 開始使用



1. 打開包含可選文字的 PDF。
2. 選擇頁面並調整順序，再提取文字。
3. 複製結果或下載 TXT、JSON。JSON 保留原始頁碼。







## 示例



### 輸入



```
圖文混合 PDF，輸出選 JSON，按 3、2、1 提取。第 2 頁只有藍色色樣圖。
```

[示例 · PDF](<https://toolpony.com/samples/toolpony-mixed-pages.pdf>)

### 預期結果



```
[{"page":3,"text":"Total 42"},{"page":2,"text":""},{"page":1,"text":"Order 417"}]
```





<a id="case-study"></a>



## 找出圖文混合 PDF 中沒有提取出文字的那一頁



1. 打開混合樣例 PDF。第 1 頁寫着「Order 417」，第 2 頁只有一張藍色色樣圖，第 3 頁寫着「Total 42」。在完整工具中點「試用圖文混合 PDF」，會自動載入文件、選擇 3、2、1 頁並設置 JSON 輸出。
2. 提取後，第一條記錄是第 3 頁的「Total 42」，中間一條是第 2 頁，text 爲空，最後一條是第 1 頁的「Order 417」。結果還會單獨列出沒有可提取文字的原始頁碼 2。
3. 把自己的 PDF 文字導入其他系統前，可以先按這個方法覈對列出的頁面。如果頁面是圖表，可以保留爲圖片。如果是拍下的文字，需要用 OCR 識別並生成文字層。



[PDF 轉 JPG 或 PNG](<https://toolpony.com/zh-hant/tools/pdf-to-jpg/>)



[toolpony-mixed-pages.pdf](<https://toolpony.com/samples/toolpony-mixed-pages.pdf>)





## 試一試

[打開完整工具 · PDF 轉文字](<https://toolpony.com/zh-hant/tools/pdf-to-text/#example-mixed-pdf>)





## 使用提示



TXT 用換頁符分隔頁面。提取按 PDF 內部文字順序進行，多欄佈局的輸出順序可能與視覺閱讀順序不同。掃描件需要 OCR。 文檔不超過八頁時，可以先清空，再按導出順序點頁號。更長的文檔可以一鍵選擇奇數頁或偶數頁。







## 適用範圍



最大 30 MB、300 頁、200 萬字符及 20 萬段文字。輸出遵循 PDF 內部文字順序。掃描件需要 OCR，不支持加密文件。



掃描件看得清卻提取不到文字時，先在 PDF 閱讀器裏試着選中一個詞。拍成圖片的頁面需要先用 OCR 建立文字層。如果文檔既有文字頁也有掃描頁，可導出 JSON，根據空 text 字段和原始頁碼找到需要識別的頁面。





**方法來源** [PDF Association · ISO 32000-2](<https://pdfa.org/resource/iso-32000-2/>) · [Adobe · PDF / OCR](<https://helpx.adobe.com/acrobat/desktop/create-documents/scan-documents-to-pdfs/recognize-text.html>)



[ZooChief](<https://docs.toolpony.com/zh-hant/about/>) · [反饋結果問題](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fzh-hant%2Fguides%2Fpdf-to-text%2F>)

[文檔站](https://docs.toolpony.com/zh-hant/guides/pdf-to-text/)
