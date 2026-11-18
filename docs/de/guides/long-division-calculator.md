# Schriftliche Division



Teilen Sie ganze Zahlen oder Dezimalzahlen und prüfen Sie Quotient, Rest, Dezimalwert und jeden Long-Division-Schritt.





## Beispiel



### Eingabe



```
12,345 ÷ 67
```



### Erwartetes Ergebnis



```
184 Rest 17
```







## Ausprobieren



[Vollständiges Werkzeug öffnen](<https://toolpony.com/de/tools/long-division-calculator/>)







## Berechnungsmethode



Skalieren Sie beide Inputs mit der gleichen Potenz von zehn. Der Ganzzahlquotient schneidet gegen Null ab, und der signierte Rest erfüllt Dividende = Quotient x Divisor + Rest. Die Stufentabelle verwendet absolute Beträge.



$$
a=bq+r,\quad q=\operatorname{trunc}(a/b),\quad |r|<|b|
$$

[Dokumentation](https://docs.toolpony.com/de/guides/long-division-calculator/)
