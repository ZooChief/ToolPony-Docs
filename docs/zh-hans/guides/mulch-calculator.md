# 覆盖料用量计算器使用指南



估算一块或多块区域的覆盖料体积、整袋数及费用。





## 开始使用



1. 填写总面积，或每行填写一个长方形，例如 6, 2, m。各行可使用不同单位。
2. 设定厚度，选择散装或袋装计价。自定义袋装的容量在更多选项填写。







## 示例



### 输入



```
200 ft²、厚 2 in，每袋 2 ft³、单价 5。
```



### 预期结果



```
33.3 ft³，17 袋，费用 85。
```







## 试一试

[打开完整工具 · 覆盖料用量计算器](<https://toolpony.com/zh-hans/tools/mulch-calculator/>)





## 计算方法



合计互不重叠的区域面积，乘以铺设厚度并加上损耗预留。体积除以每袋容量后向上取整。散装费用按计算体积计价。



$$
A=\sum_i l_iw_i,\quad V=Ad(1+a/100),\quad N=\left\lceil\frac{V}{V_{\rm bag}}\right\rceil
$$







## 计算模式





### 已知面积



- 面积
- 面积单位 · cm² / m² / in² / ft² / yd² / acre / ha
- 铺设厚度
- 厚度单位 · mm / cm / m / in / ft / yd
- 单价
- 计价单位
- 每袋容量
- 每袋容量单位 · ft³ / yd³ / m³ / L
- 损耗预留 · %







### 多个长方形



- 每行填写长、宽、单位
- 铺设厚度
- 厚度单位 · mm / cm / m / in / ft / yd
- 单价
- 计价单位
- 每袋容量
- 每袋容量单位 · ft³ / yd³ / m³ / L
- 损耗预留 · %







[ZooChief](<https://docs.toolpony.com/zh-hans/about/>) · [反馈结果问题](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fzh-hans%2Fguides%2Fmulch-calculator%2F>)

[文档站](https://docs.toolpony.com/zh-hans/guides/mulch-calculator/)
