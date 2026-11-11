# 字数统计



粘贴文本或导入文本、DOCX、ODT、PDF、SRT 或 WebVTT。导入字幕时统计对白。查看词数和一至三个词的短语频率，可导出统计 CSV。





## 开始使用



1. 输入文本，或导入纯文本、DOCX、ODT 或含可选文字的 PDF。
2. 导入 SRT 或 WebVTT 时，自动去掉时间码和常见标记，再统计对白。
3. 在高频词中选择一至三个词的短语，再下载统计和频率 CSV。







## 示例



### 输入



```
蓝天 白云 蓝天 白云
```



### 预期结果



```
4 个词，2 个不同词
```







## 试一试



[打开完整工具](<https://toolpony.com/zh-hans/tools/word-counter/>)







## 使用提示



按 UTF-8 编码计最多 1 MiB。字符按 Unicode 码点统计。短语不会跨标点和换行，占比的分母为同长度的全部短语。







## 适用范围



文本按 UTF-8 计最多 1 MiB。分词取决于浏览器语言规则，PDF 导入使用文本层，DOCX 和 ODT 只读取正文。短语占比为出现次数除以同长度短语总数。

[文档站](https://docs.toolpony.com/zh-hans/guides/word-counter/)
