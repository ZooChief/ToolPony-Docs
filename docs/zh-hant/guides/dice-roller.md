# 擲骰子使用指南



自定義骰子面數和顆數，查看每次擲骰及合計。





## 示例



### 輸入



```
3 顆六面骰
```



### 預期結果



```
三個點數與總和
```





<a id="case-study"></a>



## 用兩顆骰子擲出至少 10 點



1. 選擇兩顆六面骰，目標設爲 10。36 種有序組合裏有 6 種達標，概率約 16.67%。把修正量改爲 +1，兩顆骰子的點數保留，達標組合增至 10 種，概率約 27.78%。



[運行示例](<https://toolpony.com/zh-hant/tools/dice-roller/#example-two-dice>)





## 試一試

[打開完整工具 · 擲骰子](<https://toolpony.com/zh-hant/tools/dice-roller/>)





## 計算方法



每顆骰子獨立使用 Web Crypto 均勻抽取。最多 100 顆，每顆可選 2 至 1,000 面。





**方法來源** [W3C · Web Cryptography](<https://www.w3.org/TR/WebCryptoAPI/#Crypto-method-getRandomValues>)



[ZooChief](<https://docs.toolpony.com/zh-hant/about/>) · [反饋結果問題](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fzh-hant%2Fguides%2Fdice-roller%2F>)

[文檔站](https://docs.toolpony.com/zh-hant/guides/dice-roller/)
