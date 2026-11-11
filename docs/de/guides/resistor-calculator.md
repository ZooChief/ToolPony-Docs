# Widerstands- und Farbcode-Rechner



Lesen Sie 3–6 Farbringe und berechnen Sie Reihen-, Parallel- oder Drahtwiderstände.





## Erste Schritte



1. Wählen Sie Ringanzahl oder Schaltungsart. Der Toleranzring ist oft weiter von den übrigen entfernt.
2. Geben Sie Durchmesser und Länge des Runddrahts ein. Eine Materialvorgabe füllt die bearbeitbare Leitfähigkeit aus.







## Beispiel



### Eingabe



```
4 Ringe: Grün, Rot, Rot, Gold
```



### Erwartetes Ergebnis



```
5,200 Ω ±5%
```







## Ausprobieren



[Vollständiges Werkzeug öffnen](<https://toolpony.com/de/tools/resistor-calculator/>)







## Hinweise



Die Verarbeitung erfolgt im Browser. Verwenden Sie einheitliche Einheiten.







## Berechnungsmethode



Lesen Sie Ziffern, Multiplikator, Toleranz und gegebenenfalls Temperaturkoeffizient. Drei Ringe bedeuten 20 % Toleranz. Für homogenen Runddraht gilt R = L/(σA). Sondermarkierungen stehen im Datenblatt.



$$
R_{\rm series}=\sum_i R_i,\quad R_{\rm parallel}=\left(\sum_i 1/R_i\right)^{-1},\quad R_{\rm wire}=\frac{L}{\sigma\pi(d/2)^2}
$$



$$
R_{\rm band}=D\,10^m,\qquad R_{\min,\max}=R_{\rm band}(1\mp t/100)
$$







## Berechnungsmodus



**4 Ringe**

- Erste Ziffer
- Zweite Ziffer
- Multiplikator
- Toleranz





**3 Ringe**

- Erste Ziffer
- Zweite Ziffer
- Multiplikator





**5 Ringe**

- Erste Ziffer
- Zweite Ziffer
- Dritte Ziffer
- Multiplikator
- Toleranz





**6 Ringe**

- Erste Ziffer
- Zweite Ziffer
- Dritte Ziffer
- Multiplikator
- Toleranz
- Temperaturkoeffizient





**Parallelschaltung**

- Widerstände in Ω





**Reihenschaltung**

- Widerstände in Ω





**Runder Leiter**

- Länge
- Längeneinheit · mm / cm / m / km / in / ft / yd / mi
- Durchmesser
- Durchmessereinheit · mm / cm / m / km / in / ft / yd / mi
- Materialvorgabe · Benutzerdefiniert / Kupfer / Geglühtes Kupfer / Aluminium / Silber / Gold
- Leitfähigkeit · S/m

[Dokumentation](https://docs.toolpony.com/de/guides/resistor-calculator/)
