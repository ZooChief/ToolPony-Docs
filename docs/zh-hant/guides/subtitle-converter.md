# 字幕轉換與時軸



互轉 SRT 與 WebVTT，偏移或縮放時軸，並在導出前檢查重疊字幕。





## 開始使用



1. 粘貼字幕文本或導入 SRT 或 VTT 文件，再選擇導出格式。
2. 正偏移會延後字幕。縮放先從錨點算相對時間，乘上比例後再加偏移。下載前可檢查裁切和重疊。







## 示例



### 輸入



```
1
00:00:00,120 --> 00:00:01,400
A line
Second line

2
00:00:01,350 --> 00:00:02,700
Overlap 50 ms
```



### 預期結果



```
WEBVTT

00:00:00.120 --> 00:00:01.400
A line
Second line

00:00:01.350 --> 00:00:02.700
Overlap 50 ms
```







## 試一試



[打開完整工具](<https://toolpony.com/zh-hant/tools/subtitle-converter/>)







## 適用範圍



最多 1 MiB 文本、10,000 條字幕。結束在零點前的字幕會被移除，跨零點的字幕從零開始。SRT 無法表達所有 WebVTT 位置、樣式和編號。

[文檔站](https://docs.toolpony.com/zh-hant/guides/subtitle-converter/)
