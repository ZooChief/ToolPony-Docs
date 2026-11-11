# 유니코드 변환기



텍스트를 유니코드 코드 포인트, UTF-8 16진수 바이트 또는 UTF-16 이스케이프로 변환하고 다시 텍스트로 디코딩합니다.





## 시작하기



1. 예제 값을 사용하거나 원하는 값을 입력하세요.
2. 계산한 결과를 복사하거나 세부 정보를 내려받을 수 있습니다.







## 예시



### 입력



```
🐴
```



### 예상 결과



```
U+1F434 또는 F0 9F 90 B4
```







## 직접 사용해 보기



[전체 도구 열기](<https://toolpony.com/ko/tools/unicode-converter/>)







## 참고 사항



브라우저에서 처리합니다. 단위를 일관되게 사용하세요.







## 계산 방법



코드 포인트 모드는 보충 문자를 하나의 스칼라로 취급합니다.Code-point mode treats a supplementary character as one scalar. UTF-16은 이러한 문자에 대해 두 개의 코드 단위를 사용합니다. 유효하지 않은 대리 시퀀스와 유효하지 않은 UTF-8 바이트는 거부됩니다.







## 계산 모드



**텍스트 인코딩**

- 입력
- 인코딩 · 유니코드 코드 포인트 / UTF-8 16진수 바이트 / JavaScript UTF-16 이스케이프





**텍스트 해독**

- 입력
- 인코딩 · 유니코드 코드 포인트 / UTF-8 16진수 바이트 / JavaScript UTF-16 이스케이프

[문서](https://docs.toolpony.com/ko/guides/unicode-converter/)
