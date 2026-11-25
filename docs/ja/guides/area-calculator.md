# 面積計算機の使い方



混合入力ユニットと選択可能な出力ユニットを備えた11のモードで、平面形状の領域を検索します。





## 例



### 入力



```
長方形 4 m × 3 m
```



### 期待される結果



```
12 m²
```





<a id="case-study"></a>



## 穴のある円板の面積と切断長



1. 外径60 mm、穴径40 mmの平パッキンなら、外半径30 mmと内半径20 mmを入力し、面積の単位にmm²を選びます。
2. 材料の面積は500π mm²（約1,570.80 mm²）。両方の円を切る長さは100π mm（約314.16 mm）です。各円周と元の寸法を出力できます。



[入力例を実行](<https://toolpony.com/ja/tools/area-calculator/#example-gasket>)





## 試してみる

[ツール全体を開く · 面積計算機](<https://toolpony.com/ja/tools/area-calculator/>)





## 計算方法



計算前にサイズをメーターに変換します。 三面三角形はヘロンの式を使用しています。 あるセクターは、半径の角の半倍の二乗半径を使用している。



$$
A_{\mathrm{rectangle}}=lw,\qquad A_{\mathrm{sector}}=\tfrac12 r^2\theta
$$



$$
A_{\mathrm{triangle}}=\sqrt{s(s-a)(s-b)(s-c)},\quad s=\tfrac12(a+b+c)
$$







## 計算モード





### 長方形



- 長さ
- 長さの単位
- 幅
- 幅の単位
- エリアユニット







### スクエア



- 辺の長さ
- 辺の長さの単位
- エリアユニット







### 三角形・三面



- 第一面
- ファーストサイドユニット
- 第二側
- 第二側ユニット
- 第三の側
- 三面ユニット
- エリアユニット







### 三角形・ベースと高さ



- 底辺の長さ
- 底辺の単位
- 多年性身長
- パーペンディキュラー高ユニット
- エリアユニット







### 台形



- 第一平行側
- ファーストパラレルサイドユニット
- 第二平行側
- 第二平行側ユニット
- 多年性身長
- パーペンディキュラー高ユニット
- エリアユニット







### 円



- 半径
- 半径ユニット
- エリアユニット







### 循環型セクター



- 半径
- 半径ユニット
- 中央の角度
- 角度の単位 · 度 / ラジアン
- エリアユニット







### 楕円



- 第1の半軸
- 第1の半軸ユニット
- 第二半軸
- 第2半軸ユニット
- エリアユニット







### 平行項目



- 底辺の長さ
- 底辺の単位
- 多年性身長
- パーペンディキュラー高ユニット
- エリアユニット







### 円環



- 外半径
- 外半径単位
- 内半径
- 内半径単位
- エリアユニット







### 通常のポリゴン



- 辺の長さ
- 辺の長さの単位
- 辺の数
- エリアユニット







**計算・処理の参考資料** [BIPM · SI](<https://www.bipm.org/en/publications/si-brochure>) · [NIST DLMF · Lengths of plane curves](<https://dlmf.nist.gov/19.30>)



[ZooChief](<https://docs.toolpony.com/ja/about/>) · [結果の問題を報告](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fja%2Fguides%2Farea-calculator%2F>)

[ドキュメント](https://docs.toolpony.com/ja/guides/area-calculator/)
