# 配速计算器使用指南



在配速、用时和距离之间反算，支持分段比较、单位转换与完赛时间估算。





## 示例



### 输入



```
10 km，用时 00:50:00
```



### 预期结果



```
每公里 05:00，速度 12 km/h
```





<a id="case-study"></a>



## 核对两个公里检查点



1. 运动表在 1 公里处显示 3:25，2 公里处显示 6:55。选择累计记录，第二公里的实际用时是 3:30，两公里平均配速为 3:27.5/公里。
2. 计划 4:00:00 跑完全马，检查点选每 1 公里。最后一段为 195 米，计入这一段后，最后的累计时间恰为 4:00:00。



[运行示例](<https://toolpony.com/zh-hans/tools/pace-calculator/#example-watch-checkpoints>)





## 试一试

[打开完整工具 · 配速计算器](<https://toolpony.com/zh-hans/tools/pace-calculator/>)





## 计算方法



平均配速为总用时除以总距离。两段计时表示分和秒，三段表示时、分、秒。支持 100 条实测分段或 500 个按匀速推算的检查点。



$$
p=\frac{t}{d},\qquad v=\frac{d}{t}
$$







## 计算模式





### 求配速和完赛时间



- 距离
- 距离单位 · km / mi / m / yd
- 用时
- 配速单位 · km / mi / 100 m / 100 yd
- 目标距离 · 5 km / 10 km / 半程马拉松 / 全程马拉松 / 自定义公里
- 自定义目标距离 · km







### 求用时



- 距离
- 距离单位 · km / mi / m / yd
- 配速（分:秒）
- 配速单位 · km / mi / 100 m / 100 yd







### 求距离



- 用时
- 配速（分:秒）
- 配速单位 · km / mi / 100 m / 100 yd







### 配速换算



- 配速（分:秒）
- 配速单位 · km / mi / 100 m / 100 yd







### 比较分段



- 分段记录
- 距离单位 · km / mi / m / yd
- 配速单位 · km / mi / 100 m / 100 yd
- 各行采用累计里程和时间







### 分段计划



- 目标距离 · 5 km / 10 km / 半程马拉松 / 全程马拉松 / 自定义公里
- 自定义目标距离 · km
- 目标完赛时间
- 检查点间距 · 1 km / 1 mi / 400 m / 100 m / 5 km / 10 km
- 配速单位 · km / mi / 100 m / 100 yd







**方法来源** [World Athletics · Marathon](<https://worldathletics.org/disciplines/road-running-event/marathon>) · [NIST · Unit conversion factors](<https://www.nist.gov/pml/special-publication-811/nist-guide-si-appendix-b-conversion-factors/nist-guide-si-appendix-b8>)



[ZooChief](<https://docs.toolpony.com/zh-hans/about/>) · [反馈结果问题](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fzh-hans%2Fguides%2Fpace-calculator%2F>)

[文档站](https://docs.toolpony.com/zh-hans/guides/pace-calculator/)
