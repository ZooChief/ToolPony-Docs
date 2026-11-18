# 割り算の筆算



整数または小数を割り、数量、残り、10進数、および各長分割ステップを点検してください。





## 例



### 入力



```
12,345 ÷ 67
```



### 期待される結果



```
184 残り 17
```







## 試してみる



[ツール全体を開く](<https://toolpony.com/ja/tools/long-division-calculator/>)







## 計算方法



両方の入力を10の同じ出力でスケールします。 整数の分配はゼロに向かって切り、署名した残りは配当=量的×配当+残りを満たす。 ステップテーブルは絶対大きさを使用します。



$$
a=bq+r,\quad q=\operatorname{trunc}(a/b),\quad |r|<|b|
$$

[ドキュメント](https://docs.toolpony.com/ja/guides/long-division-calculator/)
