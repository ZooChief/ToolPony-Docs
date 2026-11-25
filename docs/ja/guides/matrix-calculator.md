# 行列計算機の使い方



分数と小数を正確に扱い、連立方程式、行列式、逆行列、階数や行列演算を計算します。表計算のセルを貼り付け、結果を出力できます。





## 例



### 入力



```
A = [2, 4; 1, 3], B = [1, −2; 4, 5]
```



### 期待される結果



```
A + B = [3, 2; 5, 8]
```





<a id="case-study"></a>



## 2種類の箱の個数



1. 小箱には黒いクリップが2個と白が1個、大箱には黒が3個と白が2個入ります。合計は黒17個、白10個です。A の列を各箱の内訳、B を合計にすると小箱4箱、大箱3箱と分かります。A × X で合計を確認できます。



[入力例を実行](<https://toolpony.com/ja/tools/matrix-calculator/#example-packing-matrix>)





## 行列式がちょうど 1



対角線の積は 10 億の2乗、もう一方の積は (10 億 − 1)(10 億 + 1) です。差はちょうど 1 なので、数値が似ていても2行は線形独立です。



[入力例を実行](<https://toolpony.com/ja/tools/matrix-calculator/#example-determinant-one>)







## 2個の自由変数



2本目の式は1本目の2倍です。x + y + z = 4 では y、z を自由に選び、x = 4 − y − z とします。特殊解 (4, 0, 0) に零空間の2方向を足せます。2つ目の合計を 8 から 9 にすると矛盾が現れます。



[入力例を実行](<https://toolpony.com/ja/tools/matrix-calculator/#example-free-variables>)







## 試してみる

[ツール全体を開く · 行列計算機](<https://toolpony.com/ja/tools/matrix-calculator/>)





## 計算方法



行基本変形は有理数で厳密に計算します。ピボット列の数が階数です。A × X = B で左辺がすべてゼロの行に非ゼロの右辺があれば、その右辺に解はありません。自由列は特殊解に加えられる方向を決めます。



$$
(AB)_{ij}=\sum_{k=1}^{n}A_{ik}B_{kj},\qquad A^{-1}A=I
$$



$$
[A\mid B]\longrightarrow[I\mid X]\quad\Rightarrow\quad AX=B
$$







## 計算モード





### A+Bを追加



- マトリックスA
- マトリックスB







### A−Bを差し引く



- マトリックスA
- マトリックスB







### A × B を計算



- マトリックスA
- マトリックスB







### A × X = B を解く



- マトリックスA
- マトリックスB







### 決定者



- マトリックスA







### 逆



- マトリックスA







### 転置



- マトリックスA







### 整数パワー



- マトリックスA
- 指数







### スカラーの乗算



- マトリックスA
- スカラー







### ランク付けと短縮された列の形



- マトリックスA







**計算・処理の参考資料** [MIT OpenCourseWare · Solving Ax = b](<https://ocw.mit.edu/courses/18-06sc-linear-algebra-fall-2011/resources/solving-ax-b-row-reduced-form-r/>)



[ZooChief](<https://docs.toolpony.com/ja/about/>) · [結果の問題を報告](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fja%2Fguides%2Fmatrix-calculator%2F>)

[ドキュメント](https://docs.toolpony.com/ja/guides/matrix-calculator/)
