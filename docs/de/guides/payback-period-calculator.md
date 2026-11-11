# Amortisationsdauer-Rechner



Finden Sie regelmäßige und diskontierte Amortisation aus wachsenden oder unregelmäßigen jährlichen Cashflows.





## Erste Schritte



1. Verwenden Sie das Beispiel oder geben Sie eigene Werte ein.
2. Berechnen Sie das Ergebnis und kopieren oder laden Sie die Details herunter.







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



[Vollständiges Werkzeug öffnen](<https://toolpony.com/de/tools/payback-period-calculator/>)







## Hinweise



Die Verarbeitung erfolgt im Browser. Verwenden Sie einheitliche Einheiten.







## Berechnungsmethode



Beim ersten Durchgang von Null interpolieren Sie den Bruchteil dieses Jahres. Diskontierte Zahlungsströme teilen Jahr k durch (1+r)^k. Ein konstanter Strom verwendet die inverse Annuitätsformel für die diskontierte Amortisation.



$$
C_k=\sum_{i=0}^{k}F_i,\qquad F_i^{\mathrm{PV}}=\frac{F_i}{(1+r)^i}
$$







## Berechnungsmodus



**Regelmäßige oder wachsende Cashflows**

- Anfangsinvestition
- Cashflow des ersten Jahres
- Jährliches Wachstum oder Rückgang · %
- Jahre
- Jährlicher Abzinsungssatz · %





**Unregelmäßige jährliche Cashflows**

- Anfangsinvestition
- Spätere jährliche Cashflows
- Jährlicher Abzinsungssatz · %

[Dokumentation](https://docs.toolpony.com/de/guides/payback-period-calculator/)
