# Base64 编码与解码使用指南



将 UTF-8 文本或十六进制字节转换为 Base64、Base64url，可查看解码字节并保存二进制文件。





## 示例



### 输入



```
编码 hello
```



### 预期结果



```
aGVsbG8=
```





<a id="case-study"></a>



## 从 Base64url 还原二进制字节



1. 选择解码、URL 安全和十六进制字节，粘贴 \_wCA7w。结果 FF 00 80 EF 含一个零字节，也有无法组成 UTF-8 文本的值。点击“下载原始字节”可保存这四个字节。



[运行示例](<https://toolpony.com/zh-hans/tools/base64-encoder-decoder/#example-binary-bytes>)





## 试一试

[打开完整工具 · Base64 编码与解码](<https://toolpony.com/zh-hans/tools/base64-encoder-decoder/>)





## 计算方法



标准 Base64 使用 + 和 /，Base64url 使用 - 和 \_，输出省略填充。文本模式校验 UTF-8 并保留开头的 U+FEFF。文本输入上限为 500,000 个 UTF-16 码元，二进制输入上限为 500,000 字节。





**方法来源** [IETF · RFC 4648 (Base64)](<https://www.rfc-editor.org/rfc/rfc4648>) · [IETF · RFC 3629](<https://www.rfc-editor.org/rfc/rfc3629>)



[ZooChief](<https://docs.toolpony.com/zh-hans/about/>) · [反馈结果问题](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fzh-hans%2Fguides%2Fbase64-encoder-decoder%2F>)

[文档站](https://docs.toolpony.com/zh-hans/guides/base64-encoder-decoder/)
