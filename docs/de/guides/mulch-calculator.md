# Mulchrechner



Berechnen Sie Volumen, Sackzahl und Kosten für eine oder mehrere Flächen.





## Erste Schritte



1. Geben Sie die Gesamtfläche oder ein Rechteck pro Zeile ein, etwa 6, 2, m. Jede Zeile kann eine andere Einheit haben.
2. Geben Sie die Schichtdicke ein und wählen Sie eine Preis- oder Sackeinheit. Eigene Sackgrößen finden Sie unter Weitere Optionen.







## Beispiel



### Eingabe



```
200 ft², 2 in Schichtdicke, 2-ft³-Säcke zu je 5.
```



### Erwartetes Ergebnis



```
33,3 ft³, 17 Säcke, Gesamtkosten 85.
```







## Ausprobieren



[Vollständiges Werkzeug öffnen](<https://toolpony.com/de/tools/mulch-calculator/>)







## Hinweise



Die Verarbeitung erfolgt im Browser. Verwenden Sie einheitliche Einheiten.







## Berechnungsmethode



Addieren Sie die Flächen ohne Überschneidung und wenden Sie Schichtdicke und Zugabe an. Teilen Sie durch den Sackinhalt und runden Sie auf. Lose Ware wird nach Volumen berechnet.



$$
A=\sum_i l_iw_i,\quad V=Ad(1+a/100),\quad N=\left\lceil\frac{V}{V_{\rm bag}}\right\rceil
$$







## Berechnungsmodus



**Bekannte Fläche**

- Fläche
- Flächeneinheit · cm² / m² / in² / ft² / yd² / acre / ha
- Schichtdicke
- Einheit der Schichtdicke · mm / cm / m / in / ft / yd
- Einzelpreis
- Preiseinheit
- Inhalt je Sack
- Einheit je Sack · ft³ / yd³ / m³ / L
- Verschnittzugabe · %





**Mehrere Rechtecke**

- Länge, Breite, Einheit je Zeile
- Schichtdicke
- Einheit der Schichtdicke · mm / cm / m / in / ft / yd
- Einzelpreis
- Preiseinheit
- Inhalt je Sack
- Einheit je Sack · ft³ / yd³ / m³ / L
- Verschnittzugabe · %

[Dokumentation](https://docs.toolpony.com/de/guides/mulch-calculator/)
