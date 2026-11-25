# 공학용 계산기 사용 가이드



거듭제곱, 팩토리얼, 삼각함수, 근호, 로그가 포함된 수식을 계산합니다.





## 예시



### 입력



```
sqrt(81) + 2^3 × sin(30), 도
```



### 예상 결과



```
13
```





<a id="case-study"></a>



## 대각선 길이 구하기



1. 12 × 5 cm 판의 대각선은 √(12² + 5²) = 13 cm입니다. 식의 일부를 선택하고 x²를 눌러 그 부분만 제곱할 수 있습니다.
2. 대각선을 계산한 직후 DEG에서 asin(5/Ans)를 입력하면 5 cm 변의 맞은각은 약 22.62°입니다.



[예제 실행](<https://toolpony.com/ko/tools/scientific-calculator/#example-panel-diagonal>)





## 직접 사용해 보기

[전체 도구 열기 · 공학용 계산기](<https://toolpony.com/ko/tools/scientific-calculator/>)





## 계산 방법



괄호, 후위 연산, 거듭제곱, 곱셈·나눗셈, 덧셈·뺄셈 순으로 계산합니다. 거듭제곱은 오른쪽부터 결합하며 %는 100으로 나눕니다. 부동소수점 연산을 사용합니다.





**계산 및 처리 방식의 출처** [Python · Power and unary operators](<https://docs.python.org/3/reference/expressions.html#the-power-operator>)



[ZooChief](<https://docs.toolpony.com/ko/about/>) · [결과 문제 제보](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fko%2Fguides%2Fscientific-calculator%2F>)

[문서](https://docs.toolpony.com/ko/guides/scientific-calculator/)
