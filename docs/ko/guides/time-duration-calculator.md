# 시간 간격 계산기 사용 가이드



시간 간격을 구하고 시간을 더하거나 빼며 날짜와 시간을 이동합니다.





## 시작하기



1. 한 교대는 시각 간격, 여러 날은 날짜와 시간 간격, 계산은 시간 식을 선택하세요.







## 예시



### 입력



```
22:30부터 다음 날 06:15까지
```



### 예상 결과



```
07:45:00
```





<a id="case-study"></a>



## 녹음 세 구간 합산



1. 세 녹음은 47분 35초, 1시간 12분 40초, 8분 15초입니다. 이어 붙이면 두 번째 구간은 02:00:15에 끝나고 총 길이는 02:08:30입니다. 누적 시간을 내려받아 각 편집점을 확인하세요.



[예제 실행](<https://toolpony.com/ko/tools/time-duration-calculator/#example-recording-sessions>)





## 직접 사용해 보기

[전체 도구 열기 · 시간 간격 계산기](<https://toolpony.com/ko/tools/time-duration-calculator/>)





## 계산 방법



시간 간격은 자정을 넘길 수 있습니다. 날짜를 지정하면 하루를 24시간으로 봅니다. 식에서 d, h, m, s는 일, 시간, 분, 초입니다. 빼기는 다음 시간 묶음 전체에 적용됩니다.



$$
T=86400d+3600h+60m+s
$$







## 계산 모드





### 시각 간격



- 시작 시간
- 종료 시간
- 휴식 · min
- 자정 넘김 허용







### 소요 시간 합계



- 시간 목록







### 날짜와 시간 사이



- 시작 날짜
- 시작 시간
- 종료 날짜
- 종료 시간







### 시간 더하기 또는 빼기



- 첫 번째 시간
- 연산 · 더하기 / 빼기
- 두 번째 시간







### 날짜와 시간 이동



- 시작 날짜
- 시작 시간
- 연산 · 더하기 / 빼기
- 소요 시간







### 시간 식



- 시간 식







[ZooChief](<https://docs.toolpony.com/ko/about/>) · [결과 문제 제보](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fko%2Fguides%2Ftime-duration-calculator%2F>)

[문서](https://docs.toolpony.com/ko/guides/time-duration-calculator/)
