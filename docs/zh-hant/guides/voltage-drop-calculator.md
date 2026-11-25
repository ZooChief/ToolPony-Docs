# 電壓降計算器使用指南



用線規、截面積或已知阻抗計算直流、單相和三相平衡電路壓降。





## 開始使用



1. 選擇模型。三相輸入線電壓與線電流，距離只填單程。
2. 距離上限按你設定的壓降比例計算。載流量、溫度和安裝要求另行覈對。







## 示例



### 輸入



```
120 V、單相、500 ft、1 A、1.2 Ω/km
```



### 預期結果



```
壓降 0.37 V，0.30%
```





<a id="case-study"></a>



## 按電纜表計算



1. 迴路係數 1 mV/(A·m)、單程 50 m、電流 100 A，這段電纜壓降 5 V。施耐德的算例再加上游的 10 V，整條路徑合計 15 V。



[運行示例](<https://toolpony.com/zh-hant/tools/voltage-drop-calculator/#example-cable-table>)





## 三相併聯迴路



每相兩條相同線路均分 20 A。400 V 系統單程 100 m，R 爲 1 Ω/km、X 爲 0.5 Ω/km、滯後功率因數 0.8，壓降爲 1.91 V，負載端爲 398.09 V。



[運行示例](<https://toolpony.com/zh-hant/tools/voltage-drop-calculator/#example-parallel-cable>)







## 壓降超過電源電壓



24 V 直流、10 A、單程 1 km、每根線 5 Ω/km，往返壓降爲 100 V。按這個電流，模型無法給出負載端電壓。



[運行示例](<https://toolpony.com/zh-hant/tools/voltage-drop-calculator/#example-cable-limit>)







## 試一試

[打開完整工具 · 電壓降計算器](<https://toolpony.com/zh-hant/tools/voltage-drop-calculator/>)





## 計算方法



填單程長度和相同的並聯導體數。直流或單相的 I·L·R 乘 2，平衡三相乘 √3。交流滯後負載按功率因數合成 R、X。線徑估算採用約 20 °C 的標稱電阻，實際線纜請用製造商數據。



$$
\Delta V=\frac{k I L R_{\rm eff}}{n},\quad k=2\ \text{(DC, 1)}\phi,\quad k=\sqrt{3}\ \text{(3)}\phi
$$



$$
R_{\rm eff}=R\cos\theta+X\sin\theta,\quad \%\Delta V=100\frac{\Delta V}{V_s}
$$







## 計算模式





### 已知電阻或阻抗



- 資料給出的量 · 導體阻抗 / 迴路壓降係數
- 每單位長度的電阻或阻抗
- 每長度單位 · Ω/km / Ω/m / mΩ/m / Ω/1000 ft / Ω/ft / mΩ/ft
- 表列迴路壓降係數 · mV/(A·m)
- 電壓 · V
- 電路類型 · DC / 單相交流 / 三相交流
- 每相併聯導體數
- 單程距離
- 長度單位 · ft / m / mi / km
- 電流 · A
- 距離估算的壓降上限 · %







### 按線規估算



- 材料 · 銅 / 鋁 / 銀 / 金
- 線規
- 電壓 · V
- 電路類型 · DC / 單相交流 / 三相交流
- 每相併聯導體數
- 單程距離
- 長度單位 · ft / m / mi / km
- 電流 · A
- 距離估算的壓降上限 · %







### 按截面積估算



- 材料 · 銅 / 鋁 / 銀 / 金
- 截面積 · mm²
- 電壓 · V
- 電路類型 · DC / 單相交流 / 三相交流
- 每相併聯導體數
- 單程距離
- 長度單位 · ft / m / mi / km
- 電流 · A
- 距離估算的壓降上限 · %







### 電阻和電抗



- 電阻
- 每單位長度的電抗
- 每長度單位 · Ω/km / Ω/m / mΩ/m / Ω/1000 ft / Ω/ft / mΩ/ft
- 滯後功率因數
- 電壓 · V
- 電路類型 · DC / 單相交流 / 三相交流
- 每相併聯導體數
- 單程距離
- 長度單位 · ft / m / mi / km
- 電流 · A
- 距離估算的壓降上限 · %







**方法來源** [Schneider Electric · Voltage drop in steady load conditions](<https://www.electrical-installation.org/enwiki/Calculation_of_voltage_drop_in_steady_load_conditions>)



[ZooChief](<https://docs.toolpony.com/zh-hant/about/>) · [反饋結果問題](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fzh-hant%2Fguides%2Fvoltage-drop-calculator%2F>)

[文檔站](https://docs.toolpony.com/zh-hant/guides/voltage-drop-calculator/)
