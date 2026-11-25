# 確率計算機の使い方



事象の確率や度数表から条件付き確率を比較し、独立事象、反復試行、正規分布の範囲を計算します。





## 例



### 入力



```
独立種事象A = 0.31、B = 0.56
```



### 期待される結果



```
少なくとも 1 回は 0.6964
```





<a id="case-study"></a>



## 2回の講座の出席状況



1. 50人のうち両方に参加したのは18人、午前（AM）のみ12人、午後（PM）のみ6人、どちらも欠席は14人です。午後の24人のうち午前にも参加した人は18人で75%。午前の30人のうち午後も参加した人は18人で60%です。



[入力例を実行](<https://toolpony.com/ja/tools/probability-calculator/#example-workshop-attendance>)





## 試してみる

[ツール全体を開く · 確率計算機](<https://toolpony.com/ja/tools/probability-calculator/>)





## 計算方法



和事象は2つの周辺確率の和から積事象を引きます。B の中で A の割合は P(A ∩ B) / P(B) です。独立なら積事象は周辺確率の積です。



$$
P(A\cup B)=P(A)+P(B)-P(A\cap B)
$$



$$
P(A\cap B)=P(A)P(B)\quad\text{(independent)}
$$







## 計算モード





### 2つの独立したイベント



- Aの確率
- Bの確率







### 既知の交差点



- 入力方法 · 確率 / 観測度数
- Aの確率
- Bの確率
- 両方のイベント
- 事象 A の名前
- 事象 B の名前
- A ∩ B
- A ∩ ¬B
- ¬A ∩ B
- ¬A ∩ ¬B







### 独立したイベントを復旧



- 最初に確認した量 · Aの確率 / Bの確率 / いいえA / Bではない / 両方のイベント / 少なくとも1つのイベント / まさに一つの出来事 / どちらの出来事も
- 第一確率
- 第二既知の量 · Aの確率 / Bの確率 / いいえA / Bではない / 両方のイベント / 少なくとも1つのイベント / まさに一つの出来事 / どちらの出来事も
- 第二確率







### 繰り返される独立した試験



- Aの確率
- Aの試練
- Bの確率
- Bの試練







### 通常の分布間隔



- 平均
- 標準偏差
- 下限
- 上限







**計算・処理の参考資料** [OpenStax · Contingency Tables](<https://openstax.org/books/introductory-statistics-2e/pages/3-4-contingency-tables>)



[ZooChief](<https://docs.toolpony.com/ja/about/>) · [結果の問題を報告](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fja%2Fguides%2Fprobability-calculator%2F>)

[ドキュメント](https://docs.toolpony.com/ja/guides/probability-calculator/)
