# 가상 주소 생성기 사용 가이드



18개 국가와 지역에서 행정구역을 선택하고 현지 주소 형식으로 예제를 생성해 일괄 내보냅니다.





## 시작하기



1. 국가나 지역과 행정구역을 선택하고 개수와 연락처 항목을 설정하세요.
2. 같은 설정과 시드로 같은 배치를 다시 생성할 수 있습니다. 필드를 개별 복사하거나 TXT, CSV, JSON으로 내보내세요.
3. 기기에 저장하면 주소 예제가 현재 브라우저에 남습니다. 도구에서 삭제할 수 있습니다.







## 예시



### 입력



```
독일 · 베를린 · 시드 pony-demo
```



### 예상 결과



```
Testperson 001
Beispielstraße 4957
10115 Berlin
Deutschland
```





<a id="case-study"></a>



## 캐나다 호수 포함 주소 확인



1. 온타리오와 시드 label-review를 선택해 호수는 포함하고 연락처는 뺀 테스트 주소 두 개를 만듭니다. 같은 설정이면 같은 결과가 나옵니다.
2. 텍스트에서는 호수가 번지 앞에 오고 둘을 하이픈으로 연결합니다. 도시 줄에서 ON과 우편번호 사이는 공백 두 칸입니다. JSON에는 각 요소가 별도 필드로도 저장됩니다.



[예제 실행](<https://toolpony.com/ko/tools/sample-address-generator/#example-canadian-label>)





## 직접 사용해 보기

[전체 도구 열기 · 가상 주소 생성기](<https://toolpony.com/ko/tools/sample-address-generator/>)





## 계산 방법



한 번에 최대 100개를 생성합니다. 도시와 우편번호는 형식 예제이며 도로명과 수취인은 합성 데이터입니다. 전화번호는 예약된 예시 번호나 마스크를 사용합니다. 양식과 소프트웨어 테스트용입니다.





**계산 및 처리 방식의 출처** [USPS · Publication 28, §213](<https://pe.usps.com/text/pub28/28c2_003.htm>) · [Canada Post · Civic address](<https://www.canadapost-postescanada.ca/cpc/en/support/articles/addressing-guidelines/civic-address.page>)



[ZooChief](<https://docs.toolpony.com/ko/about/>) · [결과 문제 제보](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fko%2Fguides%2Fsample-address-generator%2F>)

[문서](https://docs.toolpony.com/ko/guides/sample-address-generator/)
