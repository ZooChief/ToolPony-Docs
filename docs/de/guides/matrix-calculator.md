# Matrizenrechner



Addieren, multiplizieren, transponieren, invertieren, lösen oder finden Sie den Rang und die Determinante. Kopieren Sie das Ergebnis als TSV oder laden Sie CSV herunter.





## Beispiel



### Eingabe



```
A = [2, 4; 1, 3], B = [1, −2; 4, 5]
```



### Erwartetes Ergebnis



```
A + B = [3, 2; 5, 8]
```







## Ausprobieren

[Vollständiges Werkzeug öffnen · Matrizenrechner](<https://toolpony.com/de/tools/matrix-calculator/>)





## Berechnungsmethode



Jede Zeile mit einer neuen Zeile oder einem Semikolon trennen. Werte können durch Leerzeichen oder Kommas getrennt werden. Ein verschachteltes JSON-Array wird akzeptiert. Quadrat-Matrix-Methoden verwenden Gauß-Eliminierung mit skalierter Schwenkung.



$$
(AB)_{ij}=\sum_{k=1}^{n}A_{ik}B_{kj},\qquad A^{-1}A=I
$$



$$
[A\mid B]\longrightarrow[I\mid X]\quad\Rightarrow\quad AX=B
$$







## Berechnungsmodus



**Hinzufügen A + B**

- Matrix A
- Matrix B





**Subtrahieren A - B**

- Matrix A
- Matrix B





**A × B multiplizieren**

- Matrix A
- Matrix B





**Lösung A × X = B**

- Matrix A
- Matrix B





**Determinant**

- Matrix A





**Invers**

- Matrix A





**Transponieren**

- Matrix A





**Integrierte Leistung**

- Matrix A
- Exponent





**Skalare Multiplikation**

- Matrix A
- Skalar





**Rank- und Reduzierte Reihen-Echelon-Form**

- Matrix A







[ZooChief](<https://docs.toolpony.com/de/about/>) · [Ergebnisfehler melden](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fde%2Fguides%2Fmatrix-calculator%2F>)

[Dokumentation](https://docs.toolpony.com/de/guides/matrix-calculator/)
