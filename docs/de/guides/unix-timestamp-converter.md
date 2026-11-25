# Anleitung: Unix-Zeitstempel-Umrechner



Unix-Zeit in Sekunden, Millisekunden, Mikrosekunden oder Nanosekunden exakt in UTC umrechnen und zurück.





## Beispiel



### Eingabe



```
0 Sekunden
```



### Erwartetes Ergebnis



```
1970-01-01T00:00:00.000Z
```





<a id="case-study"></a>



## Eine Nanosekunde vor der Epoche



1. Mit ns und -1 erhalten Sie 1969-12-31T23:59:59.999999999Z. Wechseln Sie die Richtung, um dieselbe ganze Zahl zurückzuerhalten.
2. 1970-01-01T05:44:59.999999999+05:45 bezeichnet denselben Zeitpunkt. Kopieren Sie eine Einheit oder exportieren Sie alle vier in einer CSV-Zeile.



[Beispiel ausführen](<https://toolpony.com/de/tools/unix-timestamp-converter/#example-before-epoch>)





## Ausprobieren

[Vollständiges Werkzeug öffnen · Unix-Zeitstempel-Umrechner](<https://toolpony.com/de/tools/unix-timestamp-converter/>)





## Berechnungsmethode



Unix-Zeit zählt ab 1970-01-01T00:00:00Z ohne Schaltsekunden. UTC-Daten von 1900 bis 9999 erlauben neun Nachkommastellen und erfordern eine Zeitzonenangabe.







## Berechnungsmodus





### Zeitstempel → Datum



- Unix-Zeitstempel
- Einheit · Sekunden / Millisekunden / Mikrosekunden / Nanosekunden







### Datum → Zeitstempel



- ISO 8601 mit UTC-Versatz
- Einheit · Sekunden / Millisekunden / Mikrosekunden / Nanosekunden







**Quellen zur Methode** [GNU · Seconds since the Epoch](<https://www.gnu.org/software/coreutils/manual/html_node/Seconds-since-the-Epoch.html>) · [IETF · RFC 3339](<https://www.rfc-editor.org/rfc/rfc3339>)



[ZooChief](<https://docs.toolpony.com/de/about/>) · [Ergebnisfehler melden](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fde%2Fguides%2Funix-timestamp-converter%2F>)

[Dokumentation](https://docs.toolpony.com/de/guides/unix-timestamp-converter/)
