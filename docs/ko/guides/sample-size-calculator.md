# 표본 크기 계산기



최소 설문조사 샘플을 찾거나 유한 인구 수정으로 오차범위를 추정합니다.





## 예시



### 입력



```
95% 신뢰, 4% 마진, 35% 비율, N = 1,000
```



### 예상 결과



```
354 샘플
```







## 직접 사용해 보기

[전체 도구 열기 · 표본 크기 계산기](<https://toolpony.com/ko/tools/sample-size-calculator/>)





## 계산 방법



초기 크기는 z2p(1−p)/e2입니다. 유한한 개체군의 경우 해당 크기를 1 +(초기 크기-1)/N으로 나누고 반올림합니다. 오류 계산은 동일한 비율 및 유한 인구 모델을 사용합니다.



$$
n_0=\frac{z^2p(1-p)}{e^2},\qquad n=\left\lceil\frac{n_0}{1+(n_0-1)/N}\right\rceil
$$







## 계산 모드



**샘플 크기 찾기**

- 신뢰수준 · %
- 오차 한계 · %
- 인구 비율 · %
- 인구 크기 (0 무제한)





**오차범위 찾기**

- 신뢰수준 · %
- 표본 크기
- 인구 비율 · %
- 인구 크기 (0 무제한)







[ZooChief](<https://docs.toolpony.com/ko/about/>) · [결과 문제 제보](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fko%2Fguides%2Fsample-size-calculator%2F>)

[문서](https://docs.toolpony.com/ko/guides/sample-size-calculator/)
