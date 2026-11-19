# Flächenrechner



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



**Rechteck**

- Länge
- Längeneinheit
- Breite
- Breiteneinheit
- Flächeneinheit





**Quadrat**

- Kantenlänge
- Kantenlängeneinheit
- Flächeneinheit





**Dreieck · drei Seiten**

- erste Seite
- erste Seiteneinheit
- zweite Seite
- zweite Seiteneinheit
- dritte Seite
- dritte Seiteneinheit
- Flächeneinheit





**Dreieck · Basis und Höhe**

- erste Parallelseite
- erste Parallelseiteneinheit
- Senkrechte Höhe
- Senkrechte Höheneinheit
- Flächeneinheit





**Trapez**

- erste Parallelseite
- erste Parallelseiteneinheit
- zweite Parallelseite
- zweite Parallelseiteneinheit
- Senkrechte Höhe
- Senkrechte Höheneinheit
- Flächeneinheit





**Kreis**

- Radius
- Radiuseinheit
- Flächeneinheit





**Kreissektor**

- Radius
- Radiuseinheit
- Mittelwinkel
- Winkeleinheit · Grad / Radianten
- Flächeneinheit





**Ellipse**

- Erste Halbachse
- Erste Halbachseneinheit
- zweite Halbachse
- zweite Halbachseneinheit
- Flächeneinheit





**Parallelogramm**

- erste Parallelseite
- erste Parallelseiteneinheit
- Senkrechte Höhe
- Senkrechte Höheneinheit
- Flächeneinheit





**Kreisring**

- Außendurchmesser
- Außendurchmessereinheit
- Innenradius
- Innenradiuseinheit
- Flächeneinheit





**Regelmäßiges Polygon**

- Kantenlänge
- Kantenlängeneinheit
- Seitenanzahl
- Flächeneinheit







**Quellen zur Methode** [BIPM · SI](<https://www.bipm.org/en/publications/si-brochure>)



[ZooChief](<https://docs.toolpony.com/de/about/>) · [Ergebnisfehler melden](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fde%2Fguides%2Farea-calculator%2F>)

[Dokumentation](https://docs.toolpony.com/de/guides/area-calculator/)
