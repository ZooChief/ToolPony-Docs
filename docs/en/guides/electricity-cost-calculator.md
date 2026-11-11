# Electricity cost calculator



Estimate electricity use and cost by device, load and tariff for a fixed duration or daily to yearly periods.





## Get started



1. Enter the device’s electrical power, use and tariff. Device presets fill editable example values.







## Example



### Input



```
1,000 W, 2 h/day, 30 days, 0.2 per kWh
```



### Expected result



```
60 kWh, cost 12
```







## Try it



[Open full tool](<https://toolpony.com/en/tools/electricity-cost-calculator/>)







## Good to know



The calculation runs in your browser. Use consistent units in fields with no explicit unit.







## Calculation method



Energy equals kW times operating hours, average load and device count. Cost uses a flat tariff. Period estimates use 30.44 days per month and 365.25 per year. A cooling rating describes heat moved; use electrical input power for billing.



$$
E_{\rm kWh}=P_{\rm kW}\,t_{\rm h}\,f\,n,\qquad C=E_{\rm kWh}\,r
$$







## Calculation mode



**Fixed days**

- Power
- Power unit · W / kW / BTU/h / PS / TR
- Average load · %
- Devices
- Hours per day · h
- Days
- Cost per kWh





**Daily to yearly estimates**

- Appliance preset
- Power
- Power unit · W / kW / BTU/h / PS / TR
- Average load · %
- Devices
- Usage
- Usage unit · Minutes per day / Hours per day / Hours per week / Hours per month / Days per week / Days per month / Days per year / Months per year
- Cost per kWh

[Documentation](https://docs.toolpony.com/en/guides/electricity-cost-calculator/)
