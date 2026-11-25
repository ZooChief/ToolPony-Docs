# 이미지 형식 변환 사용 가이드



형식이 다른 이미지를 한꺼번에 추가하면 파일 내용으로 형식을 감지합니다. 이미지별로 출력 형식, 품질, 배경을 설정하고 개별 파일 또는 ZIP으로 저장하세요.





## 시작하기



1. 형식이 다른 이미지를 한꺼번에 추가하면 파일 내용으로 형식을 감지합니다.
2. 이미지별로 출력 형식, 품질, 배경을 설정하고 개별 파일 또는 ZIP으로 저장하세요.







## 예시



### 입력



```
PNG · 64 × 32 px (투명한 모서리) → JPEG · 흰색 배경
```

[예시 · PNG](<https://toolpony.com/samples/toolpony-64x32.png>)

### 예상 결과



```
JPEG · 64 × 32 px (흰색 모서리)
```





<a id="case-study"></a>



## 투명 PNG를 JPEG로 보낼 때 배경 확인하기



1. 빈 변환기에서 ‘예제 파일 사용’을 누릅니다. 64 × 32 px의 투명 PNG와 흰 배경 JPEG가 추가되며 출력 형식은 각각 JPEG와 PNG로 설정됩니다.
2. 변환 후 원본과 결과를 나란히 비교하세요. 이미지를 선택하면 실제 픽셀 크기로 볼 수 있습니다. 첫 JPEG의 모서리는 흰색입니다. JPEG에서 만든 PNG의 모서리도 원본에 흰색 픽셀이 있어 불투명합니다. 원래 투명도를 유지하려면 첫 파일의 출력을 PNG로, 배경을 투명으로 바꾸세요.
3. 긴 배너는 파일 행의 출력 크기를 확인하세요. 10,000 × 100 px라면 비율을 유지해 8,192 × 82 px로 줄어듭니다. 품질 설정은 인코딩 품질에만 영향을 줍니다.
4. 픽셀을 확인하려면 예제 JPEG를 색상 추출기에서 열고 (0, 0)을 보세요. Chromium에서 이 모서리는 RGBA (255, 255, 243, 255)로 디코딩되었습니다. 같은 JPEG를 변환한 PNG도 이 값을 유지하며 마지막 255는 완전 불투명을 뜻합니다.



[이미지 색상 추출](<https://toolpony.com/ko/tools/image-color-picker/>)





## 직접 사용해 보기

[전체 도구 열기 · 이미지 형식 변환](<https://toolpony.com/ko/tools/image-converter/#example-mixed-images>)





## 제한 사항



입력 최대 20 MB, 2,400만 화소이며 출력은 한 변 8,192픽셀까지입니다. AVIF 디코딩은 브라우저에 따라 다릅니다. 애니메이션은 정지 이미지가 되며 원본 메타데이터는 제거됩니다. 한 번에 최대 12장, 총 64 MiB.



투명 영역을 유지하려면 PNG를, 사진과 호환성을 우선하려면 JPEG를 선택하세요. JPEG는 투명 영역을 선택한 배경색으로 채웁니다. WebP는 투명도와 품질 조정을 지원합니다. 브라우저에서 AVIF 인코딩을 지원하면 해당 출력 옵션이 표시됩니다.



예를 들어 투명 영역이 있는 WebP 로고는 투명 PNG로 바꿀 수 있습니다. JPEG만 받는 양식에는 흰색 배경으로 내보낼 수 있습니다. JPEG를 PNG로 변환하면 원본에서 보이는 세부 정보가 유지됩니다.





**계산 및 처리 방식의 출처** [W3C · PNG](<https://www.w3.org/TR/png-3/>) · [WHATWG · HTML Canvas](<https://html.spec.whatwg.org/multipage/canvas.html#dom-canvas-toblob-dev>)



[ZooChief](<https://docs.toolpony.com/ko/about/>) · [결과 문제 제보](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fko%2Fguides%2Fimage-converter%2F>)

[문서](https://docs.toolpony.com/ko/guides/image-converter/)
