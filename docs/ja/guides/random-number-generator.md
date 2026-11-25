# 乱数生成の使い方



指定範囲の両端を含む整数を抽選します。重複なしの抽選と昇順表示を選べます。





## 例



### 入力



```
最小 1、最大 10、個数 5
```



### 期待される結果



```
1～10 の乱数（整数）を 5 個
```





<a id="case-study"></a>



## 4枚抽選する



1. 12枚の券に 101〜112 の番号を付け、重複なしで4枚引きます。読み上げ用に昇順にし、並べ替えを解除すると元の抽選順に戻ります。CSV には各券の元の順番が残ります。



[入力例を実行](<https://toolpony.com/ja/tools/random-number-generator/#example-ticket-draw>)





## 試してみる

[ツール全体を開く · 乱数生成](<https://toolpony.com/ja/tools/random-number-generator/>)





## 計算方法



Web Crypto の乱数を使います。棄却サンプリングで剰余の偏りを避けます。−1,000,000,000 から 1,000,000,000 までの整数を最大 1,000 個生成します。





**計算・処理の参考資料** [W3C · Web Cryptography](<https://www.w3.org/TR/WebCryptoAPI/#Crypto-method-getRandomValues>)



[ZooChief](<https://docs.toolpony.com/ja/about/>) · [結果の問題を報告](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fja%2Fguides%2Frandom-number-generator%2F>)

[ドキュメント](https://docs.toolpony.com/ja/guides/random-number-generator/)
