# Autokreditrechner



Berechnen Sie Monatsrate oder maximalen Fahrzeugpreis mit Inzahlungnahme, Restschuld, Rabatten und Steuern.





## Erste Schritte



1. Geben Sie Preis oder Zielrate ein. Ergänzen Sie Anzahlung, Inzahlungnahme, Restschuld und Rabatte.
2. Geben Sie Steuer und Gebühren ein. Legen Sie Abzüge und Finanzierung fest und exportieren Sie den Plan.







## Beispiel



### Eingabe



```
Preis 30.000, Anzahlung 5.000, 5 % bei 60 Monaten
```



### Erwartetes Ergebnis



```
471,78 monatlich ohne Steuern und Gebühren
```







## Ausprobieren



[Vollständiges Werkzeug öffnen](<https://toolpony.com/de/tools/auto-loan-calculator/>)







## Hinweise



Die Verarbeitung erfolgt im Browser. Verwenden Sie einheitliche Einheiten.







## Berechnungsmethode



Geben Sie Steuersatz und Abzüge von der Bemessungsgrundlage an. Mitfinanzierte Steuern und Gebühren erhöhen den Kreditbetrag. Der Nettowert der Inzahlungnahme ist der Wert abzüglich Restschuld. Der Monatszins ist fest.



$$
P=V-D-(T-O)-R+F,\quad M=\frac{Pr}{1-(1+r)^{-n}},\quad M=\frac Pn\; (r=0)
$$



V ist der Fahrzeugpreis, D die Anzahlung, T der Inzahlungnahmewert, O die Restschuld, R der Rabatt und F sind mitfinanzierte Steuern und Gebühren. P ist der Kreditbetrag, M die Monatsrate, r der Monatszins und n die Monatszahl.







## Berechnungsmodus



**Monatsrate berechnen**

- Fahrzeugpreis
- Monate
- Jahreszins · %
- Anzahlung
- Inzahlungnahmewert
- Restschuld des Altfahrzeugs
- Bar-Rabatt
- Verkaufssteuer · %
- Zulassung und weitere Gebühren
- Inzahlungnahme vom Steuerwert abziehen
- Rabatt vom Steuerwert abziehen
- Steuer und Gebühren mitfinanzieren
- Währung





**Fahrzeugpreis berechnen**

- Monatsrate
- Monate
- Jahreszins · %
- Anzahlung
- Inzahlungnahmewert
- Restschuld des Altfahrzeugs
- Bar-Rabatt
- Verkaufssteuer · %
- Zulassung und weitere Gebühren
- Inzahlungnahme vom Steuerwert abziehen
- Rabatt vom Steuerwert abziehen
- Steuer und Gebühren mitfinanzieren
- Währung

[Dokumentation](https://docs.toolpony.com/de/guides/auto-loan-calculator/)
