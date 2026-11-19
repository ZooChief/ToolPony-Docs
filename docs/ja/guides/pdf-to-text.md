# PDF からテキストへ



選択可能な文字を端末内で抽出し、TXT または JSON に保存します。





## 使い方



1. テキストを選択できる PDF を開きます。
2. ページ順を指定して抽出します。TXT を保存するか、元のページ番号付きの JSON を保存します。







## 例



### 入力



```
最初の 2 ページが「One」「Two」の PDF、選択 2, 1
```

[例 · PDF](<https://toolpony.com/samples/toolpony-pages.pdf>)

### 期待される結果



```
JSON：2 ページ目が Two、次に 1 ページ目が One
```





<a id="case-study"></a>



## 文字と画像が混在する PDF で抽出できないページを見つける



1. 混在サンプルの 1 ページ目には「Order 417」、2 ページ目には青い見本画像だけ、3 ページ目には「Total 42」があります。単独のツールで混在 PDF の例を選ぶと、3、2、1 の順と JSON 出力が設定されます。
2. 抽出結果の先頭は 3 ページの「Total 42」、中央は text が空の 2 ページ、最後は 1 ページの「Order 417」です。文字がないページとして元のページ番号 2 も表示されます。
3. 自分のファイルを他のシステムに取り込む前に、表示されたページを確認してください。図は画像のまま保存できます。印刷文字のスキャンからは OCR で文字層を作成します。



[PDF を JPG・PNG に変換](<https://toolpony.com/ja/tools/pdf-to-jpg/>)



[toolpony-mixed-pages.pdf](<https://toolpony.com/samples/toolpony-mixed-pages.pdf>)





## 試してみる

[ツール全体を開く · PDF からテキストへ](<https://toolpony.com/ja/tools/pdf-to-text/>)





## 制限



最大 30 MB、300 ページ、200 万文字、20 万テキスト要素。PDF 内部のテキスト順を使用します。スキャン文書には OCR が必要です。暗号化 PDF は対象外です。



スキャンが読めるのに抽出できない場合は、PDF ビューアーで単語を選択してみてください。写真だけのページには OCR でテキスト層を追加します。文字と画像が混在する文書では、JSON の空の text 欄と元のページ番号から対象ページを特定できます。





**計算・処理の参考資料** [PDF Association · ISO 32000-2](<https://pdfa.org/resource/iso-32000-2/>) · [Adobe · PDF / OCR](<https://helpx.adobe.com/acrobat/desktop/create-documents/scan-documents-to-pdfs/recognize-text.html>)



[ZooChief](<https://docs.toolpony.com/ja/about/>) · [結果の問題を報告](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fja%2Fguides%2Fpdf-to-text%2F>)

[ドキュメント](https://docs.toolpony.com/ja/guides/pdf-to-text/)
