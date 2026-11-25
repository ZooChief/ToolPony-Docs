# Unix 타임스탬프 변환기 사용 가이드



Unix 초·밀리초·마이크로초·나노초와 UTC 날짜를 정밀하게 상호 변환합니다.





## 예시



### 입력



```
0 초
```



### 예상 결과



```
1970-01-01T00:00:00.000Z
```





<a id="case-study"></a>



## 에포크 1나노초 전



1. ns를 선택하고 -1을 입력하면 UTC 시간은 1969-12-31T23:59:59.999999999Z입니다. 방향을 바꿔 같은 정수를 확인하세요.
2. 1970-01-01T05:44:59.999999999+05:45도 같은 순간입니다. 단위 하나를 복사하거나 네 단위를 CSV 한 줄로 내보내세요.



[예제 실행](<https://toolpony.com/ko/tools/unix-timestamp-converter/#example-before-epoch>)





## 직접 사용해 보기

[전체 도구 열기 · Unix 타임스탬프 변환기](<https://toolpony.com/ko/tools/unix-timestamp-converter/>)





## 계산 방법



Unix 시간은 1970-01-01T00:00:00Z부터 윤초를 제외하고 셉니다. UTC 1900~9999년, 명시적 오프셋과 소수 초 9자리까지 지원합니다.







## 계산 모드





### 타임스탬프 → 날짜·시간



- Unix 타임스탬프
- 단위 · 초 / 밀리초 / 마이크로초 / 나노초







### 날짜·시간 → 타임스탬프



- UTC 오프셋이 있는 날짜·시간 (ISO 8601)
- 단위 · 초 / 밀리초 / 마이크로초 / 나노초







**계산 및 처리 방식의 출처** [GNU · Seconds since the Epoch](<https://www.gnu.org/software/coreutils/manual/html_node/Seconds-since-the-Epoch.html>) · [IETF · RFC 3339](<https://www.rfc-editor.org/rfc/rfc3339>)



[ZooChief](<https://docs.toolpony.com/ko/about/>) · [결과 문제 제보](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fko%2Fguides%2Funix-timestamp-converter%2F>)

[문서](https://docs.toolpony.com/ko/guides/unix-timestamp-converter/)
