# Time card calculator



Record a week of shifts and breaks, with rounding, editable pay rules and CSV export.





## Get started



1. Enter clocks such as 08:30, 8.30 or 8:30 AM. Enter breaks as hours and minutes, such as 00:30.
2. Choose rounding and optional pay rules. Download CSV or print the report. Saving the draft to this browser is optional.







## Example



### Input



```
08:30–17:00 with a 00:30 break
```



### Expected result



```
08:00:00
```







## Try it



[Open full tool](<https://toolpony.com/en/tools/time-card-calculator/>)







## Good to know



The calculation runs in your browser. Use consistent units in fields with no explicit unit.







## Calculation method



Subtract each break from the shift, then round the net time to the selected interval. An earlier end means the next day. Daily or weekly thresholds and rates are user settings.



$$
t_i=(e_i-s_i)\bmod 1440-b_i,\qquad t'_i=q\,\operatorname{round}(t_i/q)\quad(q>0)
$$



$$
P=(t_{\rm base}+m\,t_{\rm overtime})r/60
$$

[Documentation](https://docs.toolpony.com/en/guides/time-card-calculator/)
