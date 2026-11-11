# Spannungsfallrechner



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







## Ausprobieren



[Vollständiges Werkzeug öffnen](<https://toolpony.com/de/tools/voltage-drop-calculator/>)







## Hinweise



Die Verarbeitung erfolgt im Browser. Verwenden Sie einheitliche Einheiten.







## Berechnungsmethode



Nutzen Sie die einfache Länge und identische parallele Leiter. Multiplizieren Sie I·L·R bei Gleichstrom und Einphasenstrom mit 2, bei symmetrischem Drehstrom mit √3. Bei induktiver Last gehen R und X über den Leistungsfaktor ein. Größenwerte sind nominal bei etwa 20 °C. Verwenden Sie für das konkrete Kabel Herstellerdaten.



$$
\Delta V=\frac{k I L R_{\rm eff}}{n},\quad k=2\ \text{(DC, 1)}\phi,\quad k=\sqrt{3}\ \text{(3)}\phi
$$



$$
R_{\rm eff}=R\cos\theta+X\sin\theta,\quad \%\Delta V=100\frac{\Delta V}{V_s}
$$







## Berechnungsmodus



**Bekannter Widerstand oder Impedanz**

- Widerstand oder Impedanz je Länge
- Einheit je Länge · Ω/km / Ω/m / mΩ/m / Ω/1000 ft / Ω/ft / mΩ/ft
- Spannung · V
- Schaltung · DC / Einphasen-Wechselstrom / Drehstrom
- Parallele Leiter je Phase
- Einfache Entfernung
- Längeneinheit · ft / m / mi / km
- Stromstärke · A
- Grenze für die Entfernungsschätzung · %





**Nach Drahtstärke schätzen**

- Material · Kupfer / Aluminium / Silber / Gold
- Drahtgröße
- Spannung · V
- Schaltung · DC / Einphasen-Wechselstrom / Drehstrom
- Parallele Leiter je Phase
- Einfache Entfernung
- Längeneinheit · ft / m / mi / km
- Stromstärke · A
- Grenze für die Entfernungsschätzung · %





**Nach Querschnitt schätzen**

- Material · Kupfer / Aluminium / Silber / Gold
- Querschnittsfläche · mm²
- Spannung · V
- Schaltung · DC / Einphasen-Wechselstrom / Drehstrom
- Parallele Leiter je Phase
- Einfache Entfernung
- Längeneinheit · ft / m / mi / km
- Stromstärke · A
- Grenze für die Entfernungsschätzung · %





**Widerstand und Reaktanz**

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

[Dokumentation](https://docs.toolpony.com/de/guides/voltage-drop-calculator/)
