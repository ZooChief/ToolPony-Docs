# Base64 のエンコード・デコードの使い方



UTF-8 または 16 進バイトを Base64、Base64url に変換し、復元したバイトを保存できます。





## 例



### 入力



```
hello をエンコード
```



### 期待される結果



```
aGVsbG8=
```





<a id="case-study"></a>



## Base64url からバイト列を復元



1. デコード、URL セーフ、16 進バイトを選び \_wCA7w を貼り付けます。結果 FF 00 80 EF はゼロバイトと UTF-8 にできない値を含みます。バイト列を保存すると 4 バイトがそのまま残ります。



[入力例を実行](<https://toolpony.com/ja/tools/base64-encoder-decoder/#example-binary-bytes>)





## 試してみる

[ツール全体を開く · Base64 のエンコード・デコード](<https://toolpony.com/ja/tools/base64-encoder-decoder/>)





## 計算方法



標準は + と /、URL 用は - と \_ を使い、URL 用の出力はパディングを省略します。UTF-8 を検証し、先頭の U+FEFF を保持します。上限はテキスト 500,000 UTF-16 単位、バイト列 500,000 バイトです。





**計算・処理の参考資料** [IETF · RFC 4648 (Base64)](<https://www.rfc-editor.org/rfc/rfc4648>) · [IETF · RFC 3629](<https://www.rfc-editor.org/rfc/rfc3629>)



[ZooChief](<https://docs.toolpony.com/ja/about/>) · [結果の問題を報告](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fja%2Fguides%2Fbase64-encoder-decoder%2F>)

[ドキュメント](https://docs.toolpony.com/ja/guides/base64-encoder-decoder/)
