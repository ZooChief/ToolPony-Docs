# 屋顶用料计算器



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







## 试一试



[打开完整工具](<https://toolpony.com/zh-hans/tools/roofing-calculator/>)







## 使用提示



计算在浏览器内完成。无单位标记的字段请使用一致单位。







## 计算方法



仅有底面积时，含挑檐投影面积按 A + 4.4e(√A + e) 估算，e 为水平挑檐宽度。已知长方形的实测长宽时，用 (l + 2e)(w + 2e)。水平投影再乘坡度系数。一屋面方等于 100 ft²，卷材和瓦片采用常见美制覆盖量，请核对包装规格。



$$
A_{\rm proj}\approx A+4.4e(\sqrt A+e),\qquad A_{\rm rect}=(l+2e)(w+2e)
$$



$$
A_{\rm roof}=A_{\rm proj}\sqrt{1+(p/12)^2}=\frac{A_{\rm proj}}{\cos\theta},\quad N_{\rm squares}=\left\lceil\frac{A_{\rm roof,ft^2}(1+a/100)}{100}\right\rceil
$$







## 计算模式



**底面积与坡比**

- 底面积
- 面积单位 · cm² / m² / in² / ft² / yd² / acre / ha
- 每水平 12 单位的升高
- 水平挑檐宽度
- 挑檐单位 · mm / cm / m / in / ft / yd
- 单价
- 计价单位 · cm² / m² / in² / ft² / yd² / acre / ha
- 损耗预留 · %





**底面积与坡角**

- 底面积
- 面积单位 · cm² / m² / in² / ft² / yd² / acre / ha
- 屋顶坡角 · °
- 水平挑檐宽度
- 挑檐单位 · mm / cm / m / in / ft / yd
- 单价
- 计价单位 · cm² / m² / in² / ft² / yd² / acre / ha
- 损耗预留 · %





**已知屋面面积**

- 屋面面积
- 面积单位 · cm² / m² / in² / ft² / yd² / acre / ha
- 单价
- 计价单位 · cm² / m² / in² / ft² / yd² / acre / ha
- 损耗预留 · %





**实测长宽**

- 长度
- 长度单位 · mm / cm / m / in / ft / yd
- 宽度
- 宽度单位 · mm / cm / m / in / ft / yd
- 每水平 12 单位的升高
- 水平挑檐宽度
- 挑檐单位 · mm / cm / m / in / ft / yd
- 单价
- 计价单位 · cm² / m² / in² / ft² / yd² / acre / ha
- 损耗预留 · %

[文档站](https://docs.toolpony.com/zh-hans/guides/roofing-calculator/)
