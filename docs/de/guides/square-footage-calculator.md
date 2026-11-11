# Flächenrechner in Quadratfuß



Schätzen Sie die Flächen- und Materialkosten für neun Formen mit gemischten Messungen und einer Abfallmenge.





## Erste Schritte



1. Wählen Sie die Form des Bereichs, verwenden Sie Außenabmessungen für den Rechteckrand oder -ring. Der Sektor nimmt einen Radius und einen Mittelwinkel ein.
2. Geben Sie die Anzahl der identischen Flächen und optional den Preis pro ausgewählter Flächeneinheit ein.
3. Lesen Sie die Nettofläche in Quadratmetern und Metern. Fügen Sie eine Abfallmenge unter Weitere Optionen hinzu, um zu schätzen, wie viel bestellt werden soll.







## Beispiel



### Eingabe



```
13 ft × 9 ft, Menge 1
```



### Erwartetes Ergebnis



```
117 ft² (10,86965568 m²)
```







## Ausprobieren



[Vollständiges Werkzeug öffnen](<https://toolpony.com/de/tools/square-footage-calculator/>)







## Hinweise



Die Verarbeitung erfolgt im Browser. Verwenden Sie einheitliche Einheiten.







## Berechnungsmethode



Umrechnen der Abmessungen in eine gemeinsame Einheit, die Fläche einer Form finden und mit der Menge multiplizieren. Kosten verwendet Fläche mit einer beliebigen ausgewählten Zulage, umgerechnet in die Preiseinheit. Grenzabmessungen werden von außen nach außen gemessen.



$$
A_{\rm border}=lw-(l-2b)(w-2b),\qquad A_{\rm ring}=\pi b(d-b)
$$



$$
A_{\rm sector}=r^2\theta/2,\qquad A_{\rm order}=q A(1+w/100)
$$



Die Randbreite b wird von jeder Kante nach innen gemessen. Bei einem Ring ist d der Außendurchmesser. A 13 ft × 9 ft außerhalb des Rechtecks mit einem 2 ft Rand hat 72 ft2 Rand pro Stück.



Für einen Sektor ist r der Radius und θ der Winkel in Radiant nach jeder Umrechnung. In der Ordnungsformel ist q die Menge und w die prozentuale Zulage.







## Berechnungsmodus



**Rechteck**

- Länge
- Längeneinheit
- Breite
- Breiteneinheit
- Menge
- Stückpreis
- Preis pro Fläche
- Abfallentschädigung · %





**Rechteckgrenze**

- Länge
- Längeneinheit
- Breite
- Breiteneinheit
- Grenzbreite
- Grenzbreiteneinheit
- Menge
- Stückpreis
- Preis pro Fläche
- Abfallentschädigung · %





**Kreis**

- Durchmesser
- Durchmessereinheit
- Menge
- Stückpreis
- Preis pro Fläche
- Abfallentschädigung · %





**Ring**

- Außendurchmesser
- Außendurchmessereinheit
- Grenzbreite
- Grenzbreiteneinheit
- Menge
- Stückpreis
- Preis pro Fläche
- Abfallentschädigung · %





**Dreieck · drei Seiten**

- erste Seite
- erste Seiteneinheit
- zweite Seite
- zweite Seiteneinheit
- dritte Seite
- dritte Seiteneinheit
- Menge
- Stückpreis
- Preis pro Fläche
- Abfallentschädigung · %





**Dreieck · Basis und Höhe**

- Basis
- Basiseinheit
- Senkrechte Höhe
- Senkrechte Höheneinheit
- Menge
- Stückpreis
- Preis pro Fläche
- Abfallentschädigung · %





**Trapez**

- erste Parallelseite
- erste Parallelseiteneinheit
- zweite Parallelseite
- zweite Parallelseiteneinheit
- Senkrechte Höhe
- Senkrechte Höheneinheit
- Menge
- Stückpreis
- Preis pro Fläche
- Abfallentschädigung · %





**Kreissektor**

- Radius
- Radiuseinheit
- Mittelwinkel
- Winkeleinheit · Grad / Radianten
- Menge
- Stückpreis
- Preis pro Fläche
- Abfallentschädigung · %





**Parallelogramm**

- Basis
- Basiseinheit
- Senkrechte Höhe
- Senkrechte Höheneinheit
- Menge
- Stückpreis
- Preis pro Fläche
- Abfallentschädigung · %

[Dokumentation](https://docs.toolpony.com/de/guides/square-footage-calculator/)
