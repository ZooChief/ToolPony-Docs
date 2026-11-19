# PDF를 텍스트로 변환



선택할 수 있는 PDF 텍스트를 기기에서 추출해 TXT 또는 JSON으로 저장합니다.





## 시작하기



1. 텍스트를 선택할 수 있는 PDF를 엽니다.
2. 페이지 순서를 지정해 추출합니다. TXT 또는 원본 페이지 번호가 포함된 JSON을 저장합니다.







## 예시



### 입력



```
첫 두 페이지가 「One」「Two」인 PDF, 선택 2, 1
```

[예시 · PDF](<https://toolpony.com/samples/toolpony-pages.pdf>)

### 예상 결과



```
JSON에서 2페이지 Two 다음에 1페이지 One
```







## 직접 사용해 보기

[전체 도구 열기 · PDF를 텍스트로 변환](<https://toolpony.com/ko/tools/pdf-to-text/>)





## 제한 사항



최대 30 MB, 300페이지, 200만 자, 텍스트 항목 20만 개입니다. PDF 내부의 텍스트 순서를 따릅니다. 스캔 페이지에는 OCR이 필요합니다. 암호화된 파일은 지원하지 않습니다.



스캔 문서를 읽을 수 있는데도 추출에 실패하면 PDF 뷰어에서 단어 하나를 선택해 보세요. 사진으로만 된 페이지는 먼저 OCR로 텍스트 레이어를 만들어야 합니다. 혼합 문서는 JSON의 빈 text 값과 원본 페이지 번호로 해당 페이지를 찾을 수 있습니다.

[문서](https://docs.toolpony.com/ko/guides/pdf-to-text/)
