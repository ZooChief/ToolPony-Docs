# Statistikrechner



Fassen Sie einen Datensatz mit Mittelwert, Median, Modi, Quartilen und Populations- und Probendispersion zusammen.





## Erste Schritte



1. Verwenden Sie das Beispiel oder geben Sie eigene Werte ein.
2. Berechnen Sie das Ergebnis und kopieren oder laden Sie die Details herunter.







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



[Vollständiges Werkzeug öffnen](<https://toolpony.com/de/tools/statistics-calculator/>)







## Hinweise



Die Verarbeitung erfolgt im Browser. Verwenden Sie einheitliche Einheiten.







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



**Zusammenfassung des Datensatzes**

- Werte





**Standardabweichung der Stichprobe**

- Werte





**Standardabweichung der Population**

- Werte

[Dokumentation](https://docs.toolpony.com/de/guides/statistics-calculator/)
