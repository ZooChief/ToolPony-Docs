# 색상 대비 검사기



불투명한 두 색상을 WCAG 2.2 대비 기준으로 비교합니다.





## 예시



### 입력



```
#FFFFFF 위의 #000000
```



### 예상 결과



```
21:1
```







## 직접 사용해 보기

[전체 도구 열기 · 색상 대비 검사기](<https://toolpony.com/ko/tools/contrast-checker/>)





## 계산 방법



대비율은 (밝은 색의 휘도 + 0.05)를 (어두운 색의 휘도 + 0.05)로 나눈 값입니다. 판정에는 반올림 전 값을 사용합니다. 일반 텍스트는 AA 4.5:1, AAA 7:1이고 큰 텍스트는 AA 3:1, AAA 4.5:1입니다.

[문서](https://docs.toolpony.com/ko/guides/contrast-checker/)
