# 유니코드 변환기 사용 가이드



유니코드 코드 포인트, UTF-8 바이트, JavaScript 이스케이프를 변환하고 문자와 정규화 형식을 비교하세요.





## 예시



### 입력



```
🐴
```



### 예상 결과



```
U+1F434 또는 F0 9F 90 B4
```





<a id="case-study"></a>



## 같아 보이는 두 é 비교



1. e, 결합 악센트 U+0301, 공백, 🐴를 검사하세요. 원문은 문자소 군집 3개, 코드 포인트 4개, UTF-16 단위 5개, UTF-8 8바이트입니다. NFC에서는 U+00E9로 합쳐져 7바이트가 됩니다. 🐴는 여전히 1코드 포인트, 2개의 UTF-16 단위입니다.



[예제 실행](<https://toolpony.com/ko/tools/unicode-converter/#example-combining-accent>)





## 직접 사용해 보기

[전체 도구 열기 · 유니코드 변환기](<https://toolpony.com/ko/tools/unicode-converter/>)





## 계산 방법



코드 포인트 모드는 보충 문자를 하나의 스칼라로 취급합니다.Code-point mode treats a supplementary character as one scalar. UTF-16은 이러한 문자에 대해 두 개의 코드 단위를 사용합니다. 유효하지 않은 대리 시퀀스와 유효하지 않은 UTF-8 바이트는 거부됩니다.







## 계산 모드





### 텍스트 인코딩



- 입력
- 인코딩 · 유니코드 코드 포인트 / UTF-8 16진수 바이트 / JavaScript UTF-16 이스케이프 / JavaScript 코드 포인트 이스케이프







### 텍스트 해독



- 입력
- 인코딩 · 유니코드 코드 포인트 / UTF-8 16진수 바이트 / JavaScript UTF-16 이스케이프 / JavaScript 코드 포인트 이스케이프







### 문자 검사



- 입력
- 정규화 · 원문 / NFC / NFD / NFKC / NFKD







**계산 및 처리 방식의 출처** [IETF · RFC 3629](<https://www.rfc-editor.org/rfc/rfc3629>) · [Unicode · UAX \#15](<https://www.unicode.org/reports/tr15/>)



[ZooChief](<https://docs.toolpony.com/ko/about/>) · [결과 문제 제보](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fko%2Fguides%2Funicode-converter%2F>)

[문서](https://docs.toolpony.com/ko/guides/unicode-converter/)
