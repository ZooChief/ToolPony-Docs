# 이익률과 원가 가산율 사용 가이드



매출총이익률과 가산율을 비교하고 최저 판매가나 매입 원가 상한을 0.01 단위로 확인합니다.





## 예시



### 입력



```
비용 60, 가격 100
```



### 예상 결과



```
40% 마진; 66.67% 마크업
```





<a id="case-study"></a>



## 마진율 34%를 달성하는 판매가



1. 원가가 10.00이면 이론 가격은 10 ÷ 0.66 ≈ 15.1515입니다. 15.15에서는 마진율이 34%에 못 미치므로 0.01 단위의 최소 가격은 15.16입니다. 이 가격을 확인하면 이익 5.16, 마진율 약 34.04%입니다.





## 12% 가산율을 충족하는 견적



원가 17.20에 12%를 더한 가격은 19.264입니다. 19.26으로 팔면 실제 가산율은 약 11.98%, 19.27이면 약 12.03%입니다. 매출 기준 마진율 12%를 목표로 하면 최저 판매가는 19.55입니다.



[예제 실행](<https://toolpony.com/ko/tools/margin-calculator/#example-markup-quote>)







## 매입 원가 상한 정하기



판매가 20.01에 목표 마진율이 30%라면 정확한 원가 한도는 14.007입니다. 14.00에 매입하면 목표를 달성하고 14.01이면 30%에 미달합니다.



[예제 실행](<https://toolpony.com/ko/tools/margin-calculator/#example-cost-ceiling>)







## 직접 사용해 보기

[전체 도구 열기 · 이익률과 원가 가산율](<https://toolpony.com/ko/tools/margin-calculator/#example-cent-price>)





## 계산 방법



매출총이익은 판매가에서 원가를 뺀 값입니다. 마진율은 판매가로, 가산율은 원가로 나눕니다. 0.01 단위 최저가는 올림하고 최대 원가는 내림합니다.







## 계산 모드





### 비용 및 가격



- 비용
- 판매 가격







### 목표 마진의 가격



- 비용
- 목표 마진 · %







### 가산율로 가격 계산



- 비용
- 목표 가산율 · %







### 판매가와 마진율로 원가 계산



- 판매 가격
- 목표 마진 · %







**계산 및 처리 방식의 출처** [BDC · Gross margin](<https://www.bdc.ca/en/articles-tools/entrepreneur-toolkit/templates-business-guides/glossary/gross-margin>)



[ZooChief](<https://docs.toolpony.com/ko/about/>) · [결과 문제 제보](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fko%2Fguides%2Fmargin-calculator%2F>)

[문서](https://docs.toolpony.com/ko/guides/margin-calculator/)
