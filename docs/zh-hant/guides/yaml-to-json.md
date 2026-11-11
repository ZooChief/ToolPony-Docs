# YAML 轉 JSON



粘貼 YAML 文檔，一鍵轉換爲排版整齊的 JSON。映射使用字符串鍵，結果可複製或下載。





## 開始使用



1. 粘貼一份 YAML 文檔，映射鍵應爲字符串。
2. 轉換爲 JSON。
3. 檢查結果，然後複製或下載。







## 示例



### 輸入



```
name: ToolPony
ready: true
```



### 預期結果



```
{
  "name": "ToolPony",
  "ready": true
}
```







## 試一試



[打開完整工具](<https://toolpony.com/zh-hant/tools/yaml-to-json/>)







## 使用提示



不支持多文檔、自定義標籤、循環別名，以及 JSON 無法表達的值。若某個值應當是字符串而非布爾值或數字，請使用引號。







## 適用範圍



最大 1 MB。不支持自定義標籤、多文檔、非字符串鍵、過量別名、循環結構或無法被 JSON 保真的值。

[文檔站](https://docs.toolpony.com/zh-hant/guides/yaml-to-json/)
