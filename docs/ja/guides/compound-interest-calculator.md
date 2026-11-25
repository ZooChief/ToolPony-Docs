# 複利計算機の使い方



繰り返しの寄与とインフレとのバランスを図ること、または複利周波数を変換すること。





## 例



### 入力



```
元金 10,000、年利 5%、10 年間
```



### 期待される結果



```
16,288.95
```





<a id="case-study"></a>



## 30 か月の積立を比較



1. 元本 10,000 に毎月 100 を 2 年 6 か月積み立てます。名目年率 6% の月複利で月末に入金すると残高は 14,842.00、拠出総額は 13,000 です。月初入金なら 14,858.14 です。年 3% のインフレで月末入金の残高を現在価値に直すと 13,784.77 です。





## 試してみる

[ツール全体を開く · 複利計算機](<https://toolpony.com/ja/tools/compound-interest-calculator/#example-30-months>)





## 計算方法



持続的な複結合による有効な年間成長率は(1+r/m)^m−1、またはexp(r)−1である。 寄付金は、各期間の選択された開始または終了から利息を獲得します。



$$
A=P(1+r/m)^{mt},\qquad \mathrm{APY}=(1+r/m)^m-1
$$







## 計算モード





### 将来の均衡



- 元金
- 年利 · %
- 年
- か月
- 複利頻度
- 定期的貢献
- 貢献頻度 · 年1回 / 半年ごと / 四半期ごと / 毎月 / 月2回 / 2週間ごと / 毎週 / 毎日
- 期間開始時に貢献してください
- 年間インフレ · %







### 同等金利



- 年利 · %
- オリジナルコンパウンディング
- ターゲット複合化







**計算・処理の参考資料** [Investor.gov · Compound Interest](<https://www.investor.gov/financial-tools-calculators/calculators/compound-interest-calculator>)



[ZooChief](<https://docs.toolpony.com/ja/about/>) · [結果の問題を報告](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fja%2Fguides%2Fcompound-interest-calculator%2F>)

[ドキュメント](https://docs.toolpony.com/ja/guides/compound-interest-calculator/)
