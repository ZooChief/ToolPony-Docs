# サイコロの使い方



面数と個数を指定してサイコロを振り、各出目と合計を確認します。





## 例



### 入力



```
6面サイコロを3個
```



### 期待される結果



```
3個の出目とその合計
```





<a id="case-study"></a>



## 2個のサイコロで10以上



1. 6面ダイス2個で目標を10にすると、36通り中6通り (16.67%) が達成します。補正を +1 に変えても出目は同じで、達成は10通り (27.78%) になります。



[入力例を実行](<https://toolpony.com/ja/tools/dice-roller/#example-two-dice>)





## 試してみる

[ツール全体を開く · サイコロ](<https://toolpony.com/ja/tools/dice-roller/>)





## 計算方法



Web Crypto を使い、各サイコロの出目を独立に等確率で抽選します。最大 100 個で、各 2〜1,000 面に対応します。





**計算・処理の参考資料** [W3C · Web Cryptography](<https://www.w3.org/TR/WebCryptoAPI/#Crypto-method-getRandomValues>)



[ZooChief](<https://docs.toolpony.com/ja/about/>) · [結果の問題を報告](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fja%2Fguides%2Fdice-roller%2F>)

[ドキュメント](https://docs.toolpony.com/ja/guides/dice-roller/)
