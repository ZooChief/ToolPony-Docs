# URL のエンコード・デコードの使い方



URL とフォーム値を変換し、同名や空値を含むクエリパラメーターを順番どおりに編集できます。





## 例



### 入力



```
エンコードコンポーネント: A+b および c
```



### 期待される結果



```
a%2Bb%20%26%20c
```





<a id="case-study"></a>



## 検索語のプラス記号を保つ



1. C++ &amp; tea をフォーム値として変換すると C%2B%2B+%26+tea です。元の + は %2B、空白は +、&amp; は %26 になります。逆変換で元に戻せます。URI 要素では空白は %20 です。
2. クエリパラメーターで tag が 2 つある例を開き、2 番目を UI &amp; UX に変更します。最初の tag、空値、\#filters は残り、変更値は UI+%26+UX になります。



[入力例を実行](<https://toolpony.com/ja/tools/url-encoder-decoder/#example-query-plus>)





## 試してみる

[ツール全体を開く · URL のエンコード・デコード](<https://toolpony.com/ja/tools/url-encoder-decoder/>)





## 計算方法



URI 要素は区切りをエスケープし、URL 全体は区切りを保持します。フォームでは空白は + です。クエリ編集では各名前と値を個別に変換し、パスとフラグメントを保持します。





**計算・処理の参考資料** [IETF · RFC 3986](<https://www.rfc-editor.org/rfc/rfc3986>) · [WHATWG · Form encoding](<https://url.spec.whatwg.org/#application/x-www-form-urlencoded>)



[ZooChief](<https://docs.toolpony.com/ja/about/>) · [結果の問題を報告](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fja%2Fguides%2Furl-encoder-decoder%2F>)

[ドキュメント](https://docs.toolpony.com/ja/guides/url-encoder-decoder/)
