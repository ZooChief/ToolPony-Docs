# 나눗셈 세로셈 계산기



정수 또는 소수를 나누고 quotient, remainder, decimal value 및 각 long-division 단계를 검사합니다.





## 예시



### 입력



```
12,345 ÷ 67
```



### 예상 결과



```
184 나머지 17
```







## 직접 사용해 보기

[전체 도구 열기 · 나눗셈 세로셈 계산기](<https://toolpony.com/ko/tools/long-division-calculator/>)





## 계산 방법



두 입력을 동일한 10의 힘으로 확장합니다. 정수 지수는 0으로, 서명된 나머지 부분은 배당 = quotient × visor + 나머지를 만족시킨다. 단계 테이블은 절대 크기를 사용합니다.



$$
a=bq+r,\quad q=\operatorname{trunc}(a/b),\quad |r|<|b|
$$





[ZooChief](<https://docs.toolpony.com/ko/about/>) · [결과 문제 제보](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fko%2Fguides%2Flong-division-calculator%2F>)

[문서](https://docs.toolpony.com/ko/guides/long-division-calculator/)
