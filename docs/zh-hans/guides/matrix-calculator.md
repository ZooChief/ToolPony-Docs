# 矩阵计算器



支持矩阵加法、乘法、转置、求逆、解方程、求秩与行列式。可复制 TSV 或下载 CSV。





## 开始使用



1. 按示例填写数值，或输入你自己的测量值。
2. 计算后可复制结果或下载明细。







## 示例



### 输入



```
A = [2, 4; 1, 3]，B = [1, −2; 4, 5]
```



### 预期结果



```
A + B = [3, 2; 5, 8]
```







## 试一试



[打开完整工具](<https://toolpony.com/zh-hans/tools/matrix-calculator/>)







## 使用提示



计算在浏览器内完成。无单位标记的字段请使用一致单位。







## 计算方法



用换行或分号分隔行，用空格或逗号分隔数值，也可输入嵌套 JSON 数组。方阵方法使用带缩放主元的高斯消元。



$$
(AB)_{ij}=\sum_{k=1}^{n}A_{ik}B_{kj},\qquad A^{-1}A=I
$$



$$
[A\mid B]\longrightarrow[I\mid X]\quad\Rightarrow\quad AX=B
$$







## 计算模式



**相加 A + B**

- 矩阵 A
- 矩阵 B





**相减 A − B**

- 矩阵 A
- 矩阵 B





**相乘 A × B**

- 矩阵 A
- 矩阵 B





**求解 A × X = B**

- 矩阵 A
- 矩阵 B





**行列式**

- 矩阵 A





**逆矩阵**

- 矩阵 A





**转置**

- 矩阵 A





**整数次幂**

- 矩阵 A
- 指数





**标量乘法**

- 矩阵 A
- 标量





**秩与最简行阶梯形**

- 矩阵 A

[文档站](https://docs.toolpony.com/zh-hans/guides/matrix-calculator/)
