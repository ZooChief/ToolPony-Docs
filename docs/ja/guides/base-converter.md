# 進数変換・計算機の使い方



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





<a id="case-study"></a>



## 長い16進数の ID を読む



1. 0x20\_0000\_0000\_0001 を10進数にすると、末尾の 1 を保った 9007199254740993 になります。基数を交換したり、2進数を区切りなしでコピーしたりできます。



[入力例を実行](<https://toolpony.com/ja/tools/base-converter/#example-large-hex-id>)





## 試してみる

[ツール全体を開く · 進数変換・計算機](<https://toolpony.com/ja/tools/base-converter/>)





## 計算方法



整数は全桁を保持します。基数変換は最大4,096ビット、演算は各オペランド256桁までです。整数除算はゼロ方向に丸めます。桁の間に空白やアンダースコアを入れられます。







## 計算モード





### 変換ベース



- 整数
- 入力ベース
- 出力ベース
- 最小出力桁







### 整数算術



- 最初の整数
- 第二整数
- 入力ベース
- 出力ベース
- 最小出力桁
- 演算 · 追加 / 控除 / 多量に / 分割 / 余り / AND / OR / XOR







[ZooChief](<https://docs.toolpony.com/ja/about/>) · [結果の問題を報告](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fja%2Fguides%2Fbase-converter%2F>)

[ドキュメント](https://docs.toolpony.com/ja/guides/base-converter/)
