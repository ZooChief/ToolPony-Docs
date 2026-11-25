# パスワード生成の使い方



文字セット、カスタム除外、およびオプションの固有の文字を使用して、ローカルでパスワードを生成します。





## 例



### 入力



```
20 文字、4 種類の文字グループ
```



### 期待される結果



```
新しいランダムなパスワード
```





<a id="case-study"></a>



## 手入力用テストコード



1. 英大文字と数字で16文字のコードを6件生成します。除外欄に 2Z5S8B を入れ、印刷時に見分けにくい3組を外します。
2. 各行に英字と数字が含まれ、同じ行内で文字は重複しません。1行をコピーして入力フォームを試せます。例を開き直すと新しく生成されます。



[入力例を実行](<https://toolpony.com/ja/tools/password-generator/#example-readable-codes>)





## 試してみる

[ツール全体を開く · パスワード生成](<https://toolpony.com/ja/tools/password-generator/>)





## 計算方法



Web Cryptoはランダム性を実現します。 必要なグループが有効になると、各グループから1つの文字が選択され、その後、位置がシャッフルされます。 パスワードは、あなたが退出または消去するまで、現在のページに存在します。





**計算・処理の参考資料** [W3C · Web Cryptography](<https://www.w3.org/TR/WebCryptoAPI/#Crypto-method-getRandomValues>)



[ZooChief](<https://docs.toolpony.com/ja/about/>) · [結果の問題を報告](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fja%2Fguides%2Fpassword-generator%2F>)

[ドキュメント](https://docs.toolpony.com/ja/guides/password-generator/)
