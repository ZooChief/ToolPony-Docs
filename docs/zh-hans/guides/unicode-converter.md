# Unicode 编码转换



在文本、Unicode 码点、UTF-8 十六进制字节与 UTF-16 转义间双向转换。





## 示例



### 输入



```
🐴
```



### 预期结果



```
U+1F434 或 F0 9F 90 B4
```







## 试一试



[打开完整工具](<https://toolpony.com/zh-hans/tools/unicode-converter/>)







## 计算方法



码点模式将辅助平面字符视为一个标量。UTF-16 对该字符使用两个编码单元。无效代理项序列和 UTF-8 字节会被拒绝。







## 计算模式



**编码文本**

- 输入
- 编码 · Unicode 码点 / UTF-8 十六进制字节 / JavaScript UTF-16 转义





**解码文本**

- 输入
- 编码 · Unicode 码点 / UTF-8 十六进制字节 / JavaScript UTF-16 转义

[文档站](https://docs.toolpony.com/zh-hans/guides/unicode-converter/)
