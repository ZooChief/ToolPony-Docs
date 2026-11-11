# Triangle calculator



Solve a triangle from three known measurements. Find angles, heights, medians and circle centers.





## Get started



1. Enter three measurements, including at least one side.
2. Select radians for inputs like π/2, or use degrees. In SSA, both an acute and a supplementary angle can give valid triangles.
3. The coordinate table uses A at the origin and B on the positive x-axis. Export the selected table as CSV.







## Example



### Input



```
a = 7, b = 10, A = 30°
```



### Expected result



```
Two solutions, with c about 13.55923 and 3.76127.
```







## Try it



[Open full tool](<https://toolpony.com/en/tools/triangle-calculator/>)







## Good to know



The calculation runs in your browser. Use consistent units in fields with no explicit unit.







## Calculation method



Use one length unit. Side a is opposite angle A, and likewise for b/B and c/C. Angles alone do not determine a size.



$$
\frac{a}{\sin A}=\frac{b}{\sin B}=\frac{c}{\sin C},\qquad a^2=b^2+c^2-2bc\cos A
$$



$$
\Delta=\sqrt{s(s-a)(s-b)(s-c)},\quad s=\tfrac{a+b+c}{2},\quad h_a=2\Delta/a
$$



$$
m_a=\tfrac12\sqrt{2b^2+2c^2-a^2},\qquad r=\Delta/s,\qquad R=abc/(4\Delta)
$$







## Calculation mode



**Known measurements**

- Side a
- Side b
- Side c
- Angle A
- Angle B
- Angle C
- Angle unit · Degrees / Radians





**Three sides (SSS)**

- Side a
- Side b
- Side c





**Two sides and included angle (SAS)**

- Side b
- Side c
- Angle A · °





**Two angles and one side (ASA / AAS)**

- Angle A · °
- Angle B · °
- Known side · a / b / c
- Side





**Two sides and opposite angle (SSA)**

- Side a
- Side b
- Angle A · °





**Right triangle legs**

- Side a
- Side b

[Documentation](https://docs.toolpony.com/en/guides/triangle-calculator/)
