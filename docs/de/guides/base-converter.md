# Anleitung: Zahlensystem-Umrechner und Rechner



Konvertieren Sie signierte ganze Zahlen zwischen den Basen 2–36 und führen Sie genaue arithmetische, restliche oder bitweise Operationen aus.





## Beispiel



### Eingabe



```
FF, Basis 16 zu Basis 10
```



### Erwartetes Ergebnis



```
255
```





<a id="case-study"></a>



## Eine lange Hex-ID prüfen



1. Wandle 0x20\_0000\_0000\_0001 in eine Dezimalzahl um. Die letzte 1 bleibt in 9007199254740993 erhalten. Tausche die Basen oder kopiere die Binärdarstellung ohne Abstände.



[Beispiel ausführen](<https://toolpony.com/de/tools/base-converter/#example-large-hex-id>)





## Ausprobieren

[Vollständiges Werkzeug öffnen · Zahlensystem-Umrechner und Rechner](<https://toolpony.com/de/tools/base-converter/>)





## Berechnungsmethode



BigInt erhält jede Ziffer. Die Umrechnung unterstützt bis zu 4.096 Bit, die Arithmetik bis zu 256 Ziffern je Operand. Die Ganzzahldivision rundet zu null. Leerzeichen oder Unterstriche dürfen Ziffern trennen.







## Berechnungsmodus





### Konverterbasis



- Ganze Zahl
- Input-Basis
- Outputbasis
- Mindestausgangsstellen







### Ganzheitliche Arithmetik



- Erste ganze Zahl
- Zweite ganze Zahl
- Input-Basis
- Outputbasis
- Mindestausgangsstellen
- Rechenoperation · Additiv / Subtraktion / Multiplikation / Teilung / Rest / AND / OR / XOR







[ZooChief](<https://docs.toolpony.com/de/about/>) · [Ergebnisfehler melden](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fde%2Fguides%2Fbase-converter%2F>)

[Dokumentation](https://docs.toolpony.com/de/guides/base-converter/)
