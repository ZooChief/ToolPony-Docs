# 달리기 페이스 계산기 사용 가이드



속도, 경과 된 시간 및 거리를 해결하십시오. 분할 속도를 비교하고, 단위를 변환하고, 완료 시간을 추정합니다.





## 예시



### 입력



```
10 km를 00:50:00에 주행
```



### 예상 결과



```
05:00/km, 12 km/h
```





<a id="case-study"></a>



## 두 지점의 통과 시간 확인



1. 시계에 1 km 지점 3:25, 2 km 지점 6:55가 표시됩니다. 누적을 선택하면 두 번째 1 km는 3:30, 전체 평균은 3:27.5/km입니다.
2. 4:00:00 마라톤에 1 km 간격을 선택하면 마지막 구간은 195 m입니다. 마지막 누적 시간은 정확히 4:00:00입니다.



[예제 실행](<https://toolpony.com/ko/tools/pace-calculator/#example-watch-checkpoints>)





## 직접 사용해 보기

[전체 도구 열기 · 달리기 페이스 계산기](<https://toolpony.com/ko/tools/pace-calculator/>)





## 계산 방법



평균 페이스는 총시간을 총거리로 나눕니다. 두 부분은 분·초, 세 부분은 시·분·초입니다. 실측 100구간 또는 일정한 페이스로 계획한 500개 지점을 지원합니다.



$$
p=\frac{t}{d},\qquad v=\frac{d}{t}
$$







## 계산 모드





### 페이스와 완주 시간



- 거리
- 거리 단위 · km / mi / m / yd는
- 경과 시간
- 페이스 기준 거리 · km / mi / 100 m / 100 yd는
- 목표 거리 · 5 km / 10 km / 하프 마라톤 / 마라톤 / 거리 직접 입력 (km)
- 직접 입력한 경기 거리 · km







### 소요 시간 계산



- 거리
- 거리 단위 · km / mi / m / yd는
- 페이스(분:초)
- 페이스 기준 거리 · km / mi / 100 m / 100 yd는







### 거리 계산



- 경과 시간
- 페이스(분:초)
- 페이스 기준 거리 · km / mi / 100 m / 100 yd는







### 페이스 단위 변환



- 페이스(분:초)
- 페이스 기준 거리 · km / mi / 100 m / 100 yd는







### 구간 기록 비교



- 구간 기록
- 거리 단위 · km / mi / m / yd는
- 페이스 기준 거리 · km / mi / 100 m / 100 yd는
- 행별 누적 거리와 시간







### 구간 계획



- 목표 거리 · 5 km / 10 km / 하프 마라톤 / 마라톤 / 거리 직접 입력 (km)
- 직접 입력한 경기 거리 · km
- 목표 완주 시간
- 체크포인트 간격 · 1 km / 1 mi / 400 m / 100 m / 5 km / 10 km
- 페이스 기준 거리 · km / mi / 100 m / 100 yd는







**계산 및 처리 방식의 출처** [World Athletics · Marathon](<https://worldathletics.org/disciplines/road-running-event/marathon>) · [NIST · Unit conversion factors](<https://www.nist.gov/pml/special-publication-811/nist-guide-si-appendix-b-conversion-factors/nist-guide-si-appendix-b8>)



[ZooChief](<https://docs.toolpony.com/ko/about/>) · [결과 문제 제보](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fko%2Fguides%2Fpace-calculator%2F>)

[문서](https://docs.toolpony.com/ko/guides/pace-calculator/)
