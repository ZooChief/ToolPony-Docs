# タイムゾーン変換の使い方



IANA タイムゾーンまたは固定 UTC オフセット間で日時を変換します。





## 例



### 入力



```
2026-01-15 09:00, Asia/Shanghai → America/New_York
```



### 期待される結果



```
2026-01-14 20:00:00
```





<a id="case-study"></a>



## 繰り返す時刻の会議



1. 2026年11月1日、ニューヨークでは 01:30 が2回あります。上海では1回目が 13:30、2回目が 14:30 です。招待に合う方の UTC 時刻をコピーします。都市を入れ替えても会議の瞬間は同じです。



[入力例を実行](<https://toolpony.com/ja/tools/time-zone-converter/#example-repeated-meeting>)





## 11月のハバナとの通話



2026年11月のキューバは UTC−04:00 です。11月23日のハバナ 09:00 は 13:00 UTC に当たります。現地時刻で予定を決めるときは America/Havana を選ぶと、その日の規則が適用されます。



[入力例を実行](<https://toolpony.com/ja/tools/time-zone-converter/#example-havana-clock>)







## 時計が30分進む日



2026年10月4日、ロードハウ島では 01:59:59 の次が 02:30:00 です。02:15 を入力すると、30分前の 01:45 または30分後の 02:45 を選べます。後者は UTC で10月3日 15:45 です。



[入力例を実行](<https://toolpony.com/ja/tools/time-zone-converter/#example-half-hour-change>)







## 試してみる

[ツール全体を開く · タイムゾーン変換](<https://toolpony.com/ja/tools/time-zone-converter/>)





## 計算方法



現地時刻には選んだ日の IANA 規則を使います。繰り返す時刻には2つの UTC 時刻があり、時計が進むと間の時刻が飛びます。固定オフセットは一定です。



$$
T_{\rm target}=T_{\rm source}-O_{\rm source}+O_{\rm target}
$$







## 計算モード





### IANA



- 日付
- 現地時刻
- 元の IANA タイムゾーン
- 変換先の IANA タイムゾーン
- 重複する時間帯 · 早い方 / 遅い方







### 固定 UTC オフセット



- 日付
- 現地時刻
- 元の UTC オフセット
- 変換先の UTC オフセット







**計算・処理の参考資料** [IANA · Time Zone Database](<https://www.iana.org/time-zones>)



[ZooChief](<https://docs.toolpony.com/ja/about/>) · [結果の問題を報告](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fja%2Fguides%2Ftime-zone-converter%2F>)

[ドキュメント](https://docs.toolpony.com/ja/guides/time-zone-converter/)
