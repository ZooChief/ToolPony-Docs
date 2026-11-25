# 基础代谢与热量计算器使用指南



使用三种公式估算静息能量消耗与每日总能量消耗，支持公制和美制。





## 示例



### 输入



```
男性公式，30 岁，70 kg，175 cm，Mifflin–St Jeor
```



### 预期结果



```
静息约 1,648.75 kcal/天
```





<a id="case-study"></a>



## 用去脂体重估算



1. 体重为 70 公斤、假设体脂率为 20%，去脂体重就是 56 公斤。Katch–McArdle 公式给出的静息估算为 370 + 21.6 × 56 = 1,579.6 千卡/天。
2. 活动系数取 1.20 时，每日总消耗估算是 1,895.52 千卡。将假设改为 1.55，总消耗变为 2,448.38 千卡，两次使用同一静息估算。



[运行示例](<https://toolpony.com/zh-hans/tools/bmr-calculator/#example-lean-mass>)





## 试一试

[打开完整工具 · 基础代谢与热量计算器](<https://toolpony.com/zh-hans/tools/bmr-calculator/>)





## 计算方法



静息消耗使用 Mifflin–St Jeor、修订版 Harris–Benedict 或 Katch–McArdle 估算。每日总消耗为估算值乘以活动系数。







## 计算模式





### 公制



- 计算公式 · Mifflin–St Jeor / 修订版 Harris–Benedict / Katch–McArdle
- 年龄
- 公式分组 · 男性 / 女性
- 体重 · kg
- 身高 · cm
- Katch–McArdle 的体脂率 · %
- 活动系数
- 能量单位 · kcal/天 / kJ/天







### 美制



- 计算公式 · Mifflin–St Jeor / 修订版 Harris–Benedict / Katch–McArdle
- 年龄
- 公式分组 · 男性 / 女性
- 体重 · lb
- 身高英尺部分 · ft
- 额外英寸 · in
- Katch–McArdle 的体脂率 · %
- 活动系数
- 能量单位 · kcal/天 / kJ/天







**方法来源** [Mifflin et al. (1990)](<https://pubmed.ncbi.nlm.nih.gov/2305711/>) · [Roza &amp; Shizgal (1984)](<https://pubmed.ncbi.nlm.nih.gov/6741850/>) · [Cunningham (1991) · Fat-free mass and resting energy](<https://pubmed.ncbi.nlm.nih.gov/1957828/>) · [NIST · Thermochemical calorie](<https://www.nist.gov/pml/special-publication-811/nist-guide-si-appendix-b-conversion-factors/nist-guide-si-appendix-b8>)



[ZooChief](<https://docs.toolpony.com/zh-hans/about/>) · [反馈结果问题](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fzh-hans%2Fguides%2Fbmr-calculator%2F>)

[文档站](https://docs.toolpony.com/zh-hans/guides/bmr-calculator/)
