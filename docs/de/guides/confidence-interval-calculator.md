# Konfidenzintervall-Rechner



Schätzen Sie ein normales mittleres Intervall oder ein Wilson-Intervall für einen Anteil.





## Erste Schritte



1. Verwenden Sie das Beispiel oder geben Sie eigene Werte ein.
2. Berechnen Sie das Ergebnis und kopieren oder laden Sie die Details herunter.







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



[Vollständiges Werkzeug öffnen](<https://toolpony.com/de/tools/confidence-interval-calculator/>)







## Hinweise



Die Verarbeitung erfolgt im Browser. Verwenden Sie einheitliche Einheiten.







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

[Dokumentation](https://docs.toolpony.com/de/guides/confidence-interval-calculator/)
