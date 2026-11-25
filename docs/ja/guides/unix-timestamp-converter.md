# Unix タイムスタンプ変換の使い方



Unix 秒・ミリ秒・マイクロ秒・ナノ秒と UTC 日時を桁落ちなく相互変換します。





## 例



### 入力



```
0秒
```



### 期待される結果



```
1970-01-01T00:00:00.000Z
```





<a id="case-study"></a>



## 起点の1ナノ秒前



1. ns を選び -1 と入力すると UTC は 1969-12-31T23:59:59.999999999Z です。方向を切り替えると同じ整数に戻ります。
2. 1970-01-01T05:44:59.999999999+05:45 も同じ瞬間です。単位ごとの値をコピーするか、4単位を CSV の1行に書き出せます。



[入力例を実行](<https://toolpony.com/ja/tools/unix-timestamp-converter/#example-before-epoch>)





## 試してみる

[ツール全体を開く · Unix タイムスタンプ変換](<https://toolpony.com/ja/tools/unix-timestamp-converter/>)





## 計算方法



Unix 時間は 1970-01-01T00:00:00Z を起点とし、うるう秒を数えません。UTC 1900〜9999 年に対応し、日時には時差と小数秒9桁までを指定できます。







## 計算モード





### タイムスタンプ → 日時



- Unix タイムスタンプ
- 単位 · 秒 / ミリ秒 / マイクロ秒 / ナノ秒







### 日時 → タイムスタンプ



- UTC オフセット付き日時 (ISO 8601)
- 単位 · 秒 / ミリ秒 / マイクロ秒 / ナノ秒







**計算・処理の参考資料** [GNU · Seconds since the Epoch](<https://www.gnu.org/software/coreutils/manual/html_node/Seconds-since-the-Epoch.html>) · [IETF · RFC 3339](<https://www.rfc-editor.org/rfc/rfc3339>)



[ZooChief](<https://docs.toolpony.com/ja/about/>) · [結果の問題を報告](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fja%2Fguides%2Funix-timestamp-converter%2F>)

[ドキュメント](https://docs.toolpony.com/ja/guides/unix-timestamp-converter/)
