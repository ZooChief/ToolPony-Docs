# 전압 강하 계산기 사용 가이드



전선 규격, 단면적, 저항으로 직류·단상·평형 삼상 전압 강하를 계산합니다.





## 시작하기



1. 모델을 고르세요. 삼상은 선간 전압과 선전류를 입력하세요. 거리는 편도입니다.
2. 거리 한도는 선택한 강하율로 계산됩니다. 허용 전류, 온도, 설치 요건은 별도로 확인하세요.







## 예시



### 입력



```
120 V, 단상, 500 ft, 1 A, 1.2 Ω/km
```



### 예상 결과



```
0.37 V 강하, 0.30%
```





<a id="case-study"></a>



## 케이블 표 적용



1. 계수 1 mV/(A·m), 편도 50 m, 100 A이면 이 구간 강하는 5 V입니다. Schneider 예시는 상류 10 V를 더해 전체 15 V입니다.



[예제 실행](<https://toolpony.com/ko/tools/voltage-drop-calculator/#example-cable-table>)





## 3상 병렬 회로



상당 두 선로가 20 A를 분담합니다. 400 V, 100 m, R = 1 Ω/km, X = 0.5 Ω/km, 지상 역률 0.8이면 강하 1.91 V, 부하 398.09 V입니다.



[예제 실행](<https://toolpony.com/ko/tools/voltage-drop-calculator/#example-parallel-cable>)







## 전원보다 큰 강하



24 V 직류, 10 A, 편도 1 km, 5 Ω/km이면 왕복 강하는 100 V입니다. 이 전류에서 부하 전압을 추정할 수 없습니다.



[예제 실행](<https://toolpony.com/ko/tools/voltage-drop-calculator/#example-cable-limit>)







## 직접 사용해 보기

[전체 도구 열기 · 전압 강하 계산기](<https://toolpony.com/ko/tools/voltage-drop-calculator/>)





## 계산 방법



편도 길이와 동일한 병렬 도체 수를 사용하세요. 직류·단상은 I·L·R에 2, 평형 삼상은 √3을 곱합니다. 지상 부하의 R과 X는 역률로 합성합니다. 전선 규격은 약 20 °C의 공칭 저항으로 추정합니다. 실제 전선에는 제조사 값을 사용하세요.



$$
\Delta V=\frac{k I L R_{\rm eff}}{n},\quad k=2\ \text{(DC, 1)}\phi,\quad k=\sqrt{3}\ \text{(3)}\phi
$$



$$
R_{\rm eff}=R\cos\theta+X\sin\theta,\quad \%\Delta V=100\frac{\Delta V}{V_s}
$$







## 계산 모드





### 알고 있는 저항 또는 임피던스



- 자료의 값 · 도체 임피던스 / 회로 전압강하 계수
- 단위 길이당 저항 또는 임피던스
- 길이당 단위 · Ω/km / Ω/m / mΩ/m / Ω/1000 ft / Ω/ft / mΩ/ft
- 표에 기재된 회로 계수 · mV/(A·m)
- 전압 · V
- 회로 · DC / 단상 교류 / 삼상 교류
- 상당 병렬 도체 수
- 편도 거리
- 길이 단위 · ft / m / mi / km
- 전류 · A
- 거리 추정용 강하 한도 · %







### 전선 규격으로 추정



- 재질 · 구리 / 알루미늄 / 은 / 금
- 전선 규격
- 전압 · V
- 회로 · DC / 단상 교류 / 삼상 교류
- 상당 병렬 도체 수
- 편도 거리
- 길이 단위 · ft / m / mi / km
- 전류 · A
- 거리 추정용 강하 한도 · %







### 단면적으로 추정



- 재질 · 구리 / 알루미늄 / 은 / 금
- 단면적 · mm²
- 전압 · V
- 회로 · DC / 단상 교류 / 삼상 교류
- 상당 병렬 도체 수
- 편도 거리
- 길이 단위 · ft / m / mi / km
- 전류 · A
- 거리 추정용 강하 한도 · %







### 저항과 리액턴스



- 저항
- 단위 길이당 리액턴스
- 길이당 단위 · Ω/km / Ω/m / mΩ/m / Ω/1000 ft / Ω/ft / mΩ/ft
- 지상 역률
- 전압 · V
- 회로 · DC / 단상 교류 / 삼상 교류
- 상당 병렬 도체 수
- 편도 거리
- 길이 단위 · ft / m / mi / km
- 전류 · A
- 거리 추정용 강하 한도 · %







**계산 및 처리 방식의 출처** [Schneider Electric · Voltage drop in steady load conditions](<https://www.electrical-installation.org/enwiki/Calculation_of_voltage_drop_in_steady_load_conditions>)



[ZooChief](<https://docs.toolpony.com/ko/about/>) · [결과 문제 제보](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fko%2Fguides%2Fvoltage-drop-calculator%2F>)

[문서](https://docs.toolpony.com/ko/guides/voltage-drop-calculator/)
