# 面积计算器使用指南



提供 11 种平面面积计算模式，尺寸单位可混用，并可选择结果单位。





## 示例



### 输入



```
长方形长 4 米，宽 3 米
```



### 预期结果



```
12 平方米
```





<a id="case-study"></a>



## 核对圆环的用料与切边



1. 一块平垫片的外径为 60 mm，孔径为 40 mm。在圆环模式填入外半径 30 mm、内半径 20 mm，面积单位选 mm²。
2. 用料面积是 500π mm²，约 1,570.80 mm²。内外圈都要切，切边总长是 100π mm，约 314.16 mm。导出文件中可分别核对两圈周长和原始尺寸。



[运行示例](<https://toolpony.com/zh-hans/tools/area-calculator/#example-gasket>)





## 试一试

[打开完整工具 · 面积计算器](<https://toolpony.com/zh-hans/tools/area-calculator/>)





## 计算方法



各尺寸先换算为米。三边求三角形面积采用海伦公式。扇形面积等于半径平方乘以弧度角再除以二。



$$
A_{\mathrm{rectangle}}=lw,\qquad A_{\mathrm{sector}}=\tfrac12 r^2\theta
$$



$$
A_{\mathrm{triangle}}=\sqrt{s(s-a)(s-b)(s-c)},\quad s=\tfrac12(a+b+c)
$$







## 计算模式





### 长方形



- 长度
- 长度单位
- 宽度
- 宽度单位
- 面积单位







### 正方形



- 边长
- 边长单位
- 面积单位







### 三角形 · 三边



- 第一边
- 第一边单位
- 第二边
- 第二边单位
- 第三边
- 第三边单位
- 面积单位







### 三角形 · 底和高



- 底边长度
- 底边长度单位
- 垂直高度
- 垂直高度单位
- 面积单位







### 梯形



- 第一条平行边
- 第一条平行边单位
- 第二条平行边
- 第二条平行边单位
- 垂直高度
- 垂直高度单位
- 面积单位







### 圆形



- 半径
- 半径单位
- 面积单位







### 扇形



- 半径
- 半径单位
- 圆心角
- 角度单位 · 度 / 弧度
- 面积单位







### 椭圆



- 第一半轴
- 第一半轴单位
- 第二半轴
- 第二半轴单位
- 面积单位







### 平行四边形



- 底边长度
- 底边长度单位
- 垂直高度
- 垂直高度单位
- 面积单位







### 圆环



- 外半径
- 外半径单位
- 内半径
- 内半径单位
- 面积单位







### 正多边形



- 边长
- 边长单位
- 边数
- 面积单位







**方法来源** [BIPM · SI](<https://www.bipm.org/en/publications/si-brochure>) · [NIST DLMF · Lengths of plane curves](<https://dlmf.nist.gov/19.30>)



[ZooChief](<https://docs.toolpony.com/zh-hans/about/>) · [反馈结果问题](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fzh-hans%2Fguides%2Farea-calculator%2F>)

[文档站](https://docs.toolpony.com/zh-hans/guides/area-calculator/)
