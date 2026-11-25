# Anleitung: Prozentrechner



Prozente und Prozentpunkte vergleichen, zwei Rabatte anwenden oder zurückrechnen.





## Erste Schritte



1. Wählen Sie für einen Teil wie 15% von 240 den Prozentsatz eines Wertes. Wenn der Teil 36 ist und Sie die Gesamtsumme oder die Rate kennen, wählen Sie den entsprechenden inversen Modus.
2. Wählen Sie prozentuale Änderung für einen bestellten alten und neuen Wert. Verwenden Sie die prozentuale Differenz für zwei positive Werte ohne Baseline.
3. Geben Sie 15 für 15% ein, vergleichen Sie das Ergebnis mit den unten beschriebenen Beispielen.







## Beispiel



### Eingabe



```
15 % von 240
```



### Erwartetes Ergebnis



```
36
```





<a id="case-study"></a>



## Zwei Rabatte auf einen Preis



1. Von 250 gehen zuerst 20 % ab. Auf die verbleibenden 200 gelten weitere 10 %. Der Endpreis beträgt 180, insgesamt 28 % weniger. Die Rückrechnung ergibt den Ausgangspreis.



[Beispiel ausführen](<https://toolpony.com/de/tools/percentage-calculator/#example-two-discounts>)





## Von 4 % auf 5 %



Eine Anmeldequote steigt von 4 % auf 5 %. Die Differenz beträgt einen Prozentpunkt. Bezogen auf die ursprünglichen 4 % ergibt 1 ÷ 4 einen Anstieg um 25 %.



[Beispiel ausführen](<https://toolpony.com/de/tools/percentage-calculator/#example-percentage-points>)







## Ausprobieren

[Vollständiges Werkzeug öffnen · Prozentrechner](<https://toolpony.com/de/tools/percentage-calculator/>)





## Berechnungsmethode



Relative Änderungen beziehen sich auf den Betrag des Ausgangswerts. Die Differenz zweier Quoten ergibt Prozentpunkte. Aufeinanderfolgende Faktoren werden multipliziert. Die symmetrische Differenz nutzt den Mittelwert der Beträge.



$$
x=yp/100,\quad p=100x/y,\quad y=100x/p
$$



$$
\Delta\%=100\frac{x_1-x_0}{|x_0|},\quad D\%=200\frac{|x_1-x_0|}{|x_1|+|x_0|}
$$



80 → 100 ist eine Veränderung von 25%, weil 80 der Startwert ist. Der prozentuale Unterschied zwischen den gleichen Zahlen beträgt etwa 22,22%, weil der Nenner ihr Mittelwert ist, 90.



Nach einem Anstieg von 20% auf 120 ergibt Reverse eine Änderung 100. Eine Änderung von -100% kann nicht rückgängig gemacht werden.



Bei einem Messwert von 90 und einem Referenzwert von 96 beträgt der absolute Fehlerprozent 6,25 %. Das signierte Ergebnis mit diesem positiven Referenzwert ist -6,25 %.







## Berechnungsmodus





### Prozentsatz eines Wertes



- Prozentsatz · %
- Wert







### Finden Sie den Prozentsatz



- Teil
- ganz







### Finde das Ganze



- Teil
- Prozentsatz · %







### prozentuale Veränderung



- Art der Werte · Beträge / Quoten (%)
- Ausgangswert
- Neuwert







### Prozentuale Differenz



- Erster Wert
- zweiter Wert







### Differenz zu signierten Werten



- Erster Wert
- zweiter Wert







### Anwenden einer Änderung



- Ausgangswert
- Unterzeichnete Änderung · %
- Zweite Änderung · %







### Eine Änderung rückgängig machen



- Neuwert
- Unterzeichnete Änderung · %
- Zweite Änderung · %







### Fehler in Prozent



- Messwert
- Bezugswert
- Fehlerkonvention · Absolute Werte / Vorzeichen relativ zur Referenz







**Quellen zur Methode** [Eurostat · Percentage point](<https://ec.europa.eu/eurostat/statistics-explained/index.php?title=Glossary:Percentage_point>)



[ZooChief](<https://docs.toolpony.com/de/about/>) · [Ergebnisfehler melden](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fde%2Fguides%2Fpercentage-calculator%2F>)

[Dokumentation](https://docs.toolpony.com/de/guides/percentage-calculator/)
