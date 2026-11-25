# Anleitung: Lauftempo-Rechner



Lösen Sie Tempo, verstrichene Zeit und Entfernung, vergleichen Sie geteilte Tempos, konvertieren Sie Einheiten und schätzen Sie eine Endzeit.





## Beispiel



### Eingabe



```
10 km in 00:50:00
```



### Erwartetes Ergebnis



```
05:00 min/km, 12 km/h
```





<a id="case-study"></a>



## Zwei Kilometer-Zwischenzeiten prüfen



1. Die Uhr zeigt nach 1 km 3:25 und nach 2 km 6:55. Mit kumulierten Zeiten dauert der zweite Kilometer 3:30. Der Mittelwert beträgt 3:27,5/km.
2. Für einen Marathon in 4:00:00 mit Zwischenzeiten je Kilometer bleiben am Ende 195 m. Einschließlich dieses Abschnitts steht im Ziel genau 4:00:00.



[Beispiel ausführen](<https://toolpony.com/de/tools/pace-calculator/#example-watch-checkpoints>)





## Ausprobieren

[Vollständiges Werkzeug öffnen · Lauftempo-Rechner](<https://toolpony.com/de/tools/pace-calculator/>)





## Berechnungsmethode



Das mittlere Tempo ist Gesamtzeit geteilt durch Gesamtstrecke. Zwei Zeitfelder bedeuten Minuten und Sekunden, drei zusätzlich Stunden. Bis zu 100 gemessene Abschnitte oder 500 geplante Zwischenzeiten bei konstantem Tempo sind möglich.



$$
p=\frac{t}{d},\qquad v=\frac{d}{t}
$$







## Berechnungsmodus





### Tempo und Zielzeit



- Entfernung
- Distanzeinheit · km / mi / m / yd
- Verstrichene Zeit
- Tempo je · km / mi / 100 m / 100 yd
- Zieldistanz · 5 km / 10 km / Halbmarathon / Marathon / Eigene Distanz (km)
- Eigene Wettkampfdistanz · km







### Benötigte Zeit berechnen



- Entfernung
- Distanzeinheit · km / mi / m / yd
- Tempo (min:s)
- Tempo je · km / mi / 100 m / 100 yd







### Distanz berechnen



- Verstrichene Zeit
- Tempo (min:s)
- Tempo je · km / mi / 100 m / 100 yd







### Tempo umrechnen



- Tempo (min:s)
- Tempo je · km / mi / 100 m / 100 yd







### Abschnitte vergleichen



- Abschnitte
- Distanzeinheit · km / mi / m / yd
- Tempo je · km / mi / 100 m / 100 yd
- Kumulierte Distanz und Zeit je Zeile







### Zwischenzeiten planen



- Zieldistanz · 5 km / 10 km / Halbmarathon / Marathon / Eigene Distanz (km)
- Eigene Wettkampfdistanz · km
- Zielzeit
- Abstand der Zwischenzeiten · 1 km / 1 mi / 400 m / 100 m / 5 km / 10 km
- Tempo je · km / mi / 100 m / 100 yd







**Quellen zur Methode** [World Athletics · Marathon](<https://worldathletics.org/disciplines/road-running-event/marathon>) · [NIST · Unit conversion factors](<https://www.nist.gov/pml/special-publication-811/nist-guide-si-appendix-b-conversion-factors/nist-guide-si-appendix-b8>)



[ZooChief](<https://docs.toolpony.com/de/about/>) · [Ergebnisfehler melden](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fde%2Fguides%2Fpace-calculator%2F>)

[Dokumentation](https://docs.toolpony.com/de/guides/pace-calculator/)
