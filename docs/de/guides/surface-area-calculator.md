# Anleitung: Oberflächenrechner



Berechne die Oberfläche eines Körpers. Wähle bei Behältern, Rohren und anderen Körpern mit ebenen Endflächen die zu bedeckenden Flächen aus.





## Beispiel



### Eingabe



```
Kugel mit Radius von 2 m
```



### Erwartetes Ergebnis



```
≈50.2655 m²
```





<a id="case-study"></a>



## Einen offenen Tank auskleiden



1. Die Innenmaße sind 120 cm mal 0,8 m, die Tiefe beträgt 450 mm. Wähle Mantel und ein Ende für die vier Wände und den Boden.
2. Die Wände haben 1,80 m², der Boden 0,96 m². Ohne Nahtzugabe und Verschnitt sind das 2,76 m². Mit allen Flächen kommt der Deckel hinzu, insgesamt 3,72 m².



[Beispiel ausführen](<https://toolpony.com/de/tools/surface-area-calculator/#example-open-tank>)





## Ausprobieren

[Vollständiges Werkzeug öffnen · Oberflächenrechner](<https://toolpony.com/de/tools/surface-area-calculator/>)





## Berechnungsmethode



Eine geschlossene Oberfläche enthält alle Endflächen. Sie werden aus ihren Abmessungen berechnet. Die Ellipsoidoberfläche wird numerisch mit einem symmetrischen elliptischen Integral bestimmt.



$$
A_{\mathrm{cylinder}}=2\pi r^2+2\pi rh,\qquad A_{\mathrm{sphere}}=4\pi r^2
$$







## Berechnungsmodus





### Kugel



- Radius
- Radiuseinheit
- Flächeneinheit







### Kegel



- Radius
- Radiuseinheit
- Senkrechte Höhe
- Senkrechte Höheneinheit
- Zu bedeckende Flächen · Alle Flächen / Nur Mantel
- Flächeneinheit







### Würfel



- Kantenlänge
- Kantenlängeneinheit
- Zu bedeckende Flächen · Alle Flächen / Nur Mantel / Mantel und ein Ende
- Flächeneinheit







### Zylinder



- Radius
- Radiuseinheit
- Senkrechte Höhe
- Senkrechte Höheneinheit
- Zu bedeckende Flächen · Alle Flächen / Nur Mantel / Mantel und ein Ende
- Flächeneinheit







### Rechteckbehälter



- Länge
- Längeneinheit
- Breite
- Breiteneinheit
- Senkrechte Höhe
- Senkrechte Höheneinheit
- Zu bedeckende Flächen · Alle Flächen / Nur Mantel / Mantel und ein Ende
- Flächeneinheit







### Kapsel



- Radius
- Radiuseinheit
- Länge des geraden Zylinders
- Längeneinheit des Zylinders
- Flächeneinheit







### Kugelkappe



- Kugelradius
- Einheit des Kugelradius
- Grundradius
- Basisradiuseinheit
- Höhe des Deckels
- Deckelhöheneinheit
- Kappe mit beiden Radien bekannt · Kleinere Kappe / Größere Kappe
- Zu bedeckende Flächen · Alle Flächen / Nur Mantel
- Flächeneinheit







### Kegelstumpf



- erster Endradius
- erste Endradiuseinheit
- zweiter Endradius
- zweite Endradiuseinheit
- Senkrechte Höhe
- Senkrechte Höheneinheit
- Zu bedeckende Flächen · Alle Flächen / Nur Mantel / Mantel und erstes Ende / Mantel und zweites Ende
- Flächeneinheit







### Ellipsoid



- Erste Halbachse
- Erste Halbachseneinheit
- zweite Halbachse
- zweite Halbachseneinheit
- dritte Halbachse
- dritte Halbachseneinheit
- Flächeneinheit







### Quadratpyramide



- Kantenlänge
- Kantenlängeneinheit
- Senkrechte Höhe
- Senkrechte Höheneinheit
- Zu bedeckende Flächen · Alle Flächen / Nur Mantel
- Flächeneinheit







### Hohlrohr



- Außendurchmesser
- Außendurchmessereinheit
- Innendurchmesser
- Innendurchmessereinheit
- Länge
- Längeneinheit
- Zu bedeckende Flächen · Alle Flächen / Nur Mantel / Mantel und ein Ende
- Flächeneinheit







### Hemisphäre



- Radius
- Radiuseinheit
- Zu bedeckende Flächen · Alle Flächen / Nur Mantel
- Flächeneinheit







### Ringtorus



- Mittellinienradius
- Einheit für den Mittelradius
- Rohrradius
- Einheit des Rohrradius
- Flächeneinheit







**Quellen zur Methode** [BIPM · SI](<https://www.bipm.org/en/publications/si-brochure>) · [NIST DLMF · Triaxial ellipsoids](<https://dlmf.nist.gov/19.33>)



[ZooChief](<https://docs.toolpony.com/de/about/>) · [Ergebnisfehler melden](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fde%2Fguides%2Fsurface-area-calculator%2F>)

[Dokumentation](https://docs.toolpony.com/de/guides/surface-area-calculator/)
