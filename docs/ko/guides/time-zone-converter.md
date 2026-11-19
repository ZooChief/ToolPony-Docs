# 시간대 변환기



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







## 직접 사용해 보기

[전체 도구 열기 · 시간대 변환기](<https://toolpony.com/ko/tools/time-zone-converter/>)





## 계산 방법



IANA는 브라우저의 규칙을 씁니다. 중복 시각은 두 가지이고 건너뛴 시각은 없습니다. 고정 UTC 오프셋은 연중 일정합니다.



$$
T_{\rm target}=T_{\rm source}-O_{\rm source}+O_{\rm target}
$$







## 계산 모드



**IANA**

- 날짜
- 현지 시간
- 원본 IANA 시간대
- 대상 IANA 시간대
- 중복 시간 · 이른 쪽 / 늦은 쪽





**고정 UTC 오프셋**

- 날짜
- 현지 시간
- 원본 UTC 오프셋
- 대상 UTC 오프셋

[문서](https://docs.toolpony.com/ko/guides/time-zone-converter/)
