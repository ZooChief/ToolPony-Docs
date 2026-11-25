# 전기 요금 계산기 사용 가이드



입력 전력, 냉방 능력과 효율, 또는 두 검침값으로 전력량 요금을 계산하고 하루 및 청구 기간 사용량을 확인합니다.





## 시작하기



1. 기기의 입력 전력, 사용 시간, 요율을 입력하세요. 프리셋 예시는 수정할 수 있습니다.







## 예시



### 입력



```
1,000 W, 하루 2시간, 30일, kWh당 0.2
```



### 예상 결과



```
60 kWh, 요금 12
```





<a id="case-study"></a>



## 창문형 에어컨 명판으로 계산



1. LG LW6014ER의 냉방 능력은 6,000 BTU/h이고 입력 전력은 530 W입니다. 한 대를 최대 부하로 하루 8시간, 30일 사용하면 0.53 × 8 × 30 = 127.2 kWh입니다. kWh당 0.20이면 사용 요금은 25.44입니다.



[예제 실행](<https://toolpony.com/ko/tools/electricity-cost-calculator/#example-window-power>)





## 검침값 두 개로 요금 확인



30일간 계량기가 612345.125에서 612492.365 kWh로 증가했습니다. 차이는 147.24 kWh, 하루 평균은 4.908 kWh입니다. kWh당 0.15이면 기본료와 세금 전 사용 요금은 22.086입니다.



[예제 실행](<https://toolpony.com/ko/tools/electricity-cost-calculator/#example-meter-readings>)







## EER로 입력 전력 추정



냉방 능력 6,000 BTU/h, 정격 EER 12 BTU/Wh이면 입력 전력은 6,000 ÷ 12 = 500 W입니다. 최대 부하로 하루 8시간씩 30일 사용하면 120 kWh입니다. 같은 운전 조건의 정격 EER를 사용하세요.



[예제 실행](<https://toolpony.com/ko/tools/electricity-cost-calculator/#example-cooling-eer>)







## 직접 사용해 보기

[전체 도구 열기 · 전기 요금 계산기](<https://toolpony.com/ko/tools/electricity-cost-calculator/>)





## 계산 방법



사용 요금 = kWh × 단가. 계량기 사용량은 종료값에서 시작값을 뺍니다. 냉방 능력(BTU/h)을 EER로 나누거나 냉방 능력(W)을 COP로 나누면 입력 W를 얻습니다. 기간 환산은 월 30.44일, 연 365.25일입니다.



$$
E_{\rm kWh}=M_1-M_0,\qquad P_{\rm W}=\frac{Q_{\rm Btu/h}}{\mathrm{EER}}=\frac{Q_{\rm W}}{\mathrm{COP}}
$$



$$
E_{\rm kWh}=P_{\rm kW}\,t_{\rm h}\,f\,n,\qquad C=E_{\rm kWh}\,r
$$







## 계산 모드





### 일수 지정



- 계산 기준 · 입력 전력 / 냉방 능력 / 전력량계 검침값
- 입력 전력
- 전력 단위 · W / kW / BTU/h / PS / TR
- 냉방 능력
- 냉방 능력 단위 · BTU/h / kW / TR
- 효율 표기 · EER (BTU/Wh) / COP (W/W)
- 정격 효율
- 시작 검침값 · kWh
- 마지막 검침값 · kWh
- 평균 부하 · %
- 기기 수
- 하루 작동 시간 · h
- 일수
- kWh당 요금







### 일·주·월·연간 추정



- 가전 프리셋
- 계산 기준 · 입력 전력 / 냉방 능력
- 입력 전력
- 전력 단위 · W / kW / BTU/h / PS / TR
- 냉방 능력
- 냉방 능력 단위 · BTU/h / kW / TR
- 효율 표기 · EER (BTU/Wh) / COP (W/W)
- 정격 효율
- 평균 부하 · %
- 기기 수
- 사용 시간
- 사용 시간 단위 · 분/일 / 하루 작동 시간 / 시간/주 / 시간/월 / 일/주 / 일/월 / 일/년 / 개월/년
- kWh당 요금







**계산 및 처리 방식의 출처** [LG · LW6014ER electrical specification](<https://images.thdstatic.com/catalog/pdfImages/e3/e3b8396a-44d1-4372-b120-7532036b2488.pdf>) · [Ohio Consumers’ Counsel · Read an electric meter](<https://www.occ.ohio.gov/sites/default/files/2021-07/OCC-How-to-Read-an-Electric-Meter.pdf>) · [U.S. Department of Energy · Room air conditioner ratings](<https://www.energy.gov/sites/prod/files/2015/06/f22/room_ac_rfi.pdf>) · [NIST · International Table Btu](<https://www.nist.gov/pml/special-publication-811/nist-guide-si-footnotes>)



[ZooChief](<https://docs.toolpony.com/ko/about/>) · [결과 문제 제보](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fko%2Fguides%2Felectricity-cost-calculator%2F>)

[문서](https://docs.toolpony.com/ko/guides/electricity-cost-calculator/)
