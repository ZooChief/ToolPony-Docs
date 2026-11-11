# Stromkostenrechner



Schätzen Sie Verbrauch und Kosten nach Gerät, Auslastung und Tarif für feste Tage oder verschiedene Zeiträume.





## Erste Schritte



1. Geben Sie Aufnahmeleistung, Nutzung und Tarif ein. Gerätevorgaben liefern bearbeitbare Beispielwerte.







## Beispiel



### Eingabe



```
1.000 W, 2 h/Tag, 30 Tage, 0,2 je kWh
```



### Erwartetes Ergebnis



```
60 kWh, Kosten 12
```







## Ausprobieren



[Vollständiges Werkzeug öffnen](<https://toolpony.com/de/tools/electricity-cost-calculator/>)







## Hinweise



Die Verarbeitung erfolgt im Browser. Verwenden Sie einheitliche Einheiten.







## Berechnungsmethode



Energie ist kW mal Betriebsstunden, Auslastung und Gerätezahl. Die Kosten folgen einem festen Tarif. Der Monat hat im Modell 30,44 Tage, das Jahr 365,25 Tage. Für Kühlgeräte zählt die elektrische Aufnahmeleistung.



$$
E_{\rm kWh}=P_{\rm kW}\,t_{\rm h}\,f\,n,\qquad C=E_{\rm kWh}\,r
$$







## Berechnungsmodus



**Feste Tageszahl**

- Leistung
- Leistungseinheit · W / kW / BTU/h / PS / TR
- Mittlere Auslastung · %
- Geräte
- Stunden pro Tag · h
- Tage
- Preis je kWh





**Tages- bis Jahreskosten**

- Gerätevorgabe
- Leistung
- Leistungseinheit · W / kW / BTU/h / PS / TR
- Mittlere Auslastung · %
- Geräte
- Nutzung
- Nutzungseinheit · Minuten pro Tag / Stunden pro Tag / Stunden pro Woche / Stunden pro Monat / Tage pro Woche / Tage pro Monat / Tage pro Jahr / Monate pro Jahr
- Preis je kWh

[Dokumentation](https://docs.toolpony.com/de/guides/electricity-cost-calculator/)
