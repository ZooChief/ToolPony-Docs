# UUID 生成の使い方



ブラウザの安全な乱数源でバージョン 4 の UUID を生成します。





## 例



### 入力



```
識別子を 1 件生成
```



### 期待される結果



```
形式例 550e8400-e29b-41d4-a716-446655440000
```





<a id="case-study"></a>



## インポート用に27件のIDを用意



1. 大文字のUUIDを27件生成します。第3グループの先頭は4、第4グループは8、9、A、Bのいずれかです。
2. 最終ページは25～27行目です。27行目をコピーして1件を確認するか、テキストをダウンロードして全27行を元の順で取り込めます。



[入力例を実行](<https://toolpony.com/ja/tools/uuid-generator/#example-import-ids>)





## 試してみる

[ツール全体を開く · UUID 生成](<https://toolpony.com/ja/tools/uuid-generator/>)





## 計算方法



バージョン 4 の UUID では 122 ビットがランダムで、6 ビットはバージョンとバリアント用です。一度に 500 件まで生成できます。





**計算・処理の参考資料** [IETF · RFC 9562 (UUID)](<https://www.rfc-editor.org/rfc/rfc9562>)



[ZooChief](<https://docs.toolpony.com/ja/about/>) · [結果の問題を報告](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fja%2Fguides%2Fuuid-generator%2F>)

[ドキュメント](https://docs.toolpony.com/ja/guides/uuid-generator/)
