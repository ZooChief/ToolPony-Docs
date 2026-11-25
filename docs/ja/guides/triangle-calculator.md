# 三角形計算機の使い方



三つの既知の値から三角形の角、高さ、中線、円の中心を求めます。





## 使い方



1. 辺を一つ以上含む三つの値を入力してください。
2. π/2 のような入力ではラジアンを選びます。SSA では鋭角とその補角の両方で三角形ができる場合があります。
3. 座標表では A が原点、B が x 軸の正の方向にあります。選択中の表を CSV で保存できます。







## 例



### 入力



```
a = 7、b = 10、A = 30°
```



### 期待される結果



```
二つの解があり、c は約 13.55923 と 3.76127 です。
```





<a id="case-study"></a>



## 同じ測定値から2つの三角形ができる場合



1. a = 7、b = 10、A = 30°とします。辺aは角Aの対辺です。頂点は2か所に置けるため、cは約13.56または3.76になります。2つの図と寸法を比べてください。
2. aを5にすると b × sin A と一致し、直角三角形が1つだけできます。5より短いと三角形はできません。角度表でラジアンと度分秒も確認できます。



[入力例を実行](<https://toolpony.com/ja/tools/triangle-calculator/#example-two-triangles>)





## 試してみる

[ツール全体を開く · 三角形計算機](<https://toolpony.com/ja/tools/triangle-calculator/>)





## 計算方法



辺の単位を統一します。辺 a は角 A の向かい側です。b/B、c/C も同様です。角だけでは大きさは決まりません。



$$
\frac{a}{\sin A}=\frac{b}{\sin B}=\frac{c}{\sin C},\qquad a^2=b^2+c^2-2bc\cos A
$$



$$
\Delta=\sqrt{s(s-a)(s-b)(s-c)},\quad s=\tfrac{a+b+c}{2},\quad h_a=2\Delta/a
$$



$$
m_a=\tfrac12\sqrt{2b^2+2c^2-a^2},\qquad r=\Delta/s,\qquad R=abc/(4\Delta)
$$







## 計算モード





### 既知の値



- 辺 a
- 辺 b
- 辺 c
- 角 A
- 角 B
- 角 C
- 角度の単位 · 度 / ラジアン







### 三辺（SSS）



- 辺 a
- 辺 b
- 辺 c







### 二辺とその間の角（SAS）



- 辺 b
- 辺 c
- 角 A · °







### 二角と一辺（ASA / AAS）



- 角 A · °
- 角 B · °
- 既知の辺 · a / b / c
- 辺







### 二辺と一方の対角（SSA）



- 辺 a
- 辺 b
- 角 A · °







### 直角を挟む二辺



- 辺 a
- 辺 b







**計算・処理の参考資料** [MathWorld · Law of sines](<https://mathworld.wolfram.com/LawofSines.html>)



[ZooChief](<https://docs.toolpony.com/ja/about/>) · [結果の問題を報告](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fja%2Fguides%2Ftriangle-calculator%2F>)

[ドキュメント](https://docs.toolpony.com/ja/guides/triangle-calculator/)
