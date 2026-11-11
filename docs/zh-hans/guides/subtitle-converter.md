# 字幕转换与时轴



互转 SRT 与 WebVTT，偏移或缩放时轴，并在导出前检查重叠字幕。





## 开始使用



1. 粘贴字幕文本或导入 SRT 或 VTT 文件，再选择导出格式。
2. 正偏移会延后字幕。缩放先从锚点算相对时间，乘上比例后再加偏移。下载前可检查裁切和重叠。







## 示例



### 输入



```
1
00:00:00,120 --> 00:00:01,400
A line
Second line

2
00:00:01,350 --> 00:00:02,700
Overlap 50 ms
```



### 预期结果



```
WEBVTT

00:00:00.120 --> 00:00:01.400
A line
Second line

00:00:01.350 --> 00:00:02.700
Overlap 50 ms
```







## 试一试



[打开完整工具](<https://toolpony.com/zh-hans/tools/subtitle-converter/>)







## 适用范围



最多 1 MiB 文本、10,000 条字幕。结束在零点前的字幕会被移除，跨零点的字幕从零开始。SRT 无法表达所有 WebVTT 位置、样式和编号。

[文档站](https://docs.toolpony.com/zh-hans/guides/subtitle-converter/)
