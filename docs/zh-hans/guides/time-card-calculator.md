# 工时卡计算器



记录一周的班次和休息，可设置舍入、计薪规则并导出 CSV。





## 开始使用



1. 输入 08:30、8.30 或 8:30 AM 等时刻。休息时长填小时和分钟，例如 00:30。
2. 设置舍入和可选的计薪规则，再下载 CSV 或打印。可选保存草稿到当前浏览器。







## 示例



### 输入



```
08:30–17:00，休息 00:30
```



### 预期结果



```
08:00:00
```







## 试一试



[打开完整工具](<https://toolpony.com/zh-hans/tools/time-card-calculator/>)







## 使用提示



计算在浏览器内完成。无单位标记的字段请使用一致单位。







## 计算方法



每班先扣休息，再把净工时舍入到所选间隔。结束早于开始时按次日处理。日、周阈值和费率由你设定。



$$
t_i=(e_i-s_i)\bmod 1440-b_i,\qquad t'_i=q\,\operatorname{round}(t_i/q)\quad(q>0)
$$



$$
P=(t_{\rm base}+m\,t_{\rm overtime})r/60
$$

[文档站](https://docs.toolpony.com/zh-hans/guides/time-card-calculator/)
