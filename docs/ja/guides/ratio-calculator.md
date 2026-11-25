# 比の計算機の使い方



比例の未知項や分数の倍率を求め、画像の縦横比を保った余白と切り取り量を計算します。





## 例



### 入力



```
3:4 = x:20
```



### 期待される結果



```
x=15
```





<a id="case-study"></a>



## 横長画像をポスターに収める



1. 1920 × 1080 の画像を 1200 × 900 の枠に入れます。幅で倍率が 5/8 に決まり、画像は 1200 × 675 になります。縦の余白は計225ピクセル、中央配置で上下112.5ピクセルずつです。



[入力例を実行](<https://toolpony.com/ja/tools/ratio-calculator/#example-fit-poster>)





## 同じ枠を余白なく埋める



ポスターを埋めるには高さに合わせます。倍率 5/6 で 1600 × 900 になり、中央に置くと左右から200ピクセルずつ切り取ります。



[入力例を実行](<https://toolpony.com/ja/tools/ratio-calculator/#example-fill-poster>)







## 試してみる

[ツール全体を開く · 比の計算機](<https://toolpony.com/ja/tools/ratio-calculator/>)





## 計算方法



分母が0でなければ A:B = C:D で A × D = B × C です。枠に収める場合は幅と高さの倍率の小さい方、埋める場合は大きい方を使います。余白と切り取りは各軸の合計です。







## 計算モード





### 割合を解く



- A
- B
- C
- D







### 簡素化またはスケーリング



- 初項
- 第二期
- スケールファクター







### 比率を拡大または縮小する



- 初項
- 第二期
- 変更方法 · 倍率 / 枠に収める / 埋めて切り抜く
- 方向 · 削減 / 拡大
- 係数
- 枠の幅
- 枠の高さ







**計算・処理の参考資料** [W3C · Object fitting](<https://www.w3.org/TR/css-images-3/#the-object-fit>)



[ZooChief](<https://docs.toolpony.com/ja/about/>) · [結果の問題を報告](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fja%2Fguides%2Fratio-calculator%2F>)

[ドキュメント](https://docs.toolpony.com/ja/guides/ratio-calculator/)
