# 지붕 자재 계산기 사용 가이드



지붕 면적, 루핑 스퀘어, 슁글 묶음, 펠트 롤과 비용을 계산합니다.





## 시작하기



1. 바닥 면적과 경사비 또는 각도를 선택하세요. 직사각형이면 실측 길이와 너비를 사용할 수 있습니다.
2. 복잡한 지붕은 경사면별로 측정한 뒤 합계를 알고 있는 지붕 면적에 입력하세요.







## 예시



### 입력



```
바닥 면적 2,000 ft², 경사비 6/12, 처마 1 ft.
```



### 예상 결과



```
약 2,461 ft², 여유 10% 포함 28스퀘어.
```





<a id="case-study"></a>



## 지붕재 주문



1. 25 × 40 ft 평지붕은 1,000 ft²입니다. 10% 여유분과 100 ft²당 3묶음을 적용하면 33묶음이며, 묶음당 75로 총 2,475입니다.



[예제 실행](<https://toolpony.com/ko/tools/roofing-calculator/#example-roof-order>)





## 포장 표시 면적



필요 면적은 1,100 ft²입니다. 포장당 33.3 ft²라면 33개로 1,098.9 ft²만 덮습니다. 34개를 주문하면 1,132.2 ft²입니다.



[예제 실행](<https://toolpony.com/ko/tools/roofing-calculator/#example-package-label>)







## 서로 다른 돌출 길이



8 × 5 m 건물에 처마 25 cm, 박공 40 cm이면 평면은 8.8 × 5.5 m입니다. 경사 5/12, 여유 10%, 포장당 3 m²로 20포장이 필요합니다.



[예제 실행](<https://toolpony.com/ko/tools/roofing-calculator/#example-roof-overhang>)







## 직접 사용해 보기

[전체 도구 열기 · 지붕 자재 계산기](<https://toolpony.com/ko/tools/roofing-calculator/>)





## 계산 방법



바닥 면적만 알 때는 A + 4.4e(√A + e)로 처마를 포함한 면적을 추정합니다. e는 수평 처마 길이입니다. 직사각형의 길이와 너비를 알 때는 (l + 2e)(w + 2e)에 경사 계수를 곱합니다. 루핑 스퀘어 하나는 100 ft²입니다. 제품별 시공 면적을 확인하세요.



$$
A_{\rm proj}\approx A+4.4e(\sqrt A+e),\qquad A_{\rm rect}=(l+2e)(w+2e)
$$



$$
A_{\rm roof}=A_{\rm proj}\sqrt{1+(p/12)^2}=\frac{A_{\rm proj}}{\cos\theta},\quad N_{\rm squares}=\left\lceil\frac{A_{\rm roof,ft^2}(1+a/100)}{100}\right\rceil
$$







## 계산 모드





### 바닥 면적과 경사비



- 바닥 면적
- 면적 단위 · cm² / m² / in² / ft² / yd² / 에이커 / ha
- 수평 12당 높이
- 수평 처마 길이
- 처마 길이 단위 · mm / cm / m / 에서 / ft / yd는
- 단가
- 가격 단위 · cm² / m² / in² / ft² / yd² / 에이커 / ha
- 여유분 · %
- 포장당 면적 · 스퀘어당 묶음 수 / 포장당 시공 면적
- 100 ft²당 묶음 수
- 포장당 유효 면적
- 포장 단가(선택)







### 바닥 면적과 경사각



- 바닥 면적
- 면적 단위 · cm² / m² / in² / ft² / yd² / 에이커 / ha
- 지붕 경사각 · °
- 수평 처마 길이
- 처마 길이 단위 · mm / cm / m / 에서 / ft / yd는
- 단가
- 가격 단위 · cm² / m² / in² / ft² / yd² / 에이커 / ha
- 여유분 · %
- 포장당 면적 · 스퀘어당 묶음 수 / 포장당 시공 면적
- 100 ft²당 묶음 수
- 포장당 유효 면적
- 포장 단가(선택)







### 알고 있는 지붕 면적



- 지붕 면적
- 면적 단위 · cm² / m² / in² / ft² / yd² / 에이커 / ha
- 단가
- 가격 단위 · cm² / m² / in² / ft² / yd² / 에이커 / ha
- 여유분 · %
- 포장당 면적 · 스퀘어당 묶음 수 / 포장당 시공 면적
- 100 ft²당 묶음 수
- 포장당 유효 면적
- 포장 단가(선택)







### 실측 길이와 너비



- 길이
- 길이 단위 · mm / cm / m / 에서 / ft / yd는
- 너비
- 너비 단위 · mm / cm / m / 에서 / ft / yd는
- 수평 12당 높이
- 수평 처마 길이
- 처마 길이 단위 · mm / cm / m / 에서 / ft / yd는
- 박공 쪽 돌출 길이(다르면 입력)
- 단가
- 가격 단위 · cm² / m² / in² / ft² / yd² / 에이커 / ha
- 여유분 · %
- 포장당 면적 · 스퀘어당 묶음 수 / 포장당 시공 면적
- 100 ft²당 묶음 수
- 포장당 유효 면적
- 면적 단위 · cm² / m² / in² / ft² / yd² / 에이커 / ha
- 포장 단가(선택)







**계산 및 처리 방식의 출처** [GAF · Bundle coverage per roofing square](<https://www.gaf.com/en-us/blog/your-home/how-many-bundles-of-shingles-are-in-a-square---63a47862-f7e1-4e73-abcf-8d09917a8b8d>)



[ZooChief](<https://docs.toolpony.com/ko/about/>) · [결과 문제 제보](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fko%2Fguides%2Froofing-calculator%2F>)

[문서](https://docs.toolpony.com/ko/guides/roofing-calculator/)
