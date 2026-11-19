# PDF 转文字



选择页面，复制文字或下载 TXT、带原页码的 JSON。





## 开始使用



1. 打开包含可选文字的 PDF。
2. 选择页面并调整顺序，再提取文字。
3. 复制结果或下载 TXT、JSON。JSON 保留原始页码。







## 示例



### 输入



```
PDF 的前两页分别写着 One 和 Two。选页 2, 1，格式为 JSON。
```

[示例 · PDF](<https://toolpony.com/samples/toolpony-pages.pdf>)

### 预期结果



```
[{"page":2,"text":"Two"},{"page":1,"text":"One"}]
```







## 试一试

[打开完整工具 · PDF 转文字](<https://toolpony.com/zh-hans/tools/pdf-to-text/>)





## 使用提示



TXT 用换页符分隔页面。提取按 PDF 内部文字顺序进行，多栏布局的输出顺序可能与视觉阅读顺序不同。扫描件需要 OCR。







## 适用范围



最大 30 MB、300 页、200 万字符及 20 万段文字。输出遵循 PDF 内部文字顺序。扫描件需要 OCR，不支持加密文件。



扫描件看得清却提取不到文字时，先在 PDF 阅读器里试着选中一个词。拍成图片的页面需要先用 OCR 建立文字层。如果文档既有文字页也有扫描页，可导出 JSON，根据空 text 字段和原始页码找到需要识别的页面。

[文档站](https://docs.toolpony.com/zh-hans/guides/pdf-to-text/)
