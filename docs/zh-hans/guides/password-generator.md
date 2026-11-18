# 密码生成器



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







## 试一试



[打开完整工具](<https://toolpony.com/zh-hans/tools/password-generator/>)







## 计算方法



使用 Web Crypto 随机取样。要求包含每个启用的字符组时，先分别抽取，再随机打乱位置。密码仅显示在当前页面。

[文档站](https://docs.toolpony.com/zh-hans/guides/password-generator/)
