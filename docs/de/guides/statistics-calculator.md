# Anleitung: Statistikrechner



Fassen Sie einen Datensatz mit Mittelwert, Median, Modi, Quartilen und Populations- und Probendispersion zusammen.





## Beispiel



### Eingabe



```
2, 4, 4, 6, 9
```



### Erwartetes Ergebnis



```
Mittelwert 5, Median 4
```







## Ausprobieren

[Vollständiges Werkzeug öffnen · Statistikrechner](<https://toolpony.com/de/tools/statistics-calculator/>)





## Berechnungsmethode



Quartile verwenden lineare Interpolation bei (n-1)p. Die Populationsvarianz wird durch n und die Probenvarianz durch n-1 geteilt. Geben Sie bis zu 1.000 Werte ein, die durch Kommas oder Weißraum getrennt sind.



$$
\bar x=\frac{1}{n}\sum_{i=1}^{n} x_i,\qquad s=\sqrt{\frac{\sum_i(x_i-\bar x)^2}{n-1}}
$$



$$
\operatorname{SE}(\bar x)=\frac{s}{\sqrt n},\qquad \bar x\pm z\operatorname{SE}(\bar x)
$$



Die Standardabweichung der Stichprobe für eine Teilmenge einer Population und die Standardabweichung der Population für einen vollständigen Satz verwenden; die Konfidenztabelle zeigt die normale Näherung des Mittelwerts bei mehreren Konfidenzniveaus.







## Berechnungsmodus





### Zusammenfassung des Datensatzes



- Werte







### Standardabweichung der Stichprobe



- Werte







### Standardabweichung der Population



- Werte







[ZooChief](<https://docs.toolpony.com/de/about/>) · [Ergebnisfehler melden](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fde%2Fguides%2Fstatistics-calculator%2F>)

[Dokumentation](https://docs.toolpony.com/de/guides/statistics-calculator/)
