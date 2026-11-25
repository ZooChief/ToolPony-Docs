# Unicode 编码转换使用指南



转换 Unicode 码点、UTF-8 字节与 JavaScript 转义，逐字符检查并比较规范化形式。





## 示例



### 输入



```
🐴
```



### 预期结果



```
U+1F434 或 F0 9F 90 B4
```





<a id="case-study"></a>



## 检查两种看起来相同的 é



1. 检查由 e、组合重音 U+0301、空格和 🐴 组成的文本。原文有 3 个字素簇、4 个码点、5 个 UTF-16 码元和 8 个 UTF-8 字节。选择 NFC 后，重音合成为 U+00E9，UTF-8 长度减为 7 字节。🐴 始终是 1 个码点、2 个 UTF-16 码元。



[运行示例](<https://toolpony.com/zh-hans/tools/unicode-converter/#example-combining-accent>)





## 试一试

[打开完整工具 · Unicode 编码转换](<https://toolpony.com/zh-hans/tools/unicode-converter/>)





## 计算方法



码点模式将辅助平面字符视为一个标量。UTF-16 对该字符使用两个编码单元。无效代理项序列和 UTF-8 字节会被拒绝。







## 计算模式





### 编码文本



- 输入
- 编码 · Unicode 码点 / UTF-8 十六进制字节 / JavaScript UTF-16 转义 / JavaScript 码点转义







### 解码文本



- 输入
- 编码 · Unicode 码点 / UTF-8 十六进制字节 / JavaScript UTF-16 转义 / JavaScript 码点转义







### 检查字符



- 输入
- 规范化形式 · 原文 / NFC / NFD / NFKC / NFKD







**方法来源** [IETF · RFC 3629](<https://www.rfc-editor.org/rfc/rfc3629>) · [Unicode · UAX \#15](<https://www.unicode.org/reports/tr15/>)



[ZooChief](<https://docs.toolpony.com/zh-hans/about/>) · [反馈结果问题](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fzh-hans%2Fguides%2Funicode-converter%2F>)

[文档站](https://docs.toolpony.com/zh-hans/guides/unicode-converter/)
