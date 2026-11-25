# Anleitung: Wahrscheinlichkeitsrechner



Ereignisse als Wahrscheinlichkeiten oder Häufigkeiten untersuchen, bedingte Wahrscheinlichkeiten vergleichen und unabhängige Ereignisse berechnen.





## Beispiel



### Eingabe



```
Unabhängige Ereignisse A = 0,31, B = 0,56
```



### Erwartetes Ergebnis



```
Mindestens ein Ereignis 0,6964
```





<a id="case-study"></a>



## Teilnahme an zwei Workshops



1. Von 50 Personen kamen 18 zu beiden Terminen, 12 nur morgens (AM), 6 nur nachmittags (PM) und 14 gar nicht. Von den 24 am Nachmittag waren 18 auch morgens da (75 %). Von den 30 am Morgen kamen 18 wieder (60 %).



[Beispiel ausführen](<https://toolpony.com/de/tools/probability-calculator/#example-workshop-attendance>)





## Ausprobieren

[Vollständiges Werkzeug öffnen · Wahrscheinlichkeitsrechner](<https://toolpony.com/de/tools/probability-calculator/>)





## Berechnungsmethode



Die Vereinigung ist die Summe der Randwahrscheinlichkeiten abzüglich der Schnittmenge. Innerhalb B ist der Anteil von A gleich P(A ∩ B) / P(B). Bei Unabhängigkeit ergibt das Produkt der Randwahrscheinlichkeiten den Schnitt.



$$
P(A\cup B)=P(A)+P(B)-P(A\cap B)
$$



$$
P(A\cap B)=P(A)P(B)\quad\text{(independent)}
$$







## Berechnungsmodus





### Zwei unabhängige Veranstaltungen



- Wahrscheinlichkeit von A
- Wahrscheinlichkeit von B







### Bekannter Schnittpunkt



- Eingabe · Wahrscheinlichkeiten / Häufigkeiten
- Wahrscheinlichkeit von A
- Wahrscheinlichkeit von B
- Beide Veranstaltungen
- Name für Ereignis A
- Name für Ereignis B
- A ∩ B
- A ∩ ¬B
- ¬A ∩ B
- ¬A ∩ ¬B







### Unabhängige Veranstaltungen wiederherstellen



- Erste bekannte Menge · Wahrscheinlichkeit von A / Wahrscheinlichkeit von B / Nicht A / Nicht B / Beide Veranstaltungen / Mindestens ein Ereignis / Genau ein Ereignis / Keine der beiden Veranstaltungen
- Erste Wahrscheinlichkeit
- Zweite bekannte Menge · Wahrscheinlichkeit von A / Wahrscheinlichkeit von B / Nicht A / Nicht B / Beide Veranstaltungen / Mindestens ein Ereignis / Genau ein Ereignis / Keine der beiden Veranstaltungen
- Zweite Wahrscheinlichkeit







### Wiederholte unabhängige Versuche



- Wahrscheinlichkeit von A
- Versuche von A
- Wahrscheinlichkeit von B
- Versuche von B







### Normalverteilungsintervall



- Mittelwert
- Standardabweichung
- Untere Grenze
- Obere Grenze







**Quellen zur Methode** [OpenStax · Contingency Tables](<https://openstax.org/books/introductory-statistics-2e/pages/3-4-contingency-tables>)



[ZooChief](<https://docs.toolpony.com/de/about/>) · [Ergebnisfehler melden](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fde%2Fguides%2Fprobability-calculator%2F>)

[Dokumentation](https://docs.toolpony.com/de/guides/probability-calculator/)
