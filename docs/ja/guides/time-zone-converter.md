# タイムゾーン変換



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







## 試してみる

[ツール全体を開く · タイムゾーン変換](<https://toolpony.com/ja/tools/time-zone-converter/>)





## 計算方法



IANA はブラウザーのルールを使います。重複時刻には 2 つの候補があり、飛ばされた時刻には候補がありません。固定 UTC オフセットは年間一定です。



$$
T_{\rm target}=T_{\rm source}-O_{\rm source}+O_{\rm target}
$$







## 計算モード



**IANA**

- 日付
- 現地時刻
- 元の IANA タイムゾーン
- 変換先の IANA タイムゾーン
- 重複する時間帯 · 早い方 / 遅い方





**固定 UTC オフセット**

- 日付
- 現地時刻
- 元の UTC オフセット
- 変換先の UTC オフセット







**計算・処理の参考資料** [IANA · Time Zone Database](<https://www.iana.org/time-zones>)



[ZooChief](<https://docs.toolpony.com/ja/about/>) · [結果の問題を報告](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fja%2Fguides%2Ftime-zone-converter%2F>)

[ドキュメント](https://docs.toolpony.com/ja/guides/time-zone-converter/)
