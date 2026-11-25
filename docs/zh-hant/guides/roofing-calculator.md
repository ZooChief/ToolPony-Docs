# 屋頂用料計算器使用指南



估算屋面面積、屋面方數、瓦片包數、油氈卷數和費用。





## 開始使用



1. 選擇底面積和坡比或坡角。長方形底面可直接用實測長寬。
2. 複雜屋面請分別實測各坡面，再把合計值填入「已知屋面面積」。







## 示例



### 輸入



```
底面積 2,000 ft²，坡比 6/12，挑檐 1 ft。
```



### 預期結果



```
約 2,461 ft²，預留 10% 後爲 28 屋面方。
```





<a id="case-study"></a>



## 瓦片訂貨



1. 25 × 40 ft 的平屋面淨面積爲 1,000 ft²。預留 10%，每 100 ft² 用 3 包，應買 33 包。每包 75，整單爲 2,475。



[運行示例](<https://toolpony.com/zh-hant/tools/roofing-calculator/#example-roof-order>)





## 按包裝標註採購



含預留需鋪 1,100 ft²。標籤若寫每包 33.3 ft²，33 包只能鋪 1,098.9 ft²，應買 34 包，可鋪 1,132.2 ft²。



[運行示例](<https://toolpony.com/zh-hant/tools/roofing-calculator/#example-package-label>)







## 分別計入檐口與山牆挑出



8 × 5 m 的建築，檐口每側挑出 25 cm，山牆兩端各挑出 40 cm，水平投影爲 8.8 × 5.5 m。坡比 5∶12、預留 10%、每包鋪 3 m²，應買 20 包。



[運行示例](<https://toolpony.com/zh-hant/tools/roofing-calculator/#example-roof-overhang>)







## 試一試

[打開完整工具 · 屋頂用料計算器](<https://toolpony.com/zh-hant/tools/roofing-calculator/>)





## 計算方法



僅有底面積時，含挑檐投影面積按 A + 4.4e(√A + e) 估算，e 爲水平挑檐寬度。已知長方形的實測長寬時，用 (l + 2e)(w + 2e)。水平投影再乘坡度係數。一屋面方等於 100 ft²，卷材和瓦片採用常見美製覆蓋量，請覈對包裝規格。



$$
A_{\rm proj}\approx A+4.4e(\sqrt A+e),\qquad A_{\rm rect}=(l+2e)(w+2e)
$$



$$
A_{\rm roof}=A_{\rm proj}\sqrt{1+(p/12)^2}=\frac{A_{\rm proj}}{\cos\theta},\quad N_{\rm squares}=\left\lceil\frac{A_{\rm roof,ft^2}(1+a/100)}{100}\right\rceil
$$







## 計算模式





### 底面積與坡比



- 底面積
- 面積單位 · cm² / m² / in² / ft² / yd² / acre / ha
- 每水平 12 單位的升高
- 水平挑檐寬度
- 挑檐單位 · mm / cm / m / in / ft / yd
- 單價
- 計價單位 · cm² / m² / in² / ft² / yd² / acre / ha
- 損耗預留 · %
- 包裝覆蓋量 · 每屋面方包數 / 每包覆蓋面積
- 每 100 ft² 的包數
- 每包有效覆蓋面積
- 整包單價（選填）







### 底面積與坡角



- 底面積
- 面積單位 · cm² / m² / in² / ft² / yd² / acre / ha
- 屋頂坡角 · °
- 水平挑檐寬度
- 挑檐單位 · mm / cm / m / in / ft / yd
- 單價
- 計價單位 · cm² / m² / in² / ft² / yd² / acre / ha
- 損耗預留 · %
- 包裝覆蓋量 · 每屋面方包數 / 每包覆蓋面積
- 每 100 ft² 的包數
- 每包有效覆蓋面積
- 整包單價（選填）







### 已知屋面面積



- 屋面面積
- 面積單位 · cm² / m² / in² / ft² / yd² / acre / ha
- 單價
- 計價單位 · cm² / m² / in² / ft² / yd² / acre / ha
- 損耗預留 · %
- 包裝覆蓋量 · 每屋面方包數 / 每包覆蓋面積
- 每 100 ft² 的包數
- 每包有效覆蓋面積
- 整包單價（選填）







### 實測長寬



- 長度
- 長度單位 · mm / cm / m / in / ft / yd
- 寬度
- 寬度單位 · mm / cm / m / in / ft / yd
- 每水平 12 單位的升高
- 水平挑檐寬度
- 挑檐單位 · mm / cm / m / in / ft / yd
- 山牆端伸出（與檐口不同時填寫）
- 單價
- 計價單位 · cm² / m² / in² / ft² / yd² / acre / ha
- 損耗預留 · %
- 包裝覆蓋量 · 每屋面方包數 / 每包覆蓋面積
- 每 100 ft² 的包數
- 每包有效覆蓋面積
- 面積單位 · cm² / m² / in² / ft² / yd² / acre / ha
- 整包單價（選填）







**方法來源** [GAF · Bundle coverage per roofing square](<https://www.gaf.com/en-us/blog/your-home/how-many-bundles-of-shingles-are-in-a-square---63a47862-f7e1-4e73-abcf-8d09917a8b8d>)



[ZooChief](<https://docs.toolpony.com/zh-hant/about/>) · [反饋結果問題](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fzh-hant%2Fguides%2Froofing-calculator%2F>)

[文檔站](https://docs.toolpony.com/zh-hant/guides/roofing-calculator/)
