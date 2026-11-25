# 時區轉換器使用指南



在 IANA 時區或固定 UTC 偏移間換算日期和時間。





## 示例



### 輸入



```
2026-01-15 09:00，Asia/Shanghai → America/New_York
```



### 預期結果



```
2026-01-14 20:00:00
```





<a id="case-study"></a>



## 重複時段裏的會議



1. 2026 年 11 月 1 日，紐約的凌晨 01:30 出現兩次。第一次對應上海 13:30，第二次對應 14:30。按邀請函選擇對應的一次，再複製 UTC 時刻。交換兩地仍指向同一場會議。



[運行示例](<https://toolpony.com/zh-hant/tools/time-zone-converter/#example-repeated-meeting>)





## 哈瓦那的十一月通話



2026 年 11 月古巴沿用 UTC−04:00。11 月 23 日在哈瓦那上午 09:00 通話，對應 UTC 13:00。約定當地時間時選擇 America/Havana，換算會採用當天生效的規則。



[運行示例](<https://toolpony.com/zh-hant/tools/time-zone-converter/#example-havana-clock>)







## 時鐘跳過半小時



2026 年 10 月 4 日，豪勳爵島的時鐘從 01:59:59 跳到 02:30:00。試着輸入 02:15。把這次預約前移或後移半小時，可以選 01:45 或 02:45。後者對應 UTC 10 月 3 日 15:45。



[運行示例](<https://toolpony.com/zh-hant/tools/time-zone-converter/#example-half-hour-change>)







## 試一試

[打開完整工具 · 時區轉換器](<https://toolpony.com/zh-hant/tools/time-zone-converter/>)





## 計算方法



當地時刻按所選日期的 IANA 規則換算。重複時刻對應兩個 UTC 時刻，跳過的時刻落在調鍾間隙。固定偏移全年相同。



$$
T_{\rm target}=T_{\rm source}-O_{\rm source}+O_{\rm target}
$$







## 計算模式





### IANA



- 日期
- 當地時間
- 原 IANA 時區
- 目標 IANA 時區
- 重複時段 · 較早一次 / 較晚一次







### 固定 UTC 偏移



- 日期
- 當地時間
- 原 UTC 偏移
- 目標 UTC 偏移







**方法來源** [IANA · Time Zone Database](<https://www.iana.org/time-zones>)



[ZooChief](<https://docs.toolpony.com/zh-hant/about/>) · [反饋結果問題](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fzh-hant%2Fguides%2Ftime-zone-converter%2F>)

[文檔站](https://docs.toolpony.com/zh-hant/guides/time-zone-converter/)
