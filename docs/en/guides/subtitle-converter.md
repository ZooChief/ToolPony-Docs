# Subtitle converter



Convert SRT and WebVTT, shift or scale their timing, and check overlapping cues before export.





## Get started



1. Paste subtitle text or import an SRT or VTT file. Choose an output format.
2. A positive offset delays cues. For scaling, measure from the anchor, multiply by the time scale, then add the offset. Check clipping and overlaps before downloading.







## Example



### Input



```
1
00:00:00,120 --> 00:00:01,400
A line
Second line

2
00:00:01,350 --> 00:00:02,700
Overlap 50 ms
```



### Expected result



```
WEBVTT

00:00:00.120 --> 00:00:01.400
A line
Second line

00:00:01.350 --> 00:00:02.700
Overlap 50 ms
```







## Try it

[Open full tool · Subtitle converter](<https://toolpony.com/en/tools/subtitle-converter/>)





## Limits



Up to 1 MiB of text and 10,000 cues. Cues ending before zero are removed, and crossing cues start at zero. SRT cannot carry all WebVTT positioning, styles or cue identifiers.





**Method references** [W3C · WebVTT](<https://www.w3.org/TR/webvtt1/>)



[ZooChief](<https://docs.toolpony.com/en/about/>) · [Report a problem with this result](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fen%2Fguides%2Fsubtitle-converter%2F>)

[Documentation](https://docs.toolpony.com/en/guides/subtitle-converter/)
