# 직각삼각형 계산기



높이, 넓이, 둘레 등을 포함한 두 값으로 직각변, 빗변, 각을 구합니다.





## 시작하기



1. 길이, 넓이, 둘레 중 하나를 포함해 두 값을 입력하세요.
2. 두 해는 직각변과 예각의 이름을 서로 바꾼 것입니다.







## 예시



### 입력



```
c = 5, h = 2.4
```



### 예상 결과



```
직각변은 3과 4, 넓이는 6, 둘레는 12입니다. 어느 쪽을 a로 두어도 됩니다.
```







## 직접 사용해 보기



[전체 도구 열기](<https://toolpony.com/ko/tools/right-triangle-calculator/>)







## 참고 사항



브라우저에서 처리합니다. 단위를 일관되게 사용하세요.







## 계산 방법



c는 빗변, h는 빗변에 내린 높이입니다. 길이 단위를 통일하고 넓이에는 그 제곱 단위를 쓰세요.



$$
c^2=a^2+b^2,\quad h=ab/c,\quad S=ab/2,\quad P=a+b+c
$$



$$
a,b=\frac{\sqrt{c^2+2ch}\;\pm\;\sqrt{c^2-2ch}}{2}
$$

[문서](https://docs.toolpony.com/ko/guides/right-triangle-calculator/)
