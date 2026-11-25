# 확률 계산기 사용 가이드



확률 또는 빈도표로 조건부 확률을 비교하고 독립 사건과 반복 시행, 정규 구간을 계산합니다.





## 예시



### 입력



```
독립 이벤트 A = 0.31, B = 0.56
```



### 예상 결과



```
한 번 이상일 확률 0.6964
```





<a id="case-study"></a>



## 두 워크숍의 참석자



1. 50명 중 두 번 다 참석한 사람은 18명, 오전(AM)만 12명, 오후(PM)만 6명, 모두 불참은 14명입니다. 오후 참석자 24명 중 오전에도 온 사람은 18명으로 75%입니다. 오전 참석자 30명 중 오후에도 온 사람은 18명으로 60%입니다.



[예제 실행](<https://toolpony.com/ko/tools/probability-calculator/#example-workshop-attendance>)





## 직접 사용해 보기

[전체 도구 열기 · 확률 계산기](<https://toolpony.com/ko/tools/probability-calculator/>)





## 계산 방법



합집합의 확률은 두 주변확률의 합에서 교집합을 뺀 값입니다. B 중 A의 비율은 P(A ∩ B) / P(B)입니다. 독립이면 교집합은 주변확률의 곱입니다.



$$
P(A\cup B)=P(A)+P(B)-P(A\cap B)
$$



$$
P(A\cap B)=P(A)P(B)\quad\text{(independent)}
$$







## 계산 모드





### 두 개의 독립적인 이벤트



- A의 확률
- B의 확률







### 알려진 교차로



- 입력 방식 · 확률 / 관측 횟수
- A의 확률
- B의 확률
- 두 이벤트 모두
- 사건 A 이름
- 사건 B 이름
- A ∩ B
- A ∩ ¬B
- ¬A ∩ B
- ¬A ∩ ¬B







### 독립적 인 이벤트 복구



- 처음 알려진 수량 · A의 확률 / B의 확률 / A가 아닌 / B가 아닙니다 / 두 이벤트 모두 / 적어도 하나의 이벤트 / 정확히 하나의 이벤트 / 이벤트 없음
- 첫 번째 확률
- 두 번째로 알려진 수량 · A의 확률 / B의 확률 / A가 아닌 / B가 아닙니다 / 두 이벤트 모두 / 적어도 하나의 이벤트 / 정확히 하나의 이벤트 / 이벤트 없음
- 두 번째 확률







### 반복되는 독립적인 재판



- A의 확률
- A의 재판
- B의 확률
- B의 재판







### 일반 분포 간격



- 평균
- 표준편차
- 하한
- 상한







**계산 및 처리 방식의 출처** [OpenStax · Contingency Tables](<https://openstax.org/books/introductory-statistics-2e/pages/3-4-contingency-tables>)



[ZooChief](<https://docs.toolpony.com/ko/about/>) · [결과 문제 제보](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fko%2Fguides%2Fprobability-calculator%2F>)

[문서](https://docs.toolpony.com/ko/guides/probability-calculator/)
