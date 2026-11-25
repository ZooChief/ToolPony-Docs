# 随机数生成器使用指南



在闭区间内生成随机整数，支持去重和排序。





## 示例



### 输入



```
最小 1，最大 10，生成 5 个
```



### 预期结果



```
5 个 1 至 10 的随机整数
```





<a id="case-study"></a>



## 抽四张票



1. 给 12 张票编号 101 至 112，勾选不重复，抽取 4 张。开启升序便于唱票，关闭后可看原始抽取次序。CSV 保留每张票原本是第几次抽中的。



[运行示例](<https://toolpony.com/zh-hans/tools/random-number-generator/#example-ticket-draw>)





## 试一试

[打开完整工具 · 随机数生成器](<https://toolpony.com/zh-hans/tools/random-number-generator/>)





## 计算方法



随机值来自 Web Crypto，采用拒绝采样避免取模偏差。最多生成 1,000 个数，区间范围为 −10 亿至 10 亿。





**方法来源** [W3C · Web Cryptography](<https://www.w3.org/TR/WebCryptoAPI/#Crypto-method-getRandomValues>)



[ZooChief](<https://docs.toolpony.com/zh-hans/about/>) · [反馈结果问题](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fzh-hans%2Fguides%2Frandom-number-generator%2F>)

[文档站](https://docs.toolpony.com/zh-hans/guides/random-number-generator/)
