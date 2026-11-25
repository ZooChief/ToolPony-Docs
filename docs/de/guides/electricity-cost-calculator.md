# Anleitung: Stromkostenrechner



Berechnen Sie Verbrauchskosten aus Aufnahmeleistung, Kühlleistung und Effizienz oder zwei Zählerständen. Vergleichen Sie kWh pro Tag und Abrechnungszeitraum.





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





<a id="case-study"></a>



## Wattangabe am Fensterklimagerät lesen



1. Das Datenblatt des LG LW6014ER nennt 6.000 BTU/h Kühlleistung und 530 W elektrische Aufnahmeleistung. Eine Anlage verbraucht bei Volllast an 30 Tagen mit je 8 Stunden 0,53 × 8 × 30 = 127,2 kWh. Bei 0,20 je kWh kostet der Verbrauch 25,44.



[Beispiel ausführen](<https://toolpony.com/de/tools/electricity-cost-calculator/#example-window-power>)





## Zwei Zählerstände abrechnen



Der Bezugszähler steigt in 30 Tagen von 612345,125 auf 612492,365 kWh. Das sind 147,24 kWh oder 4,908 kWh pro Tag. Bei 0,15 je kWh beträgt der Verbrauchspreis vor Grundpreis und Steuern 22,086.



[Beispiel ausführen](<https://toolpony.com/de/tools/electricity-cost-calculator/#example-meter-readings>)







## Stromaufnahme aus dem EER schätzen



Bei 6.000 BTU/h Kühlleistung und einem EER von 12 BTU/Wh beträgt die elektrische Aufnahme 6.000 ÷ 12 = 500 W. Acht Stunden täglich an 30 Tagen bei Volllast ergeben 120 kWh. Der EER muss zum angegebenen Betriebspunkt gehören.



[Beispiel ausführen](<https://toolpony.com/de/tools/electricity-cost-calculator/#example-cooling-eer>)







## Ausprobieren

[Vollständiges Werkzeug öffnen · Stromkostenrechner](<https://toolpony.com/de/tools/electricity-cost-calculator/>)





## Berechnungsmethode



Verbrauchskosten = kWh × Arbeitspreis. Der Zählerverbrauch ist Endstand minus Anfangsstand. BTU/h geteilt durch EER oder Kühlwatt geteilt durch COP ergeben elektrische Watt. Für Monats- und Jahreswerte gelten 30,44 bzw. 365,25 Tage.



$$
E_{\rm kWh}=M_1-M_0,\qquad P_{\rm W}=\frac{Q_{\rm Btu/h}}{\mathrm{EER}}=\frac{Q_{\rm W}}{\mathrm{COP}}
$$



$$
E_{\rm kWh}=P_{\rm kW}\,t_{\rm h}\,f\,n,\qquad C=E_{\rm kWh}\,r
$$







## Berechnungsmodus





### Feste Tageszahl



- Berechnung nach · Elektrische Leistung / Kühlleistung / Zählerstände
- Elektrische Leistung
- Leistungseinheit · W / kW / BTU/h / PS / TR
- Kühlleistung
- Einheit der Kühlleistung · BTU/h / kW / TR
- Effizienzangabe · EER (BTU/Wh) / COP (W/W)
- Nennwirkungsgrad
- Anfangsstand · kWh
- Endstand · kWh
- Mittlere Auslastung · %
- Geräte
- Stunden pro Tag · h
- Tage
- Preis je kWh







### Tages- bis Jahreskosten



- Gerätevorgabe
- Berechnung nach · Elektrische Leistung / Kühlleistung
- Elektrische Leistung
- Leistungseinheit · W / kW / BTU/h / PS / TR
- Kühlleistung
- Einheit der Kühlleistung · BTU/h / kW / TR
- Effizienzangabe · EER (BTU/Wh) / COP (W/W)
- Nennwirkungsgrad
- Mittlere Auslastung · %
- Geräte
- Nutzung
- Nutzungseinheit · Minuten pro Tag / Stunden pro Tag / Stunden pro Woche / Stunden pro Monat / Tage pro Woche / Tage pro Monat / Tage pro Jahr / Monate pro Jahr
- Preis je kWh







**Quellen zur Methode** [LG · LW6014ER electrical specification](<https://images.thdstatic.com/catalog/pdfImages/e3/e3b8396a-44d1-4372-b120-7532036b2488.pdf>) · [Ohio Consumers’ Counsel · Read an electric meter](<https://www.occ.ohio.gov/sites/default/files/2021-07/OCC-How-to-Read-an-Electric-Meter.pdf>) · [U.S. Department of Energy · Room air conditioner ratings](<https://www.energy.gov/sites/prod/files/2015/06/f22/room_ac_rfi.pdf>) · [NIST · International Table Btu](<https://www.nist.gov/pml/special-publication-811/nist-guide-si-footnotes>)



[ZooChief](<https://docs.toolpony.com/de/about/>) · [Ergebnisfehler melden](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fde%2Fguides%2Felectricity-cost-calculator%2F>)

[Dokumentation](https://docs.toolpony.com/de/guides/electricity-cost-calculator/)
