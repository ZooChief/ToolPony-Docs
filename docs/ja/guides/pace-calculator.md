# ランニングペース計算機



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







## 試してみる

[ツール全体を開く · ランニングペース計算機](<https://toolpony.com/ja/tools/pace-calculator/>)





## 計算方法



ペースは距離で割りられた時間です。 フィニッシュタイムは一定のペースを推定する。 分割列は選択した距離単位を使用し、最大100行まで受け付けます。



$$
p=\frac{t}{d},\qquad v=\frac{d}{t}
$$







## 計算モード



**ペースと終了時間を見つけましょう**

- 距離
- 距離ユニット · km / ミー / m / yd
- 時間の失速(hh:mm:ss)
- ペースの距離単位 · km / ミー / 100 m / 100 yd
- 目標距離 · 5km / 10km / ハーフマラソン / マラソン / カスタムkm
- カスタムレース距離 · km





**使用時間を確認してください**

- 距離
- 距離ユニット · km / ミー / m / yd
- ペース（分:秒）
- ペースの距離単位 · km / ミー / 100 m / 100 yd





**距離を見つける**

- 時間の失速(hh:mm:ss)
- ペース（分:秒）
- ペースの距離単位 · km / ミー / 100 m / 100 yd





**ペース単位を変換**

- ペース（分:秒）
- ペースの距離単位 · km / ミー / 100 m / 100 yd





**分割を比較する**

- 距離、1列あたりの所要時間
- 距離ユニット · km / ミー / m / yd
- ペースの距離単位 · km / ミー / 100 m / 100 yd
- 行は累積チェックポイントです







[ZooChief](<https://docs.toolpony.com/ja/about/>) · [結果の問題を報告](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fja%2Fguides%2Fpace-calculator%2F>)

[ドキュメント](https://docs.toolpony.com/ja/guides/pace-calculator/)
