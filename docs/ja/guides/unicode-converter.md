# Unicode 変換



テキストをUnicodeコードポイント、UTF-8 六十元バイト、またはUTF-16エスケープに変換し、テキストに復号します。





## 例



### 入力



```
🐴
```



### 期待される結果



```
U+1F434またはF0 9F 90 B4
```







## 試してみる



[ツール全体を開く](<https://toolpony.com/ja/tools/unicode-converter/>)







## 計算方法



コードポイントモードでは補助文字を 1 個の Unicode スカラー値として扱います。UTF-16 では補助文字に 2 個のコード単位を使います。無効なサロゲートの並びや不正な UTF-8 のバイト列はエラーになります。







## 計算モード



**テキストをエンコードする**

- 入力
- エンコーディング · Unicodeコードポイント / UTF-8 の16進バイト列 / JavaScript の UTF-16 エスケープ





**テキストをデコードする**

- 入力
- エンコーディング · Unicodeコードポイント / UTF-8 の16進バイト列 / JavaScript の UTF-16 エスケープ

[ドキュメント](https://docs.toolpony.com/ja/guides/unicode-converter/)
