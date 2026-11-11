# 三角形计算器



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







## 试一试



[打开完整工具](<https://toolpony.com/zh-hans/tools/triangle-calculator/>)







## 使用提示



计算在浏览器内完成。无单位标记的字段请使用一致单位。







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



**已知量**

- 边长 a
- 边长 b
- 边长 c
- 角度 A
- 角度 B
- 角度 C
- 角度单位 · 度 / 弧度





**三边（SSS）**

- 边长 a
- 边长 b
- 边长 c





**两边及夹角（SAS）**

- 边长 b
- 边长 c
- 角度 A · °





**两角一边（ASA / AAS）**

- 角度 A · °
- 角度 B · °
- 已知边 · a / b / c
- 边长





**两边及一对角（SSA）**

- 边长 a
- 边长 b
- 角度 A · °





**直角三角形的两条直角边**

- 边长 a
- 边长 b

[文档站](https://docs.toolpony.com/zh-hans/guides/triangle-calculator/)
