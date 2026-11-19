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





<a id="case-study"></a>



## Ein Grau für normalen Text auf weißem Grund wählen



1. Testen Sie \#777777 auf Weiß. Das Verhältnis beträgt etwa 4,48:1. Auf eine Nachkommastelle gerundet erscheint 4,5, doch mit dem ungerundeten Wert verfehlt normaler Text WCAG AA.
2. Testen Sie \#767676 auf demselben Weiß. Etwa 4,54:1 reichen für normalen Text nach AA. Beide Beispiele erreichen die Schwelle von 3:1 für Großschrift.
3. Prüfen Sie die tatsächlich dargestellten Vorder- und Hintergrundfarben. Bei Text über Bildern oder durchscheinenden Ebenen nehmen Sie die zusammengesetzten Farben an der kontrastärmsten Stelle. Das Ergebnis gilt für das geprüfte Farbpaar.





## Ausprobieren

[Vollständiges Werkzeug öffnen · Kontrastprüfer](<https://toolpony.com/de/tools/contrast-checker/>)





## Berechnungsmethode



Der Kontrast ist (hellere Leuchtdichte + 0,05) geteilt durch (dunklere Leuchtdichte + 0,05). Geprüft wird der ungerundete Wert. Normaler Text benötigt 4,5:1 für AA und 7:1 für AAA, großer Text 3:1 für AA und 4,5:1 für AAA.





**Quellen zur Methode** [W3C · WCAG 2.2 (1.4.3, AA)](<https://www.w3.org/WAI/WCAG22/Understanding/contrast-minimum.html>) · [W3C · WCAG 2.2 (1.4.6, AAA)](<https://www.w3.org/WAI/WCAG22/Understanding/contrast-enhanced.html>)



[ZooChief](<https://docs.toolpony.com/de/about/>) · [Ergebnisfehler melden](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fde%2Fguides%2Fcontrast-checker%2F>)

[Dokumentation](https://docs.toolpony.com/de/guides/contrast-checker/)
