# グラフ作成の使い方



見出し・項目名の列・数値の列を含む CSV を貼り付けます。棒グラフか折れ線グラフを選び、SVG で保存できます。





## 使い方



1. CSVヘッダーを入力してください。 最初の列にカテゴリラベルを、残りの列に数値系列を配置してください。
2. 棒グラフか折れ線グラフを選びます。データを編集するとグラフに反映されます。
3. グラフをSVGとしてダウンロードしてください。







## 例



### 入力



```
Month,Visits
Jan,24
Feb,38
```



### 期待される結果



```
1月と2月の2つの価値観が左から右へとプロットされた。
```







## 試してみる

[ツール全体を開く · グラフ作成](<https://toolpony.com/ja/tools/chart-maker/>)





## 注意点



カンマを含む名言表示のラベル。 期間を小数列区切りとして使用してください。 負の値は、正の値と同じスケールを使用します。







## 制限



最大 120 行、数値系列は 6 本までです。引用符で囲んだセルにはカンマを含められます。1 行ずつ入力すると、入力順に描画します。





[ZooChief](<https://docs.toolpony.com/ja/about/>) · [結果の問題を報告](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fja%2Fguides%2Fchart-maker%2F>)

[ドキュメント](https://docs.toolpony.com/ja/guides/chart-maker/)
