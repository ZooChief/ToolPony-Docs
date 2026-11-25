# 주사위 굴리기 사용 가이드



면 수와 개수를 지정해 주사위를 굴리고 각 눈과 합계를 확인합니다.





## 예시



### 입력



```
6면 주사위 3개
```



### 예상 결과



```
세 주사위의 눈과 합계
```





<a id="case-study"></a>



## 주사위 두 개로 10 이상



1. 6면 주사위 두 개로 목표 10을 설정하면 36가지 중 6가지(16.67%)가 성공합니다. 보정을 +1로 바꾸면 눈은 유지되고 성공은 10가지(27.78%)가 됩니다.



[예제 실행](<https://toolpony.com/ko/tools/dice-roller/#example-two-dice>)





## 직접 사용해 보기

[전체 도구 열기 · 주사위 굴리기](<https://toolpony.com/ko/tools/dice-roller/>)





## 계산 방법



각 주사위의 눈은 Web Crypto로 독립적으로 같은 확률로 뽑습니다. 주사위는 최대 100개, 각 2~1,000면까지 지원합니다.





**계산 및 처리 방식의 출처** [W3C · Web Cryptography](<https://www.w3.org/TR/WebCryptoAPI/#Crypto-method-getRandomValues>)



[ZooChief](<https://docs.toolpony.com/ko/about/>) · [결과 문제 제보](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fko%2Fguides%2Fdice-roller%2F>)

[문서](https://docs.toolpony.com/ko/guides/dice-roller/)
