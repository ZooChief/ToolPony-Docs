# 文字数・単語数カウンターの使い方



テキストを入力・貼り付けるか、テキストや選択可能な文字のある PDF を読み込みます。 1〜3 語の頻出語句と出現割合を確認し、CSV に保存します。 DOCX と ODT も読み込めます。文書の本文を集計します。 SRTとWebVTTを読み込むと時刻と書式を除き、せりふだけを数えます。





## 使い方



1. テキストを入力・貼り付けるか、テキストや選択可能な文字のある PDF を読み込みます。
2. 1〜3 語の頻出語句と出現割合を確認し、CSV に保存します。
3. DOCX と ODT も読み込めます。文書の本文を集計します。
4. SRTとWebVTTを読み込むと時刻と書式を除き、せりふだけを数えます。







## 例



### 入力



```
青い空 青い空
```



### 期待される結果



```
4 語、異なる単語 2 語
```







## 試してみる

[ツール全体を開く · 文字数・単語数カウンター](<https://toolpony.com/ja/tools/word-counter/>)





## 制限



集計するテキストは UTF-8 換算で最大 1 MiB。単語分割はブラウザーの言語規則に従います。語句は句読点や改行をまたぎません。分母はその長さで数えた全語句です。





[ZooChief](<https://docs.toolpony.com/ja/about/>) · [結果の問題を報告](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fja%2Fguides%2Fword-counter%2F>)

[ドキュメント](https://docs.toolpony.com/ja/guides/word-counter/)
