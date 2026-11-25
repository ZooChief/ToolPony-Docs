# Electricity cost calculator guide



Estimate an energy charge from electrical input, cooling capacity and efficiency, or two meter readings. Inspect kWh and cost per day or billing period.





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





<a id="case-study"></a>



## Read the watts on a window AC



1. The LG LW6014ER spec sheet lists 6,000 BTU/h of cooling and 530 W of electrical input. At full load for 8 hours a day over 30 days, one unit uses 0.53 × 8 × 30 = 127.2 kWh. At 0.20 per kWh the energy charge is 25.44.



[Run example](<https://toolpony.com/en/tools/electricity-cost-calculator/#example-window-power>)





## Check a meter reading against a bill



An import meter rises from 612345.125 to 612492.365 kWh over 30 days. The difference is 147.24 kWh, or 4.908 kWh per day. At 0.15 per kWh this adds 22.086 to the bill before fixed charges and taxes.



[Run example](<https://toolpony.com/en/tools/electricity-cost-calculator/#example-meter-readings>)







## Estimate input power from an EER rating



For a unit rated at 6,000 BTU/h with a rated EER of 12 BTU/Wh, electrical input is 6,000 ÷ 12 = 500 W. Running 8 hours a day for 30 days at full load takes 120 kWh. Use EER at the stated operating condition for this calculation.



[Run example](<https://toolpony.com/en/tools/electricity-cost-calculator/#example-cooling-eer>)







## Try it

[Open full tool · Electricity cost calculator](<https://toolpony.com/en/tools/electricity-cost-calculator/>)





## Calculation method



Energy charge = kWh × the unit rate. Metered kWh = ending reading − starting reading. For rated cooling, BTU/h ÷ EER gives electrical watts, or divide cooling watts by COP. Period estimates use 30.44 days per month and 365.25 per year.



$$
E_{\rm kWh}=M_1-M_0,\qquad P_{\rm W}=\frac{Q_{\rm Btu/h}}{\mathrm{EER}}=\frac{Q_{\rm W}}{\mathrm{COP}}
$$



$$
E_{\rm kWh}=P_{\rm kW}\,t_{\rm h}\,f\,n,\qquad C=E_{\rm kWh}\,r
$$







## Calculation mode





### Fixed days



- Estimate from · Electrical input / Cooling capacity / Meter readings
- Electrical input
- Power unit · W / kW / BTU/h / PS / TR
- Cooling capacity
- Cooling capacity unit · BTU/h / kW / TR
- Efficiency rating · EER (BTU/Wh) / COP (W/W)
- Rated efficiency
- Starting reading · kWh
- Ending reading · kWh
- Average load · %
- Devices
- Hours per day · h
- Days
- Cost per kWh







### Daily to yearly estimates



- Appliance preset
- Estimate from · Electrical input / Cooling capacity
- Electrical input
- Power unit · W / kW / BTU/h / PS / TR
- Cooling capacity
- Cooling capacity unit · BTU/h / kW / TR
- Efficiency rating · EER (BTU/Wh) / COP (W/W)
- Rated efficiency
- Average load · %
- Devices
- Usage
- Usage unit · Minutes per day / Hours per day / Hours per week / Hours per month / Days per week / Days per month / Days per year / Months per year
- Cost per kWh







**Method references** [LG · LW6014ER electrical specification](<https://images.thdstatic.com/catalog/pdfImages/e3/e3b8396a-44d1-4372-b120-7532036b2488.pdf>) · [Ohio Consumers’ Counsel · Read an electric meter](<https://www.occ.ohio.gov/sites/default/files/2021-07/OCC-How-to-Read-an-Electric-Meter.pdf>) · [U.S. Department of Energy · Room air conditioner ratings](<https://www.energy.gov/sites/prod/files/2015/06/f22/room_ac_rfi.pdf>) · [NIST · International Table Btu](<https://www.nist.gov/pml/special-publication-811/nist-guide-si-footnotes>)



[ZooChief](<https://docs.toolpony.com/en/about/>) · [Report a problem with this result](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fen%2Fguides%2Felectricity-cost-calculator%2F>)

[Documentation](https://docs.toolpony.com/en/guides/electricity-cost-calculator/)
