# 画像形式変換



形式の異なる画像を一括追加できます。ファイルの内容から形式を判別します。 画像ごとに出力形式、画質、背景を設定し、個別または ZIP で保存します。





## 使い方



1. 形式の異なる画像を一括追加できます。ファイルの内容から形式を判別します。
2. 画像ごとに出力形式、画質、背景を設定し、個別または ZIP で保存します。







## 例



### 入力



```
PNG · 64 × 32 px (四隅が透明) → JPEG · 白い背景
```

[例 · PNG](<https://toolpony.com/samples/toolpony-64x32.png>)

### 期待される結果



```
JPEG · 64 × 32 px (四隅が白)
```





<a id="case-study"></a>



## 透明 PNG を JPEG で送る前に背景を確かめる



1. 空の変換画面で「サンプルファイルで試す」を選びます。64 × 32 px の透明 PNG と白背景の JPEG が入り、それぞれ JPEG と PNG が出力先になります。
2. 変換後に各サムネイルを押して出力を確認します。最初の JPEG の四隅は白く、JPEG から作った PNG の四隅も不透明です。元の透明部分を残すには、最初の画像の出力を PNG、背景を透明にします。
3. 横長の画像では行に表示される出力寸法を確認します。10,000 × 100 px は同比率で 8,192 × 82 px になります。画質設定はエンコード品質に作用します。
4. 画素を確かめるにはサンプル JPEG をカラーピッカーで開き、(0, 0) を調べます。Chromium では RGBA (255, 255, 243, 255) でした。同じ JPEG から出力した PNG でもこの値が保たれ、最後の 255 は完全な不透明を示します。



[画像から色を抽出](<https://toolpony.com/ja/tools/image-color-picker/>)





## 試してみる

[ツール全体を開く · 画像形式変換](<https://toolpony.com/ja/tools/image-converter/>)





## 制限



入力は最大 20 MB・2400 万画素、出力は一辺 8192 px まで。AVIF の読み込みはブラウザーに依存します。アニメーションは静止画になり、元のメタデータは削除されます。 1 バッチ最大 12 枚、合計 64 MiB。



透明部分を残すには PNG を、写真や互換性を優先する場合は JPEG を選びます。JPEG は透明部分を選択した背景色で塗りつぶします。WebP は透明度と画質調整に対応します。AVIF はブラウザがエンコードに対応している場合に選べます。



たとえば、透明部分のある WebP ロゴは透明な PNG に変換できます。JPEG 専用のフォームには白い背景で出力できます。JPEG を PNG に変換すると、元画像で見える細部が保たれます。





**計算・処理の参考資料** [W3C · PNG](<https://www.w3.org/TR/png-3/>) · [WHATWG · HTML Canvas](<https://html.spec.whatwg.org/multipage/canvas.html#dom-canvas-toblob-dev>)



[ZooChief](<https://docs.toolpony.com/ja/about/>) · [結果の問題を報告](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fja%2Fguides%2Fimage-converter%2F>)

[ドキュメント](https://docs.toolpony.com/ja/guides/image-converter/)
