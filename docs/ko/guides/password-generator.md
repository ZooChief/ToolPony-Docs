# 비밀번호 생성기 사용 가이드



문자 집합, 사용자 지정 제외 및 선택적 고유 문자로 로컬로 암호를 생성합니다.





## 예시



### 입력



```
20자, 문자 그룹 4개
```



### 예상 결과



```
신선한 무작위 비밀번호
```





<a id="case-study"></a>



## 직접 입력할 테스트 코드



1. 대문자와 숫자로 16자리 코드 6개를 만듭니다. 제외 목록에 2Z5S8B를 넣어 인쇄했을 때 헷갈리는 세 쌍을 뺍니다.
2. 각 행에는 두 종류가 모두 들어가며 같은 문자가 반복되지 않습니다. 한 행을 복사해 양식을 시험하세요. 예시를 다시 열면 기기에서 새로 생성됩니다.



[예제 실행](<https://toolpony.com/ko/tools/password-generator/#example-readable-codes>)





## 직접 사용해 보기

[전체 도구 열기 · 비밀번호 생성기](<https://toolpony.com/ko/tools/password-generator/>)





## 계산 방법



Web Crypto는 무작위성을 제공합니다. 필요한 그룹이 활성화되면 각 그룹에서 한 개의 문자가 선택되고 위치는 셔플됩니다. 비밀번호는 현재 페이지에 남기거나 지울 때까지 현재 페이지에 있습니다.





**계산 및 처리 방식의 출처** [W3C · Web Cryptography](<https://www.w3.org/TR/WebCryptoAPI/#Crypto-method-getRandomValues>)



[ZooChief](<https://docs.toolpony.com/ko/about/>) · [결과 문제 제보](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fko%2Fguides%2Fpassword-generator%2F>)

[문서](https://docs.toolpony.com/ko/guides/password-generator/)
