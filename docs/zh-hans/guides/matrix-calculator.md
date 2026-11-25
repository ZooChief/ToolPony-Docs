# 矩阵计算器使用指南



用精确分数和小数解线性方程组、求行列式、逆矩阵和秩，也可做矩阵运算。支持粘贴表格、复制 TSV 和下载 CSV。





## 示例



### 输入



```
A = [2, 4; 1, 3]，B = [1, −2; 4, 5]
```



### 预期结果



```
A + B = [3, 2; 5, 8]
```





<a id="case-study"></a>



## 两种包装各有几盒



1. 小盒装 2 个黑夹和 1 个白夹，大盒装 3 个黑夹和 2 个白夹。这批货一共有 17 个黑夹、10 个白夹。A 的两列分别表示小盒和大盒，B 填入总数。解得小盒 4 个、大盒 3 个。点击 A × X 可以核对两种夹子的总数。



[运行示例](<https://toolpony.com/zh-hans/tools/matrix-calculator/#example-packing-matrix>)





## 行列式恰好为 1



主对角线乘积是 10 亿的平方，另一条对角线乘积是（10 亿 − 1）×（10 亿 + 1）。相减恰好得到 1。两行数值非常接近，仍然线性无关。



[运行示例](<https://toolpony.com/zh-hans/tools/matrix-calculator/#example-determinant-one>)







## 两个自由变量



第二条方程是第一条的两倍。对于 x + y + z = 4，可以任取 y、z，再取 x = 4 − y − z。特解从 (4, 0, 0) 开始，两个零空间基向量给出可变化的方向。把第二个总数从 8 改成 9，就能看到两条方程的矛盾。



[运行示例](<https://toolpony.com/zh-hans/tools/matrix-calculator/#example-free-variables>)







## 试一试

[打开完整工具 · 矩阵计算器](<https://toolpony.com/zh-hans/tools/matrix-calculator/>)





## 计算方法



行消元使用精确有理数。主元列数就是秩。对于 A × X = B，若某行左边全为零而右边非零，该右端列无解。自由列决定了可以加到特解上的变化方向。



$$
(AB)_{ij}=\sum_{k=1}^{n}A_{ik}B_{kj},\qquad A^{-1}A=I
$$



$$
[A\mid B]\longrightarrow[I\mid X]\quad\Rightarrow\quad AX=B
$$







## 计算模式





### 相加 A + B



- 矩阵 A
- 矩阵 B







### 相减 A − B



- 矩阵 A
- 矩阵 B







### 相乘 A × B



- 矩阵 A
- 矩阵 B







### 求解 A × X = B



- 矩阵 A
- 矩阵 B







### 行列式



- 矩阵 A







### 逆矩阵



- 矩阵 A







### 转置



- 矩阵 A







### 整数次幂



- 矩阵 A
- 指数







### 标量乘法



- 矩阵 A
- 标量







### 秩与最简行阶梯形



- 矩阵 A







**方法来源** [MIT OpenCourseWare · Solving Ax = b](<https://ocw.mit.edu/courses/18-06sc-linear-algebra-fall-2011/resources/solving-ax-b-row-reduced-form-r/>)



[ZooChief](<https://docs.toolpony.com/zh-hans/about/>) · [反馈结果问题](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fzh-hans%2Fguides%2Fmatrix-calculator%2F>)

[文档站](https://docs.toolpony.com/zh-hans/guides/matrix-calculator/)
