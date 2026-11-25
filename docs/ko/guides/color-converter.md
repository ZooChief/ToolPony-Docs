# 색상 변환기 사용 가이드



CSS 색상을 HEX, RGB, HSL, OKLCH로 변환하고 불투명도와 광색역의 sRGB 대체 색상을 확인하세요.





## 예시



### 입력



```
rgb(102, 51, 153)
```



### 예상 결과



```
#663399, hsl (270 50% 40%)
```





<a id="case-study"></a>



## 광색역 색상의 sRGB 대체 색상 만들기



1. color(display-p3 0 1 0 / 70%)를 붙여 넣으세요. 이 녹색은 sRGB 밖에 있습니다. 두 견본은 원본과 대체 색상을 보여 주며, 이 방식의 HEX는 \#00FB29B3입니다.
2. RGB 행은 불투명도 0.7을 정확히 유지합니다. 8자리 HEX에서는 B3, 즉 179/255입니다.



[예제 실행](<https://toolpony.com/ko/tools/color-converter/#example-wide-gamut>)





## 직접 사용해 보기

[전체 도구 열기 · 색상 변환기](<https://toolpony.com/ko/tools/color-converter/>)





## 계산 방법



HEX는 sRGB 채널을 바이트로 반올림합니다. 색역 밖은 OKLCH 채도로 매핑하며 원본 미리보기는 입력 색공간을 유지합니다.





**계산 및 처리 방식의 출처** [W3C · CSS Color 4](<https://www.w3.org/TR/css-color-4/>)



[ZooChief](<https://docs.toolpony.com/ko/about/>) · [결과 문제 제보](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fko%2Fguides%2Fcolor-converter%2F>)

[문서](https://docs.toolpony.com/ko/guides/color-converter/)
