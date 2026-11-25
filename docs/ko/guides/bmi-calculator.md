# 성인 BMI 계산기 사용 가이드



미터법 또는 미국 단위에서 성인 BMI를 계산하고, 기준 범위를 비교하고, BMI Prime 및 ponderal 지수를 참조하십시오.





## 예시



### 입력



```
70 kg, 175 cm
```



### 예상 결과



```
BMI ≈22.86 kg/m2
```





<a id="case-study"></a>



## BMI 25 경계 확인



1. 키 180 cm, 몸무게 80.99 kg이면 BMI는 약 24.997입니다. 81 kg에서는 정확히 25로 CDC 성인 선별 분류의 다음 구간에 들어갑니다. 경계 근처에서는 소수 자릿수를 늘립니다.



[예제 실행](<https://toolpony.com/ko/tools/bmi-calculator/#example-bmi-boundary>)





## 직접 사용해 보기

[전체 도구 열기 · 성인 BMI 계산기](<https://toolpony.com/ko/tools/bmi-calculator/>)





## 계산 방법



BMI는 체중(kg) ÷ 키(m)²입니다. 기준 범위는 CDC의 20세 이상 성인 선별 기준을 사용합니다. BMI Prime은 BMI ÷ 25, 폰데랄 지수는 체중(kg) ÷ 키(m)³입니다.



$$
\operatorname{BMI}=\frac{m_{\mathrm{kg}}}{h_{\mathrm{m}}^2}
$$







## 계산 모드





### 미터법



- 나이
- 체중 · kg
- 키 · cm







### 미국 관용 단위



- 나이
- 체중 · lb
- 키(피트 부분) · ft
- 나머지 인치 · in







**계산 및 처리 방식의 출처** [CDC · Adult BMI Categories](<https://www.cdc.gov/bmi/adult-calculator/bmi-categories.html>)



[ZooChief](<https://docs.toolpony.com/ko/about/>) · [결과 문제 제보](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fko%2Fguides%2Fbmi-calculator%2F>)

[문서](https://docs.toolpony.com/ko/guides/bmi-calculator/)
