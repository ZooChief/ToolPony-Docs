# 成人の BMI 計算機の使い方



成人のBMIをメートル単位または米国単位で算出し、基準範囲を比較し、BMIプライムおよびポンデラル指数を参照する。





## 例



### 入力



```
70kg、175cm
```



### 期待される結果



```
BMI ≈22.86 kg/m2
```





<a id="case-study"></a>



## BMI 25 の境界を読む



1. 身長180 cm、体重80.99 kgの BMI は約24.997です。81 kgではちょうど25となり、CDC成人分類の次の区分に入ります。境界付近では表示桁数が増えます。



[入力例を実行](<https://toolpony.com/ja/tools/bmi-calculator/#example-bmi-boundary>)





## 試してみる

[ツール全体を開く · 成人の BMI 計算機](<https://toolpony.com/ja/tools/bmi-calculator/>)





## 計算方法



BMI は体重 (kg) ÷ 身長 (m)² です。参照範囲は CDC が定める 20 歳以上の成人向けの区分です。BMI Prime は BMI ÷ 25、ポンデラル指数は体重 (kg) ÷ 身長 (m)³ です。



$$
\operatorname{BMI}=\frac{m_{\mathrm{kg}}}{h_{\mathrm{m}}^2}
$$







## 計算モード





### メートル法



- 年齢
- 体重 · kg
- 身長 · cm







### 米国慣用単位



- 年齢
- 体重 · lb
- 身長（フィート） · ft
- 追加のインチ · in







**計算・処理の参考資料** [CDC · Adult BMI Categories](<https://www.cdc.gov/bmi/adult-calculator/bmi-categories.html>)



[ZooChief](<https://docs.toolpony.com/ja/about/>) · [結果の問題を報告](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fja%2Fguides%2Fbmi-calculator%2F>)

[ドキュメント](https://docs.toolpony.com/ja/guides/bmi-calculator/)
