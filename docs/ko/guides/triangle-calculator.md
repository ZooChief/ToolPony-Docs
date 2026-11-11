# 삼각형 계산기



세 가지 값으로 삼각형의 각, 높이, 중선과 원의 중심을 구합니다.





## 시작하기



1. 한 변 이상을 포함해 세 값을 입력하세요.
2. π/2 같은 입력에는 라디안을 선택하세요. SSA에서는 예각과 그 보각이 모두 유효할 수 있습니다.
3. 좌표 표에서 A는 원점, B는 양의 x축에 있습니다. 선택한 표를 CSV로 내보낼 수 있습니다.







## 예시



### 입력



```
a = 7, b = 10, A = 30°
```



### 예상 결과



```
두 해의 c는 약 13.55923과 3.76127입니다.
```







## 직접 사용해 보기



[전체 도구 열기](<https://toolpony.com/ko/tools/triangle-calculator/>)







## 참고 사항



브라우저에서 처리합니다. 단위를 일관되게 사용하세요.







## 계산 방법



길이 단위를 통일하세요. 변 a는 각 A의 맞은편입니다. b/B와 c/C도 같습니다. 각만으로는 크기를 정할 수 없습니다.



$$
\frac{a}{\sin A}=\frac{b}{\sin B}=\frac{c}{\sin C},\qquad a^2=b^2+c^2-2bc\cos A
$$



$$
\Delta=\sqrt{s(s-a)(s-b)(s-c)},\quad s=\tfrac{a+b+c}{2},\quad h_a=2\Delta/a
$$



$$
m_a=\tfrac12\sqrt{2b^2+2c^2-a^2},\qquad r=\Delta/s,\qquad R=abc/(4\Delta)
$$







## 계산 모드



**알려진 값**

- 변 a
- 변 b
- 변 c
- 각 A
- 각 B
- 각 C
- 각도 단위 · 도 / 라디안





**세 변(SSS)**

- 변 a
- 변 b
- 변 c





**두 변과 끼인각(SAS)**

- 변 b
- 변 c
- 각 A · °





**두 각과 한 변(ASA / AAS)**

- 각 A · °
- 각 B · °
- 알려진 변 · a / b / c
- 변





**두 변과 한 변의 맞은각(SSA)**

- 변 a
- 변 b
- 각 A · °





**두 직각변**

- 변 a
- 변 b

[문서](https://docs.toolpony.com/ko/guides/triangle-calculator/)
