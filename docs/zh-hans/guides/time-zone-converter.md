# 时区转换器



在 IANA 时区或固定 UTC 偏移间换算日期和时间。





## 开始使用



1. 按示例填写数值，或输入你自己的测量值。
2. 计算后可复制结果或下载明细。







## 示例



### 输入



```
2026-01-15 09:00，Asia/Shanghai → America/New_York
```



### 预期结果



```
2026-01-14 20:00:00
```







## 试一试



[打开完整工具](<https://toolpony.com/zh-hans/tools/time-zone-converter/>)







## 使用提示



计算在浏览器内完成。无单位标记的字段请使用一致单位。







## 计算方法



IANA 时区使用浏览器的时区规则，重复时刻有两个可能值，跳过的时刻无对应值。固定 UTC 偏移全年不变。



$$
T_{\rm target}=T_{\rm source}-O_{\rm source}+O_{\rm target}
$$







## 计算模式



**IANA**

- 日期
- 当地时间
- 原 IANA 时区
- 目标 IANA 时区
- 重复时段 · 较早一次 / 较晚一次





**固定 UTC 偏移**

- 日期
- 当地时间
- 原 UTC 偏移
- 目标 UTC 偏移

[文档站](https://docs.toolpony.com/zh-hans/guides/time-zone-converter/)
