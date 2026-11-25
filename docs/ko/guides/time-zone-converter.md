# 시간대 변환기 사용 가이드



IANA 시간대 또는 고정 UTC 오프셋으로 날짜와 시각을 변환합니다.





## 예시



### 입력



```
2026-01-15 09:00, Asia/Shanghai → America/New_York
```



### 예상 결과



```
2026-01-14 20:00:00
```





<a id="case-study"></a>



## 두 번 오는 시각의 회의



1. 2026년 11월 1일 뉴욕에서는 01:30이 두 번 옵니다. 상하이에서는 각각 13:30과 14:30입니다. 초대장에 맞는 시각을 골라 UTC를 복사하세요. 두 도시를 바꿔도 같은 회의 시각이 유지됩니다.



[예제 실행](<https://toolpony.com/ko/tools/time-zone-converter/#example-repeated-meeting>)





## 11월 아바나 통화



쿠바는 2026년 11월에 UTC−04:00을 유지했습니다. 11월 23일 아바나 09:00은 UTC 13:00입니다. 현지 약속은 America/Havana를 선택하면 해당 날짜의 규칙을 적용합니다.



[예제 실행](<https://toolpony.com/ko/tools/time-zone-converter/#example-havana-clock>)







## 시계가 30분을 건너뛸 때



2026년 10월 4일 로드하우섬에서는 01:59:59 다음이 02:30:00입니다. 02:15를 입력하면 30분 앞선 01:45나 30분 뒤인 02:45를 고를 수 있습니다. 후자는 UTC로 10월 3일 15:45입니다.



[예제 실행](<https://toolpony.com/ko/tools/time-zone-converter/#example-half-hour-change>)







## 직접 사용해 보기

[전체 도구 열기 · 시간대 변환기](<https://toolpony.com/ko/tools/time-zone-converter/>)





## 계산 방법



선택한 날짜의 IANA 규칙을 적용합니다. 반복 시각은 두 UTC 시각에 해당하며 시계를 앞으로 옮기면 그 사이 시각을 건너뜁니다. 고정 오프셋은 일정합니다.



$$
T_{\rm target}=T_{\rm source}-O_{\rm source}+O_{\rm target}
$$







## 계산 모드





### IANA



- 날짜
- 현지 시간
- 원본 IANA 시간대
- 대상 IANA 시간대
- 중복 시간 · 이른 쪽 / 늦은 쪽







### 고정 UTC 오프셋



- 날짜
- 현지 시간
- 원본 UTC 오프셋
- 대상 UTC 오프셋







**계산 및 처리 방식의 출처** [IANA · Time Zone Database](<https://www.iana.org/time-zones>)



[ZooChief](<https://docs.toolpony.com/ko/about/>) · [결과 문제 제보](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fko%2Fguides%2Ftime-zone-converter%2F>)

[문서](https://docs.toolpony.com/ko/guides/time-zone-converter/)
