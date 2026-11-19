# 順列・組み合わせ計算機



繰り返しの有無にかかわらず、注文済みおよび未順序の選択を正確に計算します。





## 例



### 入力



```
n=10、r=3、繰り返しなし
```



### 期待される結果



```
720回の変数;120個の組み合わせ
```







## 試してみる

[ツール全体を開く · 順列・組み合わせ計算機](<https://toolpony.com/ja/tools/permutation-combination-calculator/>)





## 計算方法



繰り返しなしでは、nPr = n!/(n−r)! および nCr = nPr/r! を繰り返しない。 繰り返しの場合、順序選択はnrであり、順序のない選択は C(n+r−1,r である。





[ZooChief](<https://docs.toolpony.com/ja/about/>) · [結果の問題を報告](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fja%2Fguides%2Fpermutation-combination-calculator%2F>)

[ドキュメント](https://docs.toolpony.com/ja/guides/permutation-combination-calculator/)
