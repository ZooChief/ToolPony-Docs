# 时区转换器使用指南



在 IANA 时区或固定 UTC 偏移间换算日期和时间。





## 示例



### 输入



```
2026-01-15 09:00，Asia/Shanghai → America/New_York
```



### 预期结果



```
2026-01-14 20:00:00
```





<a id="case-study"></a>



## 重复时段里的会议



1. 2026 年 11 月 1 日，纽约的凌晨 01:30 出现两次。第一次对应上海 13:30，第二次对应 14:30。按邀请函选择对应的一次，再复制 UTC 时刻。交换两地仍指向同一场会议。



[运行示例](<https://toolpony.com/zh-hans/tools/time-zone-converter/#example-repeated-meeting>)





## 哈瓦那的十一月通话



2026 年 11 月古巴沿用 UTC−04:00。11 月 23 日在哈瓦那上午 09:00 通话，对应 UTC 13:00。约定当地时间时选择 America/Havana，换算会采用当天生效的规则。



[运行示例](<https://toolpony.com/zh-hans/tools/time-zone-converter/#example-havana-clock>)







## 时钟跳过半小时



2026 年 10 月 4 日，豪勋爵岛的时钟从 01:59:59 跳到 02:30:00。试着输入 02:15。把这次预约前移或后移半小时，可以选 01:45 或 02:45。后者对应 UTC 10 月 3 日 15:45。



[运行示例](<https://toolpony.com/zh-hans/tools/time-zone-converter/#example-half-hour-change>)







## 试一试

[打开完整工具 · 时区转换器](<https://toolpony.com/zh-hans/tools/time-zone-converter/>)





## 计算方法



当地时刻按所选日期的 IANA 规则换算。重复时刻对应两个 UTC 时刻，跳过的时刻落在调钟间隙。固定偏移全年相同。



$$
T_{\rm target}=T_{\rm source}-O_{\rm source}+O_{\rm target}
$$







## 计算模式





### IANA



- 日期
- 当地时间
- 原 IANA 时区
- 目标 IANA 时区
- 重复时段 · 较早一次 / 较晚一次







### 固定 UTC 偏移



- 日期
- 当地时间
- 原 UTC 偏移
- 目标 UTC 偏移







**方法来源** [IANA · Time Zone Database](<https://www.iana.org/time-zones>)



[ZooChief](<https://docs.toolpony.com/zh-hans/about/>) · [反馈结果问题](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fzh-hans%2Fguides%2Ftime-zone-converter%2F>)

[文档站](https://docs.toolpony.com/zh-hans/guides/time-zone-converter/)
