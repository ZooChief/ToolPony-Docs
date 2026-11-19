# 投資回収期間計算機



年間キャッシュフローの増加または不規則な影響から、定期的かつ割引価格でのキャッシュバックを検索してください。





## 例



### 入力



```
初期資金17,500台、初回流入額4,700人、成長率8%、割引6%
```



### 期待される結果



```
返済額 ≈ 3.379年、割引期間 ≈ 3.841年
```







## 試してみる

[ツール全体を開く · 投資回収期間計算機](<https://toolpony.com/ja/tools/payback-period-calculator/>)





## 計算方法



初期支出からキャッシュフローを蓄積する。 ゼロの最初の横断線では、その年のその割合を補ってください。 割引キャッシュフローは年額を(1+r)^k 差額で分けます。 常に流れるストリームは、割引報酬として逆年金方式を使用します。



$$
C_k=\sum_{i=0}^{k}F_i,\qquad F_i^{\mathrm{PV}}=\frac{F_i}{(1+r)^i}
$$







## 計算モード



**定期的または拡大するキャッシュフロー**

- 初期投資額
- 初年度キャッシュフロー
- 年間成長率または低下 · %
- 年
- 年間割引率 · %





**不定期な年間キャッシュフロー**

- 初期投資額
- その後の年間キャッシュフロー
- 年間割引率 · %







[ZooChief](<https://docs.toolpony.com/ja/about/>) · [結果の問題を報告](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fja%2Fguides%2Fpayback-period-calculator%2F>)

[ドキュメント](https://docs.toolpony.com/ja/guides/payback-period-calculator/)
