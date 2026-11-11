# Untertitel-Konverter



Wandeln Sie SRT und WebVTT um, verschieben oder skalieren Sie die Zeit und prüfen Sie Überlappungen.





## Erste Schritte



1. Fügen Sie Text ein oder importieren Sie SRT oder VTT und wählen Sie das Ausgabeformat.
2. Ein positiver Versatz verzögert Untertitel. Skalieren Sie die Zeit relativ zum Anker und addieren Sie den Versatz. Prüfen Sie Kürzungen und Überlappungen.







## Beispiel



### Eingabe



```
1
00:00:00,120 --> 00:00:01,400
A line
Second line

2
00:00:01,350 --> 00:00:02,700
Overlap 50 ms
```



### Erwartetes Ergebnis



```
WEBVTT

00:00:00.120 --> 00:00:01.400
A line
Second line

00:00:01.350 --> 00:00:02.700
Overlap 50 ms
```







## Ausprobieren



[Vollständiges Werkzeug öffnen](<https://toolpony.com/de/tools/subtitle-converter/>)







## Grenzen



Bis 1 MiB Text und 10.000 Untertitel. Vor null endende Untertitel werden entfernt, übergreifende beginnen bei null. SRT kann nicht alle WebVTT-Positionen, Stile oder Kennungen abbilden.

[Dokumentation](https://docs.toolpony.com/de/guides/subtitle-converter/)
