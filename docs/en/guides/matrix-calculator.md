# Matrix calculator guide



Solve linear systems, find determinants, inverses and rank, or combine matrices using exact fractions and decimals. Paste spreadsheet cells and export the result.





## Example



### Input



```
A = [2, 4; 1, 3], B = [1, −2; 4, 5]
```



### Expected result



```
A + B = [3, 2; 5, 8]
```





<a id="case-study"></a>



## Count two kinds of packs



1. A small pack contains 2 black clips and 1 white clip. A large pack contains 3 black and 2 white. The shipment contains 17 black and 10 white clips. The columns of A describe the packs and B contains the totals. Solving gives 4 small and 3 large packs. Multiply A by X to check both totals.



[Run example](<https://toolpony.com/en/tools/matrix-calculator/#example-packing-matrix>)





## A determinant of one



The diagonal product is 1,000,000,000². The other product is (1,000,000,000 − 1)(1,000,000,000 + 1). Their difference is exactly 1. The two rows are independent even though their entries look nearly equal.



[Run example](<https://toolpony.com/en/tools/matrix-calculator/#example-determinant-one>)







## Two free variables



The second equation is twice the first. For x + y + z = 4, choose any y and z and set x = 4 − y − z. The particular solution starts at (4, 0, 0). The two null-space vectors give the permitted changes. Change the second total from 8 to 9 to see why the equations become inconsistent.



[Run example](<https://toolpony.com/en/tools/matrix-calculator/#example-free-variables>)







## Try it

[Open full tool · Matrix calculator](<https://toolpony.com/en/tools/matrix-calculator/>)





## Calculation method



Row reduction uses exact rational arithmetic. Pivot columns determine rank. For A × X = B, a zero coefficient row with a nonzero right-hand side identifies an inconsistency. Free columns give the directions that can be added to a particular solution.



$$
(AB)_{ij}=\sum_{k=1}^{n}A_{ik}B_{kj},\qquad A^{-1}A=I
$$



$$
[A\mid B]\longrightarrow[I\mid X]\quad\Rightarrow\quad AX=B
$$







## Calculation mode





### Add A + B



- Matrix A
- Matrix B







### Subtract A − B



- Matrix A
- Matrix B







### Multiply A × B



- Matrix A
- Matrix B







### Solve A × X = B



- Matrix A
- Matrix B







### Determinant



- Matrix A







### Inverse



- Matrix A







### Transpose



- Matrix A







### Integer power



- Matrix A
- Exponent







### Scalar multiplication



- Matrix A
- Scalar







### Rank and reduced row echelon form



- Matrix A







**Method references** [MIT OpenCourseWare · Solving Ax = b](<https://ocw.mit.edu/courses/18-06sc-linear-algebra-fall-2011/resources/solving-ax-b-row-reduced-form-r/>)



[ZooChief](<https://docs.toolpony.com/en/about/>) · [Report a problem with this result](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fen%2Fguides%2Fmatrix-calculator%2F>)

[Documentation](https://docs.toolpony.com/en/guides/matrix-calculator/)
