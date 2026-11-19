# 乱数生成



任意の一意と並べ替えで、包括的な範囲でランダムな整数を生成します。





## 例



### 入力



```
最小 1、最大 10、個数 5
```



### 期待される結果



```
1～10 の乱数（整数）を 5 個
```







## 試してみる

[ツール全体を開く · 乱数生成](<https://toolpony.com/ja/tools/random-number-generator/>)





## 計算方法



Web Crypto の乱数を使います。棄却サンプリングで剰余の偏りを避けます。−1,000,000,000 から 1,000,000,000 までの整数を最大 1,000 個生成します。





[ZooChief](<https://docs.toolpony.com/ja/about/>) · [結果の問題を報告](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fja%2Fguides%2Frandom-number-generator%2F>)

[ドキュメント](https://docs.toolpony.com/ja/guides/random-number-generator/)
