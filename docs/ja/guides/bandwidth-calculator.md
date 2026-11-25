# 帯域幅計算機の使い方



ファイルサイズ、リンク速度、プロトコル効率から転送時間を推定します。





## 例



### 入力



```
100Mbpsで1GB、高効率100%
```



### 期待される結果



```
80秒
```







## 試してみる

[ツール全体を開く · 帯域幅計算機](<https://toolpony.com/ja/tools/bandwidth-calculator/>)





## 計算方法



転送秒数はファイルのバイト数 × 8 ÷ 実効ビット毎秒です。1 MB/s は毎秒 1,000,000 バイト、1 MiB/s は毎秒 1,048,576 バイトです。効率を考慮して実効速度を求めます。





**計算・処理の参考資料** [NIST · Binary prefixes](<https://physics.nist.gov/cuu/Units/binary.html>)



[ZooChief](<https://docs.toolpony.com/ja/about/>) · [結果の問題を報告](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fja%2Fguides%2Fbandwidth-calculator%2F>)

[ドキュメント](https://docs.toolpony.com/ja/guides/bandwidth-calculator/)
