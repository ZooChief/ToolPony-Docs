# Base64 编码与解码



将 UTF-8 文本编码为标准或 URL 安全 Base64，并校验解码文本。





## 示例



### 输入



```
编码 hello
```



### 预期结果



```
aGVsbG8=
```







## 试一试

[打开完整工具 · Base64 编码与解码](<https://toolpony.com/zh-hans/tools/base64-encoder-decoder/>)





## 计算方法



文本以 UTF-8 转换。URL 安全模式采用 “-” 和 “\_”，输出省略填充。输入上限为 50 万字符。

[文档站](https://docs.toolpony.com/zh-hans/guides/base64-encoder-decoder/)
