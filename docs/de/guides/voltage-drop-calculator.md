# Anleitung: Spannungsfallrechner



Schätzen Sie den Spannungsfall für Gleichstrom, Einphasenstrom und symmetrischen Drehstrom anhand von Leitergröße oder Widerstand.





## Erste Schritte



1. Wählen Sie ein Modell. Geben Sie bei Drehstrom Außenleiterspannung und Leiterstrom an. Tragen Sie die einfache Entfernung ein.
2. Die Entfernung folgt dem gewählten Grenzwert. Prüfen Sie Strombelastbarkeit, Temperatur und Installationsanforderungen separat.







## Beispiel



### Eingabe



```
120 V, einphasig, 500 ft, 1 A und 1,2 Ω/km
```



### Erwartetes Ergebnis



```
0,37 V Spannungsfall, 0,30 %
```





<a id="case-study"></a>



## Kabeltabelle anwenden



1. Bei 1 mV/(A·m), 50 m einfacher Länge und 100 A fallen 5 V ab. Im Schneider-Beispiel kommen davor 10 V hinzu, insgesamt 15 V.



[Beispiel ausführen](<https://toolpony.com/de/tools/voltage-drop-calculator/#example-cable-table>)





## Parallele Drehstromleitung



Je Phase teilen sich zwei Leitungen 20 A. Bei 400 V, 100 m, R = 1 Ω/km, X = 0,5 Ω/km und induktivem Leistungsfaktor 0,8 ergeben sich 1,91 V Spannungsfall und 398,09 V an der Last.



[Beispiel ausführen](<https://toolpony.com/de/tools/voltage-drop-calculator/#example-parallel-cable>)







## Spannungsfall über Versorgung



24 V DC, 10 A, 1 km einfache Länge und 5 Ω/km ergeben 100 V Spannungsfall. Für diesen Strom liefert das Modell keine Lastspannung.



[Beispiel ausführen](<https://toolpony.com/de/tools/voltage-drop-calculator/#example-cable-limit>)







## Ausprobieren

[Vollständiges Werkzeug öffnen · Spannungsfallrechner](<https://toolpony.com/de/tools/voltage-drop-calculator/>)





## Berechnungsmethode



Nutzen Sie die einfache Länge und identische parallele Leiter. Multiplizieren Sie I·L·R bei Gleichstrom und Einphasenstrom mit 2, bei symmetrischem Drehstrom mit √3. Bei induktiver Last gehen R und X über den Leistungsfaktor ein. Größenwerte sind nominal bei etwa 20 °C. Verwenden Sie für das konkrete Kabel Herstellerdaten.



$$
\Delta V=\frac{k I L R_{\rm eff}}{n},\quad k=2\ \text{(DC, 1)}\phi,\quad k=\sqrt{3}\ \text{(3)}\phi
$$



$$
R_{\rm eff}=R\cos\theta+X\sin\theta,\quad \%\Delta V=100\frac{\Delta V}{V_s}
$$







## Berechnungsmodus





### Bekannter Widerstand oder Impedanz



- Angabe im Datenblatt · Leiterimpedanz / Spannungsfallkoeffizient
- Widerstand oder Impedanz je Länge
- Einheit je Länge · Ω/km / Ω/m / mΩ/m / Ω/1000 ft / Ω/ft / mΩ/ft
- Tabellenwert des Stromkreises · mV/(A·m)
- Spannung · V
- Schaltung · DC / Einphasen-Wechselstrom / Drehstrom
- Parallele Leiter je Phase
- Einfache Entfernung
- Längeneinheit · ft / m / mi / km
- Stromstärke · A
- Grenze für die Entfernungsschätzung · %







### Nach Drahtstärke schätzen



- Material · Kupfer / Aluminium / Silber / Gold
- Drahtgröße
- Spannung · V
- Schaltung · DC / Einphasen-Wechselstrom / Drehstrom
- Parallele Leiter je Phase
- Einfache Entfernung
- Längeneinheit · ft / m / mi / km
- Stromstärke · A
- Grenze für die Entfernungsschätzung · %







### Nach Querschnitt schätzen



- Material · Kupfer / Aluminium / Silber / Gold
- Querschnittsfläche · mm²
- Spannung · V
- Schaltung · DC / Einphasen-Wechselstrom / Drehstrom
- Parallele Leiter je Phase
- Einfache Entfernung
- Längeneinheit · ft / m / mi / km
- Stromstärke · A
- Grenze für die Entfernungsschätzung · %







### Widerstand und Reaktanz



- Widerstand
- Reaktanz je Länge
- Einheit je Länge · Ω/km / Ω/m / mΩ/m / Ω/1000 ft / Ω/ft / mΩ/ft
- Induktiver Leistungsfaktor
- Spannung · V
- Schaltung · DC / Einphasen-Wechselstrom / Drehstrom
- Parallele Leiter je Phase
- Einfache Entfernung
- Längeneinheit · ft / m / mi / km
- Stromstärke · A
- Grenze für die Entfernungsschätzung · %







**Quellen zur Methode** [Schneider Electric · Voltage drop in steady load conditions](<https://www.electrical-installation.org/enwiki/Calculation_of_voltage_drop_in_steady_load_conditions>)



[ZooChief](<https://docs.toolpony.com/de/about/>) · [Ergebnisfehler melden](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fde%2Fguides%2Fvoltage-drop-calculator%2F>)

[Dokumentation](https://docs.toolpony.com/de/guides/voltage-drop-calculator/)
