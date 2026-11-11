# JSON 格式化



粘貼 JSON，選擇縮進後格式化或壓縮。可複製結果或下載 JSON 文件，也可以按 Cmd/Ctrl + Enter 執行。





## 開始使用



1. 粘貼 JSON 文檔。
2. 選擇兩個或四個空格後格式化；需要緊湊結果時選擇壓縮。
3. 複製結果或下載 JSON 文件。







## 示例



### 輸入



```
{"name":"ToolPony","ready":true}
```



### 預期結果



```
{
  "name": "ToolPony",
  "ready": true
}
```







## 試一試



[打開完整工具](<https://toolpony.com/zh-hant/tools/json-formatter/>)







## 使用提示



鍵名和字符串需要雙引號。JSON 不允許註釋和尾隨逗號；工具會拒絕超出安全精度的數字，避免靜默改寫數值。







## 適用範圍



最大 1 MB。拒絕無效 JSON 和超出安全精度的數字；不執行應用級 schema 校驗。

[文檔站](https://docs.toolpony.com/zh-hant/guides/json-formatter/)
