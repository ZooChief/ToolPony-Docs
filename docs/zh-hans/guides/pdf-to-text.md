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



### 预期结果



```
[{"page":2,"text":"Two"},{"page":1,"text":"One"}]
```







## 试一试



[打开完整工具](<https://toolpony.com/zh-hans/tools/pdf-to-text/>)







## 使用提示



TXT 用换页符分隔页面。提取按 PDF 内部文字顺序进行，多栏布局的输出顺序可能与视觉阅读顺序不同。扫描件需要 OCR。







## 适用范围



最大 30 MB、300 页、200 万字符及 20 万段文字。输出遵循 PDF 内部文字顺序。扫描件需要 OCR，不支持加密文件。

[文档站](https://docs.toolpony.com/zh-hans/guides/pdf-to-text/)
