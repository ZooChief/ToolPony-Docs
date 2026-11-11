# Matrix calculator



Add, multiply, transpose, invert, solve, or find the rank and determinant. Copy the result as TSV or download CSV.





## Get started



1. Use the example values or enter your own measurements.
2. Calculate, then copy the result or download the available details.







## Example



### Input



```
A = [2, 4; 1, 3], B = [1, −2; 4, 5]
```



### Expected result



```
A + B = [3, 2; 5, 8]
```







## Try it



[Open full tool](<https://toolpony.com/en/tools/matrix-calculator/>)







## Good to know



The calculation runs in your browser. Use consistent units in fields with no explicit unit.







## Calculation method



Separate each row with a newline or semicolon. Values can be separated by spaces or commas. A nested JSON array is accepted. Square-matrix methods use Gaussian elimination with scaled pivoting.



$$
(AB)_{ij}=\sum_{k=1}^{n}A_{ik}B_{kj},\qquad A^{-1}A=I
$$



$$
[A\mid B]\longrightarrow[I\mid X]\quad\Rightarrow\quad AX=B
$$







## Calculation mode



**Add A + B**

- Matrix A
- Matrix B





**Subtract A − B**

- Matrix A
- Matrix B





**Multiply A × B**

- Matrix A
- Matrix B





**Solve A × X = B**

- Matrix A
- Matrix B





**Determinant**

- Matrix A





**Inverse**

- Matrix A





**Transpose**

- Matrix A





**Integer power**

- Matrix A
- Exponent





**Scalar multiplication**

- Matrix A
- Scalar





**Rank and reduced row echelon form**

- Matrix A

[Documentation](https://docs.toolpony.com/en/guides/matrix-calculator/)
