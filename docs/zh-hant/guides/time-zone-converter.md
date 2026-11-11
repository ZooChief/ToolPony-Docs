# 時區轉換器



在 IANA 時區或固定 UTC 偏移間換算日期和時間。





## 開始使用



1. 按示例填寫數值，或輸入你自己的測量值。
2. 計算後可複製結果或下載明細。







## 示例



### 輸入



```
2026-01-15 09:00，Asia/Shanghai → America/New_York
```



### 預期結果



```
2026-01-14 20:00:00
```







## 試一試



[打開完整工具](<https://toolpony.com/zh-hant/tools/time-zone-converter/>)







## 使用提示



計算在瀏覽器內完成。無單位標記的字段請使用一致單位。







## 計算方法



IANA 時區使用瀏覽器的時區規則，重複時刻有兩個可能值，跳過的時刻無對應值。固定 UTC 偏移全年不變。



$$
T_{\rm target}=T_{\rm source}-O_{\rm source}+O_{\rm target}
$$







## 計算模式



**IANA**

- 日期
- 當地時間
- 原 IANA 時區
- 目標 IANA 時區
- 重複時段 · 較早一次 / 較晚一次





**固定 UTC 偏移**

- 日期
- 當地時間
- 原 UTC 偏移
- 目標 UTC 偏移

[文檔站](https://docs.toolpony.com/zh-hant/guides/time-zone-converter/)
