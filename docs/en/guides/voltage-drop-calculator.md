# Voltage drop calculator



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







## Try it



[Open full tool](<https://toolpony.com/en/tools/voltage-drop-calculator/>)







## Good to know



The calculation runs in your browser. Use consistent units in fields with no explicit unit.







## Calculation method



Use one-way length and identical parallel conductors. Multiply I·L·R by 2 for DC or single phase and √3 for balanced three phase. For lagging AC, R and X contribute through the power factor. Wire-size estimates use nominal resistance near 20 °C; use manufacturer data for the actual cable.



$$
\Delta V=\frac{k I L R_{\rm eff}}{n},\quad k=2\ \text{(DC, 1)}\phi,\quad k=\sqrt{3}\ \text{(3)}\phi
$$



$$
R_{\rm eff}=R\cos\theta+X\sin\theta,\quad \%\Delta V=100\frac{\Delta V}{V_s}
$$







## Calculation mode



**Known resistance or impedance**

- Resistance or impedance per length
- Unit per length · Ω/km / Ω/m / mΩ/m / Ω/1000 ft / Ω/ft / mΩ/ft
- Voltage · V
- Circuit · DC / Single-phase AC / Three-phase AC
- Conductors per phase
- One-way distance
- Length unit · ft / m / mi / km
- Current · A
- Drop limit for distance estimate · %





**Estimate from wire gauge**

- Material · Copper / Aluminum / Silver / Gold
- Wire size
- Voltage · V
- Circuit · DC / Single-phase AC / Three-phase AC
- Conductors per phase
- One-way distance
- Length unit · ft / m / mi / km
- Current · A
- Drop limit for distance estimate · %





**Estimate from area**

- Material · Copper / Aluminum / Silver / Gold
- Cross-sectional area · mm²
- Voltage · V
- Circuit · DC / Single-phase AC / Three-phase AC
- Conductors per phase
- One-way distance
- Length unit · ft / m / mi / km
- Current · A
- Drop limit for distance estimate · %





**Resistance and reactance**

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

[Documentation](https://docs.toolpony.com/en/guides/voltage-drop-calculator/)
