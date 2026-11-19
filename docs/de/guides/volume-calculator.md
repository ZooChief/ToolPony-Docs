# Volumenrechner



Berechnen Sie Tankinhalt und Körpervolumen aus den Abmessungen. Bei Hohlrohren liefern Innen- und Außenradius das Materialvolumen. Ausgabe in Litern oder Kubikeinheiten.





## Beispiel



### Eingabe



```
Kugel mit Radius von 2 m
```



### Erwartetes Ergebnis



```
≈33.5103 m³
```





<a id="case-study"></a>



## Das Fassungsvermögen eines Tanks bis zur Füllmarke schätzen



1. Messen Sie Innendurchmesser und Tiefe bis zur Füllmarke. Beim Beispiel mit 1 m Innendurchmesser und 1,2 m Füllhöhe setzt der Rechner im Zylindermodus den Radius auf 0,5 m und die Ausgabe auf Liter.
2. Das Volumen ist π × 0,5² × 1,2 m³, also rund 942,48 l. Wer den Durchmesser als Radius eingibt, erhält wegen des Quadrats das Vierfache.
3. Senken Sie die Füllmarke um 0,2 m und geben Sie als Tiefe 1 m ein. Das ergibt rund 785,40 l. Zwischen den beiden Marken liegen also etwa 157,08 l.





## Ausprobieren

[Vollständiges Werkzeug öffnen · Volumenrechner](<https://toolpony.com/de/tools/volume-calculator/>)





## Berechnungsmethode



Das Volumen eines Prismas ist seine Grundfläche mal senkrechter Höhe. Ein Kegel oder eine Pyramide teilt dieses Produkt durch drei. Ein Hohlrohr subtrahiert den inneren Zylinder. Eine Kugelkappe akzeptiert zwei beliebige Dimensionen.



$$
V_{\mathrm{cone}}=\tfrac13\pi r^2h,\qquad V_{\mathrm{sphere}}=\tfrac43\pi r^3
$$







## Berechnungsmodus



**Kugel**

- Radius
- Radiuseinheit
- Volumeneinheit





**Kegel**

- Radius
- Radiuseinheit
- Senkrechte Höhe
- Senkrechte Höheneinheit
- Volumeneinheit





**Würfel**

- Kantenlänge
- Kantenlängeneinheit
- Volumeneinheit





**Zylinder**

- Radius
- Radiuseinheit
- Senkrechte Höhe
- Senkrechte Höheneinheit
- Volumeneinheit





**Rechteckbehälter**

- Länge
- Längeneinheit
- Breite
- Breiteneinheit
- Senkrechte Höhe
- Senkrechte Höheneinheit
- Volumeneinheit





**Kapsel**

- Radius
- Radiuseinheit
- Länge des geraden Zylinders
- Längeneinheit des Zylinders
- Volumeneinheit





**Kugelkappe**

- Kugelradius
- Einheit des Kugelradius
- Grundradius
- Basisradiuseinheit
- Höhe des Deckels
- Deckelhöheneinheit
- Kappe mit beiden Radien bekannt · Kleinere Kappe / Größere Kappe
- Volumeneinheit





**Kegelstumpf**

- erster Endradius
- erste Endradiuseinheit
- zweiter Endradius
- zweite Endradiuseinheit
- Senkrechte Höhe
- Senkrechte Höheneinheit
- Volumeneinheit





**Ellipsoid**

- Erste Halbachse
- Erste Halbachseneinheit
- zweite Halbachse
- zweite Halbachseneinheit
- dritte Halbachse
- dritte Halbachseneinheit
- Volumeneinheit





**Quadratpyramide**

- Kantenlänge
- Kantenlängeneinheit
- Senkrechte Höhe
- Senkrechte Höheneinheit
- Volumeneinheit





**Hohlrohr**

- Außendurchmesser
- Außendurchmessereinheit
- Innendurchmesser
- Innendurchmessereinheit
- Länge
- Längeneinheit
- Volumeneinheit





**Hemisphäre**

- Radius
- Radiuseinheit
- Volumeneinheit





**Ringtorus**

- Mittellinienradius
- Einheit für den Mittelradius
- Rohrradius
- Einheit des Rohrradius
- Volumeneinheit







**Quellen zur Methode** [BIPM · SI](<https://www.bipm.org/en/publications/si-brochure>)



[ZooChief](<https://docs.toolpony.com/de/about/>) · [Ergebnisfehler melden](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fde%2Fguides%2Fvolume-calculator%2F>)

[Dokumentation](https://docs.toolpony.com/de/guides/volume-calculator/)
