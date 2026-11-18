# 信頼区間計算機



一定の割合で通常の平均間隔またはウィルソン間隔を推定する。





## 例



### 入力



```
n = 36、平均56、標準偏差8、99%
```



### 期待される結果



```
56 ± 3.434
```







## 試してみる



[ツール全体を開く](<https://toolpony.com/ja/tools/confidence-interval-calculator/>)







## 計算方法



通常のマージンは、標準誤差s/√nの倍数です。 ウィルソンのスコア間隔は、プロポーションの中央と幅を調整し、引き続き\[0,1\]の範囲内にとどめます。



$$
\bar{x}\pm z_{1-\alpha/2}\frac{s}{\sqrt n}
$$



$$
\frac{\widehat{p}+z^2/(2n)\pm z\sqrt{\widehat{p}(1-\widehat{p})/n+z^2/(4n^2)}}{1+z^2/n}
$$







## 計算モード



**通常の平均間隔**

- サンプルサイズ
- 平均
- 標準偏差
- 信頼水準 · %





**ウィルソンの比例間隔**

- サンプルサイズ
- 成功例
- 信頼水準 · %

[ドキュメント](https://docs.toolpony.com/ja/guides/confidence-interval-calculator/)
