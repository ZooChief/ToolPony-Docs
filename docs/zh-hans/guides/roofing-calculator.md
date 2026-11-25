# 屋顶用料计算器使用指南



估算屋面面积、屋面方数、瓦片包数、油毡卷数和费用。





## 开始使用



1. 选择底面积和坡比或坡角。长方形底面可直接用实测长宽。
2. 复杂屋面请分别实测各坡面，再把合计值填入「已知屋面面积」。







## 示例



### 输入



```
底面积 2,000 ft²，坡比 6/12，挑檐 1 ft。
```



### 预期结果



```
约 2,461 ft²，预留 10% 后为 28 屋面方。
```





<a id="case-study"></a>



## 瓦片订货



1. 25 × 40 ft 的平屋面净面积为 1,000 ft²。预留 10%，每 100 ft² 用 3 包，应买 33 包。每包 75，整单为 2,475。



[运行示例](<https://toolpony.com/zh-hans/tools/roofing-calculator/#example-roof-order>)





## 按包装标注采购



含预留需铺 1,100 ft²。标签若写每包 33.3 ft²，33 包只能铺 1,098.9 ft²，应买 34 包，可铺 1,132.2 ft²。



[运行示例](<https://toolpony.com/zh-hans/tools/roofing-calculator/#example-package-label>)







## 分别计入檐口与山墙挑出



8 × 5 m 的建筑，檐口每侧挑出 25 cm，山墙两端各挑出 40 cm，水平投影为 8.8 × 5.5 m。坡比 5∶12、预留 10%、每包铺 3 m²，应买 20 包。



[运行示例](<https://toolpony.com/zh-hans/tools/roofing-calculator/#example-roof-overhang>)







## 试一试

[打开完整工具 · 屋顶用料计算器](<https://toolpony.com/zh-hans/tools/roofing-calculator/>)





## 计算方法



仅有底面积时，含挑檐投影面积按 A + 4.4e(√A + e) 估算，e 为水平挑檐宽度。已知长方形的实测长宽时，用 (l + 2e)(w + 2e)。水平投影再乘坡度系数。一屋面方等于 100 ft²，卷材和瓦片采用常见美制覆盖量，请核对包装规格。



$$
A_{\rm proj}\approx A+4.4e(\sqrt A+e),\qquad A_{\rm rect}=(l+2e)(w+2e)
$$



$$
A_{\rm roof}=A_{\rm proj}\sqrt{1+(p/12)^2}=\frac{A_{\rm proj}}{\cos\theta},\quad N_{\rm squares}=\left\lceil\frac{A_{\rm roof,ft^2}(1+a/100)}{100}\right\rceil
$$







## 计算模式





### 底面积与坡比



- 底面积
- 面积单位 · cm² / m² / in² / ft² / yd² / acre / ha
- 每水平 12 单位的升高
- 水平挑檐宽度
- 挑檐单位 · mm / cm / m / in / ft / yd
- 单价
- 计价单位 · cm² / m² / in² / ft² / yd² / acre / ha
- 损耗预留 · %
- 包装覆盖量 · 每屋面方包数 / 每包覆盖面积
- 每 100 ft² 的包数
- 每包有效覆盖面积
- 整包单价（选填）







### 底面积与坡角



- 底面积
- 面积单位 · cm² / m² / in² / ft² / yd² / acre / ha
- 屋顶坡角 · °
- 水平挑檐宽度
- 挑檐单位 · mm / cm / m / in / ft / yd
- 单价
- 计价单位 · cm² / m² / in² / ft² / yd² / acre / ha
- 损耗预留 · %
- 包装覆盖量 · 每屋面方包数 / 每包覆盖面积
- 每 100 ft² 的包数
- 每包有效覆盖面积
- 整包单价（选填）







### 已知屋面面积



- 屋面面积
- 面积单位 · cm² / m² / in² / ft² / yd² / acre / ha
- 单价
- 计价单位 · cm² / m² / in² / ft² / yd² / acre / ha
- 损耗预留 · %
- 包装覆盖量 · 每屋面方包数 / 每包覆盖面积
- 每 100 ft² 的包数
- 每包有效覆盖面积
- 整包单价（选填）







### 实测长宽



- 长度
- 长度单位 · mm / cm / m / in / ft / yd
- 宽度
- 宽度单位 · mm / cm / m / in / ft / yd
- 每水平 12 单位的升高
- 水平挑檐宽度
- 挑檐单位 · mm / cm / m / in / ft / yd
- 山墙端伸出（与檐口不同时填写）
- 单价
- 计价单位 · cm² / m² / in² / ft² / yd² / acre / ha
- 损耗预留 · %
- 包装覆盖量 · 每屋面方包数 / 每包覆盖面积
- 每 100 ft² 的包数
- 每包有效覆盖面积
- 面积单位 · cm² / m² / in² / ft² / yd² / acre / ha
- 整包单价（选填）







**方法来源** [GAF · Bundle coverage per roofing square](<https://www.gaf.com/en-us/blog/your-home/how-many-bundles-of-shingles-are-in-a-square---63a47862-f7e1-4e73-abcf-8d09917a8b8d>)



[ZooChief](<https://docs.toolpony.com/zh-hans/about/>) · [反馈结果问题](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fzh-hans%2Fguides%2Froofing-calculator%2F>)

[文档站](https://docs.toolpony.com/zh-hans/guides/roofing-calculator/)
