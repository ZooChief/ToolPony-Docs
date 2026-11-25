# Anleitung: Matrizenrechner



Löse lineare Gleichungssysteme und berechne Determinante, Inverse, Rang oder Matrixprodukte mit exakten Brüchen und Dezimalzahlen. Füge Tabellenzellen ein und exportiere das Ergebnis.





## Beispiel



### Eingabe



```
A = [2, 4; 1, 3], B = [1, −2; 4, 5]
```



### Erwartetes Ergebnis



```
A + B = [3, 2; 5, 8]
```





<a id="case-study"></a>



## Zwei Packungsgrößen



1. Eine kleine Packung enthält 2 schwarze und 1 weiße Klammer, eine große 3 schwarze und 2 weiße. Zusammen sind es 17 schwarze und 10 weiße. Die Spalten von A beschreiben die Packungen, B die Gesamtzahlen. Die Lösung ist 4 kleine und 3 große Packungen. Mit A × X lassen sich beide Summen prüfen.



[Beispiel ausführen](<https://toolpony.com/de/tools/matrix-calculator/#example-packing-matrix>)





## Determinante genau eins



Auf der Hauptdiagonale ergibt sich eine Milliarde zum Quadrat. Das andere Produkt ist (eine Milliarde − 1) mal (eine Milliarde + 1). Die Differenz beträgt genau 1. Die beiden Zeilen sind linear unabhängig.



[Beispiel ausführen](<https://toolpony.com/de/tools/matrix-calculator/#example-determinant-one>)







## Zwei freie Variablen



Die zweite Gleichung ist das Doppelte der ersten. Bei x + y + z = 4 können y und z frei gewählt werden. Dann ist x = 4 − y − z. Zur partikulären Lösung (4, 0, 0) kommen zwei Richtungen des Kerns hinzu. Ändere die zweite Summe von 8 auf 9, um den Widerspruch zu sehen.



[Beispiel ausführen](<https://toolpony.com/de/tools/matrix-calculator/#example-free-variables>)







## Ausprobieren

[Vollständiges Werkzeug öffnen · Matrizenrechner](<https://toolpony.com/de/tools/matrix-calculator/>)





## Berechnungsmethode



Die Zeilenreduktion rechnet mit exakten rationalen Zahlen. Die Anzahl der Pivotspalten ist der Rang. Bei A × X = B zeigt eine Nullzeile links mit einem von null verschiedenen Wert rechts einen Widerspruch. Freie Spalten bestimmen die Richtungen, die zur partikulären Lösung addiert werden können.



$$
(AB)_{ij}=\sum_{k=1}^{n}A_{ik}B_{kj},\qquad A^{-1}A=I
$$



$$
[A\mid B]\longrightarrow[I\mid X]\quad\Rightarrow\quad AX=B
$$







## Berechnungsmodus





### Hinzufügen A + B



- Matrix A
- Matrix B







### Subtrahieren A - B



- Matrix A
- Matrix B







### A × B multiplizieren



- Matrix A
- Matrix B







### Lösung A × X = B



- Matrix A
- Matrix B







### Determinant



- Matrix A







### Invers



- Matrix A







### Transponieren



- Matrix A







### Integrierte Leistung



- Matrix A
- Exponent







### Skalare Multiplikation



- Matrix A
- Skalar







### Rank- und Reduzierte Reihen-Echelon-Form



- Matrix A







**Quellen zur Methode** [MIT OpenCourseWare · Solving Ax = b](<https://ocw.mit.edu/courses/18-06sc-linear-algebra-fall-2011/resources/solving-ax-b-row-reduced-form-r/>)



[ZooChief](<https://docs.toolpony.com/de/about/>) · [Ergebnisfehler melden](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fde%2Fguides%2Fmatrix-calculator%2F>)

[Dokumentation](https://docs.toolpony.com/de/guides/matrix-calculator/)
