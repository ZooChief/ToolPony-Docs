# YAML을 JSON으로



YAML 문서를 붙여서 JSON으로 변환합니다. 매핑은 문자열 키를 사용해야 합니다. 출력이 포맷되어 복사하거나 다운로드할 준비가 되어 있습니다.





## 시작하기



1. 문자열 매핑 키와 함께 하나의 YAML 문서를 붙여 넣습니다.
2. JSON으로 변환.
3. 결과를 검사, 복사 또는 다운로드하십시오.







## 예시



### 입력



```
name: ToolPony
ready: true
```



### 예상 결과



```
{
  "name": "ToolPony",
  "ready": true
}
```







## 직접 사용해 보기



[전체 도구 열기](<https://toolpony.com/ko/tools/yaml-to-json/>)







## 참고 사항



JSON이 나타낼 수 없는 여러 문서, 사용자 지정 태그, 주기적인 별칭 및 값이 거부됩니다. 부울이나 숫자가 아닌 문자열을 의미하는 경우 값을 인용하십시오.







## 제한 사항



최대 1 MB. 사용자 지정 태그, 여러 문서, 문자열이 아닌 키, 과도한 별칭, 주기적 구조 및 JSON이 보존할 수 없는 값은 거부됩니다.

[문서](https://docs.toolpony.com/ko/guides/yaml-to-json/)
