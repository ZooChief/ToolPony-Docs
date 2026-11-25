# 任意精度計算機の使い方



正確な整数と小数点係数で計算し、分割と根の丸みを選定可能にする。





## 例



### 入力



```
9,007,199,254,740,993 + 7
```



### 期待される結果



```
9007199254741000
```







## 試してみる

[ツール全体を開く · 任意精度計算機](<https://toolpony.com/ja/tools/big-number-calculator/>)





## 計算方法



加算、減算、乗算、整数演算、整数演算はBigInt係数を使用します。 ディビジョンは選択した小数点数までのラウンドです。 角根は切り倒したり、最も近い場所に丸みがたることがあります。 正および負の整数の加算は、結果制限内でサポートされています。



$$
x=m\cdot 10^e,\quad x_1x_2=(m_1m_2)\cdot 10^{e_1+e_2}
$$





[ZooChief](<https://docs.toolpony.com/ja/about/>) · [結果の問題を報告](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fja%2Fguides%2Fbig-number-calculator%2F>)

[ドキュメント](https://docs.toolpony.com/ja/guides/big-number-calculator/)
