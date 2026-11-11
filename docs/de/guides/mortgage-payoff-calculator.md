# Hypotheken-Tilgungsrechner



Vergleichen Sie die verbleibenden Raten, Sondertilgungen, eine Ablösung und zwei zweiwöchentliche Modelle.





## Erste Schritte



1. Nutzen Sie nach früheren Sondertilgungen Restschuld und Rate aus dem Kontoauszug. Sonst können Sie die Restschuld aus dem ursprünglichen Kredit und der Restlaufzeit bestimmen.
2. Wählen Sie einen Plan und geben Sie monatliche, jährliche oder einmalige Zusätze ein. Standardmäßig beginnen sie in Monat 1, 12 und 1. Die erweiterten Optionen ändern den Start.
3. Vergleichen Sie den gewählten und den regulären Plan und laden Sie den Plan oder die Vergleichs-CSV herunter.
4. Berechnet werden Restschuld und Festzinsen. Ein tatsächlicher Ablösebetrag kann Tageszinsen, Gebühren und Entschädigungen enthalten. Fragen Sie Ihr Kreditinstitut.







## Beispiel



### Eingabe



```
Ursprünglich 400.000, 30 Jahre, 6 %. Noch 25 Jahre und 500 extra pro Monat.
```



### Erwartetes Ergebnis



```
207 Monate, 122.306,21 Zinsersparnis
```







## Ausprobieren



[Vollständiges Werkzeug öffnen](<https://toolpony.com/de/tools/mortgage-payoff-calculator/>)







## Hinweise



Die Verarbeitung erfolgt im Browser. Verwenden Sie einheitliche Einheiten.







## Berechnungsmethode



Im Modus mit ursprünglichem Kredit gelten alle bisherigen Zahlungen als planmäßig. Monatszinsen sind Restschuld mal Jahreszins geteilt durch zwölf. Das gebündelte Modell addiert alle sechs Monate eine halbe Monatsrate. Das Modell mit 26 Raten nutzt halbe Monatsraten und den Jahreszins geteilt durch 26.



$$
B=M\frac{1-(1+r)^{-n}}r\quad(r>0),\qquad B=Mn\quad(r=0)
$$



$$
I_k=rB_{k-1},\qquad B_k=\max(0,B_{k-1}-M+I_k-E_k)
$$



$$
E_{6j}=M/2\quad\text{(grouped)},\qquad M_{26}=M/2,\quad r_{26}=r_{\rm annual}/26
$$







## Berechnungsmodus



**Ursprünglicher Kredit und Restlaufzeit**

- Ursprünglicher Kreditbetrag
- Ursprüngliche Laufzeit in Jahren
- Zusätzliche ursprüngliche Monate
- Jahreszins · %
- Restjahre
- Zusätzliche Restmonate
- Tilgungsmodell · Sondertilgungen / Regelraten / Zweiwöchentlich, monatlich gebündelt / Zweiwöchentlich, 26 Raten pro Jahr / Restschuld sofort tilgen
- Monatliche Sondertilgung
- Jährliche Sondertilgung
- Einmalige Sondertilgung
- Erster Monat für monatliche Sondertilgungen
- Erster Monat für jährliche Sondertilgungen
- Monat der Einmalzahlung





**Aktuelle Restschuld und Rate**

- Restschuld
- Monatsrate
- Jahreszins · %
- Tilgungsmodell · Sondertilgungen / Regelraten / Zweiwöchentlich, monatlich gebündelt / Zweiwöchentlich, 26 Raten pro Jahr / Restschuld sofort tilgen
- Monatliche Sondertilgung
- Jährliche Sondertilgung
- Einmalige Sondertilgung
- Erster Monat für monatliche Sondertilgungen
- Erster Monat für jährliche Sondertilgungen
- Monat der Einmalzahlung

[Dokumentation](https://docs.toolpony.com/de/guides/mortgage-payoff-calculator/)
