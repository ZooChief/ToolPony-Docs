# Base64 인코딩 및 디코딩 사용 가이드



UTF-8 텍스트나 16진수 바이트를 Base64 또는 Base64url로 변환하고 복원한 바이너리를 저장하세요.





## 예시



### 입력



```
hello 인코딩
```



### 예상 결과



```
aGVsbG8=
```





<a id="case-study"></a>



## Base64url에서 바이트 복원



1. 디코드, URL 안전, 16진수 바이트를 선택하고 \_wCA7w를 붙여 넣으세요. FF 00 80 EF에는 0바이트와 UTF-8 텍스트가 될 수 없는 값이 있습니다. 바이트 다운로드로 네 바이트를 저장하세요.



[예제 실행](<https://toolpony.com/ko/tools/base64-encoder-decoder/#example-binary-bytes>)





## 직접 사용해 보기

[전체 도구 열기 · Base64 인코딩 및 디코딩](<https://toolpony.com/ko/tools/base64-encoder-decoder/>)





## 계산 방법



표준은 +와 /, URL용은 -와 \_를 쓰며 URL용 출력은 패딩을 생략합니다. UTF-8을 검증하고 첫 U+FEFF를 보존합니다. 한도는 UTF-16 단위 500,000개 또는 500,000바이트입니다.





**계산 및 처리 방식의 출처** [IETF · RFC 4648 (Base64)](<https://www.rfc-editor.org/rfc/rfc4648>) · [IETF · RFC 3629](<https://www.rfc-editor.org/rfc/rfc3629>)



[ZooChief](<https://docs.toolpony.com/ko/about/>) · [결과 문제 제보](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fko%2Fguides%2Fbase64-encoder-decoder%2F>)

[문서](https://docs.toolpony.com/ko/guides/base64-encoder-decoder/)
