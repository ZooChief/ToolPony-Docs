# Anleitung: Konfidenzintervall-Rechner



Mittelwertintervalle aus Messwerten oder Kennzahlen mit z oder Student-t berechnen, Anteilsintervalle nach Wilson.





## Beispiel



### Eingabe



```
n = 36, Mittelwert 56, Standardabweichung 8, 99%
```



### Erwartetes Ergebnis



```
56 ± 3.434
```





<a id="case-study"></a>



## Ein Intervall aus fünf Messungen



1. 48, 49, 50, 51 und 52 haben den Mittelwert 50. Mit der Stichprobenstandardabweichung und vier Freiheitsgraden ergibt sich ein 95%-t-Intervall von etwa 48,04 bis 51,96. Die Beobachtungen gelten als unabhängig und die Grundgesamtheit als annähernd normalverteilt.



[Beispiel ausführen](<https://toolpony.com/de/tools/confidence-interval-calculator/#example-five-measurements>)





## Kein Fehler bei 30 Prüfungen



Bei 30 unabhängigen Prüfungen gab es keinen Fehler. Das 95%-Wilson-Intervall für den Fehleranteil reicht von 0 % bis etwa 11,35 %. Weitere fehlerfreie Prüfungen verkleinern das Intervall.



[Beispiel ausführen](<https://toolpony.com/de/tools/confidence-interval-calculator/#example-no-failures>)







## Ausprobieren

[Vollständiges Werkzeug öffnen · Konfidenzintervall-Rechner](<https://toolpony.com/de/tools/confidence-interval-calculator/>)





## Berechnungsmethode



Die Fehlerspanne ist kritischer Wert × Standardabweichung / √n. Bei bekanntem σ gilt z, bei Stichproben-s die t-Verteilung mit n − 1 Freiheitsgraden. Wilson schätzt den Binomialanteil aus Treffern und Versuchen.



$$
\bar{x}\pm z_{1-\alpha/2}\frac{s}{\sqrt n}
$$



$$
\frac{\widehat{p}+z^2/(2n)\pm z\sqrt{\widehat{p}(1-\widehat{p})/n+z^2/(4n^2)}}{1+z^2/n}
$$







## Berechnungsmodus





### Intervall für den Mittelwert



- Datengrundlage · Bekanntes σ / Stichproben-s / Messwerte
- Stichprobenumfang
- Mittelwert
- Standardabweichung
- Messwerte
- Konfidenzniveau · %







### Wilson-Anteilintervall



- Stichprobenumfang
- Erfolge
- Konfidenzniveau · %







**Quellen zur Methode** [NIST · Confidence limits for the mean](<https://www.itl.nist.gov/div898/handbook/eda/section3/eda352.htm>) · [NIST · Confidence limits for a proportion](<https://www.itl.nist.gov/div898/handbook/prc/section2/prc241.htm>)



[ZooChief](<https://docs.toolpony.com/de/about/>) · [Ergebnisfehler melden](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fde%2Fguides%2Fconfidence-interval-calculator%2F>)

[Dokumentation](https://docs.toolpony.com/de/guides/confidence-interval-calculator/)
