# 신뢰구간 계산기 사용 가이드



관측값이나 요약 통계로 평균의 z 또는 t 구간을 구하고 비율에는 Wilson 구간을 사용합니다.





## 예시



### 입력



```
n = 36, 평균 56, 표준 편차 8, 99%
```



### 예상 결과



```
56 ± 3.434
```





<a id="case-study"></a>



## 다섯 측정값의 구간



1. 48, 49, 50, 51, 52의 평균은 50입니다. 표본 표준편차와 자유도 4를 쓴 평균의 95% t 신뢰구간은 약 48.04~51.96입니다. 서로 독립인 관측과 근사적으로 정규인 모집단을 가정합니다.



[예제 실행](<https://toolpony.com/ko/tools/confidence-interval-calculator/#example-five-measurements>)





## 30개 검사에서 불량 0개



독립적으로 30개를 검사해 불량이 0개였습니다. 불량률의 95% Wilson 구간은 0%에서 약 11.35%입니다. 표본을 늘려도 불량이 없으면 구간이 좁아집니다.



[예제 실행](<https://toolpony.com/ko/tools/confidence-interval-calculator/#example-no-failures>)







## 직접 사용해 보기

[전체 도구 열기 · 신뢰구간 계산기](<https://toolpony.com/ko/tools/confidence-interval-calculator/>)





## 계산 방법



평균의 오차 한계는 임계값 × 표준편차 / √n입니다. 모표준편차를 알면 z, 표본 표준편차에는 자유도 n − 1인 t를 씁니다. Wilson 구간은 성공 횟수와 시행 횟수로 이항 비율을 추정합니다.



$$
\bar{x}\pm z_{1-\alpha/2}\frac{s}{\sqrt n}
$$



$$
\frac{\widehat{p}+z^2/(2n)\pm z\sqrt{\widehat{p}(1-\widehat{p})/n+z^2/(4n^2)}}{1+z^2/n}
$$







## 계산 모드





### 평균 구간



- 자료 종류 · 모집단 σ / 표본 s / 관측값
- 표본 크기
- 평균
- 표준편차
- 표본값
- 신뢰수준 · %







### 윌슨 비율 간격



- 표본 크기
- 성공
- 신뢰수준 · %







**계산 및 처리 방식의 출처** [NIST · Confidence limits for the mean](<https://www.itl.nist.gov/div898/handbook/eda/section3/eda352.htm>) · [NIST · Confidence limits for a proportion](<https://www.itl.nist.gov/div898/handbook/prc/section2/prc241.htm>)



[ZooChief](<https://docs.toolpony.com/ko/about/>) · [결과 문제 제보](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fko%2Fguides%2Fconfidence-interval-calculator%2F>)

[문서](https://docs.toolpony.com/ko/guides/confidence-interval-calculator/)
