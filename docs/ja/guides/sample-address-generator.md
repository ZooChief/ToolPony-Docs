# サンプル住所生成の使い方



18 の国・地域のテスト住所を、地域選択と現地の書式で生成し、一括で保存します。





## 使い方



1. 国・地域と行政区を選び、件数と連絡先の有無を設定します。
2. 同じ設定とシードで同じ結果を再現できます。項目を個別にコピーするか、TXT、CSV、JSON で保存します。
3. 「端末に保存」を選ぶと住所のサンプルはこのブラウザに残ります。ツールで削除できます。







## 例



### 入力



```
ドイツ · ベルリン · シード pony-demo
```



### 期待される結果



```
Testperson 001
Beispielstraße 4957
10115 Berlin
Deutschland
```





<a id="case-study"></a>



## カナダの部屋番号付き住所を確認



1. オンタリオ州を選び、シード label-review で部屋番号付き・連絡先なしのテスト住所を2件生成します。同じ設定で同じ2件を再現できます。
2. テキストでは、部屋番号と番地がこの順でハイフンでつながります。市名の行では ON と郵便番号の間は半角スペース2つです。JSONには各項目も個別に入ります。



[入力例を実行](<https://toolpony.com/ja/tools/sample-address-generator/#example-canadian-label>)





## 試してみる

[ツール全体を開く · サンプル住所生成](<https://toolpony.com/ja/tools/sample-address-generator/>)





## 計算方法



一度に最大 100 件です。地名と郵便番号は書式例で、番地と宛名は合成データです。電話は予約番号か伏字で表示します。フォームやソフトウェアのテストに使えます。





**計算・処理の参考資料** [USPS · Publication 28, §213](<https://pe.usps.com/text/pub28/28c2_003.htm>) · [Canada Post · Civic address](<https://www.canadapost-postescanada.ca/cpc/en/support/articles/addressing-guidelines/civic-address.page>)



[ZooChief](<https://docs.toolpony.com/ja/about/>) · [結果の問題を報告](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fja%2Fguides%2Fsample-address-generator%2F>)

[ドキュメント](https://docs.toolpony.com/ja/guides/sample-address-generator/)
