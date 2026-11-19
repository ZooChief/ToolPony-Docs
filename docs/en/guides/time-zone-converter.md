# Time zone converter



Convert a date and time between IANA zones or fixed UTC offsets.





## Example



### Input



```
2026-01-15 09:00, Asia/Shanghai → America/New_York
```



### Expected result



```
2026-01-14 20:00:00
```







## Try it

[Open full tool · Time zone converter](<https://toolpony.com/en/tools/time-zone-converter/>)





## Calculation method



IANA zones use the browser’s time zone rules. A repeated hour has two possible instants; a skipped hour has none. A fixed UTC offset stays constant throughout the year.



$$
T_{\rm target}=T_{\rm source}-O_{\rm source}+O_{\rm target}
$$







## Calculation mode



**IANA**

- Date
- Local time
- Source IANA zone
- Target IANA zone
- Repeated hour · Earlier occurrence / Later occurrence





**Fixed UTC offsets**

- Date
- Local time
- Source offset
- Target offset







**Method references** [IANA · Time Zone Database](<https://www.iana.org/time-zones>)



[ZooChief](<https://docs.toolpony.com/en/about/>) · [Report a problem with this result](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fen%2Fguides%2Ftime-zone-converter%2F>)

[Documentation](https://docs.toolpony.com/en/guides/time-zone-converter/)
