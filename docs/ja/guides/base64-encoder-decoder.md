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



[ツール全体を開く](<https://toolpony.com/ja/tools/base64-encoder-decoder/>)







## 計算方法



テキストは UTF-8 として変換します。URL セーフモードでは「-」と「\_」を使い、出力のパディングを省きます。入力は最大 500,000 文字です。

[ドキュメント](https://docs.toolpony.com/ja/guides/base64-encoder-decoder/)
