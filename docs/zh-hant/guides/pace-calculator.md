# 配速計算器使用指南



在配速、用時和距離之間反算，支持分段比較、單位轉換與完賽時間估算。





## 示例



### 輸入



```
10 km，用時 00:50:00
```



### 預期結果



```
每公里 05:00，速度 12 km/h
```





<a id="case-study"></a>



## 覈對兩個公里檢查點



1. 運動表在 1 公里處顯示 3:25，2 公里處顯示 6:55。選擇累計記錄，第二公里的實際用時是 3:30，兩公里平均配速爲 3:27.5/公里。
2. 計劃 4:00:00 跑完全馬，檢查點選每 1 公里。最後一段爲 195 米，計入這一段後，最後的累計時間恰爲 4:00:00。



[運行示例](<https://toolpony.com/zh-hant/tools/pace-calculator/#example-watch-checkpoints>)





## 試一試

[打開完整工具 · 配速計算器](<https://toolpony.com/zh-hant/tools/pace-calculator/>)





## 計算方法



平均配速爲總用時除以總距離。兩段計時錶示分和秒，三段表示時、分、秒。支持 100 條實測分段或 500 個按勻速推算的檢查點。



$$
p=\frac{t}{d},\qquad v=\frac{d}{t}
$$







## 計算模式





### 求配速和完賽時間



- 距離
- 距離單位 · km / mi / m / yd
- 用時
- 配速單位 · km / mi / 100 m / 100 yd
- 目標距離 · 5 km / 10 km / 半程馬拉松 / 全程馬拉松 / 自定義公里
- 自定義目標距離 · km







### 求用時



- 距離
- 距離單位 · km / mi / m / yd
- 配速（分:秒）
- 配速單位 · km / mi / 100 m / 100 yd







### 求距離



- 用時
- 配速（分:秒）
- 配速單位 · km / mi / 100 m / 100 yd







### 配速換算



- 配速（分:秒）
- 配速單位 · km / mi / 100 m / 100 yd







### 比較分段



- 分段記錄
- 距離單位 · km / mi / m / yd
- 配速單位 · km / mi / 100 m / 100 yd
- 各行採用累計里程和時間







### 分段計劃



- 目標距離 · 5 km / 10 km / 半程馬拉松 / 全程馬拉松 / 自定義公里
- 自定義目標距離 · km
- 目標完賽時間
- 檢查點間距 · 1 km / 1 mi / 400 m / 100 m / 5 km / 10 km
- 配速單位 · km / mi / 100 m / 100 yd







**方法來源** [World Athletics · Marathon](<https://worldathletics.org/disciplines/road-running-event/marathon>) · [NIST · Unit conversion factors](<https://www.nist.gov/pml/special-publication-811/nist-guide-si-appendix-b-conversion-factors/nist-guide-si-appendix-b8>)



[ZooChief](<https://docs.toolpony.com/zh-hant/about/>) · [反饋結果問題](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fzh-hant%2Fguides%2Fpace-calculator%2F>)

[文檔站](https://docs.toolpony.com/zh-hant/guides/pace-calculator/)
