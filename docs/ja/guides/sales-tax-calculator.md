# 売上税・付加価値税計算機の使い方



売上税および付加価値税(VAT)を独自の税率で追加または削除してください。





## 例



### 入力



```
純価格 100、付加価値税 20%
```



### 期待される結果



```
売上総額120、税額20
```





<a id="case-study"></a>



## レシートから税率を逆算



1. 税抜 200.00、支払い 217.00 の差は 17.00 です。税抜価格で割ると 8.5% になります。税率を適用して支払額を確かめます。





## 試してみる

[ツール全体を開く · 売上税・付加価値税計算機](<https://toolpony.com/ja/tools/sales-tax-calculator/#example-receipt-rate>)





## 計算方法



総価格=純価格×(1 +レート)。 税率はユーザーによって提供されます。





[ZooChief](<https://docs.toolpony.com/ja/about/>) · [結果の問題を報告](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fja%2Fguides%2Fsales-tax-calculator%2F>)

[ドキュメント](https://docs.toolpony.com/ja/guides/sales-tax-calculator/)
