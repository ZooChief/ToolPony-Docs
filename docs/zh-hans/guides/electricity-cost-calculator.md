# 电费计算器使用指南



从电器输入功率、制冷量与能效比或两次电表读数计算用量电费，核对每日和账期用电量。





## 开始使用



1. 填设备输入功率、运行时间与电价。电器预设填入可修改的示例值。







## 示例



### 输入



```
1,000 W，每天 2 小时，30 天，每度 0.2
```



### 预期结果



```
用电 60 度，电费 12
```





<a id="case-study"></a>



## 从窗式空调铭牌算电费



1. LG LW6014ER 的铭牌规格分别列出 6,000 BTU/h 制冷量和 530 W 输入功率。一台满负荷每天开 8 小时，30 天用电 0.53 × 8 × 30 = 127.2 度。每度 0.20，用量电费为 25.44。



[运行示例](<https://toolpony.com/zh-hans/tools/electricity-cost-calculator/#example-window-power>)





## 用两次读数核对电费



30 天内电表从 612345.125 走到 612492.365 度，相差 147.24 度，每天平均 4.908 度。每度 0.15，对应用量电费 22.086，账单上的固定费和税费另算。



[运行示例](<https://toolpony.com/zh-hans/tools/electricity-cost-calculator/#example-meter-readings>)







## 从制冷量和 EER 推算耗电



制冷量为 6,000 BTU/h，额定 EER 为 12 BTU/Wh，输入功率就是 6,000 ÷ 12 = 500 W。满负荷每天运行 8 小时，30 天用电 120 度。这里使用同一工况下的额定 EER。



[运行示例](<https://toolpony.com/zh-hans/tools/electricity-cost-calculator/#example-cooling-eer>)







## 试一试

[打开完整工具 · 电费计算器](<https://toolpony.com/zh-hans/tools/electricity-cost-calculator/>)





## 计算方法



用量电费 = 用电度数 × 单价。电表用量 = 结束读数 − 起始读数。制冷量以 BTU/h 计时除以 EER 得到输入瓦数，以 W 计时可除以 COP。周期估算每月按 30.44 天、每年按 365.25 天。



$$
E_{\rm kWh}=M_1-M_0,\qquad P_{\rm W}=\frac{Q_{\rm Btu/h}}{\mathrm{EER}}=\frac{Q_{\rm W}}{\mathrm{COP}}
$$



$$
E_{\rm kWh}=P_{\rm kW}\,t_{\rm h}\,f\,n,\qquad C=E_{\rm kWh}\,r
$$







## 计算模式





### 固定天数



- 计算依据 · 额定输入功率 / 制冷量 / 电表读数
- 额定输入功率
- 功率单位 · W / kW / BTU/h / PS / TR
- 制冷量
- 制冷量单位 · BTU/h / kW / TR
- 能效标识 · EER (BTU/Wh) / COP (W/W)
- 铭牌能效比
- 起始读数 · kWh
- 结束读数 · kWh
- 平均负载 · %
- 设备数量
- 每天运行小时 · h
- 天数
- 每度电单价







### 日到年费用



- 电器预设
- 计算依据 · 额定输入功率 / 制冷量
- 额定输入功率
- 功率单位 · W / kW / BTU/h / PS / TR
- 制冷量
- 制冷量单位 · BTU/h / kW / TR
- 能效标识 · EER (BTU/Wh) / COP (W/W)
- 铭牌能效比
- 平均负载 · %
- 设备数量
- 使用时长
- 使用时长单位 · 分钟/天 / 每天运行小时 / 小时/周 / 小时/月 / 天/周 / 天/月 / 天/年 / 月/年
- 每度电单价







**方法来源** [LG · LW6014ER electrical specification](<https://images.thdstatic.com/catalog/pdfImages/e3/e3b8396a-44d1-4372-b120-7532036b2488.pdf>) · [Ohio Consumers’ Counsel · Read an electric meter](<https://www.occ.ohio.gov/sites/default/files/2021-07/OCC-How-to-Read-an-Electric-Meter.pdf>) · [U.S. Department of Energy · Room air conditioner ratings](<https://www.energy.gov/sites/prod/files/2015/06/f22/room_ac_rfi.pdf>) · [NIST · International Table Btu](<https://www.nist.gov/pml/special-publication-811/nist-guide-si-footnotes>)



[ZooChief](<https://docs.toolpony.com/zh-hans/about/>) · [反馈结果问题](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fzh-hans%2Fguides%2Felectricity-cost-calculator%2F>)

[文档站](https://docs.toolpony.com/zh-hans/guides/electricity-cost-calculator/)
