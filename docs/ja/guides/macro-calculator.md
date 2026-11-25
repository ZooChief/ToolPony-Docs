# 三大栄養素計算機の使い方



カロリー目標と栄養比をグラムに変換するか、またはグラムからエネルギーと比率を計算する。





## 例



### 入力



```
2,000kcal:タンパク質25%、炭水化物45%、脂肪30%
```



### 期待される結果



```
たんぱく質125g、炭水化物225g、脂質66.67g
```





<a id="case-study"></a>



## レシピを3食に分ける



1. レシピ全体にたんぱく質30 g、炭水化物60 g、脂質10 gを入力します。4/4/9の一般換算係数で450 kcalです。3等分すると1食150 kcalで、各10 g、20 g、約3.33 gになります。
2. 包装食品の表示では食物繊維や糖アルコールに別の換算係数を使う場合があり、同じグラム数でもエネルギーが変わります。



[入力例を実行](<https://toolpony.com/ja/tools/macro-calculator/#example-three-servings>)





## 試してみる

[ツール全体を開く · 三大栄養素計算機](<https://toolpony.com/ja/tools/macro-calculator/>)





## 計算方法



一般換算係数はたんぱく質・炭水化物が4 kcal/g、脂質が9 kcal/gです。割合を1つ空欄にすると合計100%まで補います。均等な食数で各栄養素とエネルギーを割ります。







## 計算モード





### エネルギーからグラムへ



- 総エネルギー · kcal
- たんぱく質 · %
- 炭水化物 · %
- 脂質 · %
- 残りを割り当てる項目 · 空欄から判定 / 手動 / たんぱく質 / 炭水化物 / 脂質
- 食数







### グラムからエネルギーへ



- たんぱく質 · g
- 炭水化物 · g
- 脂質 · g
- 食数







**計算・処理の参考資料** [21 CFR 101.9(c)(1) · General energy factors](<https://www.ecfr.gov/current/title-21/chapter-I/subchapter-B/part-101/subpart-A/section-101.9>)



[ZooChief](<https://docs.toolpony.com/ja/about/>) · [結果の問題を報告](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fja%2Fguides%2Fmacro-calculator%2F>)

[ドキュメント](https://docs.toolpony.com/ja/guides/macro-calculator/)
