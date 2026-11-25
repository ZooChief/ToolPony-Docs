# 난수 생성기 사용 가이드



양 끝값을 포함한 범위에서 정수를 뽑습니다. 중복 제외와 오름차순 정렬을 선택할 수 있습니다.





## 예시



### 입력



```
최솟값 1, 최댓값 10, 개수 5
```



### 예상 결과



```
1부터 10까지의 정수 난수 5개
```





<a id="case-study"></a>



## 표 네 장 추첨



1. 표 12장에 101~112번을 매기고 중복 없이 4장을 뽑습니다. 발표할 때 정렬하고 정렬을 끄면 처음 뽑힌 순서가 복원됩니다. CSV에는 원래 순서가 기록됩니다.



[예제 실행](<https://toolpony.com/ko/tools/random-number-generator/#example-ticket-draw>)





## 직접 사용해 보기

[전체 도구 열기 · 난수 생성기](<https://toolpony.com/ko/tools/random-number-generator/>)





## 계산 방법



임의의 값은 Web Crypto에서 제공됩니다. 거절 샘플링은 모듈로 편향을 피합니다. 범위에서 최대 1,000개의 값을 생성합니다 −1,000,000,000 내지 1,000,000,000.





**계산 및 처리 방식의 출처** [W3C · Web Cryptography](<https://www.w3.org/TR/WebCryptoAPI/#Crypto-method-getRandomValues>)



[ZooChief](<https://docs.toolpony.com/ko/about/>) · [결과 문제 제보](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fko%2Fguides%2Frandom-number-generator%2F>)

[문서](https://docs.toolpony.com/ko/guides/random-number-generator/)
