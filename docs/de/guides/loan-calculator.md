# Anleitung: Kreditrechner



Berechnen Sie Raten, die Laufzeit aus einer Monatsrate oder datierte Sondertilgungen und exportieren Sie den Plan.





## Erste Schritte



1. Wählen Sie eine feste Laufzeit, eine Zielmonatsrate oder datierte Sondertilgungen.
2. Geben Sie den ersten Zahlungsmonat an. Einmalzahlungen stehen je Zeile, etwa 2026-06, 500.
3. Berechnen Sie und wählen Sie den gewünschten Plan zum Herunterladen.







## Beispiel



### Eingabe



```
100.000 für 10 Jahre bei 6 %, monatlich
```



### Erwartetes Ergebnis



```
≈1.110,21 pro Monat
```





<a id="case-study"></a>



## Was spart eine monatliche Sondertilgung von 100?



1. Wählen Sie das Beispiel mit monatlich 100 zusätzlich. Es rechnet mit 100.000 Darlehenssumme, zehn Jahren Laufzeit und festen 6 % pro Jahr bei monatlicher Verzinsung und Zahlung.
2. Die reguläre Rate beträgt 1.110,21. Mit monatlich 100 zusätzlicher Tilgung sinkt die Zahl der Raten von 120 auf 107 und der Gesamtzins von 33.224,60 auf 29.328,37.
3. Vergleichen Sie die Restschulden und prüfen Sie die letzte Rate von 1.046,63 im Tilgungsplan. Intern wird mit ungerundeten Raten gerechnet. Sonderzahlungen tilgen direkt die Restschuld.





## Ausprobieren

[Vollständiges Werkzeug öffnen · Kreditrechner](<https://toolpony.com/de/tools/loan-calculator/#example-extra-payment>)





## Berechnungsmethode



Raten nutzen den auf die Zahlungsperiode umgerechneten Nominalzins. Datierte Sondertilgungen folgen auf die reguläre Monatsrate. Der Zinssatz bleibt fest, Zwischenwerte bleiben ungerundet.



$$
M=\frac{Pr}{1-(1+r)^{-n}},\qquad M=\frac Pn\quad(r=0)
$$



$$
n=\frac{-\ln(1-Pr/M)}{\ln(1+r)},\qquad M>Pr\quad(r>0)
$$



$$
I_k=r B_{k-1},\qquad B_k=\max(0,B_{k-1}-(M-I_k)-E_k)
$$



P ist der Kreditbetrag, r der Periodenzins, M die Regelrate und n die Laufzeit in Perioden. Bei der Laufzeit aus der Monatsrate und bei datierten Sondertilgungen gilt der Jahresprozentsatz geteilt durch 1.200. B ist die Restschuld, I sind die Zinsen und E ist die Sondertilgung.



45.000 bei 6,3 % und 785 Monatsrate ergeben rund 68,38 Monate. Monatlich abgerechnet sind es 69 Raten mit kleinerer Schlussrate. Wählen Sie den Plan vor dem Download.







## Berechnungsmodus





### Ratenzahlung



- Darlehensbetrag
- Jahre
- Monate
- Jahreszins · %
- Zinsintervall
- Zahlungsintervall · Jährlich / Halbjährlich / Vierteljährlich / Monatlich / Zweimal pro Monat / Alle zwei Wochen / Wöchentlich / Täglich
- Zusatz je Rate







### Laufzeit aus Monatsrate



- Darlehensbetrag
- Monatsrate
- Jahreszins · %







### Datierte Sondertilgungen



- Darlehensbetrag
- Jahre
- Monate
- Jahreszins · %
- Erster Zahlungsmonat
- Monatliche Sondertilgung
- Beginn der monatlichen Sondertilgung
- Jährliche Sondertilgung
- Beginn der jährlichen Sondertilgung
- Einmalzahlungen







### Einmalzahlung bei Fälligkeit



- Darlehensbetrag
- Jahre
- Monate
- Jahreszins · %
- Zinsintervall







### Barwert einer Einmalzahlung



- Betrag bei Fälligkeit
- Jahre
- Monate
- Jahreszins · %
- Zinsintervall







**Quellen zur Methode** [CFPB · Mortgage amortization](<https://www.consumerfinance.gov/ask-cfpb/how-does-paying-down-a-mortgage-work-en-1943/>)



[ZooChief](<https://docs.toolpony.com/de/about/>) · [Ergebnisfehler melden](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fde%2Fguides%2Floan-calculator%2F>)

[Dokumentation](https://docs.toolpony.com/de/guides/loan-calculator/)
