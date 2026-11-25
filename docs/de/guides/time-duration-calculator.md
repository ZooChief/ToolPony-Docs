# Anleitung: Zeitdauerrechner



Berechnen Sie Zeitabstände und Dauern oder verschieben Sie Datum und Uhrzeit.





## Erste Schritte



1. Wählen Sie Uhrzeiten für eine Schicht, Daten für mehrere Tage oder den Zeitausdruck zum Rechnen.







## Beispiel



### Eingabe



```
22:30 bis 06:15 am Folgetag
```



### Erwartetes Ergebnis



```
07:45:00
```





<a id="case-study"></a>



## Drei Aufnahmen zusammenzählen



1. Die Aufnahmen dauern 47 min 35 s, 1 h 12 min 40 s und 8 min 15 s. Auf der gemeinsamen Zeitachse endet die zweite bei 02:00:15. Insgesamt sind es 02:08:30. Die exportierten Zwischenstände markieren die Schnittpunkte.



[Beispiel ausführen](<https://toolpony.com/de/tools/time-duration-calculator/#example-recording-sessions>)





## Ausprobieren

[Vollständiges Werkzeug öffnen · Zeitdauerrechner](<https://toolpony.com/de/tools/time-duration-calculator/>)





## Berechnungsmethode



Ein Zeitintervall kann über Mitternacht reichen. Mit Datum zählt ein Tag 24 Stunden. d, h, m und s stehen für Tage, Stunden, Minuten und Sekunden. Ein Minus gilt für die folgende Gruppe von Zeitangaben.



$$
T=86400d+3600h+60m+s
$$







## Berechnungsmodus





### Zwischen Uhrzeiten



- Startzeit
- Endzeit
- Pause · min
- Über Mitternacht erlauben







### Dauern summieren



- Dauern







### Zwischen Datum und Uhrzeit



- Startdatum
- Startzeit
- Enddatum
- Endzeit







### Dauern addieren oder subtrahieren



- Erste Dauer
- Rechenart · Addieren / Subtrahieren
- Zweite Dauer







### Datum und Uhrzeit verschieben



- Startdatum
- Startzeit
- Rechenart · Addieren / Subtrahieren
- Dauer







### Zeitausdruck



- Zeitausdruck







[ZooChief](<https://docs.toolpony.com/de/about/>) · [Ergebnisfehler melden](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fde%2Fguides%2Ftime-duration-calculator%2F>)

[Dokumentation](https://docs.toolpony.com/de/guides/time-duration-calculator/)
