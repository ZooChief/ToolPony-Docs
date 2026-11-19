# Konfidenzintervall-Rechner



Schätzen Sie ein normales mittleres Intervall oder ein Wilson-Intervall für einen Anteil.





## Beispiel



### Eingabe



```
n = 36, Mittelwert 56, Standardabweichung 8, 99%
```



### Erwartetes Ergebnis



```
56 ± 3.434
```







## Ausprobieren

[Vollständiges Werkzeug öffnen · Konfidenzintervall-Rechner](<https://toolpony.com/de/tools/confidence-interval-calculator/>)





## Berechnungsmethode



Die normale Marge ist z mal dem Standardfehler s/√n. Wilson-Scoreintervalle passen die Mitte und Breite für Proportionen an und bleiben innerhalb von \[0,1\].



$$
\bar{x}\pm z_{1-\alpha/2}\frac{s}{\sqrt n}
$$



$$
\frac{\widehat{p}+z^2/(2n)\pm z\sqrt{\widehat{p}(1-\widehat{p})/n+z^2/(4n^2)}}{1+z^2/n}
$$







## Berechnungsmodus



**Normales mittleres Intervall**

- Stichprobenumfang
- Mittelwert
- Standardabweichung
- Konfidenzniveau · %





**Wilson-Anteilintervall**

- Stichprobenumfang
- Erfolge
- Konfidenzniveau · %







[ZooChief](<https://docs.toolpony.com/de/about/>) · [Ergebnisfehler melden](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fde%2Fguides%2Fconfidence-interval-calculator%2F>)

[Dokumentation](https://docs.toolpony.com/de/guides/confidence-interval-calculator/)
