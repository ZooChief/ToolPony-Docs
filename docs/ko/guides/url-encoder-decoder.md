# URL 인코딩 및 디코딩 사용 가이드



URL과 폼 값을 변환하고 이름 중복과 빈 값을 유지하며 쿼리 매개변수를 순서대로 편집하세요.





## 예시



### 입력



```
구성 요소 인코딩: a+b & c
```



### 예상 결과



```
a%2Bb%20%26%20c
```





<a id="case-study"></a>



## 검색어의 더하기 기호 보존



1. C++ &amp; tea를 폼 값으로 인코딩하면 C%2B%2B+%26+tea입니다. 실제 +는 %2B, 공백은 +, &amp;는 %26이 됩니다. 역변환하면 원문이 복원됩니다. URI 구성 요소에서는 공백이 %20입니다.
2. 쿼리 매개변수에서 tag 두 개가 있는 예제를 열고 두 번째 값을 UI &amp; UX로 바꾸세요. 첫 tag, 빈 값, \#filters가 유지되고 새 값은 UI+%26+UX가 됩니다.



[예제 실행](<https://toolpony.com/ko/tools/url-encoder-decoder/#example-query-plus>)





## 직접 사용해 보기

[전체 도구 열기 · URL 인코딩 및 디코딩](<https://toolpony.com/ko/tools/url-encoder-decoder/>)





## 계산 방법



URI 구성 요소는 구분자를 이스케이프하며 전체 URL은 구분자를 유지합니다. 폼 공백은 +입니다. 쿼리 편집은 이름과 값을 각각 폼 인코딩하며 경로와 프래그먼트를 유지합니다.





**계산 및 처리 방식의 출처** [IETF · RFC 3986](<https://www.rfc-editor.org/rfc/rfc3986>) · [WHATWG · Form encoding](<https://url.spec.whatwg.org/#application/x-www-form-urlencoded>)



[ZooChief](<https://docs.toolpony.com/ko/about/>) · [결과 문제 제보](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fko%2Fguides%2Furl-encoder-decoder%2F>)

[문서](https://docs.toolpony.com/ko/guides/url-encoder-decoder/)
