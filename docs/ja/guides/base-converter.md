# 進数変換・計算機



2〜36塩基間で符号付き整数を変換し、正確な算術演算、残り演算、またはビットワイズ演算を実行します。





## 例



### 入力



```
FF、ベース16からベース10
```



### 期待される結果



```
255
```







## 試してみる

[ツール全体を開く · 進数変換・計算機](<https://toolpony.com/ja/tools/base-converter/>)





## 計算方法



BigIntは整数の精度を保持しています。 分断はゼロに向かって傾いている。 ビットワイズ演算では、署名されたBigIntセマンティクスを使用します。 各通信番号は256桁に制限されています。







## 計算モード



**変換ベース**

- 整数
- 入力ベース
- 出力ベース
- 最小出力桁





**整数算術**

- 最初の整数
- 第二整数
- 入力ベース
- 出力ベース
- 最小出力桁
- 演算 · 追加 / 控除 / 多量に / 分割 / 余り / AND / OR / XOR







[ZooChief](<https://docs.toolpony.com/ja/about/>) · [結果の問題を報告](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fja%2Fguides%2Fbase-converter%2F>)

[ドキュメント](https://docs.toolpony.com/ja/guides/base-converter/)
