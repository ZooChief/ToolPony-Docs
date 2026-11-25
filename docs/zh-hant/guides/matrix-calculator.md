# 矩陣計算器使用指南



用精確分數和小數解線性方程組、求行列式、逆矩陣和秩，也可做矩陣運算。支持粘貼表格、複製 TSV 和下載 CSV。





## 示例



### 輸入



```
A = [2, 4; 1, 3]，B = [1, −2; 4, 5]
```



### 預期結果



```
A + B = [3, 2; 5, 8]
```





<a id="case-study"></a>



## 兩種包裝各有幾盒



1. 小盒裝 2 個黑夾和 1 個白夾，大盒裝 3 個黑夾和 2 個白夾。這批貨一共有 17 個黑夾、10 個白夾。A 的兩列分別表示小盒和大盒，B 填入總數。解得小盒 4 個、大盒 3 個。點擊 A × X 可以覈對兩種夾子的總數。



[運行示例](<https://toolpony.com/zh-hant/tools/matrix-calculator/#example-packing-matrix>)





## 行列式恰好爲 1



主對角線乘積是 10 億的平方，另一條對角線乘積是（10 億 − 1）×（10 億 + 1）。相減恰好得到 1。兩行數值非常接近，仍然線性無關。



[運行示例](<https://toolpony.com/zh-hant/tools/matrix-calculator/#example-determinant-one>)







## 兩個自由變量



第二條方程是第一條的兩倍。對於 x + y + z = 4，可以任取 y、z，再取 x = 4 − y − z。特解從 (4, 0, 0) 開始，兩個零空間基向量給出可變化的方向。把第二個總數從 8 改成 9，就能看到兩條方程的矛盾。



[運行示例](<https://toolpony.com/zh-hant/tools/matrix-calculator/#example-free-variables>)







## 試一試

[打開完整工具 · 矩陣計算器](<https://toolpony.com/zh-hant/tools/matrix-calculator/>)





## 計算方法



行消元使用精確有理數。主元列數就是秩。對於 A × X = B，若某行左邊全爲零而右邊非零，該右端列無解。自由列決定了可以加到特解上的變化方向。



$$
(AB)_{ij}=\sum_{k=1}^{n}A_{ik}B_{kj},\qquad A^{-1}A=I
$$



$$
[A\mid B]\longrightarrow[I\mid X]\quad\Rightarrow\quad AX=B
$$







## 計算模式





### 相加 A + B



- 矩陣 A
- 矩陣 B







### 相減 A − B



- 矩陣 A
- 矩陣 B







### 相乘 A × B



- 矩陣 A
- 矩陣 B







### 求解 A × X = B



- 矩陣 A
- 矩陣 B







### 行列式



- 矩陣 A







### 逆矩陣



- 矩陣 A







### 轉置



- 矩陣 A







### 整數次冪



- 矩陣 A
- 指數







### 標量乘法



- 矩陣 A
- 標量







### 秩與最簡行階梯形



- 矩陣 A







**方法來源** [MIT OpenCourseWare · Solving Ax = b](<https://ocw.mit.edu/courses/18-06sc-linear-algebra-fall-2011/resources/solving-ax-b-row-reduced-form-r/>)



[ZooChief](<https://docs.toolpony.com/zh-hant/about/>) · [反饋結果問題](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fzh-hant%2Fguides%2Fmatrix-calculator%2F>)

[文檔站](https://docs.toolpony.com/zh-hant/guides/matrix-calculator/)
