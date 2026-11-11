# 工時卡計算器



記錄一週的班次和休息，可設置舍入、計薪規則並導出 CSV。





## 開始使用



1. 輸入 08:30、8.30 或 8:30 AM 等時刻。休息時長填小時和分鐘，例如 00:30。
2. 設置舍入和可選的計薪規則，再下載 CSV 或打印。可選保存草稿到當前瀏覽器。







## 示例



### 輸入



```
08:30–17:00，休息 00:30
```



### 預期結果



```
08:00:00
```







## 試一試



[打開完整工具](<https://toolpony.com/zh-hant/tools/time-card-calculator/>)







## 使用提示



計算在瀏覽器內完成。無單位標記的字段請使用一致單位。







## 計算方法



每班先扣休息，再把淨工時舍入到所選間隔。結束早於開始時按次日處理。日、周閾值和費率由你設定。



$$
t_i=(e_i-s_i)\bmod 1440-b_i,\qquad t'_i=q\,\operatorname{round}(t_i/q)\quad(q>0)
$$



$$
P=(t_{\rm base}+m\,t_{\rm overtime})r/60
$$

[文檔站](https://docs.toolpony.com/zh-hant/guides/time-card-calculator/)
