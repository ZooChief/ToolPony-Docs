# Hypothekenrechner



Vergleichen Sie eine Festhypothek mit Anzahlung, wiederkehrenden Kosten, zusätzlichen Zahlungen und zweiwöchentlichen Auszahlungen.





## Erste Schritte



1. Verwenden Sie das Beispiel oder geben Sie eigene Werte ein.
2. Berechnen Sie das Ergebnis und kopieren oder laden Sie die Details herunter.







## Beispiel



### Eingabe



```
Home 400.000; minus 20%; 30 Jahre; 6%
```



### Erwartetes Ergebnis



```
≈1,918,56 monatliche Haupt- und Zinsen
```







## Ausprobieren



[Vollständiges Werkzeug öffnen](<https://toolpony.com/de/tools/mortgage-calculator/>)







## Hinweise



Die Verarbeitung erfolgt im Browser. Verwenden Sie einheitliche Einheiten.







## Berechnungsmethode



Die monatlichen Zinsen entsprechen dem verbleibenden Hauptzinssatz geteilt durch 12. Die Kosten folgen Ihren jährlichen Inputs und Wachstumsraten. PMI kann bei 80% des ursprünglichen Eigenheimwerts in diesem Modell aufhören. Biweekly vergleicht die Hälfte der geplanten monatlichen Zahlung alle zwei Wochen mit Zinsen geteilt durch 26.



$$
I_k=r B_{k-1},\qquad B_k=B_{k-1}-(M_k-I_k)
$$

[Dokumentation](https://docs.toolpony.com/de/guides/mortgage-calculator/)
