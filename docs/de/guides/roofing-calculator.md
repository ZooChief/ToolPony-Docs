# Anleitung: Dachflächenrechner



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





<a id="case-study"></a>



## Schindeln bestellen



1. 25 × 40 ft Flachdach ergeben 1.000 ft². Mit 10 % Zuschlag und 3 Bündeln je 100 ft² braucht man 33 Bündel. Zu je 75 kosten sie 2.475.



[Beispiel ausführen](<https://toolpony.com/de/tools/roofing-calculator/#example-roof-order>)





## Gebindeetikett lesen



Bei 1.100 ft² Bedarf decken 33 Gebinde zu 33,3 ft² nur 1.098,9 ft². 34 Gebinde decken 1.132,2 ft².



[Beispiel ausführen](<https://toolpony.com/de/tools/roofing-calculator/#example-package-label>)







## Zwei Dachüberstände



Bei 8 × 5 m Grundmaß, 25 cm Trauf- und 40 cm Giebelüberstand beträgt die Dachprojektion 8,8 × 5,5 m. Mit Neigung 5/12, 10 % Reserve und 3 m² je Gebinde sind es 20 Gebinde.



[Beispiel ausführen](<https://toolpony.com/de/tools/roofing-calculator/#example-roof-overhang>)







## Ausprobieren

[Vollständiges Werkzeug öffnen · Dachflächenrechner](<https://toolpony.com/de/tools/roofing-calculator/>)





## Berechnungsmethode



Bei bekannter Grundfläche schätzt A + 4,4e(√A + e) den Überstand e. Für gemessene Rechteckseiten gilt (l + 2e)(w + 2e). Multiplizieren Sie die horizontale Fläche mit dem Neigungsfaktor. Ein Roofing Square entspricht 100 ft². Prüfen Sie die Produktdeckung.



$$
A_{\rm proj}\approx A+4.4e(\sqrt A+e),\qquad A_{\rm rect}=(l+2e)(w+2e)
$$



$$
A_{\rm roof}=A_{\rm proj}\sqrt{1+(p/12)^2}=\frac{A_{\rm proj}}{\cos\theta},\quad N_{\rm squares}=\left\lceil\frac{A_{\rm roof,ft^2}(1+a/100)}{100}\right\rceil
$$







## Berechnungsmodus





### Grundfläche und Steigung



- Grundfläche
- Flächeneinheit · cm² / m² / in² / ft² / yd² / acre / ha
- Anstieg pro 12 horizontal
- Horizontaler Überstand
- Einheit des Überstands · mm / cm / m / in / ft / yd
- Einzelpreis
- Preiseinheit · cm² / m² / in² / ft² / yd² / acre / ha
- Verschnittzugabe · %
- Gebindedeckung · Bündel je Roofing Square / Fläche je Gebinde
- Bündel für 100 ft²
- Wirksame Fläche je Gebinde
- Preis je Gebinde (optional)







### Grundfläche und Winkel



- Grundfläche
- Flächeneinheit · cm² / m² / in² / ft² / yd² / acre / ha
- Dachneigung · °
- Horizontaler Überstand
- Einheit des Überstands · mm / cm / m / in / ft / yd
- Einzelpreis
- Preiseinheit · cm² / m² / in² / ft² / yd² / acre / ha
- Verschnittzugabe · %
- Gebindedeckung · Bündel je Roofing Square / Fläche je Gebinde
- Bündel für 100 ft²
- Wirksame Fläche je Gebinde
- Preis je Gebinde (optional)







### Bekannte Dachfläche



- Dachfläche
- Flächeneinheit · cm² / m² / in² / ft² / yd² / acre / ha
- Einzelpreis
- Preiseinheit · cm² / m² / in² / ft² / yd² / acre / ha
- Verschnittzugabe · %
- Gebindedeckung · Bündel je Roofing Square / Fläche je Gebinde
- Bündel für 100 ft²
- Wirksame Fläche je Gebinde
- Preis je Gebinde (optional)







### Gemessene Länge und Breite



- Länge
- Längeneinheit · mm / cm / m / in / ft / yd
- Breite
- Breiteneinheit · mm / cm / m / in / ft / yd
- Anstieg pro 12 horizontal
- Horizontaler Überstand
- Einheit des Überstands · mm / cm / m / in / ft / yd
- Giebelüberstand, falls abweichend
- Einzelpreis
- Preiseinheit · cm² / m² / in² / ft² / yd² / acre / ha
- Verschnittzugabe · %
- Gebindedeckung · Bündel je Roofing Square / Fläche je Gebinde
- Bündel für 100 ft²
- Wirksame Fläche je Gebinde
- Flächeneinheit · cm² / m² / in² / ft² / yd² / acre / ha
- Preis je Gebinde (optional)







**Quellen zur Methode** [GAF · Bundle coverage per roofing square](<https://www.gaf.com/en-us/blog/your-home/how-many-bundles-of-shingles-are-in-a-square---63a47862-f7e1-4e73-abcf-8d09917a8b8d>)



[ZooChief](<https://docs.toolpony.com/de/about/>) · [Ergebnisfehler melden](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fde%2Fguides%2Froofing-calculator%2F>)

[Dokumentation](https://docs.toolpony.com/de/guides/roofing-calculator/)
