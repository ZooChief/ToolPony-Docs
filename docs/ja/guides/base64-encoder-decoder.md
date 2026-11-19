# Base64 のエンコード・デコード



UTF-8テキストを標準またはURLセーフなBase64としてエンコードし、デコードされたテキストを検証してください。





## 例



### 入力



```
hello をエンコード
```



### 期待される結果



```
aGVsbG8=
```







## 試してみる

[ツール全体を開く · Base64 のエンコード・デコード](<https://toolpony.com/ja/tools/base64-encoder-decoder/>)





## 計算方法



テキストは UTF-8 として変換します。URL セーフモードでは「-」と「\_」を使い、出力のパディングを省きます。入力は最大 500,000 文字です。





**計算・処理の参考資料** [IETF · RFC 4648 (Base64)](<https://www.rfc-editor.org/rfc/rfc4648>)



[ZooChief](<https://docs.toolpony.com/ja/about/>) · [結果の問題を報告](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fja%2Fguides%2Fbase64-encoder-decoder%2F>)

[ドキュメント](https://docs.toolpony.com/ja/guides/base64-encoder-decoder/)
