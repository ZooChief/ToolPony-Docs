# 體積計算器使用指南



計算水箱容量或實心幾何體的體積，可選升或立方單位。輸入空心管的外徑、內徑和長度可得到管壁材料的體積。





## 示例



### 輸入



```
球半徑 2 米
```



### 預期結果



```
約 33.5103 立方米
```





<a id="case-study"></a>



## 按水位線估算圓柱水箱能裝多少水



1. 量水箱內徑和水位線以下的有效深度。以內徑 1 米、水深 1.2 米爲例，點「運行示例」會選擇圓柱模式，填入半徑 0.5 米，輸出單位設爲升。
2. 容量爲 π × 0.5² × 1.2 立方米，約 942.48 升。直徑如果直接填進半徑欄，平方項會讓結果放大到四倍。
3. 把水位線下移 0.2 米，將高度改爲 1 米再計算，容量約爲 785.40 升。與第一次相比，少裝的約 157.08 升就是兩條水位線之間的容積。



[運行示例](<https://toolpony.com/zh-hant/tools/volume-calculator/#example-tank-fill-line>)





## 管壁與管腔



一米長的管子外徑 60 mm、內徑 48 mm，管壁材料約佔 1.018 L，管腔約能裝 1.810 L。下載的 CSV 保留這兩個結果和原始內外徑。



[運行示例](<https://toolpony.com/zh-hant/tools/volume-calculator/#example-pipe-wall>)







## 試一試

[打開完整工具 · 體積計算器](<https://toolpony.com/zh-hant/tools/volume-calculator/>)





## 計算方法



棱柱體積等於底面積乘垂直高度，圓錐和棱錐再除以三。空心管扣除內圓柱。球冠可填寫任意兩個尺寸。



$$
V_{\mathrm{cone}}=\tfrac13\pi r^2h,\qquad V_{\mathrm{sphere}}=\tfrac43\pi r^3
$$







## 計算模式





### 球體



- 半徑
- 半徑單位
- 體積單位







### 圓錐



- 半徑
- 半徑單位
- 垂直高度
- 垂直高度單位
- 體積單位







### 立方體



- 棱長
- 棱長單位
- 體積單位







### 圓柱



- 半徑
- 半徑單位
- 垂直高度
- 垂直高度單位
- 體積單位







### 長方體



- 長度
- 長度單位
- 寬度
- 寬度單位
- 垂直高度
- 垂直高度單位
- 體積單位







### 膠囊體



- 半徑
- 半徑單位
- 中間圓柱長度
- 中間圓柱長度單位
- 體積單位







### 球冠



- 球半徑
- 球半徑單位
- 底面半徑
- 底面半徑單位
- 球冠高度
- 球冠高度單位
- 已知兩半徑時的球冠 · 較小球冠 / 較大球冠
- 體積單位







### 圓臺



- 第一端半徑
- 第一端半徑單位
- 第二端半徑
- 第二端半徑單位
- 垂直高度
- 垂直高度單位
- 體積單位







### 橢球體



- 第一半軸
- 第一半軸單位
- 第二半軸
- 第二半軸單位
- 第三半軸
- 第三半軸單位
- 體積單位







### 正四棱錐



- 棱長
- 棱長單位
- 垂直高度
- 垂直高度單位
- 體積單位







### 空心圓管



- 外直徑
- 外直徑單位
- 內直徑
- 內直徑單位
- 長度
- 長度單位
- 體積單位







### 半球



- 半徑
- 半徑單位
- 體積單位







### 圓環體



- 中心線半徑
- 中心線半徑單位
- 管截面半徑
- 管截面半徑單位
- 體積單位







**方法來源** [BIPM · SI](<https://www.bipm.org/en/publications/si-brochure>) · [NIST DLMF · Triaxial ellipsoids](<https://dlmf.nist.gov/19.33>)



[ZooChief](<https://docs.toolpony.com/zh-hant/about/>) · [反饋結果問題](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fzh-hant%2Fguides%2Fvolume-calculator%2F>)

[文檔站](https://docs.toolpony.com/zh-hant/guides/volume-calculator/)
