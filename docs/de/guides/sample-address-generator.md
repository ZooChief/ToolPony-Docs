# Anleitung: Generator für Beispieladressen



Erzeuge Testadressen für 18 Länder und Gebiete mit Regionsauswahl, lokalen Formaten und Stapelexport.





## Erste Schritte



1. Wähle Land und Region, dann die Anzahl und optionale Kontaktdaten.
2. Mit denselben Einstellungen und demselben Startwert kannst du einen Stapel wiederholen. Kopiere Felder oder exportiere TXT, CSV oder JSON.
3. Lokal gespeicherte Adressbeispiele bleiben in diesem Browser. Du kannst sie im Werkzeug löschen.







## Beispiel



### Eingabe



```
Deutschland · Berlin · Startwert pony-demo
```



### Erwartetes Ergebnis



```
Testperson 001
Beispielstraße 4957
10115 Berlin
Deutschland
```





<a id="case-study"></a>



## Eine kanadische Adresse mit Einheit prüfen



1. Erzeuge mit dem Startwert label-review zwei Testadressen in Ontario mit Einheitsnummer, ohne Kontaktdaten. Gleiche Einstellungen ergeben dasselbe Paar.
2. In der Textdatei steht die Einheit mit Bindestrich vor der Hausnummer. In der Ortszeile folgen auf ON zwei Leerzeichen und die Postleitzahl. JSON enthält die Elemente auch als einzelne Felder.



[Beispiel ausführen](<https://toolpony.com/de/tools/sample-address-generator/#example-canadian-label>)





## Ausprobieren

[Vollständiges Werkzeug öffnen · Generator für Beispieladressen](<https://toolpony.com/de/tools/sample-address-generator/>)





## Berechnungsmethode



Bis zu 100 Beispiele pro Lauf. Ort und Postleitzahl dienen als Formatbeispiele, Straße und Empfänger sind synthetisch. Telefonbeispiele verwenden reservierte Nummern oder Platzhalter. Geeignet für Formular- und Softwaretests.





**Quellen zur Methode** [USPS · Publication 28, §213](<https://pe.usps.com/text/pub28/28c2_003.htm>) · [Canada Post · Civic address](<https://www.canadapost-postescanada.ca/cpc/en/support/articles/addressing-guidelines/civic-address.page>)



[ZooChief](<https://docs.toolpony.com/de/about/>) · [Ergebnisfehler melden](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fde%2Fguides%2Fsample-address-generator%2F>)

[Dokumentation](https://docs.toolpony.com/de/guides/sample-address-generator/)
