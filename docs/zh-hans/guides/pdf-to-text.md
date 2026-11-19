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





<a id="case-study"></a>



## 找出图文混合 PDF 中没有提取出文字的那一页



1. 打开混合样例 PDF。第 1 页写着「Order 417」，第 2 页只有一张蓝色色样图，第 3 页写着「Total 42」。在完整工具中点「试用图文混合 PDF」，会自动载入文件、选择 3、2、1 页并设置 JSON 输出。
2. 提取后，第一条记录是第 3 页的「Total 42」，中间一条是第 2 页，text 为空，最后一条是第 1 页的「Order 417」。结果还会单独列出没有可提取文字的原始页码 2。
3. 把自己的 PDF 文字导入其他系统前，可以先按这个方法核对列出的页面。如果页面是图表，可以保留为图片。如果是拍下的文字，需要用 OCR 识别并生成文字层。



[PDF 转 JPG 或 PNG](<https://toolpony.com/zh-hans/tools/pdf-to-jpg/>)



[toolpony-mixed-pages.pdf](<https://toolpony.com/samples/toolpony-mixed-pages.pdf>)





## 试一试

[打开完整工具 · PDF 转文字](<https://toolpony.com/zh-hans/tools/pdf-to-text/>)





## 使用提示



TXT 用换页符分隔页面。提取按 PDF 内部文字顺序进行，多栏布局的输出顺序可能与视觉阅读顺序不同。扫描件需要 OCR。







## 适用范围



最大 30 MB、300 页、200 万字符及 20 万段文字。输出遵循 PDF 内部文字顺序。扫描件需要 OCR，不支持加密文件。



扫描件看得清却提取不到文字时，先在 PDF 阅读器里试着选中一个词。拍成图片的页面需要先用 OCR 建立文字层。如果文档既有文字页也有扫描页，可导出 JSON，根据空 text 字段和原始页码找到需要识别的页面。





**方法来源** [PDF Association · ISO 32000-2](<https://pdfa.org/resource/iso-32000-2/>) · [Adobe · PDF / OCR](<https://helpx.adobe.com/acrobat/desktop/create-documents/scan-documents-to-pdfs/recognize-text.html>)



[ZooChief](<https://docs.toolpony.com/zh-hans/about/>) · [反馈结果问题](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fzh-hans%2Fguides%2Fpdf-to-text%2F>)

[文档站](https://docs.toolpony.com/zh-hans/guides/pdf-to-text/)
