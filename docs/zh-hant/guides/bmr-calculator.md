# 基礎代謝與熱量計算器使用指南



使用三種公式估算靜息能量消耗與每日總能量消耗，支持公制和美製。





## 示例



### 輸入



```
男性公式，30 歲，70 kg，175 cm，Mifflin–St Jeor
```



### 預期結果



```
靜息約 1,648.75 kcal/天
```





<a id="case-study"></a>



## 用去脂體重估算



1. 體重爲 70 公斤、假設體脂率爲 20%，去脂體重就是 56 公斤。Katch–McArdle 公式給出的靜息估算爲 370 + 21.6 × 56 = 1,579.6 千卡/天。
2. 活動係數取 1.20 時，每日總消耗估算是 1,895.52 千卡。將假設改爲 1.55，總消耗變爲 2,448.38 千卡，兩次使用同一靜息估算。



[運行示例](<https://toolpony.com/zh-hant/tools/bmr-calculator/#example-lean-mass>)





## 試一試

[打開完整工具 · 基礎代謝與熱量計算器](<https://toolpony.com/zh-hant/tools/bmr-calculator/>)





## 計算方法



靜息消耗使用 Mifflin–St Jeor、修訂版 Harris–Benedict 或 Katch–McArdle 估算。每日總消耗爲估算值乘以活動係數。







## 計算模式





### 公制



- 計算公式 · Mifflin–St Jeor / 修訂版 Harris–Benedict / Katch–McArdle
- 年齡
- 公式分組 · 男性 / 女性
- 體重 · kg
- 身高 · cm
- Katch–McArdle 的體脂率 · %
- 活動係數
- 能量單位 · kcal/天 / kJ/天







### 美製



- 計算公式 · Mifflin–St Jeor / 修訂版 Harris–Benedict / Katch–McArdle
- 年齡
- 公式分組 · 男性 / 女性
- 體重 · lb
- 身高英尺部分 · ft
- 額外英寸 · in
- Katch–McArdle 的體脂率 · %
- 活動係數
- 能量單位 · kcal/天 / kJ/天







**方法來源** [Mifflin et al. (1990)](<https://pubmed.ncbi.nlm.nih.gov/2305711/>) · [Roza &amp; Shizgal (1984)](<https://pubmed.ncbi.nlm.nih.gov/6741850/>) · [Cunningham (1991) · Fat-free mass and resting energy](<https://pubmed.ncbi.nlm.nih.gov/1957828/>) · [NIST · Thermochemical calorie](<https://www.nist.gov/pml/special-publication-811/nist-guide-si-appendix-b-conversion-factors/nist-guide-si-appendix-b8>)



[ZooChief](<https://docs.toolpony.com/zh-hant/about/>) · [反饋結果問題](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fzh-hant%2Fguides%2Fbmr-calculator%2F>)

[文檔站](https://docs.toolpony.com/zh-hant/guides/bmr-calculator/)
