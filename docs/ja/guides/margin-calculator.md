# 利益率と値入率の使い方



粗利率と原価への上乗せ率を比較し、最低売価や仕入上限を0.01単位で確認します。





## 例



### 入力



```
料金60、価格100
```



### 期待される結果



```
40%のマージン;66.67%のマークアップ
```





<a id="case-study"></a>



## 粗利率 34% を満たす価格



1. 原価 10.00 なら理論価格は 10 ÷ 0.66 ≈ 15.1515 です。15.15 では粗利率 34% を下回るため、0.01 単位の最低価格は 15.16 です。この価格では粗利 5.16、粗利率は約 34.04% です。





## 12%の上乗せを満たす見積額



原価17.20に12%上乗せすると19.264です。19.26では約11.98%、19.27なら約12.03%になります。売価に対する粗利率を12%にするなら最低価格は19.55です。



[入力例を実行](<https://toolpony.com/ja/tools/margin-calculator/#example-markup-quote>)







## 仕入原価の上限を決める



売価20.01、目標粗利率30%なら原価上限は14.007です。0.01単位で14.00なら達成し、14.01では30%を下回ります。



[入力例を実行](<https://toolpony.com/ja/tools/margin-calculator/#example-cost-ceiling>)







## 試してみる

[ツール全体を開く · 利益率と値入率](<https://toolpony.com/ja/tools/margin-calculator/#example-cent-price>)





## 計算方法



粗利益は売価と原価の差です。粗利率は売価を、上乗せ率は原価を分母にします。0.01単位で最低売価は切り上げ、仕入上限は切り捨てます。







## 計算モード





### コストと価格



- コスト
- 販売価格







### 目標マージンでの価格



- コスト
- 目標マージン · %







### 原価への上乗せで値付け



- コスト
- 原価への上乗せ率 · %







### 価格と粗利率から原価を計算



- 販売価格
- 目標マージン · %







**計算・処理の参考資料** [BDC · Gross margin](<https://www.bdc.ca/en/articles-tools/entrepreneur-toolkit/templates-business-guides/glossary/gross-margin>)



[ZooChief](<https://docs.toolpony.com/ja/about/>) · [結果の問題を報告](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fja%2Fguides%2Fmargin-calculator%2F>)

[ドキュメント](https://docs.toolpony.com/ja/guides/margin-calculator/)
