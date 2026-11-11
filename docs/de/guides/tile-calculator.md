# Fliesenrechner



Schätzen Sie Fliesen, Boxen und Kosten aus den Fliesenabmessungen, dem Fugenabstand und dem abzudeckenden Bereich.





## Erste Schritte



1. Geben Sie die Länge, die Breite und den Abstand der Kachel ein.
2. Geben Sie entweder einen bekannten Bereich oder zwei Raumdimensionen ein, geben Sie pro Box Kacheln ein, um ganze Boxen zu berechnen.
3. Beim Schneiden und Brechen geben Sie unter Weitere Optionen eine Zulage ein.







## Beispiel



### Eingabe



```
180 ft², Fliesen 12 in × 12 in, Fuge ¼ in, 12 Stück pro Karton
```



### Erwartetes Ergebnis



```
173 Fliesen, 15 Boxen
```







## Ausprobieren



[Vollständiges Werkzeug öffnen](<https://toolpony.com/de/tools/tile-calculator/>)







## Hinweise



Die Verarbeitung erfolgt im Browser. Verwenden Sie einheitliche Einheiten.







## Berechnungsmethode



Teilen Sie die Fläche durch (Kachellänge + Lücke) × (Kachelbreite + Lücke) und runden Sie sie auf. Negative Lückenmodelle überlappen sich. Fügen Sie eine vom Benutzer ausgewählte Zulage hinzu, bevor Sie sie in ganze Boxen umwandeln.



$$
N=\left\lceil\frac{A}{(l+g)(w+g)}\right\rceil,\quad N_{\rm order}=\left\lceil N(1+a/100)\right\rceil
$$



Bei 180 ft2 mit 12 in quadratischen Kacheln und einer Lücke von 1⁄4 beträgt die Schätzung 173 Kacheln. Mit einem Zuschlag von 10% und 12 Kacheln pro Box, bestellen Sie 191 Kacheln, auf 16 Boxen aufgerundet.



Das Abdeckungsmodell verwendet eine effektive Länge und Breite für jede Kachel. Zulage deckt Schneiden, Muster und Bruch ab. Bestätigen Sie das endgültige Layout mit Ihren tatsächlichen Raum- und Kachelabmessungen.







## Berechnungsmodus



**Bekanntes Gebiet**

- Länge der Fliesen
- Längeneinheit für Fliesen
- Breite der Fliesen
- Fliesenbreiteneinheit
- Lücke oder Überlappung
- Spalt- oder Überlappungseinheit
- Gesamtfläche
- Flächeneinheit
- Fliesen pro Kiste
- Stückpreis
- Preis pro Stück
- Abfallentschädigung · %





**Rechteckiger Raum**

- Länge der Fliesen
- Längeneinheit für Fliesen
- Breite der Fliesen
- Fliesenbreiteneinheit
- Lücke oder Überlappung
- Spalt- oder Überlappungseinheit
- Raumlänge
- Raumlänge Einheit
- Raumbreite
- Raumbreiteneinheit
- Fliesen pro Kiste
- Stückpreis
- Preis pro Stück
- Abfallentschädigung · %

[Dokumentation](https://docs.toolpony.com/de/guides/tile-calculator/)
