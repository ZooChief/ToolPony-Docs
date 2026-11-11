# 屋頂用料計算器



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







## 試一試



[打開完整工具](<https://toolpony.com/zh-hant/tools/roofing-calculator/>)







## 使用提示



計算在瀏覽器內完成。無單位標記的字段請使用一致單位。







## 計算方法



僅有底面積時，含挑檐投影面積按 A + 4.4e(√A + e) 估算，e 爲水平挑檐寬度。已知長方形的實測長寬時，用 (l + 2e)(w + 2e)。水平投影再乘坡度係數。一屋面方等於 100 ft²，卷材和瓦片採用常見美製覆蓋量，請覈對包裝規格。



$$
A_{\rm proj}\approx A+4.4e(\sqrt A+e),\qquad A_{\rm rect}=(l+2e)(w+2e)
$$



$$
A_{\rm roof}=A_{\rm proj}\sqrt{1+(p/12)^2}=\frac{A_{\rm proj}}{\cos\theta},\quad N_{\rm squares}=\left\lceil\frac{A_{\rm roof,ft^2}(1+a/100)}{100}\right\rceil
$$







## 計算模式



**底面積與坡比**

- 底面積
- 面積單位 · cm² / m² / in² / ft² / yd² / acre / ha
- 每水平 12 單位的升高
- 水平挑檐寬度
- 挑檐單位 · mm / cm / m / in / ft / yd
- 單價
- 計價單位 · cm² / m² / in² / ft² / yd² / acre / ha
- 損耗預留 · %





**底面積與坡角**

- 底面積
- 面積單位 · cm² / m² / in² / ft² / yd² / acre / ha
- 屋頂坡角 · °
- 水平挑檐寬度
- 挑檐單位 · mm / cm / m / in / ft / yd
- 單價
- 計價單位 · cm² / m² / in² / ft² / yd² / acre / ha
- 損耗預留 · %





**已知屋面面積**

- 屋面面積
- 面積單位 · cm² / m² / in² / ft² / yd² / acre / ha
- 單價
- 計價單位 · cm² / m² / in² / ft² / yd² / acre / ha
- 損耗預留 · %





**實測長寬**

- 長度
- 長度單位 · mm / cm / m / in / ft / yd
- 寬度
- 寬度單位 · mm / cm / m / in / ft / yd
- 每水平 12 單位的升高
- 水平挑檐寬度
- 挑檐單位 · mm / cm / m / in / ft / yd
- 單價
- 計價單位 · cm² / m² / in² / ft² / yd² / acre / ha
- 損耗預留 · %

[文檔站](https://docs.toolpony.com/zh-hant/guides/roofing-calculator/)
