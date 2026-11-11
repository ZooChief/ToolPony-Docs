# Dachflächenrechner



Berechnen Sie Dachfläche, Squares, Schindelpakete, Filzrollen und Kosten.





## Erste Schritte



1. Wählen Sie Grundfläche und Steigung oder Winkel. Bei einem Rechteck können Sie Länge und Breite eingeben.
2. Messen Sie bei komplexen Dächern die geneigten Teilflächen und geben Sie die Summe als bekannte Dachfläche ein.







## Beispiel



### Eingabe



```
2.000 ft² Grundfläche, Steigung 6/12, Überstand 1 ft.
```



### Erwartetes Ergebnis



```
Rund 2.461 ft², 28 Squares mit 10 % Zugabe.
```







## Ausprobieren



[Vollständiges Werkzeug öffnen](<https://toolpony.com/de/tools/roofing-calculator/>)







## Hinweise



Die Verarbeitung erfolgt im Browser. Verwenden Sie einheitliche Einheiten.







## Berechnungsmethode



Bei bekannter Grundfläche schätzt A + 4,4e(√A + e) den Überstand e. Für gemessene Rechteckseiten gilt (l + 2e)(w + 2e). Multiplizieren Sie die horizontale Fläche mit dem Neigungsfaktor. Ein Roofing Square entspricht 100 ft². Prüfen Sie die Produktdeckung.



$$
A_{\rm proj}\approx A+4.4e(\sqrt A+e),\qquad A_{\rm rect}=(l+2e)(w+2e)
$$



$$
A_{\rm roof}=A_{\rm proj}\sqrt{1+(p/12)^2}=\frac{A_{\rm proj}}{\cos\theta},\quad N_{\rm squares}=\left\lceil\frac{A_{\rm roof,ft^2}(1+a/100)}{100}\right\rceil
$$







## Berechnungsmodus



**Grundfläche und Steigung**

- Grundfläche
- Flächeneinheit · cm² / m² / in² / ft² / yd² / acre / ha
- Anstieg pro 12 horizontal
- Horizontaler Überstand
- Einheit des Überstands · mm / cm / m / in / ft / yd
- Einzelpreis
- Preiseinheit · cm² / m² / in² / ft² / yd² / acre / ha
- Verschnittzugabe · %





**Grundfläche und Winkel**

- Grundfläche
- Flächeneinheit · cm² / m² / in² / ft² / yd² / acre / ha
- Dachneigung · °
- Horizontaler Überstand
- Einheit des Überstands · mm / cm / m / in / ft / yd
- Einzelpreis
- Preiseinheit · cm² / m² / in² / ft² / yd² / acre / ha
- Verschnittzugabe · %





**Bekannte Dachfläche**

- Dachfläche
- Flächeneinheit · cm² / m² / in² / ft² / yd² / acre / ha
- Einzelpreis
- Preiseinheit · cm² / m² / in² / ft² / yd² / acre / ha
- Verschnittzugabe · %





**Gemessene Länge und Breite**

- Länge
- Längeneinheit · mm / cm / m / in / ft / yd
- Breite
- Breiteneinheit · mm / cm / m / in / ft / yd
- Anstieg pro 12 horizontal
- Horizontaler Überstand
- Einheit des Überstands · mm / cm / m / in / ft / yd
- Einzelpreis
- Preiseinheit · cm² / m² / in² / ft² / yd² / acre / ha
- Verschnittzugabe · %

[Dokumentation](https://docs.toolpony.com/de/guides/roofing-calculator/)
