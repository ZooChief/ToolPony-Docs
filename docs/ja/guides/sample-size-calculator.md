# サンプルサイズ計算機



最小調査サンプルを検索するか、有限人口補正による誤差範囲を推定してください。





## 例



### 入力



```
95%の信頼感、4%のマージン、35%の割合、N = 1,000
```



### 期待される結果



```
354件のサンプル
```







## 試してみる

[ツール全体を開く · サンプルサイズ計算機](<https://toolpony.com/ja/tools/sample-size-calculator/>)





## 計算方法



初期サイズは z2p(1−p)/e2 です。 有限集団の場合、そのサイズを1 +(初期サイズ−1)/N で分割し、丸める。 誤差計算は、同じ割合と有限人口モデルを使用します。



$$
n_0=\frac{z^2p(1-p)}{e^2},\qquad n=\left\lceil\frac{n_0}{1+(n_0-1)/N}\right\rceil
$$







## 計算モード



**サンプルサイズを探す**

- 信頼水準 · %
- 誤差範囲 · %
- 人口の割合 · %
- 人口規模(無制限)





**誤差範囲を探す**

- 信頼水準 · %
- サンプルサイズ
- 人口の割合 · %
- 人口規模(無制限)







[ZooChief](<https://docs.toolpony.com/ja/about/>) · [結果の問題を報告](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fja%2Fguides%2Fsample-size-calculator%2F>)

[ドキュメント](https://docs.toolpony.com/ja/guides/sample-size-calculator/)
