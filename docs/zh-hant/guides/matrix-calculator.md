# 矩陣計算器



支持矩陣加法、乘法、轉置、求逆、解方程、求秩與行列式。可複製 TSV 或下載 CSV。





## 開始使用



1. 按示例填寫數值，或輸入你自己的測量值。
2. 計算後可複製結果或下載明細。







## 示例



### 輸入



```
A = [2, 4; 1, 3]，B = [1, −2; 4, 5]
```



### 預期結果



```
A + B = [3, 2; 5, 8]
```







## 試一試



[打開完整工具](<https://toolpony.com/zh-hant/tools/matrix-calculator/>)







## 使用提示



計算在瀏覽器內完成。無單位標記的字段請使用一致單位。







## 計算方法



用換行或分號分隔行，用空格或逗號分隔數值，也可輸入嵌套 JSON 數組。方陣方法使用帶縮放主元的高斯消元。



$$
(AB)_{ij}=\sum_{k=1}^{n}A_{ik}B_{kj},\qquad A^{-1}A=I
$$



$$
[A\mid B]\longrightarrow[I\mid X]\quad\Rightarrow\quad AX=B
$$







## 計算模式



**相加 A + B**

- 矩陣 A
- 矩陣 B





**相減 A − B**

- 矩陣 A
- 矩陣 B





**相乘 A × B**

- 矩陣 A
- 矩陣 B





**求解 A × X = B**

- 矩陣 A
- 矩陣 B





**行列式**

- 矩陣 A





**逆矩陣**

- 矩陣 A





**轉置**

- 矩陣 A





**整數次冪**

- 矩陣 A
- 指數





**標量乘法**

- 矩陣 A
- 標量





**秩與最簡行階梯形**

- 矩陣 A

[文檔站](https://docs.toolpony.com/zh-hant/guides/matrix-calculator/)
