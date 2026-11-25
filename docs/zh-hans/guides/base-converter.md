# 进制转换与计算器使用指南



在 2–36 进制之间转换带符号整数，并进行精确算术、取余和位运算。





## 示例



### 输入



```
FF，从十六进制转十进制
```



### 预期结果



```
255
```





<a id="case-study"></a>



## 核对十六进制编号



1. 把 0x20\_0000\_0000\_0001 转成十进制，末位 1 会保留在 9007199254740993 中。可以交换进制，也可以复制二进制一行，得到连续的数字。



[运行示例](<https://toolpony.com/zh-hans/tools/base-converter/#example-large-hex-id>)





## 试一试

[打开完整工具 · 进制转换与计算器](<https://toolpony.com/zh-hans/tools/base-converter/>)





## 计算方法



进制转换最多支持 4,096 位二进制整数。算术和位运算每个操作数最多 256 位数字，整数除法向零取整。空格和下划线可分隔数字。







## 计算模式





### 进制转换



- 整数
- 输入进制
- 输出进制
- 最少输出位数







### 整数运算



- 整数一
- 整数二
- 输入进制
- 输出进制
- 最少输出位数
- 运算 · 加 / 减 / 乘 / 除 / 余数 / 按位与 / 按位或 / 按位异或







[ZooChief](<https://docs.toolpony.com/zh-hans/about/>) · [反馈结果问题](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fzh-hans%2Fguides%2Fbase-converter%2F>)

[文档站](https://docs.toolpony.com/zh-hans/guides/base-converter/)
