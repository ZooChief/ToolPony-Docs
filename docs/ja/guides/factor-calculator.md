# 約数計算機



すべての正のディバイザー、すべての因子ペア、および素因数をリストアップしてください。





## 例



### 入力



```
120
```



### 期待される結果



```
1および120を含む16の正のディビジョン
```







## 試してみる



[ツール全体を開く](<https://toolpony.com/ja/tools/factor-calculator/>)







## 計算方法



分割器は残りをゼロで分割する。 各小さなディバイザーはn/dとペアを組んで、最大で検索するとすべてのペアが見つかる。



$$
d\mid n\iff n\bmod d=0,\qquad n=d\cdot(n/d)
$$

[ドキュメント](https://docs.toolpony.com/ja/guides/factor-calculator/)
