# Unix 時間戳轉換使用指南



在 Unix 秒、毫秒、微秒、納秒與 UTC 日期之間雙向轉換，保留每一位數字。





## 示例



### 輸入



```
0 秒
```



### 預期結果



```
1970-01-01T00:00:00.000Z
```





<a id="case-study"></a>



## 紀元前一納秒



1. 選擇 ns 並輸入 -1，UTC 時間是 1969-12-31T23:59:59.999999999Z。切換轉換方向可取回原整數。
2. 覈對不同時區的日誌時，1970-01-01T05:44:59.999999999+05:45 也表示這一刻。可以單獨複製某個單位，或把四種單位導出到同一行 CSV。



[運行示例](<https://toolpony.com/zh-hant/tools/unix-timestamp-converter/#example-before-epoch>)





## 試一試

[打開完整工具 · Unix 時間戳轉換](<https://toolpony.com/zh-hant/tools/unix-timestamp-converter/>)





## 計算方法



Unix 時間從 1970-01-01T00:00:00Z 開始計數，忽略閏秒。支持 UTC 1900 至 9999 年，日期須帶時區標記，小數秒最多 9 位。







## 計算模式





### 時間戳轉日期



- Unix 時間戳
- 單位 · 秒 / 毫秒 / 微秒 / 納秒







### 日期轉時間戳



- 帶時區偏移的 ISO 8601
- 單位 · 秒 / 毫秒 / 微秒 / 納秒







**方法來源** [GNU · Seconds since the Epoch](<https://www.gnu.org/software/coreutils/manual/html_node/Seconds-since-the-Epoch.html>) · [IETF · RFC 3339](<https://www.rfc-editor.org/rfc/rfc3339>)



[ZooChief](<https://docs.toolpony.com/zh-hant/about/>) · [反饋結果問題](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fzh-hant%2Fguides%2Funix-timestamp-converter%2F>)

[文檔站](https://docs.toolpony.com/zh-hant/guides/unix-timestamp-converter/)
