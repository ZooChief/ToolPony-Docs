# Anleitung: Dreiecksrechner



Berechne aus drei bekannten Werten Winkel, Höhen, Seitenhalbierende und Kreismittelpunkte.





## Erste Schritte



1. Gib drei Werte ein, darunter mindestens eine Seite.
2. Wähle für Eingaben wie π/2 das Bogenmaß. Bei SSW können ein spitzer Winkel und sein Supplement gültige Lösungen ergeben.
3. In der Koordinatentabelle liegt A im Ursprung und B auf der positiven x-Achse. Exportiere die ausgewählte Tabelle als CSV.







## Beispiel



### Eingabe



```
a = 7, b = 10, A = 30°
```



### Erwartetes Ergebnis



```
Zwei Lösungen mit c ≈ 13,55923 und 3,76127.
```





<a id="case-study"></a>



## Wann zwei Dreiecke möglich sind



1. Setze a = 7, b = 10 und A = 30°. Seite a liegt gegenüber von A. Zwei mögliche Eckpunkte ergeben für c etwa 13,56 oder 3,76. Vergleiche beide Skizzen und Maße.
2. Bei a = 5 gilt a = b × sin A. Es gibt genau ein rechtwinkliges Dreieck. Bei a unter 5 entsteht kein Dreieck. Die Winkeltabelle enthält auch Bogenmaß und Grad, Minuten, Sekunden.



[Beispiel ausführen](<https://toolpony.com/de/tools/triangle-calculator/#example-two-triangles>)





## Ausprobieren

[Vollständiges Werkzeug öffnen · Dreiecksrechner](<https://toolpony.com/de/tools/triangle-calculator/>)





## Berechnungsmethode



Verwende dieselbe Längeneinheit. Seite a liegt Winkel A gegenüber, analog für b/B und c/C. Winkel allein bestimmen die Größe nicht.



$$
\frac{a}{\sin A}=\frac{b}{\sin B}=\frac{c}{\sin C},\qquad a^2=b^2+c^2-2bc\cos A
$$



$$
\Delta=\sqrt{s(s-a)(s-b)(s-c)},\quad s=\tfrac{a+b+c}{2},\quad h_a=2\Delta/a
$$



$$
m_a=\tfrac12\sqrt{2b^2+2c^2-a^2},\qquad r=\Delta/s,\qquad R=abc/(4\Delta)
$$







## Berechnungsmodus





### Bekannte Werte



- Seite a
- Seite b
- Seite c
- Winkel A
- Winkel B
- Winkel C
- Winkeleinheit · Grad / Bogenmaß







### Drei Seiten (SSS)



- Seite a
- Seite b
- Seite c







### Zwei Seiten und Zwischenwinkel (SWS)



- Seite b
- Seite c
- Winkel A · °







### Zwei Winkel und eine Seite (WSW / SWW)



- Winkel A · °
- Winkel B · °
- Bekannte Seite · a / b / c
- Seite







### Zwei Seiten und Gegenwinkel (SSW)



- Seite a
- Seite b
- Winkel A · °







### Katheten eines rechtwinkligen Dreiecks



- Seite a
- Seite b







**Quellen zur Methode** [MathWorld · Law of sines](<https://mathworld.wolfram.com/LawofSines.html>)



[ZooChief](<https://docs.toolpony.com/de/about/>) · [Ergebnisfehler melden](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fde%2Fguides%2Ftriangle-calculator%2F>)

[Dokumentation](https://docs.toolpony.com/de/guides/triangle-calculator/)
