# Anleitung: Passwortgenerator



Generieren Sie Passwörter lokal mit Zeichensätzen, benutzerdefinierten Ausschlüssen und optionalen eindeutigen Zeichen.





## Beispiel



### Eingabe



```
20 Zeichen, vier Zeichengruppen
```



### Erwartetes Ergebnis



```
Ein neues Zufallspasswort
```





<a id="case-study"></a>



## Testcodes zum Abtippen



1. Erzeuge sechs Codes mit je 16 Großbuchstaben und Ziffern. Schließe 2Z5S8B aus, damit drei weitere leicht verwechselbare Zeichenpaare entfallen.
2. Jede Zeile enthält beide Gruppen und kein Zeichen doppelt. Kopiere eine Zeile ins Testformular. Erneutes Öffnen des Beispiels erzeugt neue Werte auf deinem Gerät.



[Beispiel ausführen](<https://toolpony.com/de/tools/password-generator/#example-readable-codes>)





## Ausprobieren

[Vollständiges Werkzeug öffnen · Passwortgenerator](<https://toolpony.com/de/tools/password-generator/>)





## Berechnungsmethode



Web Crypto liefert Zufälligkeit. Wenn erforderliche Gruppen aktiviert sind, wird aus jeder Gruppe ein Zeichen ausgewählt, dann werden Positionen gemischt. Passwörter werden auf der aktuellen Seite gespeichert, bis Sie sie verlassen oder löschen.





**Quellen zur Methode** [W3C · Web Cryptography](<https://www.w3.org/TR/WebCryptoAPI/#Crypto-method-getRandomValues>)



[ZooChief](<https://docs.toolpony.com/de/about/>) · [Ergebnisfehler melden](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fde%2Fguides%2Fpassword-generator%2F>)

[Dokumentation](https://docs.toolpony.com/de/guides/password-generator/)
