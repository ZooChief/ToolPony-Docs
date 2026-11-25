# 数値の丸め計算機の使い方



小数小数から10進数、または9つの丸型モードを持つバイナリー率で、正確な小数を算出します。





## 例



### 入力



```
−2.5 を一の位に丸める、ちょうど中間は偶数へ
```



### 期待される結果



```
−2
```







## 試してみる

[ツール全体を開く · 数値の丸め計算機](<https://toolpony.com/ja/tools/rounding-calculator/>)





## 計算方法



残りの正確な小数点を半歩で比較してください。 関係については、方向または均衡ルールを選択してください。 最寄りのはゼロから離れた場所にネクタイを使用しています。



$$
x=qs+r,\qquad 0\le r<s,\qquad r=\tfrac{s}{2}\text{ at a tie}
$$



桁数が 2 なら小数第 2 位、0 なら一の位、−2 なら百の位に丸めます。分数刻みでは 1/4 や 1/16 などの倍数に丸めます。



ハーフ・トゥ・イブンは、まったく同じタイでのみ複数選択する。 たとえば、−2.5は−2に、−3.5は−4に進む。 天井は常に正の無限へと向かう。





[ZooChief](<https://docs.toolpony.com/ja/about/>) · [結果の問題を報告](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fja%2Fguides%2Frounding-calculator%2F>)

[ドキュメント](https://docs.toolpony.com/ja/guides/rounding-calculator/)
