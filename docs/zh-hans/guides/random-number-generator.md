# 随机数生成器



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







## 试一试

[打开完整工具 · 随机数生成器](<https://toolpony.com/zh-hans/tools/random-number-generator/>)





## 计算方法



随机值来自 Web Crypto，采用拒绝采样避免取模偏差。最多生成 1,000 个数，区间范围为 −10 亿至 10 亿。





[ZooChief](<https://docs.toolpony.com/zh-hans/about/>) · [反馈结果问题](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fzh-hans%2Fguides%2Frandom-number-generator%2F>)

[文档站](https://docs.toolpony.com/zh-hans/guides/random-number-generator/)
