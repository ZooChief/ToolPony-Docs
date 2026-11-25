# 백분율 계산기 사용 가이드



백분율과 퍼센트포인트 차이를 구하고 연속 할인을 적용하거나 역산합니다.





## 시작하기



1. 25%의 240과 같은 부분은 값의 백분율을 선택합니다. 부분이 36이고 합계 또는 비율을 알고 있는 경우 해당 역방향 모드를 선택합니다.
2. 주문된 이전 및 새 값에 대한 백분율 변경을 선택합니다. 기준선이 없는 두 개의 양수 값에 대해 백분율 차이를 사용하십시오.
3. 15 for 15%를 입력합니다. 결과는 아래 작업 예제와 비교합니다.







## 예시



### 입력



```
15 %의 240
```



### 예상 결과



```
36
```





<a id="case-study"></a>



## 한 가격에 할인 두 번 적용



1. 250에서 20% 할인하면 200입니다. 다음 10% 할인은 200에 적용되어 최종 가격은 180입니다. 총 할인율은 28%이며 역산하여 원래 가격을 확인할 수 있습니다.



[예제 실행](<https://toolpony.com/ko/tools/percentage-calculator/#example-two-discounts>)





## 4%에서 5%로 변화



가입률이 4%에서 5%로 오르면 차이는 1퍼센트포인트입니다. 기존 4%를 기준으로 한 증가율은 1 ÷ 4 = 25%입니다.



[예제 실행](<https://toolpony.com/ko/tools/percentage-calculator/#example-percentage-points>)







## 직접 사용해 보기

[전체 도구 열기 · 백분율 계산기](<https://toolpony.com/ko/tools/percentage-calculator/>)





## 계산 방법



상대 변화의 분모는 원래 값의 절댓값입니다. 두 비율을 빼면 퍼센트포인트 차이입니다. 연속 변동은 배율을 곱하며 대칭 차이는 두 절댓값의 평균을 분모로 씁니다.



$$
x=yp/100,\quad p=100x/y,\quad y=100x/p
$$



$$
\Delta\%=100\frac{x_1-x_0}{|x_0|},\quad D\%=200\frac{|x_1-x_0|}{|x_1|+|x_0|}
$$



기준값이 80이므로 80 → 100의 변화율은 25%입니다. 같은 두 값의 백분율 차이는 평균 90을 분모로 사용하므로 약 22.22%입니다.



20 %가 120으로 증가한 후, 역 변화는 100을 제공합니다. −100%의 변경은 되돌릴 수 없습니다. 제로 기준선에서 변경하면 백분율 결과가 없습니다.



측정된 값(90)의 경우, 96의 참조는, 절대 퍼센트 오류는 6.25%이다. 그 긍정적 인 참조와 서명 된 결과는 -6.25%입니다.







## 계산 모드





### 값의 비율



- 백분율 · %
- 값







### 백분율 찾기



- 부품
- 전체







### 전체 찾기



- 부품
- 백분율 · %







### 백분율 변화



- 값의 종류 · 일반 수치 / 비율 (%)
- 원래 값
- 새로운 값







### 백분율 차이



- 첫 번째 값
- 두 번째 값







### 서명된 값과의 차이



- 첫 번째 값
- 두 번째 값







### 변경 사항 적용



- 원래 값
- 서명된 변경 · %
- 두 번째 변화 · %







### 변경 반전



- 새로운 값
- 서명된 변경 · %
- 두 번째 변화 · %







### 퍼센트 오류



- 측정된 값
- 참조 값
- 오류 규칙 · 절대 / 기준값 대비 부호 포함







**계산 및 처리 방식의 출처** [Eurostat · Percentage point](<https://ec.europa.eu/eurostat/statistics-explained/index.php?title=Glossary:Percentage_point>)



[ZooChief](<https://docs.toolpony.com/ko/about/>) · [결과 문제 제보](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fko%2Fguides%2Fpercentage-calculator%2F>)

[문서](https://docs.toolpony.com/ko/guides/percentage-calculator/)
