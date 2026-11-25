# Anleitung: Zufallszahlengenerator



Zufällige ganze Zahlen einschließlich beider Bereichsgrenzen ziehen, auf Wunsch ohne Wiederholung und sortiert.





## Beispiel



### Eingabe



```
Minimum 1, Maximum 10, Anzahl 5
```



### Erwartetes Ergebnis



```
Fünf zufällige Ganzzahlen von 1 bis 10
```





<a id="case-study"></a>



## Vier Lose ziehen



1. Nummerieren Sie zwölf Lose von 101 bis 112 und ziehen Sie vier ohne Wiederholung. Sortieren Sie zum Vorlesen und schalten Sie die Sortierung für die ursprüngliche Reihenfolge aus. Die CSV enthält die Ziehposition jedes Loses.



[Beispiel ausführen](<https://toolpony.com/de/tools/random-number-generator/#example-ticket-draw>)





## Ausprobieren

[Vollständiges Werkzeug öffnen · Zufallszahlengenerator](<https://toolpony.com/de/tools/random-number-generator/>)





## Berechnungsmethode



Zufallswerte kommen von Web Crypto. Ablehnungsstichproben vermeiden Modulo-Bias. Generieren Sie bis zu 1.000 Werte im Bereich -1.000.000.000 bis 1.000.000.000.





**Quellen zur Methode** [W3C · Web Cryptography](<https://www.w3.org/TR/WebCryptoAPI/#Crypto-method-getRandomValues>)



[ZooChief](<https://docs.toolpony.com/de/about/>) · [Ergebnisfehler melden](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fde%2Fguides%2Frandom-number-generator%2F>)

[Dokumentation](https://docs.toolpony.com/de/guides/random-number-generator/)
