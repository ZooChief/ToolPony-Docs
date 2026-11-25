# 基礎代謝量・消費カロリー計算機の使い方



メートル法または米国単位における安静エネルギーおよび日次エネルギー消費量を、3つの方程式で推定する。





## 例



### 入力



```
雄の方程式、30年、70kg、175cm、ミフリン=シュト・ジェオール
```



### 期待される結果



```
静息時は 1,648.75 kcal/日
```





<a id="case-study"></a>



## 除脂肪体重から推定



1. 体重70 kg、体脂肪率を20%と仮定すると除脂肪体重は56 kgです。Katch–McArdle 式では安静時 370 + 21.6 × 56 = 1,579.6 kcal/日になります。
2. 活動係数1.20では1日1,895.52 kcal、1.55では2,448.38 kcalの推定です。安静時の推定値はどちらも同じです。



[入力例を実行](<https://toolpony.com/ja/tools/bmr-calculator/#example-lean-mass>)





## 試してみる

[ツール全体を開く · 基礎代謝量・消費カロリー計算機](<https://toolpony.com/ja/tools/bmr-calculator/>)





## 計算方法



休息エネルギーは、改訂版のハリス・ベネディクト、またはカッチ=マカードルによるミフリン=セント・ジェオールの推定値である。 日々の支出は、活動要因によって推定値を複数上回る。







## 計算モード





### メートル法



- 方程式 · ミフリン=シュト・ジェオル / 改訂版ハリス・ベネディクト / カッチ・マカードル
- 年齢
- 計算式の性別項 · 男性 / 女性
- 体重 · kg
- 身長 · cm
- 体脂肪率 · %
- 活動係数
- エネルギーの単位 · kcal/day / kJ/day







### 米国慣用単位



- 方程式 · ミフリン=シュト・ジェオル / 改訂版ハリス・ベネディクト / カッチ・マカードル
- 年齢
- 計算式の性別項 · 男性 / 女性
- 体重 · lb
- 身長（フィート） · ft
- 追加のインチ · in
- 体脂肪率 · %
- 活動係数
- エネルギーの単位 · kcal/day / kJ/day







**計算・処理の参考資料** [Mifflin et al. (1990)](<https://pubmed.ncbi.nlm.nih.gov/2305711/>) · [Roza &amp; Shizgal (1984)](<https://pubmed.ncbi.nlm.nih.gov/6741850/>) · [Cunningham (1991) · Fat-free mass and resting energy](<https://pubmed.ncbi.nlm.nih.gov/1957828/>) · [NIST · Thermochemical calorie](<https://www.nist.gov/pml/special-publication-811/nist-guide-si-appendix-b-conversion-factors/nist-guide-si-appendix-b8>)



[ZooChief](<https://docs.toolpony.com/ja/about/>) · [結果の問題を報告](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fja%2Fguides%2Fbmr-calculator%2F>)

[ドキュメント](https://docs.toolpony.com/ja/guides/bmr-calculator/)
