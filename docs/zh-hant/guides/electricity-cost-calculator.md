# 電費計算器使用指南



從電器輸入功率、製冷量與能效比或兩次電錶讀數計算用量電費，覈對每日和賬期用電量。





## 開始使用



1. 填設備輸入功率、運行時間與電價。電器預設填入可修改的示例值。







## 示例



### 輸入



```
1,000 W，每天 2 小時，30 天，每度 0.2
```



### 預期結果



```
用電 60 度，電費 12
```





<a id="case-study"></a>



## 從窗式空調銘牌算電費



1. LG LW6014ER 的銘牌規格分別列出 6,000 BTU/h 製冷量和 530 W 輸入功率。一臺滿負荷每天開 8 小時，30 天用電 0.53 × 8 × 30 = 127.2 度。每度 0.20，用量電費爲 25.44。



[運行示例](<https://toolpony.com/zh-hant/tools/electricity-cost-calculator/#example-window-power>)





## 用兩次讀數覈對電費



30 天內電錶從 612345.125 走到 612492.365 度，相差 147.24 度，每天平均 4.908 度。每度 0.15，對應用量電費 22.086，賬單上的固定費和稅費另算。



[運行示例](<https://toolpony.com/zh-hant/tools/electricity-cost-calculator/#example-meter-readings>)







## 從製冷量和 EER 推算耗電



製冷量爲 6,000 BTU/h，額定 EER 爲 12 BTU/Wh，輸入功率就是 6,000 ÷ 12 = 500 W。滿負荷每天運行 8 小時，30 天用電 120 度。這裏使用同一工況下的額定 EER。



[運行示例](<https://toolpony.com/zh-hant/tools/electricity-cost-calculator/#example-cooling-eer>)







## 試一試

[打開完整工具 · 電費計算器](<https://toolpony.com/zh-hant/tools/electricity-cost-calculator/>)





## 計算方法



用量電費 = 用電度數 × 單價。電錶用量 = 結束讀數 − 起始讀數。製冷量以 BTU/h 計時除以 EER 得到輸入瓦數，以 W 計時可除以 COP。週期估算每月按 30.44 天、每年按 365.25 天。



$$
E_{\rm kWh}=M_1-M_0,\qquad P_{\rm W}=\frac{Q_{\rm Btu/h}}{\mathrm{EER}}=\frac{Q_{\rm W}}{\mathrm{COP}}
$$



$$
E_{\rm kWh}=P_{\rm kW}\,t_{\rm h}\,f\,n,\qquad C=E_{\rm kWh}\,r
$$







## 計算模式





### 固定天數



- 計算依據 · 額定輸入功率 / 製冷量 / 電錶讀數
- 額定輸入功率
- 功率單位 · W / kW / BTU/h / PS / TR
- 製冷量
- 製冷量單位 · BTU/h / kW / TR
- 能效標識 · EER (BTU/Wh) / COP (W/W)
- 銘牌能效比
- 起始讀數 · kWh
- 結束讀數 · kWh
- 平均負載 · %
- 設備數量
- 每天運行小時 · h
- 天數
- 每度電單價







### 日到年費用



- 電器預設
- 計算依據 · 額定輸入功率 / 製冷量
- 額定輸入功率
- 功率單位 · W / kW / BTU/h / PS / TR
- 製冷量
- 製冷量單位 · BTU/h / kW / TR
- 能效標識 · EER (BTU/Wh) / COP (W/W)
- 銘牌能效比
- 平均負載 · %
- 設備數量
- 使用時長
- 使用時長單位 · 分鐘/天 / 每天運行小時 / 小時/周 / 小時/月 / 天/周 / 天/月 / 天/年 / 月/年
- 每度電單價







**方法來源** [LG · LW6014ER electrical specification](<https://images.thdstatic.com/catalog/pdfImages/e3/e3b8396a-44d1-4372-b120-7532036b2488.pdf>) · [Ohio Consumers’ Counsel · Read an electric meter](<https://www.occ.ohio.gov/sites/default/files/2021-07/OCC-How-to-Read-an-Electric-Meter.pdf>) · [U.S. Department of Energy · Room air conditioner ratings](<https://www.energy.gov/sites/prod/files/2015/06/f22/room_ac_rfi.pdf>) · [NIST · International Table Btu](<https://www.nist.gov/pml/special-publication-811/nist-guide-si-footnotes>)



[ZooChief](<https://docs.toolpony.com/zh-hant/about/>) · [反饋結果問題](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fzh-hant%2Fguides%2Felectricity-cost-calculator%2F>)

[文檔站](https://docs.toolpony.com/zh-hant/guides/electricity-cost-calculator/)
