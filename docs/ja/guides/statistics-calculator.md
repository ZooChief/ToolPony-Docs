# 統計計算機



平均、中央値、モード、四分位数、および個体数とサンプル分散を持つデータセットを要約する。





## 例



### 入力



```
2, 4, 4, 6, 9
```



### 期待される結果



```
平均5、中央値4
```







## 試してみる

[ツール全体を開く · 統計計算機](<https://toolpony.com/ja/tools/statistics-calculator/>)





## 計算方法



四分位数は(n−1)pで線形補間を使用する。 人口分散はnで、サンプルの分散はn−1で分割される。 カンマまたは空白で区切られた最大1,000の値を入力してください。



$$
\bar x=\frac{1}{n}\sum_{i=1}^{n} x_i,\qquad s=\sqrt{\frac{\sum_i(x_i-\bar x)^2}{n-1}}
$$



$$
\operatorname{SE}(\bar x)=\frac{s}{\sqrt n},\qquad \bar x\pm z\operatorname{SE}(\bar x)
$$



集団のサブセットに対してサンプル標準偏差を使用し、完全な集合に対して個体群標準偏差を算出する。 信頼表は、いくつかの信頼レベルにおける平均の通常の近似値を示しています。







## 計算モード



**データセットの概要**

- 値





**標準偏差のサンプル**

- 値





**人口標準偏差**

- 値

[ドキュメント](https://docs.toolpony.com/ja/guides/statistics-calculator/)
