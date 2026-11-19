# Kontrastprüfer



Zwei deckende Farben anhand der Kontrastgrenzen von WCAG 2.2 prüfen.





## Beispiel



### Eingabe



```
#000000 auf #FFFFFF
```



### Erwartetes Ergebnis



```
21:1
```







## Ausprobieren

[Vollständiges Werkzeug öffnen · Kontrastprüfer](<https://toolpony.com/de/tools/contrast-checker/>)





## Berechnungsmethode



Der Kontrast ist (hellere Leuchtdichte + 0,05) geteilt durch (dunklere Leuchtdichte + 0,05). Geprüft wird der ungerundete Wert. Normaler Text benötigt 4,5:1 für AA und 7:1 für AAA, großer Text 3:1 für AA und 4,5:1 für AAA.

[Dokumentation](https://docs.toolpony.com/de/guides/contrast-checker/)
