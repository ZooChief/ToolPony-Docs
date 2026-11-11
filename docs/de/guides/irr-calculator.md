# Rechner für den internen Zinsfuß



Finden Sie den effektiven Jahreszinssatz aus unregelmäßigen jährlichen Stromflüssen oder einem Endwert und regelmäßigen Ein- oder Auszahlungen.





## Erste Schritte



1. Verwenden Sie das Beispiel oder geben Sie eigene Werte ein.
2. Berechnen Sie das Ergebnis und kopieren oder laden Sie die Details herunter.







## Beispiel



### Eingabe



```
55.000 Ausgaben mit 14.000, 18.000, 22.000, 26.000 Zuflüssen
```



### Erwartetes Ergebnis



```
IRR ≈ 15,093%
```







## Ausprobieren



[Vollständiges Werkzeug öffnen](<https://toolpony.com/de/tools/irr-calculator/>)







## Hinweise



Die Verarbeitung erfolgt im Browser. Verwenden Sie einheitliche Einheiten.







## Berechnungsmethode



IRR ist eine Rate, die den Netto-Barwert Null ergibt. Fixed-Mode-Cashflows verwenden die gewählte Zahlungsfrequenz und den Anfangs- oder Endzeitpunkt. Wählen Sie, ob eine Zahlung zu Beginn des Zeitraums auch an der Terminalgrenze gezählt wird. Die Ratensuche umfasst -99,9999% bis 10.000%.



$$
0=\sum_{i=0}^n\frac{F_i}{(1+r)^{t_i}}
$$







## Berechnungsmodus



**Unregelmäßige jährliche Stromgrößen**

- Anfangsinvestition
- Spätere jährliche Cashflows





**Fixed-Flows- und Endbilanz**

- Anfangsinvestition
- Ganze Jahre
- Zusätzliche Monate
- Endbilanz
- Zahlungsbetrag
- Zahlungsart · Rücknahme / Einlagen
- Zahlungen pro Jahr · 1 / 2 / 4 / 12 / 24 / 26 / 52
- Zahlungstermine · Ende des Zeitraums / Beginn des Zeitraums
- Integrieren Sie die Terminalzahlung im Startmodus

[Dokumentation](https://docs.toolpony.com/de/guides/irr-calculator/)
