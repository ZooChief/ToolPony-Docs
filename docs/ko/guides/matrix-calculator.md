# 행렬 계산기 사용 가이드



분수와 소수를 정확히 계산하여 연립방정식을 풀고 행렬식, 역행렬, 계수와 행렬 곱을 구합니다. 스프레드시트 셀을 붙여넣고 결과를 내보낼 수 있습니다.





## 예시



### 입력



```
A = [2, 4; 1, 3], B = [1, −2; 4, 5]
```



### 예상 결과



```
A + B = [3, 2; 5, 8]
```





<a id="case-study"></a>



## 두 종류의 상자 수



1. 작은 상자에는 검은 클립 2개와 흰 클립 1개, 큰 상자에는 검은 클립 3개와 흰 클립 2개가 들어갑니다. 검은색이 총 17개, 흰색이 총 10개라면 작은 상자 4개와 큰 상자 3개입니다. A의 각 열은 상자 하나의 구성입니다. A × X로 합계를 확인하세요.



[예제 실행](<https://toolpony.com/ko/tools/matrix-calculator/#example-packing-matrix>)





## 행렬식이 정확히 1



두 대각선의 곱은 각각 10억의 제곱과 (10억 − 1)(10억 + 1)입니다. 차이는 정확히 1이며, 값이 매우 비슷한 두 행은 선형 독립입니다.



[예제 실행](<https://toolpony.com/ko/tools/matrix-calculator/#example-determinant-one>)







## 두 자유 변수



두 번째 식은 첫 번째 식의 두 배입니다. x + y + z = 4에서 y와 z는 자유롭게 정하고 x = 4 − y − z로 둡니다. 특수해 (4, 0, 0)에서 영공간의 두 방향으로 이동할 수 있습니다. 두 번째 합계를 8에서 9로 바꾸면 모순이 생깁니다.



[예제 실행](<https://toolpony.com/ko/tools/matrix-calculator/#example-free-variables>)







## 직접 사용해 보기

[전체 도구 열기 · 행렬 계산기](<https://toolpony.com/ko/tools/matrix-calculator/>)





## 계산 방법



행 소거는 정확한 유리수로 계산합니다. 피벗 열의 수가 계수입니다. A × X = B에서 계수가 모두 0인 행의 우변이 0이 아니면 해당 우변에는 해가 없습니다. 자유 열은 특수해에 더할 수 있는 방향을 결정합니다.



$$
(AB)_{ij}=\sum_{k=1}^{n}A_{ik}B_{kj},\qquad A^{-1}A=I
$$



$$
[A\mid B]\longrightarrow[I\mid X]\quad\Rightarrow\quad AX=B
$$







## 계산 모드





### A + B 추가



- 매트릭스 A
- 매트릭스 B







### A − B 빼기



- 매트릭스 A
- 매트릭스 B







### A × B 곱하기



- 매트릭스 A
- 매트릭스 B







### 해결 A × X = B



- 매트릭스 A
- 매트릭스 B







### 결정 요인



- 매트릭스 A







### 역



- 매트릭스 A







### 전치



- 매트릭스 A







### 통합력



- 매트릭스 A
- 지수







### 스칼라 곱셈



- 매트릭스 A
- 스칼라







### 행 echelon 양식 순위 및 감소 행 echelon



- 매트릭스 A







**계산 및 처리 방식의 출처** [MIT OpenCourseWare · Solving Ax = b](<https://ocw.mit.edu/courses/18-06sc-linear-algebra-fall-2011/resources/solving-ax-b-row-reduced-form-r/>)



[ZooChief](<https://docs.toolpony.com/ko/about/>) · [결과 문제 제보](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fko%2Fguides%2Fmatrix-calculator%2F>)

[문서](https://docs.toolpony.com/ko/guides/matrix-calculator/)
