# コントラストチェッカーの使い方



単色や半透明の背景で文字と UI のコントラストを確認し、WCAG 基準に適合する文字色を試せます。





## 例



### 入力



```
#FFFFFF 上の #000000
```



### 期待される結果



```
21:1
```





<a id="case-study"></a>



## 白背景の本文で AA を満たすグレーを選ぶ



1. 白背景に \#777777 の例を試します。比率は約 4.48:1 です。小数点以下 1 桁では 4.5 に見えても、丸める前の値で判定するので通常サイズの本文は WCAG AA に届きません。
2. 同じ白背景で \#767676 を試すと約 4.54:1 となり、通常サイズでも AA を満たします。どちらも大きな文字の 3:1 の基準は満たします。
3. デザインに実際に表示される文字と背景の色を調べてください。画像や半透明レイヤーの上では、背景とのコントラストが最も弱い箇所の合成後の色を採取します。判定の対象は入力した 2 色です。
4. 白の上に \#00000080 を置くと、合成後は \#7F7F7F で約 4.00:1。提案色 \#767676 なら通常文字で 4.54:1 です。



[入力例を実行](<https://toolpony.com/ja/tools/contrast-checker/#example-translucent-text>)





## 試してみる

[ツール全体を開く · コントラストチェッカー](<https://toolpony.com/ja/tools/contrast-checker/>)





## 計算方法



コントラスト比は (明るい色の輝度 + 0.05) を (暗い色の輝度 + 0.05) で割った値です。判定には丸め前の値を使います。通常の文字は AA が 4.5:1、AAA が 7:1、大きな文字は AA が 3:1、AAA が 4.5:1 です。





**計算・処理の参考資料** [W3C · WCAG 2.2 (1.4.3, AA)](<https://www.w3.org/WAI/WCAG22/Understanding/contrast-minimum.html>) · [W3C · WCAG 2.2 (1.4.6, AAA)](<https://www.w3.org/WAI/WCAG22/Understanding/contrast-enhanced.html>) · [W3C · Non-text contrast](<https://www.w3.org/WAI/WCAG22/Understanding/non-text-contrast.html>) · [W3C · Source-over compositing](<https://www.w3.org/TR/compositing-1/#simplealphacompositing>)



[ZooChief](<https://docs.toolpony.com/ja/about/>) · [結果の問題を報告](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fja%2Fguides%2Fcontrast-checker%2F>)

[ドキュメント](https://docs.toolpony.com/ja/guides/contrast-checker/)
