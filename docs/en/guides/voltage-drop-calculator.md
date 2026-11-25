# Voltage drop calculator guide



Estimate voltage drop in DC, single-phase or balanced three-phase wiring from cable size or resistance.





## Get started



1. Choose a model. For three phase, enter line-to-line voltage and line current. Enter one-way distance once.
2. The distance limit uses your chosen drop percentage. Check ampacity, temperature and installation requirements separately.







## Example



### Input



```
120 V, single phase, 500 ft, 1 A and 1.2 Ω/km
```



### Expected result



```
0.37 V drop, 0.30%
```





<a id="case-study"></a>



## Use a cable table



1. At 1 mV/(A·m), a 50 m cable carrying 100 A drops 5 V. Schneider’s example adds a separate upstream drop of 10 V to obtain 15 V for the complete path.



[Run example](<https://toolpony.com/en/tools/voltage-drop-calculator/#example-cable-table>)





## Parallel three-phase run



Two identical runs per phase share 20 A. Over 100 m at 400 V, R = 1 Ω/km, X = 0.5 Ω/km and a lagging power factor of 0.8 give a 1.91 V drop and 398.09 V at the load.



[Run example](<https://toolpony.com/en/tools/voltage-drop-calculator/#example-parallel-cable>)







## Drop exceeds supply



A 24 V DC source, 10 A and a 1 km one-way run at 5 Ω/km imply a 100 V drop. At the assumed current this model cannot estimate the load voltage.



[Run example](<https://toolpony.com/en/tools/voltage-drop-calculator/#example-cable-limit>)







## Try it

[Open full tool · Voltage drop calculator](<https://toolpony.com/en/tools/voltage-drop-calculator/>)





## Calculation method



Use one-way length and identical parallel conductors. Multiply I·L·R by 2 for DC or single phase and √3 for balanced three phase. For lagging AC, R and X contribute through the power factor. Wire-size estimates use nominal resistance near 20 °C; use manufacturer data for the actual cable.



$$
\Delta V=\frac{k I L R_{\rm eff}}{n},\quad k=2\ \text{(DC, 1)}\phi,\quad k=\sqrt{3}\ \text{(3)}\phi
$$



$$
R_{\rm eff}=R\cos\theta+X\sin\theta,\quad \%\Delta V=100\frac{\Delta V}{V_s}
$$







## Calculation mode





### Known resistance or impedance



- Published value · Conductor impedance / Circuit drop coefficient
- Resistance or impedance per length
- Unit per length · Ω/km / Ω/m / mΩ/m / Ω/1000 ft / Ω/ft / mΩ/ft
- Tabulated circuit coefficient · mV/(A·m)
- Voltage · V
- Circuit · DC / Single-phase AC / Three-phase AC
- Conductors per phase
- One-way distance
- Length unit · ft / m / mi / km
- Current · A
- Drop limit for distance estimate · %







### Estimate from wire gauge



- Material · Copper / Aluminum / Silver / Gold
- Wire size
- Voltage · V
- Circuit · DC / Single-phase AC / Three-phase AC
- Conductors per phase
- One-way distance
- Length unit · ft / m / mi / km
- Current · A
- Drop limit for distance estimate · %







### Estimate from area



- Material · Copper / Aluminum / Silver / Gold
- Cross-sectional area · mm²
- Voltage · V
- Circuit · DC / Single-phase AC / Three-phase AC
- Conductors per phase
- One-way distance
- Length unit · ft / m / mi / km
- Current · A
- Drop limit for distance estimate · %







### Resistance and reactance



- Resistance
- Reactance per length
- Unit per length · Ω/km / Ω/m / mΩ/m / Ω/1000 ft / Ω/ft / mΩ/ft
- Lagging power factor
- Voltage · V
- Circuit · DC / Single-phase AC / Three-phase AC
- Conductors per phase
- One-way distance
- Length unit · ft / m / mi / km
- Current · A
- Drop limit for distance estimate · %







**Method references** [Schneider Electric · Voltage drop in steady load conditions](<https://www.electrical-installation.org/enwiki/Calculation_of_voltage_drop_in_steady_load_conditions>)



[ZooChief](<https://docs.toolpony.com/en/about/>) · [Report a problem with this result](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fen%2Fguides%2Fvoltage-drop-calculator%2F>)

[Documentation](https://docs.toolpony.com/en/guides/voltage-drop-calculator/)
