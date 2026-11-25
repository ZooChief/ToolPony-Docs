# 隨機數生成器使用指南



在閉區間內生成隨機整數，支持去重和排序。





## 示例



### 輸入



```
最小 1，最大 10，生成 5 個
```



### 預期結果



```
5 個 1 至 10 的隨機整數
```





<a id="case-study"></a>



## 抽四張票



1. 給 12 張票編號 101 至 112，勾選不重複，抽取 4 張。開啓升序便於唱票，關閉後可看原始抽取次序。CSV 保留每張票原本是第幾次抽中的。



[運行示例](<https://toolpony.com/zh-hant/tools/random-number-generator/#example-ticket-draw>)





## 試一試

[打開完整工具 · 隨機數生成器](<https://toolpony.com/zh-hant/tools/random-number-generator/>)





## 計算方法



隨機值來自 Web Crypto，採用拒絕採樣避免取模偏差。最多生成 1,000 個數，區間範圍爲 −10 億至 10 億。





**方法來源** [W3C · Web Cryptography](<https://www.w3.org/TR/WebCryptoAPI/#Crypto-method-getRandomValues>)



[ZooChief](<https://docs.toolpony.com/zh-hant/about/>) · [反饋結果問題](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fzh-hant%2Fguides%2Frandom-number-generator%2F>)

[文檔站](https://docs.toolpony.com/zh-hant/guides/random-number-generator/)
