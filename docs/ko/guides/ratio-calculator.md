# 비율 계산기 사용 가이드



비례식과 분수를 계산하고 사진 비율을 유지하며 여백과 잘리는 크기를 구합니다.





## 예시



### 입력



```
3:4 = x:20
```



### 예상 결과



```
x=15
```





<a id="case-study"></a>



## 가로 사진을 포스터에 맞추기



1. 1920 × 1080 사진을 1200 × 900 틀에 넣습니다. 너비에 맞춘 배율은 5/8이고 결과는 1200 × 675입니다. 세로 여백은 225픽셀로 가운데 정렬하면 위아래에 112.5픽셀씩 남습니다.



[예제 실행](<https://toolpony.com/ko/tools/ratio-calculator/#example-fit-poster>)





## 같은 틀을 빈틈없이 채우기



포스터를 채우려면 높이에 맞춥니다. 5/6 배율에서 1600 × 900이 되고 가운데를 기준으로 좌우 200픽셀씩 잘립니다.



[예제 실행](<https://toolpony.com/ko/tools/ratio-calculator/#example-fill-poster>)







## 직접 사용해 보기

[전체 도구 열기 · 비율 계산기](<https://toolpony.com/ko/tools/ratio-calculator/>)





## 계산 방법



분모가 0이 아니면 A:B = C:D에서 A × D = B × C입니다. 안에 맞출 때는 두 축의 배율 중 작은 값, 채울 때는 큰 값을 씁니다. 여백과 잘리는 양은 축별 합계입니다.







## 계산 모드





### 비율 해결



- A
- B
- C
- D







### 단순화 또는 규모



- 첫째 항
- 두 번째 임기
- 스케일 팩터







### 비율을 확대하거나 줄이기



- 첫째 항
- 두 번째 임기
- 크기 조절 방식 · 배율 / 안에 맞추기 / 채우고 자르기
- 방향 · 줄이기 / 확장
- 인수
- 프레임 너비
- 프레임 높이







**계산 및 처리 방식의 출처** [W3C · Object fitting](<https://www.w3.org/TR/css-images-3/#the-object-fit>)



[ZooChief](<https://docs.toolpony.com/ko/about/>) · [결과 문제 제보](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fko%2Fguides%2Fratio-calculator%2F>)

[문서](https://docs.toolpony.com/ko/guides/ratio-calculator/)
