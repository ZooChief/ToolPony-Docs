# Pace calculator guide



Solve pace, elapsed time and distance. Compare split paces, convert units, and estimate a finish time.





## Example



### Input



```
10 km in 00:50:00
```



### Expected result



```
05:00 per km, 12 km/h
```





<a id="case-study"></a>



## Read two kilometre checkpoints



1. A watch shows 3:25 at 1 km and 6:55 at 2 km. Choose cumulative splits. The second kilometre took 3:30. Average pace over the two kilometres is 3:27.5/km.
2. For a 4:00:00 marathon, plan 1 km checkpoints. The last segment is 195 m. The final checkpoint is exactly 4:00:00, including the fractional segment.



[Run example](<https://toolpony.com/en/tools/pace-calculator/#example-watch-checkpoints>)





## Try it

[Open full tool · Pace calculator](<https://toolpony.com/en/tools/pace-calculator/>)





## Calculation method



Pace is total elapsed time divided by total distance. Two clock fields are minutes and seconds. Three are hours, minutes and seconds. Enter up to 100 observed splits or plan up to 500 even-pace checkpoints.



$$
p=\frac{t}{d},\qquad v=\frac{d}{t}
$$







## Calculation mode





### Find pace and finish time



- Distance
- Distance unit · km / mi / m / yd
- Elapsed time
- Pace per · km / mi / 100 m / 100 yd
- Target distance · 5 km / 10 km / Half marathon / Marathon / Custom km
- Custom race distance · km







### Find elapsed time



- Distance
- Distance unit · km / mi / m / yd
- Pace (min:sec)
- Pace per · km / mi / 100 m / 100 yd







### Find distance



- Elapsed time
- Pace (min:sec)
- Pace per · km / mi / 100 m / 100 yd







### Convert pace units



- Pace (min:sec)
- Pace per · km / mi / 100 m / 100 yd







### Compare splits



- Splits
- Distance unit · km / mi / m / yd
- Pace per · km / mi / 100 m / 100 yd
- Rows are cumulative checkpoints







### Checkpoint plan



- Target distance · 5 km / 10 km / Half marathon / Marathon / Custom km
- Custom race distance · km
- Target finish time
- Checkpoint interval · 1 km / 1 mi / 400 m / 100 m / 5 km / 10 km
- Pace per · km / mi / 100 m / 100 yd







**Method references** [World Athletics · Marathon](<https://worldathletics.org/disciplines/road-running-event/marathon>) · [NIST · Unit conversion factors](<https://www.nist.gov/pml/special-publication-811/nist-guide-si-appendix-b-conversion-factors/nist-guide-si-appendix-b8>)



[ZooChief](<https://docs.toolpony.com/en/about/>) · [Report a problem with this result](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fen%2Fguides%2Fpace-calculator%2F>)

[Documentation](https://docs.toolpony.com/en/guides/pace-calculator/)
