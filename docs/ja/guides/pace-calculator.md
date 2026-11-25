# ランニングペース計算機の使い方



ペース、時間、距離を解く。 分割ペースを比較し、単位を変換し、終了時刻を推定します。





## 例



### 入力



```
10 km を 00:50:00 で走行
```



### 期待される結果



```
05:00/km、12 km/h
```





<a id="case-study"></a>



## 2つの通過タイムを確認



1. 1 km 地点で 3:25、2 km 地点で 6:55 と時計に表示されました。累計を選ぶと第2区間は 3:30、全体の平均は 3:27.5/km です。
2. 4:00:00 のマラソンで 1 km ごとに計画すると、最後の区間は195 mです。この区間を含む最終通過タイムは 4:00:00 です。



[入力例を実行](<https://toolpony.com/ja/tools/pace-calculator/#example-watch-checkpoints>)





## 試してみる

[ツール全体を開く · ランニングペース計算機](<https://toolpony.com/ja/tools/pace-calculator/>)





## 計算方法



平均ペースは合計時間を総距離で割ります。2欄の時刻は分・秒、3欄は時・分・秒です。実測100区間または一定ペースの通過予定500件に対応します。



$$
p=\frac{t}{d},\qquad v=\frac{d}{t}
$$







## 計算モード





### ペースとフィニッシュタイム



- 距離
- 距離の単位 · km / mi / m / yd
- 経過時間
- ペースの基準距離 · km / mi / 100 m / 100 yd
- 目標距離 · 5km / 10km / ハーフマラソン / マラソン / 距離を指定 (km)
- 任意のレース距離 · km







### 所要時間を求める



- 距離
- 距離の単位 · km / mi / m / yd
- ペース（分:秒）
- ペースの基準距離 · km / mi / 100 m / 100 yd







### 距離を求める



- 経過時間
- ペース（分:秒）
- ペースの基準距離 · km / mi / 100 m / 100 yd







### ペースの単位換算



- ペース（分:秒）
- ペースの基準距離 · km / mi / 100 m / 100 yd







### 区間タイムを比較



- 区間記録
- 距離の単位 · km / mi / m / yd
- ペースの基準距離 · km / mi / 100 m / 100 yd
- 各行は累計の距離と時間







### 通過タイム表



- 目標距離 · 5km / 10km / ハーフマラソン / マラソン / 距離を指定 (km)
- 任意のレース距離 · km
- 目標フィニッシュタイム
- 計測間隔 · 1 km / 1 mi / 400 m / 100 m / 5km / 10km
- ペースの基準距離 · km / mi / 100 m / 100 yd







**計算・処理の参考資料** [World Athletics · Marathon](<https://worldathletics.org/disciplines/road-running-event/marathon>) · [NIST · Unit conversion factors](<https://www.nist.gov/pml/special-publication-811/nist-guide-si-appendix-b-conversion-factors/nist-guide-si-appendix-b8>)



[ZooChief](<https://docs.toolpony.com/ja/about/>) · [結果の問題を報告](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fja%2Fguides%2Fpace-calculator%2F>)

[ドキュメント](https://docs.toolpony.com/ja/guides/pace-calculator/)
