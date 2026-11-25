# 密码生成器使用指南



在本地生成密码，支持字符集、自定义排除与字符不重复。





## 示例



### 输入



```
20 位，启用四个字符组
```



### 预期结果



```
生成一条随机密码
```





<a id="case-study"></a>



## 试做一批便于抄录的测试码



1. 用大写字母和数字生成六组 16 位测试码。在排除框中填入 2Z5S8B，避开印刷时容易看错的三组字符。
2. 每一行都含字母和数字，行内字符不重复。复制其中一行就能测试表单。再次打开示例会在设备上重新生成。



[运行示例](<https://toolpony.com/zh-hans/tools/password-generator/#example-readable-codes>)





## 试一试

[打开完整工具 · 密码生成器](<https://toolpony.com/zh-hans/tools/password-generator/>)





## 计算方法



使用 Web Crypto 随机取样。要求包含每个启用的字符组时，先分别抽取，再随机打乱位置。密码仅显示在当前页面。





**方法来源** [W3C · Web Cryptography](<https://www.w3.org/TR/WebCryptoAPI/#Crypto-method-getRandomValues>)



[ZooChief](<https://docs.toolpony.com/zh-hans/about/>) · [反馈结果问题](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fzh-hans%2Fguides%2Fpassword-generator%2F>)

[文档站](https://docs.toolpony.com/zh-hans/guides/password-generator/)
