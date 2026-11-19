# 公約数計算機



すべての正の共通因子をリストアップし、複数の整数の最大共通係数を算出する。





## 例



### 入力



```
12, 18, 30
```



### 期待される結果



```
1, 2, 3, 6
```







## 試してみる

[ツール全体を開く · 公約数計算機](<https://toolpony.com/ja/tools/common-factor-calculator/>)





## 計算方法



リストの共通要因は、まさにその最も一般的な分割の要因である。 ユークリッドアルゴリズムは、すべての入力の要因を列挙することなく、その分割を検出します。



$$
d\mid a_1,\ldots,a_n\iff d\mid\gcd(a_1,\ldots,a_n)
$$

[ドキュメント](https://docs.toolpony.com/ja/guides/common-factor-calculator/)
