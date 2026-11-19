# タイムカード計算機



1 週間の勤務と休憩を記録し、丸め・給与ルール・CSV を利用できます。





## 使い方



1. 08:30、8.30、8:30 AM などを入力します。休憩は 00:30 のように時と分で入力します。
2. 丸めと必要な給与ルールを設定し、CSV 保存または印刷を行います。ブラウザーへの下書き保存は任意です。







## 例



### 入力



```
08:30〜17:00、休憩 00:30
```



### 期待される結果



```
08:00:00
```







## 試してみる

[ツール全体を開く · タイムカード計算機](<https://toolpony.com/ja/tools/time-card-calculator/>)





## 計算方法



休憩を引いてから実働時間を丸めます。終了が開始より早ければ翌日です。日別・週別の上限と時給は指定できます。



$$
t_i=(e_i-s_i)\bmod 1440-b_i,\qquad t'_i=q\,\operatorname{round}(t_i/q)\quad(q>0)
$$



$$
P=(t_{\rm base}+m\,t_{\rm overtime})r/60
$$





[ZooChief](<https://docs.toolpony.com/ja/about/>) · [結果の問題を報告](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fja%2Fguides%2Ftime-card-calculator%2F>)

[ドキュメント](https://docs.toolpony.com/ja/guides/time-card-calculator/)
