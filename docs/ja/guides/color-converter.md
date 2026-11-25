# 色変換の使い方



CSS 色を HEX、RGB、HSL、OKLCH に変換。透明度と広色域の sRGB 代替色を確認できます。





## 例



### 入力



```
rgb(102, 51, 153)
```



### 期待される結果



```
#663399、hsl(270 50% 40%)
```





<a id="case-study"></a>



## 広色域色の sRGB 代替色を用意する



1. color(display-p3 0 1 0 / 70%) を貼り付けます。この緑は sRGB の外にあります。元の色と代替色の見本を比べると、変換後の HEX は \#00FB29B3 です。
2. RGB 行をコピーすると不透明度 0.7 を保てます。8 桁 HEX では B3、つまり 179/255 です。



[入力例を実行](<https://toolpony.com/ja/tools/color-converter/#example-wide-gamut>)





## 試してみる

[ツール全体を開く · 色変換](<https://toolpony.com/ja/tools/color-converter/>)





## 計算方法



HEX は sRGB の値を 8 ビットに丸めます。色域外は OKLCH の彩度方向にマッピングし、入力プレビューは元の色空間を保持します。





**計算・処理の参考資料** [W3C · CSS Color 4](<https://www.w3.org/TR/css-color-4/>)



[ZooChief](<https://docs.toolpony.com/ja/about/>) · [結果の問題を報告](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fja%2Fguides%2Fcolor-converter%2F>)

[ドキュメント](https://docs.toolpony.com/ja/guides/color-converter/)
