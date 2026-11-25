# QR コード生成の使い方



読み取り時に開く種類を選び、リンクやテキスト、必要項目を入力します。 入力に合わせてコードが更新されます。Wi-Fi や連絡先は内容を確認してから PNG または SVG を保存できます。 濃い色を選ぶか、6桁の HEX 色を入力します。どちらの出力でも白い余白が残ります。





## 使い方



1. 読み取り時に開く種類を選び、リンクやテキスト、必要項目を入力します。
2. 入力に合わせてコードが更新されます。Wi-Fi や連絡先は内容を確認してから PNG または SVG を保存できます。
3. 濃い色を選ぶか、6桁の HEX 色を入力します。どちらの出力でも白い余白が残ります。







## 例



### 入力



```
https://example.com/ · M · 512 px
```



### 期待される結果



```
PNG · 512 × 512 px → https://example.com/
```







## 試してみる

[ツール全体を開く · QR コード生成](<https://toolpony.com/ja/tools/qr-code-generator/>)





## 制限



静的 QR は入力した内容を直接格納します。UTF-8 で最大 2,048 バイトで、高い誤り訂正では容量が減ります。白い余白は 4 モジュールです。Wi-Fi QR には入力したパスワードが含まれます。





**計算・処理の参考資料** [DENSO WAVE · QR error correction](<https://www.qrcode.com/en/about/error_correction.html>)



[ZooChief](<https://docs.toolpony.com/ja/about/>) · [結果の問題を報告](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fja%2Fguides%2Fqr-code-generator%2F>)

[ドキュメント](https://docs.toolpony.com/ja/guides/qr-code-generator/)
