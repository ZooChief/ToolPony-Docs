# 成人 BMI 計算器使用指南



用公制或美製計算成人 BMI，查看參考區間、BMI Prime 和體重指數 PI。





## 示例



### 輸入



```
70 kg，175 cm
```



### 預期結果



```
BMI 約 22.86 kg/m²
```





<a id="case-study"></a>



## 讀懂 BMI 25 的邊界



1. 身高 180 釐米、體重 80.99 公斤時，BMI 約爲 24.997。將體重改爲 81 公斤，BMI 恰好是 25，進入 CDC 成人篩查的下一個分類。讀數在邊界附近會保留更多小數位。



[運行示例](<https://toolpony.com/zh-hant/tools/bmi-calculator/#example-bmi-boundary>)





## 試一試

[打開完整工具 · 成人 BMI 計算器](<https://toolpony.com/zh-hant/tools/bmi-calculator/>)





## 計算方法



BMI = 體重 kg ÷ 身高 m²。參考分類採用 CDC 的 20 歲及以上成人篩查區間。BMI Prime 爲 BMI 除以 25。PI = 體重 kg ÷ 身高 m³。



$$
\operatorname{BMI}=\frac{m_{\mathrm{kg}}}{h_{\mathrm{m}}^2}
$$







## 計算模式





### 公制



- 年齡
- 體重 · kg
- 身高 · cm







### 美製



- 年齡
- 體重 · lb
- 身高英尺部分 · ft
- 額外英寸 · in







**方法來源** [CDC · Adult BMI Categories](<https://www.cdc.gov/bmi/adult-calculator/bmi-categories.html>)



[ZooChief](<https://docs.toolpony.com/zh-hant/about/>) · [反饋結果問題](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fzh-hant%2Fguides%2Fbmi-calculator%2F>)

[文檔站](https://docs.toolpony.com/zh-hant/guides/bmi-calculator/)
