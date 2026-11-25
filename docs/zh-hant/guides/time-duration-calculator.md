# 時長計算器使用指南



計算時刻或日期時間的間隔、加減時長，也可移動日期時間。





## 開始使用



1. 單班用時刻間隔，多天用日期時間間隔，混合加減可用表達式。







## 示例



### 輸入



```
22:30 至 06:15，跨日
```



### 預期結果



```
07:45:00
```





<a id="case-study"></a>



## 合計三段錄音



1. 三段錄音分別長 47 分 35 秒、1 小時 12 分 40 秒和 8 分 15 秒。拼接後第二段在 02:00:15 結束，總時長爲 02:08:30。導出累計時長即可找到每個剪輯點。



[運行示例](<https://toolpony.com/zh-hant/tools/time-duration-calculator/#example-recording-sessions>)





## 試一試

[打開完整工具 · 時長計算器](<https://toolpony.com/zh-hant/tools/time-duration-calculator/>)





## 計算方法



時刻間隔可以跨午夜。填寫日期時，每日按 24 小時。表達式用 d、h、m、s 表示天、小時、分鐘和秒，減號作用於後面一整組時間量。



$$
T=86400d+3600h+60m+s
$$







## 計算模式





### 時刻間隔



- 開始時間
- 結束時間
- 休息時間 · min
- 允許跨日







### 時長求和



- 時長列表







### 日期與時刻間隔



- 起始日期
- 開始時間
- 結束日期
- 結束時間







### 時長加減



- 第一段時長
- 運算 · 加 / 減
- 第二段時長







### 日期與時間加減



- 起始日期
- 開始時間
- 運算 · 加 / 減
- 時長







### 時長表達式



- 時長表達式







[ZooChief](<https://docs.toolpony.com/zh-hant/about/>) · [反饋結果問題](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fzh-hant%2Fguides%2Ftime-duration-calculator%2F>)

[文檔站](https://docs.toolpony.com/zh-hant/guides/time-duration-calculator/)
