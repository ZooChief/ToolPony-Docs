# 三角形計算器



根據三個已知量求三角形的角、高、中線與圓心。





## 開始使用



1. 請輸入三個已知量，其中至少一項是邊長。
2. 輸入 π/2 等寫法時選弧度，也可直接輸入度數。SSA 中銳角及其補角均可能構成有效三角形。
3. 座標表以 A 爲原點，B 在 x 軸正半軸。可以將當前表格導出爲 CSV。







## 示例



### 輸入



```
a = 7，b = 10，A = 30°
```



### 預期結果



```
有兩個解，c 約爲 13.55923 和 3.76127。
```







## 試一試



[打開完整工具](<https://toolpony.com/zh-hant/tools/triangle-calculator/>)







## 使用提示



計算在瀏覽器內完成。無單位標記的字段請使用一致單位。







## 計算方法



各邊使用同一長度單位。邊 a 與角 A 相對，b/B 和 c/C 同理。僅有角度無法確定大小。



$$
\frac{a}{\sin A}=\frac{b}{\sin B}=\frac{c}{\sin C},\qquad a^2=b^2+c^2-2bc\cos A
$$



$$
\Delta=\sqrt{s(s-a)(s-b)(s-c)},\quad s=\tfrac{a+b+c}{2},\quad h_a=2\Delta/a
$$



$$
m_a=\tfrac12\sqrt{2b^2+2c^2-a^2},\qquad r=\Delta/s,\qquad R=abc/(4\Delta)
$$







## 計算模式



**已知量**

- 邊長 a
- 邊長 b
- 邊長 c
- 角度 A
- 角度 B
- 角度 C
- 角度單位 · 度 / 弧度





**三邊（SSS）**

- 邊長 a
- 邊長 b
- 邊長 c





**兩邊及夾角（SAS）**

- 邊長 b
- 邊長 c
- 角度 A · °





**兩角一邊（ASA / AAS）**

- 角度 A · °
- 角度 B · °
- 已知邊 · a / b / c
- 邊長





**兩邊及一對角（SSA）**

- 邊長 a
- 邊長 b
- 角度 A · °





**直角三角形的兩條直角邊**

- 邊長 a
- 邊長 b

[文檔站](https://docs.toolpony.com/zh-hant/guides/triangle-calculator/)
