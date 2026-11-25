# Anleitung: Flächenrechner



Finden Sie den Bereich der ebenen Formen in elf Modi mit gemischten Eingabeeinheiten und einer auswählbaren Ausgabeeinheit.





## Beispiel



### Eingabe



```
Ein Rechteck 4 m mal 3 m
```



### Erwartetes Ergebnis



```
12 m²
```





<a id="case-study"></a>



## Fläche und Schnittlänge eines Rings



1. Bei 60 mm Außendurchmesser und einer Öffnung von 40 mm sind die Radien 30 und 20 mm. Wähle mm² als Flächeneinheit.
2. Die Materialfläche beträgt 500π mm², etwa 1.570,80 mm². Beide Schnitte ergeben 100π mm oder etwa 314,16 mm. Der Export enthält beide Umfänge und die Eingabemaße.



[Beispiel ausführen](<https://toolpony.com/de/tools/area-calculator/#example-gasket>)





## Ausprobieren

[Vollständiges Werkzeug öffnen · Flächenrechner](<https://toolpony.com/de/tools/area-calculator/>)





## Berechnungsmethode



Die Abmessungen werden vor der Berechnung in Meter umgerechnet. Das dreiseitige Dreieck verwendet die Heronsche Formel. Ein Sektor verwendet den halben Quadratradius mal seinen Winkel in Radianten.



$$
A_{\mathrm{rectangle}}=lw,\qquad A_{\mathrm{sector}}=\tfrac12 r^2\theta
$$



$$
A_{\mathrm{triangle}}=\sqrt{s(s-a)(s-b)(s-c)},\quad s=\tfrac12(a+b+c)
$$







## Berechnungsmodus





### Rechteck



- Länge
- Längeneinheit
- Breite
- Breiteneinheit
- Flächeneinheit







### Quadrat



- Seitenlänge
- Einheit der Seitenlänge
- Flächeneinheit







### Dreieck · drei Seiten



- erste Seite
- erste Seiteneinheit
- zweite Seite
- zweite Seiteneinheit
- dritte Seite
- dritte Seiteneinheit
- Flächeneinheit







### Dreieck · Basis und Höhe



- Grundseite
- Einheit der Grundseite
- Senkrechte Höhe
- Senkrechte Höheneinheit
- Flächeneinheit







### Trapez



- erste Parallelseite
- erste Parallelseiteneinheit
- zweite Parallelseite
- zweite Parallelseiteneinheit
- Senkrechte Höhe
- Senkrechte Höheneinheit
- Flächeneinheit







### Kreis



- Radius
- Radiuseinheit
- Flächeneinheit







### Kreissektor



- Radius
- Radiuseinheit
- Mittelwinkel
- Winkeleinheit · Grad / Radiant
- Flächeneinheit







### Ellipse



- Erste Halbachse
- Erste Halbachseneinheit
- zweite Halbachse
- zweite Halbachseneinheit
- Flächeneinheit







### Parallelogramm



- Grundseite
- Einheit der Grundseite
- Senkrechte Höhe
- Senkrechte Höheneinheit
- Flächeneinheit







### Kreisring



- Außendurchmesser
- Außendurchmessereinheit
- Innenradius
- Innenradiuseinheit
- Flächeneinheit







### Regelmäßiges Polygon



- Seitenlänge
- Einheit der Seitenlänge
- Seitenanzahl
- Flächeneinheit







**Quellen zur Methode** [BIPM · SI](<https://www.bipm.org/en/publications/si-brochure>) · [NIST DLMF · Lengths of plane curves](<https://dlmf.nist.gov/19.30>)



[ZooChief](<https://docs.toolpony.com/de/about/>) · [Ergebnisfehler melden](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fde%2Fguides%2Farea-calculator%2F>)

[Dokumentation](https://docs.toolpony.com/de/guides/area-calculator/)
