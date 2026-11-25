# 三角形计算器使用指南



根据三个已知量求三角形的角、高、中线与圆心。





## 开始使用



1. 请输入三个已知量，其中至少一项是边长。
2. 输入 π/2 等写法时选弧度，也可直接输入度数。SSA 中锐角及其补角均可能构成有效三角形。
3. 坐标表以 A 为原点，B 在 x 轴正半轴。可以将当前表格导出为 CSV。







## 示例



### 输入



```
a = 7，b = 10，A = 30°
```



### 预期结果



```
有两个解，c 约为 13.55923 和 3.76127。
```





<a id="case-study"></a>



## 判断同一组测量能得到几个三角形



1. 已知 a = 7、b = 10、A = 30°，边 a 在角 A 对面。第三个顶点有两个可能的位置，边 c 分别约为 13.56 和 3.76。对照两张图可以看清两种解。
2. 把 a 改成 5，正好等于 b × sin A，此时只有一个直角三角形。a 小于 5 时无法构成三角形。角度表可查看弧度和度分秒。



[运行示例](<https://toolpony.com/zh-hans/tools/triangle-calculator/#example-two-triangles>)





## 试一试

[打开完整工具 · 三角形计算器](<https://toolpony.com/zh-hans/tools/triangle-calculator/>)





## 计算方法



各边使用同一长度单位。边 a 与角 A 相对，b/B 和 c/C 同理。仅有角度无法确定大小。



$$
\frac{a}{\sin A}=\frac{b}{\sin B}=\frac{c}{\sin C},\qquad a^2=b^2+c^2-2bc\cos A
$$



$$
\Delta=\sqrt{s(s-a)(s-b)(s-c)},\quad s=\tfrac{a+b+c}{2},\quad h_a=2\Delta/a
$$



$$
m_a=\tfrac12\sqrt{2b^2+2c^2-a^2},\qquad r=\Delta/s,\qquad R=abc/(4\Delta)
$$







## 计算模式





### 已知量



- 边长 a
- 边长 b
- 边长 c
- 角度 A
- 角度 B
- 角度 C
- 角度单位 · 度 / 弧度







### 三边（SSS）



- 边长 a
- 边长 b
- 边长 c







### 两边及夹角（SAS）



- 边长 b
- 边长 c
- 角度 A · °







### 两角一边（ASA / AAS）



- 角度 A · °
- 角度 B · °
- 已知边 · a / b / c
- 边长







### 两边及一对角（SSA）



- 边长 a
- 边长 b
- 角度 A · °







### 直角三角形的两条直角边



- 边长 a
- 边长 b







**方法来源** [MathWorld · Law of sines](<https://mathworld.wolfram.com/LawofSines.html>)



[ZooChief](<https://docs.toolpony.com/zh-hans/about/>) · [反馈结果问题](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fzh-hans%2Fguides%2Ftriangle-calculator%2F>)

[文档站](https://docs.toolpony.com/zh-hans/guides/triangle-calculator/)
