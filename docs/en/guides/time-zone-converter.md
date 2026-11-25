# Time zone converter guide



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





<a id="case-study"></a>



## A meeting in the repeated hour



1. New York has two 01:30s on November 1, 2026. Shanghai sees the first at 13:30 and the second at 14:30. Choose the occurrence on the invitation, then copy its UTC instant. Swapping the cities keeps that meeting time.



[Run example](<https://toolpony.com/en/tools/time-zone-converter/#example-repeated-meeting>)





## A November call in Havana



Cuba kept UTC−04:00 in November 2026. A call at 09:00 in Havana on November 23 is at 13:00 UTC. Use America/Havana for a local appointment so the rules for that date are applied.



[Run example](<https://toolpony.com/en/tools/time-zone-converter/#example-havana-clock>)







## When the clock skips 30 minutes



On October 4, 2026, Lord Howe Island jumps from 01:59:59 to 02:30:00. Try entering 02:15. To keep the same position within the half-hour gap, choose 01:45 before the jump or 02:45 after it. The latter is 15:45 UTC on October 3.



[Run example](<https://toolpony.com/en/tools/time-zone-converter/#example-half-hour-change>)







## Try it

[Open full tool · Time zone converter](<https://toolpony.com/en/tools/time-zone-converter/>)





## Calculation method



Local times use IANA rules for the selected date. A repeated time has two UTC instants. A skipped time falls in the gap between clock settings. A fixed offset is constant.



$$
T_{\rm target}=T_{\rm source}-O_{\rm source}+O_{\rm target}
$$







## Calculation mode





### IANA



- Date
- Local time
- Source IANA zone
- Target IANA zone
- Repeated hour · Earlier occurrence / Later occurrence







### Fixed UTC offsets



- Date
- Local time
- Source offset
- Target offset







**Method references** [IANA · Time Zone Database](<https://www.iana.org/time-zones>)



[ZooChief](<https://docs.toolpony.com/en/about/>) · [Report a problem with this result](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fen%2Fguides%2Ftime-zone-converter%2F>)

[Documentation](https://docs.toolpony.com/en/guides/time-zone-converter/)
