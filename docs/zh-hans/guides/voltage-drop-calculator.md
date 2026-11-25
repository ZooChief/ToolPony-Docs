# 电压降计算器使用指南



用线规、截面积或已知阻抗计算直流、单相和三相平衡电路压降。





## 开始使用



1. 选择模型。三相输入线电压与线电流，距离只填单程。
2. 距离上限按你设定的压降比例计算。载流量、温度和安装要求另行核对。







## 示例



### 输入



```
120 V、单相、500 ft、1 A、1.2 Ω/km
```



### 预期结果



```
压降 0.37 V，0.30%
```





<a id="case-study"></a>



## 按电缆表计算



1. 回路系数 1 mV/(A·m)、单程 50 m、电流 100 A，这段电缆压降 5 V。施耐德的算例再加上游的 10 V，整条路径合计 15 V。



[运行示例](<https://toolpony.com/zh-hans/tools/voltage-drop-calculator/#example-cable-table>)





## 三相并联回路



每相两条相同线路均分 20 A。400 V 系统单程 100 m，R 为 1 Ω/km、X 为 0.5 Ω/km、滞后功率因数 0.8，压降为 1.91 V，负载端为 398.09 V。



[运行示例](<https://toolpony.com/zh-hans/tools/voltage-drop-calculator/#example-parallel-cable>)







## 压降超过电源电压



24 V 直流、10 A、单程 1 km、每根线 5 Ω/km，往返压降为 100 V。按这个电流，模型无法给出负载端电压。



[运行示例](<https://toolpony.com/zh-hans/tools/voltage-drop-calculator/#example-cable-limit>)







## 试一试

[打开完整工具 · 电压降计算器](<https://toolpony.com/zh-hans/tools/voltage-drop-calculator/>)





## 计算方法



填单程长度和相同的并联导体数。直流或单相的 I·L·R 乘 2，平衡三相乘 √3。交流滞后负载按功率因数合成 R、X。线径估算采用约 20 °C 的标称电阻，实际线缆请用制造商数据。



$$
\Delta V=\frac{k I L R_{\rm eff}}{n},\quad k=2\ \text{(DC, 1)}\phi,\quad k=\sqrt{3}\ \text{(3)}\phi
$$



$$
R_{\rm eff}=R\cos\theta+X\sin\theta,\quad \%\Delta V=100\frac{\Delta V}{V_s}
$$







## 计算模式





### 已知电阻或阻抗



- 资料给出的量 · 导体阻抗 / 回路压降系数
- 每单位长度的电阻或阻抗
- 每长度单位 · Ω/km / Ω/m / mΩ/m / Ω/1000 ft / Ω/ft / mΩ/ft
- 表列回路压降系数 · mV/(A·m)
- 电压 · V
- 电路类型 · DC / 单相交流 / 三相交流
- 每相并联导体数
- 单程距离
- 长度单位 · ft / m / mi / km
- 电流 · A
- 距离估算的压降上限 · %







### 按线规估算



- 材料 · 铜 / 铝 / 银 / 金
- 线规
- 电压 · V
- 电路类型 · DC / 单相交流 / 三相交流
- 每相并联导体数
- 单程距离
- 长度单位 · ft / m / mi / km
- 电流 · A
- 距离估算的压降上限 · %







### 按截面积估算



- 材料 · 铜 / 铝 / 银 / 金
- 截面积 · mm²
- 电压 · V
- 电路类型 · DC / 单相交流 / 三相交流
- 每相并联导体数
- 单程距离
- 长度单位 · ft / m / mi / km
- 电流 · A
- 距离估算的压降上限 · %







### 电阻和电抗



- 电阻
- 每单位长度的电抗
- 每长度单位 · Ω/km / Ω/m / mΩ/m / Ω/1000 ft / Ω/ft / mΩ/ft
- 滞后功率因数
- 电压 · V
- 电路类型 · DC / 单相交流 / 三相交流
- 每相并联导体数
- 单程距离
- 长度单位 · ft / m / mi / km
- 电流 · A
- 距离估算的压降上限 · %







**方法来源** [Schneider Electric · Voltage drop in steady load conditions](<https://www.electrical-installation.org/enwiki/Calculation_of_voltage_drop_in_steady_load_conditions>)



[ZooChief](<https://docs.toolpony.com/zh-hans/about/>) · [反馈结果问题](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fzh-hans%2Fguides%2Fvoltage-drop-calculator%2F>)

[文档站](https://docs.toolpony.com/zh-hans/guides/voltage-drop-calculator/)
