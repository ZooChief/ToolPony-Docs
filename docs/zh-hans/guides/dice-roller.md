# 掷骰子使用指南



自定义骰子面数和颗数，查看每次掷骰及合计。





## 示例



### 输入



```
3 颗六面骰
```



### 预期结果



```
三个点数与总和
```





<a id="case-study"></a>



## 用两颗骰子掷出至少 10 点



1. 选择两颗六面骰，目标设为 10。36 种有序组合里有 6 种达标，概率约 16.67%。把修正量改为 +1，两颗骰子的点数保留，达标组合增至 10 种，概率约 27.78%。



[运行示例](<https://toolpony.com/zh-hans/tools/dice-roller/#example-two-dice>)





## 试一试

[打开完整工具 · 掷骰子](<https://toolpony.com/zh-hans/tools/dice-roller/>)





## 计算方法



每颗骰子独立使用 Web Crypto 均匀抽取。最多 100 颗，每颗可选 2 至 1,000 面。





**方法来源** [W3C · Web Cryptography](<https://www.w3.org/TR/WebCryptoAPI/#Crypto-method-getRandomValues>)



[ZooChief](<https://docs.toolpony.com/zh-hans/about/>) · [反馈结果问题](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fzh-hans%2Fguides%2Fdice-roller%2F>)

[文档站](https://docs.toolpony.com/zh-hans/guides/dice-roller/)
