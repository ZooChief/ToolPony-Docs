# PDF in Text umwandeln



Extrahieren Sie auswählbaren Text lokal aus PDFs und speichern Sie ihn als TXT oder JSON.





## Erste Schritte



1. Öffnen Sie ein PDF mit auswählbarem Text.
2. Geben Sie die Reihenfolge der Seiten an und extrahieren Sie den Text. Speichern Sie TXT oder JSON mit den Originalseitenzahlen.







## Beispiel



### Eingabe



```
PDF mit „One“ und „Two“ auf den ersten zwei Seiten, Auswahl 2, 1
```



### Erwartetes Ergebnis



```
JSON mit Seite 2 „Two“, gefolgt von Seite 1 „One“
```







## Ausprobieren



[Vollständiges Werkzeug öffnen](<https://toolpony.com/de/tools/pdf-to-text/>)







## Grenzen



Maximal 30 MB, 300 Seiten, zwei Millionen Zeichen und 200.000 Textabschnitte. Die Textreihenfolge folgt der PDF-Datei. Gescannte Seiten erfordern OCR. Verschlüsselte PDFs werden abgelehnt.

[Dokumentation](https://docs.toolpony.com/de/guides/pdf-to-text/)
