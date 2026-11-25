# 진법 변환 및 계산기 사용 가이드



데이터베이스(2–36) 사이에 서명된 정수를 변환하고 정확한 산술, 나머지 또는 비트별 연산을 수행합니다.





## 예시



### 입력



```
FF, 기초 16에 기초 10
```



### 예상 결과



```
255
```





<a id="case-study"></a>



## 큰 16진수 ID 확인



1. 0x20\_0000\_0000\_0001을 10진수로 바꾸면 끝의 1이 보존된 9007199254740993이 됩니다. 진법을 바꾸거나 이진수 행을 공백 없이 복사할 수 있습니다.



[예제 실행](<https://toolpony.com/ko/tools/base-converter/#example-large-hex-id>)





## 직접 사용해 보기

[전체 도구 열기 · 진법 변환 및 계산기](<https://toolpony.com/ko/tools/base-converter/>)





## 계산 방법



진법 변환은 최대 4,096비트 정수를, 연산은 피연산자당 최대 256자리를 지원합니다. 정수 나눗셈은 0 방향으로 버립니다. 숫자 사이에 공백이나 밑줄을 넣을 수 있습니다.







## 계산 모드





### Convert 기초



- 정수
- 입력 기초
- 출력 기초
- 최소 출력 자릿수







### 정수 산술



- 첫 번째 정수
- 두 번째 정수
- 입력 기초
- 출력 기초
- 최소 출력 자릿수
- 연산 · 추가 / 뺄셈 / Multiply / Divide는 / 나머지 / AND / OR / XOR







[ZooChief](<https://docs.toolpony.com/ko/about/>) · [결과 문제 제보](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fko%2Fguides%2Fbase-converter%2F>)

[문서](https://docs.toolpony.com/ko/guides/base-converter/)
