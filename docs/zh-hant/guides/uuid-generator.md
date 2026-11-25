# UUID 生成器使用指南



使用瀏覽器的安全隨機源生成第 4 版 UUID。





## 示例



### 輸入



```
生成 1 個標識符
```



### 預期結果



```
格式示例：550e8400-e29b-41d4-a716-446655440000
```





<a id="case-study"></a>



## 爲導入文件準備 27 個 ID



1. 生成 27 個大寫 UUID。每個標識符的第三段以 4 開頭，第四段以 8、9、A 或 B 開頭。
2. 最後一頁是第 25 至 27 行。可以複製第 27 行覈對單條記錄，也可以下載文本文件，一次導入原順序的全部 27 行。



[運行示例](<https://toolpony.com/zh-hant/tools/uuid-generator/#example-import-ids>)





## 試一試

[打開完整工具 · UUID 生成器](<https://toolpony.com/zh-hant/tools/uuid-generator/>)





## 計算方法



第 4 版 UUID 使用 122 個隨機位，另有 6 位用於版本和變體。每批最多 500 個。





**方法來源** [IETF · RFC 9562 (UUID)](<https://www.rfc-editor.org/rfc/rfc9562>)



[ZooChief](<https://docs.toolpony.com/zh-hant/about/>) · [反饋結果問題](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fzh-hant%2Fguides%2Fuuid-generator%2F>)

[文檔站](https://docs.toolpony.com/zh-hant/guides/uuid-generator/)
