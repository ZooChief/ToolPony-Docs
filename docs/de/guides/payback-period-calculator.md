# Anleitung: Amortisationsdauer-Rechner



Finden Sie regelmäßige und diskontierte Amortisation aus wachsenden oder unregelmäßigen jährlichen Cashflows.





## Beispiel



### Eingabe



```
17.500 anfänglicher, erster Zufluss 4.700, Wachstum 8%, Rabatt 6%
```



### Erwartetes Ergebnis



```
Amortisation ≈ 3.379 Jahre, diskontiert ≈ 3.841 Jahre
```







## Ausprobieren

[Vollständiges Werkzeug öffnen · Amortisationsdauer-Rechner](<https://toolpony.com/de/tools/payback-period-calculator/>)





## Berechnungsmethode



Beim ersten Durchgang von Null interpolieren Sie den Bruchteil dieses Jahres. Diskontierte Zahlungsströme teilen Jahr k durch (1+r)^k. Ein konstanter Strom verwendet die inverse Annuitätsformel für die diskontierte Amortisation.



$$
C_k=\sum_{i=0}^{k}F_i,\qquad F_i^{\mathrm{PV}}=\frac{F_i}{(1+r)^i}
$$







## Berechnungsmodus





### Regelmäßige oder wachsende Cashflows



- Anfangsinvestition
- Cashflow des ersten Jahres
- Jährliches Wachstum oder Rückgang · %
- Jahre
- Jährlicher Abzinsungssatz · %







### Unregelmäßige jährliche Cashflows



- Anfangsinvestition
- Spätere jährliche Cashflows
- Jährlicher Abzinsungssatz · %







[ZooChief](<https://docs.toolpony.com/de/about/>) · [Ergebnisfehler melden](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fde%2Fguides%2Fpayback-period-calculator%2F>)

[Dokumentation](https://docs.toolpony.com/de/guides/payback-period-calculator/)
