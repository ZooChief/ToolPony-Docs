# 넓이 계산기 사용 가이드



입력이 혼합된 입력 유닛과 선택 가능한 출력 유닛이 있는 11가지 모드에서 평면 도형의 영역을 찾습니다.





## 예시



### 입력



```
직사각형 4 m x 3 m
```



### 예상 결과



```
12 m²
```





<a id="case-study"></a>



## 고리의 면적과 절단 길이



1. 바깥지름 60 mm, 구멍 지름 40 mm인 평평한 개스킷에는 바깥 반지름 30 mm, 안쪽 반지름 20 mm를 입력하고 mm²를 선택합니다.
2. 재료 면적은 500π mm²(약 1,570.80 mm²)입니다. 두 원을 모두 자르는 길이는 100π mm(약 314.16 mm)입니다. 내보낸 파일에서 두 둘레와 원래 치수를 확인하세요.



[예제 실행](<https://toolpony.com/ko/tools/area-calculator/#example-gasket>)





## 직접 사용해 보기

[전체 도구 열기 · 넓이 계산기](<https://toolpony.com/ko/tools/area-calculator/>)





## 계산 방법



치수는 계산 전에 미터로 변환합니다. 3면 삼각형은 Heron의 공식을 사용합니다. 섹터는 반경의 절반의 제곱 반경 곱하기 라디안을 사용합니다.



$$
A_{\mathrm{rectangle}}=lw,\qquad A_{\mathrm{sector}}=\tfrac12 r^2\theta
$$



$$
A_{\mathrm{triangle}}=\sqrt{s(s-a)(s-b)(s-c)},\quad s=\tfrac12(a+b+c)
$$







## 계산 모드





### 직사각형



- 길이
- 길이 단위
- 너비
- 너비 단위
- 면적 단위







### 광장



- 변 길이
- 변 길이 단위
- 면적 단위







### 삼각형 · 3개의 측



- 첫 번째 측면
- 제1부
- 제2의
- 제2부 단위
- 제3의 측면
- 제3부 단위
- 면적 단위







### 삼각형 · 기초와 고도



- 밑변 길이
- 밑변 단위
- 수직 고도
- 수직 고도 단위
- 면적 단위







### 사다리꼴



- 첫 번째 병렬 측면
- 제1 병렬 측면 단위
- 두 번째 병렬 측면
- 두 번째 병렬 측면 단위
- 수직 고도
- 수직 고도 단위
- 면적 단위







### 원



- 반지름
- 반경 단위
- 면적 단위







### 순환 부문



- 반지름
- 반경 단위
- 중앙 각
- 각도 단위 · 도 / 라디안
- 면적 단위







### 타원



- 첫 번째 반축
- 첫 번째 반축 단위
- 두 번째 반축
- 두 번째 반축 단위
- 면적 단위







### 병렬



- 밑변 길이
- 밑변 단위
- 수직 고도
- 수직 고도 단위
- 면적 단위







### 원환



- 외부 반경
- 외부 반경 단위
- 내부 반경
- 내부 반경 단위
- 면적 단위







### 일반 다각형



- 변 길이
- 변 길이 단위
- 변의 수
- 면적 단위







**계산 및 처리 방식의 출처** [BIPM · SI](<https://www.bipm.org/en/publications/si-brochure>) · [NIST DLMF · Lengths of plane curves](<https://dlmf.nist.gov/19.30>)



[ZooChief](<https://docs.toolpony.com/ko/about/>) · [결과 문제 제보](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fko%2Fguides%2Farea-calculator%2F>)

[문서](https://docs.toolpony.com/ko/guides/area-calculator/)
