# Unicode 変換の使い方



Unicode のコードポイント、UTF-8 バイト、JavaScript エスケープを変換し、文字と正規化形式を比較します。





## 例



### 入力



```
🐴
```



### 期待される結果



```
U+1F434またはF0 9F 90 B4
```





<a id="case-study"></a>



## 同じ見た目の é を比較



1. e、結合アクセント U+0301、空白、🐴 を調べます。元は書記素クラスタ 3、コードポイント 4、UTF-16 単位 5、UTF-8 は 8 バイト。NFC では U+00E9 に合成され 7 バイトになります。🐴 は 1 コードポイントで UTF-16 は 2 単位です。



[入力例を実行](<https://toolpony.com/ja/tools/unicode-converter/#example-combining-accent>)





## 試してみる

[ツール全体を開く · Unicode 変換](<https://toolpony.com/ja/tools/unicode-converter/>)





## 計算方法



コードポイントモードでは補助文字を 1 個の Unicode スカラー値として扱います。UTF-16 では補助文字に 2 個のコード単位を使います。無効なサロゲートの並びや不正な UTF-8 のバイト列はエラーになります。







## 計算モード





### テキストをエンコードする



- 入力
- エンコーディング · Unicodeコードポイント / UTF-8 の16進バイト列 / JavaScript の UTF-16 エスケープ / JavaScript コードポイントエスケープ







### テキストをデコードする



- 入力
- エンコーディング · Unicodeコードポイント / UTF-8 の16進バイト列 / JavaScript の UTF-16 エスケープ / JavaScript コードポイントエスケープ







### 文字を調べる



- 入力
- 正規化 · 原文 / NFC / NFD / NFKC / NFKD







**計算・処理の参考資料** [IETF · RFC 3629](<https://www.rfc-editor.org/rfc/rfc3629>) · [Unicode · UAX \#15](<https://www.unicode.org/reports/tr15/>)



[ZooChief](<https://docs.toolpony.com/ja/about/>) · [結果の問題を報告](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fja%2Fguides%2Funicode-converter%2F>)

[ドキュメント](https://docs.toolpony.com/ja/guides/unicode-converter/)
