# 成人 BMI 计算器使用指南



用公制或美制计算成人 BMI，查看参考区间、BMI Prime 和体重指数 PI。





## 示例



### 输入



```
70 kg，175 cm
```



### 预期结果



```
BMI 约 22.86 kg/m²
```





<a id="case-study"></a>



## 读懂 BMI 25 的边界



1. 身高 180 厘米、体重 80.99 公斤时，BMI 约为 24.997。将体重改为 81 公斤，BMI 恰好是 25，进入 CDC 成人筛查的下一个分类。读数在边界附近会保留更多小数位。



[运行示例](<https://toolpony.com/zh-hans/tools/bmi-calculator/#example-bmi-boundary>)





## 试一试

[打开完整工具 · 成人 BMI 计算器](<https://toolpony.com/zh-hans/tools/bmi-calculator/>)





## 计算方法



BMI = 体重 kg ÷ 身高 m²。参考分类采用 CDC 的 20 岁及以上成人筛查区间。BMI Prime 为 BMI 除以 25。PI = 体重 kg ÷ 身高 m³。



$$
\operatorname{BMI}=\frac{m_{\mathrm{kg}}}{h_{\mathrm{m}}^2}
$$







## 计算模式





### 公制



- 年龄
- 体重 · kg
- 身高 · cm







### 美制



- 年龄
- 体重 · lb
- 身高英尺部分 · ft
- 额外英寸 · in







**方法来源** [CDC · Adult BMI Categories](<https://www.cdc.gov/bmi/adult-calculator/bmi-categories.html>)



[ZooChief](<https://docs.toolpony.com/zh-hans/about/>) · [反馈结果问题](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fzh-hans%2Fguides%2Fbmi-calculator%2F>)

[文档站](https://docs.toolpony.com/zh-hans/guides/bmi-calculator/)
