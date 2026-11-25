# 信頼区間計算機の使い方



観測値や要約統計から平均の z または t 区間を求め、割合には Wilson 区間を計算します。





## 例



### 入力



```
n = 36、平均56、標準偏差8、99%
```



### 期待される結果



```
56 ± 3.434
```





<a id="case-study"></a>



## 5回の測定から区間を推定



1. 48、49、50、51、52 の平均は50です。標本標準偏差を使うと自由度は4で、平均の95% t 信頼区間は約48.04〜51.96です。観測の独立性と母集団の近似正規性を仮定します。



[入力例を実行](<https://toolpony.com/ja/tools/confidence-interval-calculator/#example-five-measurements>)





## 30個を調べて不良0個



独立に30個を調べて不良は0個でした。不良率の95% Wilson 区間は0%から約11.35%です。不良0のまま標本を増やすと区間は狭くなります。



[入力例を実行](<https://toolpony.com/ja/tools/confidence-interval-calculator/#example-no-failures>)







## 試してみる

[ツール全体を開く · 信頼区間計算機](<https://toolpony.com/ja/tools/confidence-interval-calculator/>)





## 計算方法



平均の誤差幅は臨界値 × 標準偏差 / √n です。母標準偏差が既知なら z、標本標準偏差なら自由度 n − 1 の t を使います。Wilson 区間は二項試行の成功数と試行数から割合を推定します。



$$
\bar{x}\pm z_{1-\alpha/2}\frac{s}{\sqrt n}
$$



$$
\frac{\widehat{p}+z^2/(2n)\pm z\sqrt{\widehat{p}(1-\widehat{p})/n+z^2/(4n^2)}}{1+z^2/n}
$$







## 計算モード





### 平均の区間



- データの種類 · 母標準偏差 σ / 標本偏差 s / 観測値
- サンプルサイズ
- 平均
- 標準偏差
- 観測値
- 信頼水準 · %







### ウィルソンの比例間隔



- サンプルサイズ
- 成功例
- 信頼水準 · %







**計算・処理の参考資料** [NIST · Confidence limits for the mean](<https://www.itl.nist.gov/div898/handbook/eda/section3/eda352.htm>) · [NIST · Confidence limits for a proportion](<https://www.itl.nist.gov/div898/handbook/prc/section2/prc241.htm>)



[ZooChief](<https://docs.toolpony.com/ja/about/>) · [結果の問題を報告](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fja%2Fguides%2Fconfidence-interval-calculator%2F>)

[ドキュメント](https://docs.toolpony.com/ja/guides/confidence-interval-calculator/)
