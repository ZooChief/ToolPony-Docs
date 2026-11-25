# 屋根材計算機の使い方



屋根面積、スクエア数、シングル材やフェルトの必要数、費用を見積もります。





## 使い方



1. 水平面積と勾配または角度を指定します。長方形では実測した長さと幅も使えます。
2. 複雑な屋根は斜面ごとに測って合計し、既知の屋根面積として入力します。







## 例



### 入力



```
水平面積 2,000 ft²、勾配 6/12、軒 1 ft。
```



### 期待される結果



```
約 2,461 ft²、予備 10% で 28 スクエア。
```





<a id="case-study"></a>



## 屋根材の発注



1. 25 × 40 ft の平屋根は1,000 ft²です。予備10%、100 ft²当たり3束なら33束。1束75で合計2,475です。



[入力例を実行](<https://toolpony.com/ja/tools/roofing-calculator/#example-roof-order>)





## 包装の施工面積



必要面積1,100 ft²に対し、表示が1包33.3 ft²なら33包では1,098.9 ft²です。34包で1,132.2 ft²を施工できます。



[入力例を実行](<https://toolpony.com/ja/tools/roofing-calculator/#example-package-label>)







## 異なる軒の出幅



8 × 5 m、軒25 cm、妻側40 cmなら水平投影は8.8 × 5.5 mです。勾配5/12、予備10%、1包3 m²で20包です。



[入力例を実行](<https://toolpony.com/ja/tools/roofing-calculator/#example-roof-overhang>)







## 試してみる

[ツール全体を開く · 屋根材計算機](<https://toolpony.com/ja/tools/roofing-calculator/>)





## 計算方法



水平面積のみの場合は A + 4.4e(√A + e) で推定します。e は軒の水平出幅です。長方形の実測寸法がある場合は (l + 2e)(w + 2e) を使い、勾配係数を掛けます。1 スクエアは 100 ft²。製品ごとの施工面積を確認してください。



$$
A_{\rm proj}\approx A+4.4e(\sqrt A+e),\qquad A_{\rm rect}=(l+2e)(w+2e)
$$



$$
A_{\rm roof}=A_{\rm proj}\sqrt{1+(p/12)^2}=\frac{A_{\rm proj}}{\cos\theta},\quad N_{\rm squares}=\left\lceil\frac{A_{\rm roof,ft^2}(1+a/100)}{100}\right\rceil
$$







## 計算モード





### 水平面積と勾配



- 水平面積
- 面積の単位 · cm² / m² / in² / ft² / yd² / エーカー / ハ
- 水平 12 に対する立ち上がり
- 軒の水平出幅
- 軒の出幅の単位 · mm / cm / m / で / フィート / yd
- 単価
- 価格の単位 · cm² / m² / in² / ft² / yd² / エーカー / ハ
- 予備率 · %
- 包装の施工面積 · 1スクエアあたりの束数 / 1包の施工面積
- 100 ft²あたりの束数
- 1包の有効施工面積
- 1包の価格（任意）







### 水平面積と角度



- 水平面積
- 面積の単位 · cm² / m² / in² / ft² / yd² / エーカー / ハ
- 屋根勾配の角度 · °
- 軒の水平出幅
- 軒の出幅の単位 · mm / cm / m / で / フィート / yd
- 単価
- 価格の単位 · cm² / m² / in² / ft² / yd² / エーカー / ハ
- 予備率 · %
- 包装の施工面積 · 1スクエアあたりの束数 / 1包の施工面積
- 100 ft²あたりの束数
- 1包の有効施工面積
- 1包の価格（任意）







### 屋根面積が既知



- 屋根面積
- 面積の単位 · cm² / m² / in² / ft² / yd² / エーカー / ハ
- 単価
- 価格の単位 · cm² / m² / in² / ft² / yd² / エーカー / ハ
- 予備率 · %
- 包装の施工面積 · 1スクエアあたりの束数 / 1包の施工面積
- 100 ft²あたりの束数
- 1包の有効施工面積
- 1包の価格（任意）







### 実測した長さと幅



- 長さ
- 長さの単位 · mm / cm / m / で / フィート / yd
- 幅
- 幅の単位 · mm / cm / m / で / フィート / yd
- 水平 12 に対する立ち上がり
- 軒の水平出幅
- 軒の出幅の単位 · mm / cm / m / で / フィート / yd
- 妻側の出幅（異なる場合）
- 単価
- 価格の単位 · cm² / m² / in² / ft² / yd² / エーカー / ハ
- 予備率 · %
- 包装の施工面積 · 1スクエアあたりの束数 / 1包の施工面積
- 100 ft²あたりの束数
- 1包の有効施工面積
- 面積の単位 · cm² / m² / in² / ft² / yd² / エーカー / ハ
- 1包の価格（任意）







**計算・処理の参考資料** [GAF · Bundle coverage per roofing square](<https://www.gaf.com/en-us/blog/your-home/how-many-bundles-of-shingles-are-in-a-square---63a47862-f7e1-4e73-abcf-8d09917a8b8d>)



[ZooChief](<https://docs.toolpony.com/ja/about/>) · [結果の問題を報告](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fja%2Fguides%2Froofing-calculator%2F>)

[ドキュメント](https://docs.toolpony.com/ja/guides/roofing-calculator/)
