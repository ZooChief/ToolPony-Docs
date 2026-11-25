# URL 編碼與解碼使用指南



編碼或解碼 URL、組件和表單值，也可按順序編輯查詢參數，保留同名參數與空值。





## 示例



### 輸入



```
編碼組件：a+b & c
```



### 預期結果



```
a%2Bb%20%26%20c
```





<a id="case-study"></a>



## 保留搜索詞裏的加號



1. 用表單值模式編碼 C++ &amp; tea，結果是 C%2B%2B+%26+tea。原有加號寫成 %2B，空格寫成 +，&amp; 寫成 %26。反向轉換可還原原文；切換到 URI 組件模式，空格會寫成 %20。
2. 在“查詢參數”中打開含兩個 tag 的案例，把第二個值改爲 UI &amp; UX。首個 tag、空值與 \#filters 都會保留，改過的值會寫成 UI+%26+UX。



[運行示例](<https://toolpony.com/zh-hant/tools/url-encoder-decoder/#example-query-plus>)





## 試一試

[打開完整工具 · URL 編碼與解碼](<https://toolpony.com/zh-hant/tools/url-encoder-decoder/>)





## 計算方法



組件會轉義保留分隔符，完整 URL 保留分隔符，表單值以 + 表示空格。編輯查詢參數時，參數名和值分別按表單規則編碼，路徑和片段保留。





**方法來源** [IETF · RFC 3986](<https://www.rfc-editor.org/rfc/rfc3986>) · [WHATWG · Form encoding](<https://url.spec.whatwg.org/#application/x-www-form-urlencoded>)



[ZooChief](<https://docs.toolpony.com/zh-hant/about/>) · [反饋結果問題](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fzh-hant%2Fguides%2Furl-encoder-decoder%2F>)

[文檔站](https://docs.toolpony.com/zh-hant/guides/url-encoder-decoder/)
