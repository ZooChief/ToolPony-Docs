# UUID 생성기 사용 가이드



브라우저의 안전한 난수 생성기로 버전 4 UUID를 생성합니다.





## 예시



### 입력



```
식별자 1개 생성
```



### 예상 결과



```
형식 예시 550e8400-e29b-41d4-a716-446655440000
```





<a id="case-study"></a>



## 가져오기용 ID 27개 준비



1. 대문자 UUID를 27개 만듭니다. 세 번째 그룹은 4, 네 번째 그룹은 8, 9, A, B 중 하나로 시작합니다.
2. 마지막 페이지에는 25~27행이 있습니다. 27행을 복사해 한 건을 확인하거나 텍스트 파일로 27행 전체를 원래 순서대로 가져오세요.



[예제 실행](<https://toolpony.com/ko/tools/uuid-generator/#example-import-ids>)





## 직접 사용해 보기

[전체 도구 열기 · UUID 생성기](<https://toolpony.com/ko/tools/uuid-generator/>)





## 계산 방법



버전 4 UUID는 122개의 난수 비트와 버전 및 변형용 6비트를 사용합니다. 한 번에 최대 500개를 생성할 수 있습니다.





**계산 및 처리 방식의 출처** [IETF · RFC 9562 (UUID)](<https://www.rfc-editor.org/rfc/rfc9562>)



[ZooChief](<https://docs.toolpony.com/ko/about/>) · [결과 문제 제보](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fko%2Fguides%2Fuuid-generator%2F>)

[문서](https://docs.toolpony.com/ko/guides/uuid-generator/)
