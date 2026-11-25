# 색상 대비 검사기 사용 가이드



단색 또는 반투명 배경에서 텍스트와 UI 대비를 확인하고 WCAG 기준을 충족하는 글자색을 적용하세요.





## 예시



### 입력



```
#FFFFFF 위의 #000000
```



### 예상 결과



```
21:1
```





<a id="case-study"></a>



## 흰 배경에서 본문 AA를 충족하는 회색 고르기



1. 흰 배경에 \#777777 예제를 계산하면 약 4.48:1입니다. 소수 첫째 자리로 반올림하면 4.5지만 판정에는 반올림 전 값을 사용하므로 일반 크기 본문은 WCAG AA에 미달합니다.
2. 같은 배경에서 \#767676을 선택하면 약 4.54:1로 일반 본문도 AA를 충족합니다. 두 색 모두 큰 글자의 기준인 3:1은 충족합니다.
3. 디자인에서 실제로 보이는 글자색과 배경색을 확인하세요. 이미지나 반투명 레이어 위의 글자는 대비가 가장 약한 위치의 최종 합성색으로 비교합니다. 결과는 입력한 두 단색 조합에 해당합니다.
4. 흰색 위의 \#00000080은 \#7F7F7F로 합성되어 약 4.00:1입니다. 제안 색상 \#767676을 적용하면 일반 텍스트 대비는 4.54:1입니다.



[예제 실행](<https://toolpony.com/ko/tools/contrast-checker/#example-translucent-text>)





## 직접 사용해 보기

[전체 도구 열기 · 색상 대비 검사기](<https://toolpony.com/ko/tools/contrast-checker/>)





## 계산 방법



대비율은 (밝은 색의 휘도 + 0.05)를 (어두운 색의 휘도 + 0.05)로 나눈 값입니다. 판정에는 반올림 전 값을 사용합니다. 일반 텍스트는 AA 4.5:1, AAA 7:1이고 큰 텍스트는 AA 3:1, AAA 4.5:1입니다.





**계산 및 처리 방식의 출처** [W3C · WCAG 2.2 (1.4.3, AA)](<https://www.w3.org/WAI/WCAG22/Understanding/contrast-minimum.html>) · [W3C · WCAG 2.2 (1.4.6, AAA)](<https://www.w3.org/WAI/WCAG22/Understanding/contrast-enhanced.html>) · [W3C · Non-text contrast](<https://www.w3.org/WAI/WCAG22/Understanding/non-text-contrast.html>) · [W3C · Source-over compositing](<https://www.w3.org/TR/compositing-1/#simplealphacompositing>)



[ZooChief](<https://docs.toolpony.com/ko/about/>) · [결과 문제 제보](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fko%2Fguides%2Fcontrast-checker%2F>)

[문서](https://docs.toolpony.com/ko/guides/contrast-checker/)
